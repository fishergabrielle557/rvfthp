VS注册娱乐【Q-——333307——】VS注册娱乐【 辋芷《888yx●vip》 】
VS注册娱乐【Q-——333307——】VS注册娱乐【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

你是不是也想拥有一个属于自己的博客，却卡在“买服务器、配环境、写代码”这三座大山前？其实，用GitHub Pages部署静态博客，完全免费，而且半小时就能上线。今天这期纯实操，带你走一遍最省心的路径。

 为什么推荐 GitHub Pages + Hexo？

- 零成本：托管在GitHub，无服务器费用；
- 够灵活：Markdown写作，Git版本管理，天然适合程序员；
- 易扩展：主题丰富，SEO友好，可绑定自定义域名。

 第一步：本地环境准备

确保你的电脑已安装 Node.js（建议v18+）和 Git。在终端验证：

```bash
node -v
git --version
```

 第二步：安装Hexo并初始化项目

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo s
```

浏览器访问 `http://localhost:4000`，看到默认页面即成功。

> 小提示：如果安装速度慢，先执行 `npm config set registry https://registry.npmmirror.com` 切换国内镜像。

 第三步：创建GitHub仓库并部署

1. 新建仓库，命名为 `你的用户名.github.io`；
2. 修改根目录 `_config.yml` 中的 `url` 和 `deploy` 配置；
3. 安装部署插件：

```bash
npm install hexo-deployer-git --save
hexo d -g
```

几分钟后，访问 `https://你的用户名.github.io`，博客即上线。

 第四步：写作与日常维护

```bash
hexo new post "我的第一篇文章"
```

用任意Markdown编辑器写内容，然后 `hexo g && hexo d` 一键发布。

 常见问题速查

- 样式丢失：清浏览器缓存，或检查 `_config.yml` 中的 `root` 路径；
- 部署失败：确认仓库权限，或删除 `.deploy_git` 重新生成。

 下一步玩什么？

- 更换主题（推荐 `Next`、`Fluid`，搜索“hexo主题”即可找到）；
- 绑定自己的域名（在仓库Settings → Pages中配置CNAME）。

如果你在搭建过程中遇到任何问题，欢迎在评论区留言，我看到都会回复。也可以收藏本文，方便以后查阅。如果这篇教程对你有帮助，帮我点个赞，让更多需要的朋友看到，谢谢！

相关推荐：

https://github.com/vargasallison5/hyhncj/blob/main/2026%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%EF%BC%9AVS%E5%B9%B3%E5%8F%B0%E5%AE%98%E6%96%B9_%E6%A1%88%E6%B1%B2%E8%80%98%E8%90%8C%E6%B4%BEUVQKQ.md

<img src="https://i.postimg.cc/P5kgrYxk/V8-00014.png" />

相关推荐：

https://github.com/vargasallison5/hyhncj/commit/133372d862a36e0bd0242cbfab0203f806b08480

<img src="https://i.postimg.cc/90Rpy8Ls/V8-00008.png" />
相关推荐：

https://github.com/gallowayhoward8/ohrtks/blob/main/2026%E6%9D%83%E5%A8%81%E6%89%8B%E5%86%8C%EF%BC%9AVS%E5%B9%B3%E5%8F%B0%E5%BC%80%E5%8F%B7_%E9%94%B9%E6%96%97%E9%99%85%E6%B9%9B%E9%83%B4HOJDL.md

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />
相关推荐：

https://github.com/gallowayhoward8/ohrtks/commit/ddc1b48cdf3ef7149bbd7268e310d55f95bd1937

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
