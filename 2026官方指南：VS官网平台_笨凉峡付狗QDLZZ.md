VS官网平台【Q-——333307——】VS官网平台【 辋芷《888yx●vip》 】
VS官网平台【Q-——333307——】VS官网平台【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

你是否厌倦了在第三方平台写博客，受限于排版和广告？使用 GitHub Pages 搭建个人博客，不仅完全免费，还能100%掌控代码与内容。今天这份教程将手把手带你从零开始，利用 Hexo 框架，30分钟上线一个极简风技术博客。

 为什么要用GitHub Pages？

- 免费稳定：绑定GitHub仓库，全球CDN加速。
- 版本管理：写文章如同提交代码，支持历史回滚。
- 极致灵活：支持自定义域名、HTTPS和各类主题。

 开始搭建前的准备

1. 注册GitHub账号（需邮箱验证）。
2. 安装Git（Windows用户需配置环境变量）。
3. 安装Node.js（建议LTS版本，自带npm）。

 第一步：创建GitHub仓库

登录GitHub，点击右上角“+”选择 New repository。仓库名格式必须为 `你的用户名.github.io`（例如 `john.github.io`）。勾选“Public”并点击创建。

 第二步：安装Hexo与初始化项目

打开终端（Mac/Linux）或CMD（Windows），依次执行：

```bash
npm install hexo-cli -g
hexo init my-blog
cd my-blog
npm install
hexo server
```

浏览器访问 `http://localhost:4000`，看到默认页面即成功。

 第三步：部署到GitHub Pages

先安装部署插件：

```bash
npm install hexo-deployer-git --save
```

在 `_config.yml` 文件中修改deploy配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

执行 `hexo clean && hexo generate && hexo deploy`，然后访问 `你的用户名.github.io`，博客已公开上线！

 第四步：个性化与写作

- 更换主题：搜索“hexo themes”，如NexT、Fluid等，下载到 `themes` 目录并修改配置。
- 发布在终端执行 `hexo new "文章标题"`，然后在 `source/_posts` 下用Markdown编写，最后执行 `hexo d -g` 一键生成并部署。

 常见问题排查

1. 页面404：检查仓库名是否包含用户名且为唯一。
2. 部署失败：确认Git身份配置 `git config`。
3. 图片不显示：将图片放入 `source/images`，使用相对路径引用。

---

动动手指，你的技术博客今天就上线！如果本文对你有帮助，欢迎 Star 仓库或 分享 给更多需要的朋友。遇到任何问题，在评论区留言，我会逐一解答。下一期我们将解读“如何使用GitHub Actions自动部署博客”，不想错过就点个 关注 吧！

相关推荐：

https://github.com/williamsjohn6346/dkavjx/blob/main/2026%E7%A7%91%E6%8A%80%E6%8C%87%E5%8D%97%EF%BC%9AV8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80_%E8%A4%90%E9%80%9F%E6%BA%90%E7%BF%B0%E6%B1%B2IPWDX.md

<img src="https://i.postimg.cc/c4YqSXdK/V8-00012.png" />

相关推荐：

https://github.com/williamsjohn6346/dkavjx/commit/2cb2c20e7470da567db3cac592f585f177dea72a

<img src="https://i.postimg.cc/fLkFgvHt/V8-00020.png" />
相关推荐：

https://github.com/stoneconnor94/facjpk/blob/main/2026%E7%AC%AC%E4%B8%80%E7%94%84%E9%80%89%EF%BC%9AV8%E5%AE%98%E7%BD%91%E4%B8%BB%E7%AE%A1_%E9%AA%8B%E9%A2%93%E5%8D%AE%E6%8A%80%E9%AD%84UUTNN.md

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />
相关推荐：

https://github.com/stoneconnor94/facjpk/commit/acf83e737609e2ab45c9f7b8863416c80b2e6aeb

<img src="https://i.postimg.cc/d05pBf9J/V8-00019.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
