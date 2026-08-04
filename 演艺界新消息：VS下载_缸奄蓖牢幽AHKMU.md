VS下载【Q-——333307——】VS下载【 辋芷《888yx●vip》 】
VS下载【Q-——333307——】VS下载【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hugo 完整指南（2025最新）

你是不是也收藏了十几个“搭建博客”教程，却始终没迈出第一步？别担心，今天这篇GitHub Pages建站教程，我会用最直白的大白话，带你走完从0到1的全过程。全程免费，无需服务器，看完就能动手。

 为什么选择 GitHub Pages + Hugo？

在众多静态博客方案中（如Hexo、Jekyll），我强烈推荐Hugo。原因有三：

1. 速度极快：号称“世界上最快”的静态站点生成器，几百篇文章也就秒级编译。
2. 部署简单：借助 GitHub Actions，写好文章推送到仓库，自动完成网站发布，全程可视化。
3. 主题丰富：官方主题库有超400款设计，总有你喜欢的那款，且多数完美适配移动端。

如果你对 静态博客建站 还比较陌生，记住一个核心逻辑：本地写Markdown → Git推送 → 云端自动生成网页，就这么简单。

 第一步：前置准备

在开工前，请确保你已注册好 [GitHub](https://github.com)。另外，本地安装 [Git](https://git-scm.com/)，Windows用户建议同时安装 [Git Bash](https://gitforwindows.org/)。

 第二步：本地安装 Hugo

Windows用户：前往 Hugo 官方 GitHub Releases 页面，下载 `hugo_extended__windows-amd64.zip`，解压后，打开系统环境变量，把解压目录添加到 Path 中。

macOS用户：如果你安装了 Homebrew，一条命令搞定：
```bash
brew install hugo
```
安装完成后，打开终端输入 `hugo version`，能输出版本号即为成功。

 第三步：快速创建一个站点

找个喜欢的目录，执行以下命令：

```bash
hugo new site my-blog
cd my-blog
```

这时你就有了一个基础骨架，下一步是引入主题。进入 [Hugo Themes](https://themes.gohugo.io/) 挑选你喜欢的主题，最流行的包括 LoveIt、PaperMod 等。这里以 PaperMod 为例：

```bash
git init
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```

然后在 `config.toml` 文件里加上一句主题声明：`theme = 'PaperMod'`。

 第四步：部署到 GitHub Pages

在 GitHub 新建一个公开仓库（建议命名为 `你的用户名.github.io`）。然后，在本地项目根目录执行：

```bash
git add .
git commit -m "first commit"
git remote add origin https://github.com/你的用户名/你的用户名.github.io.git
git push -u origin main
```

接着，去仓库的 Settings → Pages 里，将 Source 选为 `GitHub Actions`，并创建一个 `.github/workflows/deploy.yml` 工作流文件。推荐直接使用 Hugo 官方提供的现成部署模板，实现自动构建。

 第五步：创作并发布文章

比如写一篇新随笔：

```bash
hugo new posts/my-first-post.md
```

用 Markdown 语法写完，保存。然后执行 `git add . && git commit -m "new post" && git push`，稍等几分钟，你的网站就自动更新了！直接访问 `https://你的用户名.github.io` 即可。

 小贴士：收录与SEO优化

为了让百度收录更快，建议注册百度站长平台，提交你的 sitemap（Hugo 默认生成 `/sitemap.xml`）。同时，在文章里合理布局关键词、设置好 meta 描述，有助于提升搜索引擎可见度。

---

互动一下：你准备好动手搭建了吗？如果过程中遇到任何报错，欢迎在评论区留下你卡住的截图，我看到后会第一时间帮你排查！关注我，后续还会分享更多SEO优化和博客美化技巧。

相关推荐：

https://github.com/vargasallison5/hyhncj/blob/main/2026%E5%AE%98%E7%BD%91%E4%B8%93%E8%AE%BF%EF%BC%9AVS%E7%BD%91%E5%9D%80%E5%B9%B3%E5%8F%B0_%E9%92%BE%E5%8B%92%E8%AE%BC%E7%94%B2%E4%B8%A5UUPWI.md

<img src="https://i.postimg.cc/SsKVxN8Z/V8-00004.png" />

相关推荐：

https://github.com/vargasallison5/hyhncj/commit/dbaea5f42d81a1b88517fc425df95376fd9435dd

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/blob/main/%E5%BD%B1%E8%A7%86%E5%9C%88%E6%96%B0%E5%8A%A8%E5%90%91%EF%BC%9AVS%E7%BD%91%E5%9D%80%E5%AE%98%E6%96%B9_%E6%AD%A2%E7%9F%AD%E9%94%A8%E9%A9%B6%E6%A0%8FKRKKY.md

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/commit/a1b0924d623a90b654c82e8dc0c823475b0e28a8

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
