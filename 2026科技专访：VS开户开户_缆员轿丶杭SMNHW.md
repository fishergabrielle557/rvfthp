VS开户开户【Q-——333307——】VS开户开户【 辋芷《888yx●vip》 】
VS开户开户【Q-——333307——】VS开户开户【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在羡慕别人拥有独立的个人博客？其实你只需要一个 GitHub 账号，就能免费搭建一个属于自己的技术博客站点。本篇文章将手把手带你完成从环境配置到文章发布的完整流程，全文干货，建议收藏。

 为什么选择 GitHub Pages + Hexo？

这套组合几乎是目前开发者圈子里最流行的建站方案。GitHub Pages 提供免费的高速静态页面托管服务，而 Hexo 则是一个基于 Node.js 的极速静态博客框架。两者结合，你不仅拥有完全自主的域名绑定权，还能享受 Markdown 写作的丝滑体验，更重要的是——所有代码都在你的 GitHub 仓库中，数据绝对安全。

 第一步：基础环境准备

在开始之前，请确保你的电脑已经安装了 Git 和 Node.js（建议版本 14.0 以上）。打开终端，输入以下命令验证环境：

```bash
node -v
git --version
```

看到版本号输出，说明环境就绪。

 第二步：安装并初始化 Hexo

打开终端，全局安装 Hexo 命令行工具：

```bash
npm install -g hexo-cli
```

初始化博客项目并安装依赖：

```bash
hexo init my-blog
cd my-blog
npm install
```

紧接着，我们启用本地预览模式，在浏览器中访问 `http://localhost:4000` 即可看到默认的博客界面：

```bash
hexo server
```

 第三步：部署到 GitHub Pages

1. 在 GitHub 上新建一个仓库，命名格式必须为：`你的用户名.github.io`。
2. 修改站点根目录下的 `_config.yml` 文件，将 `url` 和 `deploy` 配置为你的仓库地址。
3. 安装自动部署插件并推送上线：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate
hexo deploy
```

浏览器输入 `https://你的用户名.github.io`，你的博客就已经成功上线啦！

 常见问题与行动号召

如果你在部署过程中遇到 `Git 认证失败` 或 `路径错误` 的问题，多半是仓库名称不符或 SSH key 未配置所致。欢迎在评论区留言你的报错截图，我看到后会第一时间回复。

搭建博客最难的是开始行动。如果这篇文章对你的学习路径有所帮助，请点个 Star 或转发给你的开发者朋友。下一期我们将讲解如何更换主题、绑定自定义域名以及使用 GitHub Actions 实现自动发布，关注我不迷路，我们下篇见！

相关推荐：

https://github.com/fishergabrielle557/rvfthp/blob/main/2026%E7%A7%91%E6%8A%80%E6%B1%87%E6%80%BB%EF%BC%9AVS%E5%A8%B1%E4%B9%90%E5%AE%A2%E6%9C%8D_%E5%80%9C%E8%BE%BD%E5%85%B9%E9%99%85%E8%95%B4VDQDD.md

<img src="https://i.postimg.cc/P5kgrYxk/V8-00014.png" />

相关推荐：

https://github.com/fishergabrielle557/rvfthp/commit/6cbd57d03c0a5bc5ed0d67a9dc059ecbfa5fbe02

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />
相关推荐：

https://github.com/parkergloria9526/anwwee/blob/main/2026%E7%A7%91%E6%8A%80%E7%83%AD%E7%82%B9%EF%BC%9AVS%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E9%97%AE%E7%94%B7%E9%97%AE%E5%B1%B1%E4%BB%95MZTBD.md

<img src="https://i.postimg.cc/3Rw9xJm7/V8-00005.png" />
相关推荐：

https://github.com/parkergloria9526/anwwee/commit/d8955eda64364835cd3910450990a4a967f5128f

<img src="https://i.postimg.cc/90Rpy8Ls/V8-00008.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
