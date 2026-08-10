杏耀网址开户【Q-——333307——】杏耀网址开户【 辋芷《888yx●vip》 】
杏耀网址开户【Q-——333307——】杏耀网址开户【 辋芷《888yx●vip》 】

 2025前端必会：从零搭建一套完整的前端监控系统（附代码）

> 你的页面白屏、接口报错，用户不会告诉你，但监控系统会。

很多前端同学都有这样的经历：上线前信心满满，上线后战战兢兢。用户反馈页面打不开，你第一反应是“我本地跑得好好的”。问题出在哪？缺少一套前端监控系统。

今天手把手教你从零搭建一套轻量级的前端监控方案，涵盖错误捕获、性能监控、用户行为追踪三大核心模块，代码可直接复用。

 一、前端监控到底监控什么？

先明确目标，避免过度设计：

- JS运行时错误（SyntaxError、TypeError等）
- 资源加载失败（script、css、img）
- 接口请求异常（超时、500、网络中断）
- 核心性能指标（FCP、LCP、CLS）
- 用户关键行为（点击、路由跳转）

 二、核心代码：错误捕获与上报

```javascript
// monitor.js
class Monitor {
  constructor({ reportUrl, appId }) {
    this.reportUrl = reportUrl;
    this.appId = appId;
    this.init();
  }
  init() {
    // 捕获JS运行时错误
    window.addEventListener('error', (e) => {
      this.report({ type: 'js', msg: e.message, stack: e.error?.stack });
    }, true);
    // 捕获Promise未处理异常
    window.addEventListener('unhandledrejection', (e) => {
      this.report({ type: 'promise', msg: e.reason?.message || String(e.reason) });
    });
    // 捕获接口请求异常（拦截fetch）
    const originalFetch = window.fetch;
    window.fetch = (...args) => {
      return originalFetch(...args).catch((err) => {
        this.report({ type: 'http', url: args[0], msg: err.message });
        throw err;
      });
    };
  }
  report(data) {
    // 使用sendBeacon保证页面卸载时也能发送
    navigator.sendBeacon(this.reportUrl, JSON.stringify({ appId: this.appId, ...data, time: Date.now() }));
  }
}
// 使用
new Monitor({ reportUrl: 'https://your-api.com/report', appId: 'web-app-v1' });
```

 三、性能监控（Web Vitals）

```javascript
import { getLCP, getFID, getCLS } from 'web-vitals';

getLCP((metric) => monitor.report({ type: 'perf', name: 'LCP', value: metric.value }));
getFID((metric) => monitor.report({ type: 'perf', name: 'FID', value: metric.value }));
getCLS((metric) => monitor.report({ type: 'perf', name: 'CLS', value: metric.value }));
```

 四、可视化与告警

服务端建议采用 RabbitMQ + ClickHouse 存储，配合 Grafana 展示看板。当错误率超过阈值时，通过钉钉/企业微信机器人推送告警。

 五、避坑指南

- 别影响主流程：监控脚本用 `defer` 加载，上报用 `sendBeacon` 或 `1x1像素` 图片打点
- 错误去重：同一错误频繁上报会导致存储爆炸，加个 `key = msg + stack` 去重
- 隐私合规：不要采集用户输入框内容，上报数据脱敏

---

你现在的项目里有没有监控？踩过什么坑？欢迎在评论区聊聊你的解决方案，或者分享你遇到过的“幽灵Bug”。

如果这篇文章对你有启发，请点个 Star 或 在看，让我看到你的支持。后续会更新 SourceMap定位压缩代码错误 和 监控大屏搭建 的实战教程。

相关推荐：

https://github.com/parkergloria9526/anwwee/blob/main/%E8%BF%9B%E9%98%B6%E5%AE%9E%E6%93%8D%E6%8C%87%E5%8D%97%EF%BC%9A%E6%9D%8F%E8%80%80%E5%9C%B0%E5%9D%80%E5%AE%A2%E6%9C%8D_%E7%B0%BF%E8%AF%A8%E6%A1%83%E5%88%B9%E9%93%BApiipp.md

<img src="https://i.postimg.cc/L87MV6K7/xingyao1-00010.png" />

相关推荐：

https://github.com/parkergloria9526/anwwee/commit/f40c7f99028a99d7e860e388680d5f84040aa11f

<img src="https://i.postimg.cc/FRX52WKj/xingyao1-00014.png" />
相关推荐：

https://github.com/reidraymond02/imvanu/blob/main/2027%E7%AC%AC%E4%B8%80%E7%A7%91%E6%99%AE%EF%BC%9A%E6%9D%8F%E8%80%80%E5%9C%B0%E5%9D%80%E5%9C%B0%E5%9D%80_%E6%8D%9E%E7%BC%93%E4%BB%93%E6%8C%96%E7%BC%98uhbhh.md

<img src="https://i.postimg.cc/V69Q1qS2/xingyao1-00015.png" />
相关推荐：

https://github.com/reidraymond02/imvanu/commit/dbfbfd5fd36b3ee0fc4facf46269bad8e94062a6

<img src="https://i.postimg.cc/jdxKxFhr/xingyao1-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
