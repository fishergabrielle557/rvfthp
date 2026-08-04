VS注册【Q-——333307——】VS注册【 辋芷《888yx●vip》 】
VS注册【Q-——333307——】VS注册【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整部署教程

 为什么选择 GitHub Pages 搭建博客？

对于开发者而言，GitHub Pages 提供免费的静态网站托管服务，搭配 Hexo 框架可以快速构建高性能的个人博客。无需购买服务器、支持自定义域名、自动 HTTPS 加密，这些都是它成为开发者首选的原因。本教程将手把手教你完成从环境配置到博客发布的全流程。

---

 第一步：本地环境准备

在开始之前，请确保你的电脑已安装以下工具：

- Git（版本管理工具）
- Node.js（运行环境，建议 v16+）

安装完成后，打开终端验证环境：

```bash
git --version
node -v
npm -v
```

---

 第二步：安装 Hexo 并初始化项目

Hexo 是一个快速、简洁且高效的博客框架。通过以下命令全局安装：

```bash
npm install -g hexo-cli
```

在你的工作目录下初始化博客：

```bash
hexo init my-blog
cd my-blog
npm install
```

此时你已经拥有一个本地博客骨架，运行 `hexo s` 即可在 `http://localhost:4000` 预览默认主题。

---

 第三步：创建 GitHub 仓库并配置 SSH

前往 GitHub 新建仓库，命名为 `你的用户名.github.io`（注意：必须严格匹配）。接着在本地生成 SSH 密钥：

```bash
ssh-keygen -t rsa -C "你的邮箱"
```

将生成的公钥添加到 GitHub 的 Settings → SSH and GPG keys 中。测试连接：

```bash
ssh -T git@github.com
```

---

 第四步：部署博客到 GitHub Pages

修改站点根目录下的 `_config.yml`，填入仓库信息：

```yaml
deploy:
  type: git
  repo: git@github.com:你的用户名/你的用户名.github.io.git
  branch: main
```

安装部署插件：

```bash
npm install hexo-deployer-git --save
```

执行以下命令完成部署：

```bash
hexo clean && hexo generate && hexo deploy
```

打开 `https://你的用户名.github.io`，你的博客已正式上线！

---

 进阶优化建议

- 绑定自定义域名：在仓库 Settings 中启用 Pages 服务，并在 DNS 管理后台添加 CNAME 记录。
- 更换主题：Hexo 官网提供大量美观主题，推荐 `NexT` 和 `Fluid`，只需下载并修改配置文件即可。
- 添加搜索功能：安装 `hexo-generator-searchdb` 插件，配合本地搜索实现全站内容检索。

---

 结语

通过以上步骤，你已经拥有一个稳定、免费的专属技术博客。GitHub Pages 的加载速度极快，且与代码仓库完美集成，非常适合技术分享。如果遇到问题，欢迎在评论区留言，或参考 [Hexo 官方文档](https://hexo.io/zh-cn/docs/)。

觉得有用的话，点个赞吧！ 关注我获取更多开发者实战干货，下一期将分享如何为博客添加评论系统和文章浏览量统计。

相关推荐：

https://github.com/davisgina32/bajxxs/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E6%A2%97%EF%BC%9AV8%E7%BD%91%E5%9D%80%E5%BC%80%E6%88%B7_%E8%B0%AA%E8%8A%AD%E6%98%A7%E8%AF%BB%E6%80%A7SMUUP.md

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />

相关推荐：

https://github.com/davisgina32/bajxxs/commit/5865dd63ebde38e8248290927905f31d16d9bfa3

<img src="https://i.postimg.cc/2SFPqybC/V8-00015.png" />
相关推荐：

https://github.com/williamsjohn6346/dkavjx/blob/main/2026%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5%EF%BC%9AV8%E7%BD%91%E5%9D%80%E6%B5%8B%E9%80%9F_%E8%B0%80%E8%9A%80%E6%98%A7%E8%BF%94%E7%97%B9AHWEF.md

<img src="https://i.postimg.cc/nzw2jbGZ/V8-00006.png" />
相关推荐：

https://github.com/williamsjohn6346/dkavjx/commit/45684b44f38f768d31156ce6e1ccb00b17df5365

<img src="https://i.postimg.cc/ZYWtfJ2Z/V8-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
