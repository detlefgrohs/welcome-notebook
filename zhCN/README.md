---
tags:
  - introduction
  - why/so/cool
created: 2020-03-26T13:04:29.042Z
modified: 2020-05-15T04:17:07.045Z
---

# 📝 欢迎使用交叉笔记 (beta)

> 推荐在 [交叉笔记](https://crossnote.app/?repo=https%3A%2F%2Fgithub.com%2F0xGG%2Fwelcome-notebook.git&branch=master&filePath=README.md) 中查看这个笔记本。

<!-- @crossnote.comment "id":"75dbb115-f41b-4c0f-b74b-42b514fc1add" -->

## 🔭 介绍

**Crossnote 交叉笔记** 可能是这个世界上第一款可离线工作并且支持在浏览器中直接与 git 仓库进行同步的的 markdown 笔记阅读器 & 编辑器。

交叉笔记受到了这些产品的启发： [Markdown Preview Enhanced](https://github.com/shd101wyy/markdown-preview-enhanced)，[Google Keep](https://keep.google.com)，[Google Docs](https://docs.google.com)，[Quip](https://quip.com)，[Notion](https://www.notion.so)，[GitBook](https://gitbook.com)，[Notable](https://github.com/notable/notable)，[Evernote](https://evernote.com/)，以及 [Bear](https://bear.app/)。

不同于[交叉笔记 (_alpha_)](https://github.com/0xGG/crossnote/blob/master/README.alpha.md)这款完全基于云端的笔记软件，**交叉笔记 (beta)** 的目标是离线第一。你的所有数据将会保存于你的浏览器中。我们不会上传你的笔记和密钥到我们的服务器。**你拥有的你的数据的控制权**。

交叉笔记项目的前端是完全在 GitHub 上开源的 [0xGG/crossnote](https://github.com/0xGG/crossnote)。它使用的是 **AGPL3** 协议。任何的代码贡献或者项目建议都会对这个项目的发展产生很大的助力。

你可以非常方便地将你的笔记本和任意的 git 仓库进行同步。这点归功于一个炫酷的项目 [isomorphis-git](https://github.com/isomorphic-git/isomorphic-git)。它使得直接在浏览器中运行 git 命令成为了可能。

交叉笔记项目目前还在开发中，并且它的生产环境只部署于位于洛杉矶的一个只有 8GB 内存的 Vultr 主机上。

## 💾 安装

在电脑端或者安卓设备，我们推荐你用 **Chrome** 打开 [交叉笔记](https://crossnote.app)。你可以通过点击右上角的菜单，选择 `更多工具`，然后选择 `添加到桌面` 进行安装。

在 iOS 设备（iPhone 和 iPad）上，我建议用 **Safari** 打开 [交叉笔记](https://crossnote.app)。然后点击底部的分享按钮，选择 `添加到主屏幕` 进行安装。

> 🐞 但是，iOS 有时候会杀掉后台中不活动的任务，所以在后台运行交叉笔记有时候会有问题。我目前还没有找到解决方案。。。

## ⚗️ 功能

- 🤩 用 markdown 编写你最喜爱的笔记。查看 [markdown 的基本语法](/demo/markdown.md)。
- 📊 各种各样的图表支持. 查看 [演示](/demo/diagrams.md)。
- ~~⌨️ 协同编辑~~ 这个功能原来在 _alpha_ 版本中是支持的，但是当前的 _beta_ 版本取消了支持。我们未来会把这个功能加回来（可能用 P2P 的实现方式）。
- 🖼 和 [Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/presentation) 中相同标准的幻灯片制作。查看 [MPE 中的演示](/demo/presentation.md)。
- 🏷️ 无限嵌套式标签 #why/so/cool 。（没错我们喜欢 [Bear](https://bear.app) 和 [Notable](https://github.com/notable/notable) 的设计思路）
- 🔐 内置 AES 算法加密，支持你设置密码保护你的笔记。例如[这个加密笔记](/demo/encrypted.md)的密码是 `123456` 🙈。
- 🖨️ 打印你的笔记为 PDF。我们在未来会支持更多的导出格式！
- 📤 同步你的笔记本到任意的 git 仓库（🙋 教程请查看[这里](/zhCN/tutorial.md)）
- 🛠 让你的笔记更加强健有力的挂件。输入 `/` 来显示命令并且尝试创建些你的挂件。
  - `/timer`
  - Media
    - `/audio` [demo](/demo/audio.md)
    - `/video` [demo](/demo/video.md)
    - `/youtube` [demo](/demo/youtube.md)
    - `/bilibili` [demo](/demo/bilibili.md)
  - `/ocr`
  - `/kanban` (_beta_)
  - `/github_gist` [demo](/demo/github_gist.md)
    更多的挂件会在未来支持。
- 📖 通过添加 `SUMMARY.md` 开设置维基。

## 🌤 交叉笔记云挂件

交叉笔记云挂件是一种特殊种类的挂件。云挂件将直接与交叉笔记云服务互动。（😂 云服务器正很骄傲地运行在一个只有 8GB 内存的位于洛杉矶的 Vultr VPS 上）。

我们在交叉笔记中支持的第一个云挂件是 `/crossnote.comment` 挂件 💬。这个挂件允许你在你的 markdown 笔记中插入评论系统。例如：

<!-- @crossnote.comment "id":"edf653be-1d26-4d7a-969f-2c4b344e37d5" -->

在 _beta 测试_ 期间你可以创建无限数量的云挂件。但是在未来，普通种类账户可以创建的云挂件的数量会有不同的限制。

## 🙋 教程

我们提供了一个简短的教程来引导你利用一个 GitHub 上的仓库来创建你的第一个笔记本。请查看[这里](/zhCN/tutorial.md)。

## :spider_web: Web Clipper

我们尚未提供官方的 Web Clipper 支持，但是你可以暂时使用 Quiver 的 Web Clipper 来剪切网页为 Markdown 然后拷贝至 Crossnote。

- [Quiver Web Clipper - Chrome Web Store](https://chrome.google.com/webstore/detail/quiver-web-clipper/hcnffmpopoelpggikahccdfenoobjigj)
- [Quiver Web Clipper - Firefox Add-on](https://addons.mozilla.org/en-US/firefox/addon/quiver-web-clipper/)

## 🌍 和大众分享你的笔记本

是的我们支持用户在 `探索` 部分发布自己想要公开的笔记本。  
我们目前仅支持从 GitHub、GitLab、Gitea 或码云的公共仓库发布笔记本。  
我们只收集 `README.md` 文件数据。

## 📅 开发计划

查看 [Development Plans](/development/plans.md)。

## 📖 开发文档

看看 [这个](/development/README.md)。

## 😀 对这个项目感兴趣？

交叉笔记项目现在实际上只由一个开发者 [github/shd101wyy](https://github.com/shd101wyy) 开发而成。我期待未来有更多的人加入到这个项目中来。

这个项目的目标是帮我**挣钱** 💰。没错，现实就是很残酷 😣。我的目标是通过交叉笔记项目在 2020 年底之前得到 ￥ 12000 人民币（\$2000 美元）。因为作为一个独立开发者，我也有生存的需求。同时我需要有收入来帮助我让这个项目持续下去，租用更好的服务器，设置 CDNs，等等。

我当前的计划是，所有可以直接在浏览器中实现的功能将全部免费，但是与后端服务器有互动或者有数据要保存于后端服务器的此类功能将会进行收费。

如果你对这个项目感兴趣，或者想要更加深入地参与进来（甚至是帮助商业化这个项目 😎），你可以联系我：邮箱 `shd101wyy@gmail.com`（我其实不怎么经常查邮件），微信 `shd101wyy`，或者我的 [Linkedin](https://www.linkedin.com/in/yiyi-wang-60416380/)。

你也可以选择加入我们的微信讨论群

![webwxgetmsgimg](https://i.loli.net/2020/07/16/uk7MFJVp8O2DwEL.jpg)

最后，希望 2020 年发生的疫情早日结束 🙏。

谢谢！
