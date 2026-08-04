VS主管娱乐【Q-——333307——】VS主管娱乐【 辋芷《888yx●vip》 】
VS主管娱乐【Q-——333307——】VS主管娱乐【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：GitHub Pages + Hexo 完整指南

你是否也曾想过拥有一个属于自己的技术博客，却卡在“不会搭站点”这一步？别担心，这篇教程将带你用 GitHub Pages 和 Hexo，零成本、免服务器 搭建一个高性能个人博客。整个过程无需命令行基础，跟着操作即可上线。

 为什么选择 GitHub Pages + Hexo？

- 完全免费：托管在 GitHub 服务器上，无需购买云主机。
- 加载极快：静态页面天然具备 CDN 加速优势，利于 SEO 收录。
- 版本管理：所有文章以 Markdown 形式存入 Git 仓库，历史可追溯。
- 高度可定制：Hexo 拥有丰富的主题与插件生态，满足个性化需求。

 第一步：环境准备（5分钟）

1. 安装 Node.js（版本需 ≥ 12.0），下载地址：nodejs.org
2. 安装 Git 客户端，用于代码上传。
3. 注册 [GitHub](https://github.com) 账号，并新建一个仓库，命名为 `你的用户名.github.io`（务必勾选 Public）。

> 建议直接使用 Windows 的 PowerShell 或 macOS 的终端执行后续命令。

 第二步：本地初始化 Hexo 博客

打开终端，依次运行以下命令：

```bash
npm install -g hexo-cli    全局安装脚手架
hexo init my-blog          初始化项目
cd my-blog
npm install                安装依赖
hexo s                     本地预览（浏览器访问 http://localhost:4000）
```

看到默认页面出现，说明站点已成功跑通。此时 `source/_posts` 目录下的 `.md` 文件即为你的文章存储位置。

 第三步：部署到 GitHub Pages

修改根目录下 `_config.yml` 配置文件，找到 `deploy` 字段，填入你的仓库地址：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后执行部署命令：

```bash
npm install hexo-deployer-git --save    安装部署插件
hexo clean && hexo generate            清除缓存并生成静态文件
hexo deploy                             推送到远程仓库
```

等待约 1 分钟，访问 `https://你的用户名.github.io`，你的专属博客已面向全球开放！

 第四步：写作与日常维护

发布新文章只需两步：

1. 在终端运行 `hexo new "文章标题"`，自动生成 `.md` 文件。
2. 用任意编辑器（如 VS Code）撰写内容，保存后重复上述 `generate` + `deploy` 命令。

进阶技巧：
- 修改主题：在官网 [hexo.io/themes](https://hexo.io/themes) 下载主题包，放入 `themes` 目录并改 `_config.yml` 中的 `theme` 字段。
- 绑定域名：在仓库 Settings 的 Pages 选项里填写自定义域名，并在 DNS 处添加 CNAME 记录至 `你的用户名.github.io`。

 常见问题排查

- 部署后页面空白：检查仓库名是否为 `用户名.github.io`，且分支是否为 `main`。
- 图片不显示：将图片放入 `source/images` 目录，文章内引用路径为 `/images/xxx.jpg`。
- 无法执行 hexo 命令：大概率是 Node.js 环境变量未配置，重装或手动添加 PATH 即可。

 结语：开始输出你的第一篇技术文章

搭建博客只是第一步，持续输出才是沉淀个人 IP 的关键。建议从解决一个真实问题开始记录，哪怕只有 100 行代码，也是对知识的重组与升华。

如果本教程对你有帮助，欢迎点赞、收藏、评论你的踩坑经历，或分享给身边同样想开启写作之旅的朋友。后续我会更新“Hexo 主题深度定制”与“SEO 优化实战”系列，关注我不迷路！

---

本文关键词：GitHub Pages 搭建教程、Hexo 博客部署、免费个人博客、静态网站托管、程序员写作指南

相关推荐：

https://github.com/reidraymond02/imvanu/blob/main/%E6%96%87%E5%A8%B1%E8%A1%8C%E4%B8%9A%E5%8A%A8%E6%80%81%EF%BC%9AVS%E7%BD%91%E5%9D%80%E5%BC%80%E6%88%B7_%E8%B0%B4%E8%81%8C%E4%B8%88%E7%A8%B3%E7%A1%AEMFGGU.md

<img src="https://i.postimg.cc/d05pBf9J/V8-00019.png" />

相关推荐：

https://github.com/reidraymond02/imvanu/commit/ae55e3ff8bf4ac9a24d15a99a6ac74ef268e4795

<img src="https://i.postimg.cc/J7sVTRgT/V8-00010.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/blob/main/2026%E7%A7%91%E6%8A%80%E5%A4%8D%E7%9B%98%EF%BC%9AVS%E7%BD%91%E5%9D%80%E5%B9%B3%E5%8F%B0_%E5%81%AC%E8%B4%A8%E4%BE%A5%E8%B0%85%E6%B6%9DUBIPU.md

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/commit/c9b567b02a7833c10dc8269aef1881740fc5753e

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
