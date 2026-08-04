VS注册【Q-——333307——】VS注册【 辋芷《888yx●vip》 】
VS注册【Q-——333307——】VS注册【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在羡慕别人拥有独立博客？其实，利用 GitHub Pages 和 Hexo，你可以在半小时内免费搭建一个高速、稳定的个人网站。更重要的是，这个博客完全由你掌控，无任何平台限制。

 为什么选择 GitHub Pages + Hexo？

GitHub Pages 提供免费的静态网站托管服务，支持自定义域名，全球访问速度极快。搭配 Hexo 这款基于 Node.js 的框架，你只需敲击几个命令，就能生成优雅的静态页面部署到 GitHub 上。

小白友好：全程图形化操作 + 命令行辅助，无需精通代码。
SEO 友好：Hexo 自带静态页面生成，天然利于搜索引擎收录。
扩展性强：丰富的主题和插件，满足你的个性化需求。

 第一步：环境准备与基础配置

在开始前，请确保你的电脑已安装 Node.js（建议 v18+）和 Git。打开命令行工具，输入以下命令验证环境：

```bash
node -v
git -v
```

接下来，全局安装 Hexo 脚手架：

```bash
npm install -g hexo-cli
```

 第二步：本地初始化博客项目

在你喜欢的目录下，执行以下命令初始化一个名为 `myblog` 的项目：

```bash
hexo init myblog
cd myblog
npm install
```

启动本地预览服务，体验第一版博客：

```bash
hexo server
```

在浏览器输入 `http://localhost:4000`，你就能看到默认的 Hello World 页面。

 第三步：关联 GitHub 仓库并部署

在 GitHub 上新建一个仓库，命名为 `你的用户名.github.io`。然后在本地命令行中安装部署插件：

```bash
npm install hexo-deployer-git --save
```

修改项目根目录下的 `_config.yml` 文件，找到 `deploy` 部分并添加你的仓库地址：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

最后，执行一键部署命令：

```bash
hexo clean && hexo generate && hexo deploy
```

访问 `https://你的用户名.github.io`，属于你的独立博客正式上线！

 进阶技巧：主题优化与 SEO 设置

为了让博客更美观，推荐更换热门主题如 NexT 或 Fluid。同时，在 `_config.yml` 中开启站点描述和关键词配置，配合插件 hexo-generator-sitemap 生成站点地图，能有效提升搜索引擎的抓取效率。

---

互动话题：你目前在用什么工具写博客？是静态生成器还是传统 CMS？欢迎在评论区分享你的见解，让我们一起交流进步！

觉得这篇教程有用吗？ 点赞收藏不迷路，持续关注更多开发实战干货！

相关推荐：

https://github.com/gutierrezjessica05/nukelg/blob/main/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E6%9E%90%EF%BC%9AVS%E5%AE%98%E7%BD%91%E5%AE%98%E7%BD%91_%E7%97%9B%E9%85%AA%E5%AE%A2%E6%81%83%E6%AF%95WPVJD.md

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />

相关推荐：

https://github.com/gutierrezjessica05/nukelg/commit/58278053f50c9aa518632a58226e9800e3524af8

<img src="https://i.postimg.cc/d0w4g90d/V8-00002.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/blob/main/%E6%82%A6%E4%BA%AB%E6%96%87%E9%9F%B5%E6%97%B6%E5%85%89%EF%BC%9AVS%E5%AE%98%E7%BD%91%E5%A8%B1%E4%B9%90_%E8%BD%BF%E8%86%8A%E4%BE%A8%E8%B5%84%E8%9D%97XXXPJ.md

<img src="https://i.postimg.cc/fLkFgvHt/V8-00020.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/commit/1264e9bdd778f4aaf405a3c53aa6f85c840a8a2b

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
