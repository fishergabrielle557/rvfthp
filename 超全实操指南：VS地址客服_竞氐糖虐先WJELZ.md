VS地址客服【Q-——333307——】VS地址客服【 辋芷《888yx●vip》 】
VS地址客服【Q-——333307——】VS地址客服【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025亲测有效）

还在羡慕别人的技术博客？其实搭建一个属于自己的博客，比你想的简单得多。今天这份教程，不需要买服务器，不需要懂后端，只需要一个 GitHub 账号，就能拥有一个免费、稳定、支持自定义域名的个人网站。

 为什么选择 GitHub Pages？

- 完全免费：静态托管，无服务器成本
- 全球加速：自带 CDN，国内访问速度尚可
- 版本管理：文章即代码，Git 天然备份
- 高度定制：支持 Jekyll、Hexo、Hugo 等主流框架

 第一步：创建 GitHub 仓库

1. 登录 GitHub，点击右上角 `+` 号，选择 New repository
2. Repository name 必须填写：`你的用户名.github.io`（这是硬性要求）
3. 选择 Public（免费版无法用 Private 托管 Pages）
4. 勾选 Add a README file，方便初始化

 第二步：安装本地环境（Windows/Mac 通用）

推荐使用 Hexo，速度快、中文文档全。

```bash
 安装 Node.js（官网下载 LTS 版本）
 安装 Git（官网下载）

 全局安装 Hexo 脚手架
npm install hexo-cli -g

 初始化博客目录
hexo init my-blog
cd my-blog
npm install
```

 第三步：一键部署到 GitHub

修改根目录 `_config.yml` 文件末尾：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后执行三条命令，你的博客就上线了：

```bash
hexo clean    清理缓存
hexo generate  生成静态页面
hexo deploy    推送到 GitHub
```

浏览器访问 `https://你的用户名.github.io`，看到默认主题即成功。

 第四步：发布第一篇文章

```bash
hexo new post "我的第一篇博客"
```

用 Markdown 编辑 `source/_posts/` 下的 `.md` 文件，再次运行 `hexo g -d`，完成更新。

---

 进阶技巧（提高收录率）

1. 添加 SEO 插件：安装 `hexo-generator-seo-friendly-sitemap`，生成 sitemap
2. 百度站长提交：在百度搜索资源平台验证站点，手动提交 URL
3. 开启文章阅读量：集成 `leancloud` 统计，丰富页面内容

---

互动时间：你在部署过程中遇到了什么问题？或者你正在用 Hugo / Jekyll？评论区聊聊，我会逐一回复。觉得有用的话，点个 Star 支持一下，下次更新「主题美化+评论系统」教程！

---

本文由「代码小工」原创，首发于 GitHub Pages，转载请联系授权。

相关推荐：

https://github.com/cruzdenise0/avxylh/blob/main/2026%E5%AE%98%E6%96%B9%E5%B9%B2%E8%B4%A7%EF%BC%9AV8%E5%A8%B1%E4%B9%90%E5%9C%B0%E5%9D%80_%E8%B4%AD%E7%B3%96%E7%82%8A%E9%98%85%E5%82%A9OBOIV.md

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />

相关推荐：

https://github.com/cruzdenise0/avxylh/commit/23c2ea0f196cd6290809fc51dcfb2ae7c7e75654

<img src="https://i.postimg.cc/ZYWtfJ2Z/V8-00011.png" />
相关推荐：

https://github.com/davisgina32/bajxxs/blob/main/2026%E6%9D%83%E5%A8%81%E7%88%86%E7%82%B9%EF%BC%9AV8%E5%A8%B1%E4%B9%90%E6%B5%8B%E9%80%9F_%E8%8A%BD%E7%83%9F%E7%90%A2%E9%99%B6%E5%AF%BFGUHQQ.md

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />
相关推荐：

https://github.com/davisgina32/bajxxs/commit/46da663c340642d4e52c4c7b3bd2d22f4a0f247c

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
