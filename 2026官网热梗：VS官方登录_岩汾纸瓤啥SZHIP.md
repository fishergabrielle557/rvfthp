VS官方登录【Q-——333307——】VS官方登录【 辋芷《888yx●vip》 】
VS官方登录【Q-——333307——】VS官方登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hugo 完整指南（2025亲测有效）

> 想拥有一个免费、稳定、可自定义的博客？别再用难维护的WordPress了。今天分享一套我用了3年的方案——GitHub Pages + Hugo，零成本、秒级部署、Markdown写作，小白也能轻松上手。

 为什么选择 GitHub Pages + Hugo？

很多朋友纠结“静态博客怎么搭建”，其实核心就两点：托管平台和生成工具。GitHub Pages提供无限流量和HTTPS，Hugo号称“全球最快静态站点生成器”，两者结合，博客搭建教程里最推荐的就是这套组合。

核心优势：
- 免费托管：无需服务器，代码即内容
- 极速构建：Hugo数秒生成上千页面
- 版本管理：Git备份，永不丢失文章
- 极致体验：生成纯静态HTML，秒开且安全

 第一步：准备工作

你只需要这三个东西：
1. GitHub账号（没有的话先去注册）
2. Git工具（本地电脑安装，用于推送代码）
3. Hugo框架（下载对应系统版本，解压即用）

> 小提示：Windows用户建议用Scoop安装，Mac用户用Homebrew，一行命令搞定。

 第二步：创建你的第一个站点

```bash
 1. 生成新站点
hugo new site my-blog
cd my-blog

 2. 初始化Git仓库
git init

 3. 选择主题（推荐：LoveIt或Even）
git submodule add https://github.com/dillonzq/LoveIt.git themes/LoveIt

 4. 创建第一篇博客
hugo new posts/hello-github.md
```

注意：主题配置是新手最容易卡壳的地方。把`config.toml`里的主题名称改成`LoveIt`，同时把`baseURL`改成`https://你的用户名.github.io`。

 第三步：部署到 GitHub Pages

最推荐的自动化流程（GA工作流）：

1. 在GitHub新建仓库，命名为`你的用户名.github.io`
2. 本地把代码推送上去：

```bash
git add .
git commit -m "首次发布博客"
git branch -M main
git remote add origin https://github.com/你的用户名/你的用户名.github.io.git
git push -u origin main
```

3. 关键步骤——开启自动部署：进入仓库的Settings → Pages，Source选择`GitHub Actions`。这时你的每次push都会自动构建并更新博客。

这就是GitHub Pages部署教程里最省心的一环，全自动，不用碰服务器。

 第四步：自定义与域名绑定

- 改头像和简介：编辑`config.toml`中的`[params]`部分
- 绑定独立域名：在仓库创建`CNAME`文件，内容写你的域名。然后在DNS服务商加一条CNAME记录到`你的用户名.github.io`

 常见问题速查（踩坑经验）

| 问题 | 解决方案 |
|------|----------|
| 页面显示404 | 检查仓库名必须为`用户名.github.io` |
| 样式丢失 | 确认主题文件夹已完整下载 |
| 中文乱码 | 确保所有文件UTF-8编码 |
| 推送失败 | 先把远程仓库`git pull origin main --allow-unrelated-histories` |

 开始你的技术博客之旅

这套GitHub Pages建站教程我已经用了三年，总共写了两百多篇文章，零成本、零维护焦虑。最大的收获是：当写作变得简单，你就更愿意坚持输出。

如果你也有搭建的想法，或者过程中遇到任何问题，欢迎在评论区留言交流。你的点赞和收藏是我继续分享的最大动力！也欢迎关注我，后续我会更新更进阶的“自动发布脚本”“SEO优化”等技巧。

下一步行动： 现在就动手跑一遍上面的命令，半小时内，你的第一篇文章就能上线。遇到任何报错，直接评论区喊我！

相关推荐：

https://github.com/gutierrezjessica05/nukelg/blob/main/%E5%85%B1%E8%B5%8F%E6%96%87%E5%8C%96%E9%A3%8E%E5%8D%8E%EF%BC%9AVS_%E9%83%A7%E5%80%A8%E5%8E%A6%E9%87%8A%E7%A9%B6YERRE.md

<img src="https://i.postimg.cc/c4YqSXdK/V8-00012.png" />

相关推荐：

https://github.com/gutierrezjessica05/nukelg/commit/e9a4bdee9426810c74db8483cf4195bf235e65a3

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/blob/main/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF%EF%BC%9AVS%E4%B8%BB%E7%AE%A1%E4%B8%8B%E8%BD%BD_%E8%AF%84%E7%A8%8D%E9%92%A9%E5%A2%A9%E7%8E%87RDKEE.md

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/commit/6fa0d87734dac74655fc7ff35e3c36669dbdc614

<img src="https://i.postimg.cc/W4Nx0Vgy/V8-00017.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
