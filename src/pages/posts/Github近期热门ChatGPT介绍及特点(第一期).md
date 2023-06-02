---
layout: '../../layouts/MarkdownPost.astro'
title: 'Github近期热门ChatGPT介绍及特点(第一期)'
pubDate: 2023-04-11
description: '该文介绍了当前热门的Github ChatGPT开源项目，包括Chatbot-ui、Chatbox、ChatGPT Box、BingGPT和ChatGPT Web。这些项目都是聊天机器人工具，提供了各种功能，如自定义提示、数据存储、多语言支持等。其中ChatGPT Box被称为最强的聊天机器人工具，可以代替chathub、writely、BingGPT和openai-translator。'
author: 'geek'
cover:
    url: 'https://cloudflare-ipfs.com/ipfs/bafybeigfswxffmlqgnsry5hmjymfgxa6dvdlronybzogbyv26geszbltbq?resize=1&w=1920'
    square: 'https://cloudflare-ipfs.com/ipfs/bafybeigfswxffmlqgnsry5hmjymfgxa6dvdlronybzogbyv26geszbltbq?resize=1&w=1920'
    alt: 'cover'
tags: ["ChatGPT", "Github"]
theme: 'light'
featured: false
---

**盖此篇文所言，论当前热门之 Github ChatGPT 开源项目。详加介绍使人能够于短暂光阴內基本掌握其核心体系，藉此提升自身之選擇能力。**

## Chatbot-ui

> chatbot-ui 是一个聊天机器人 UI 也是一个高级聊天机器人工具包，可部署在 Vercel，用于在 Chatbot UI Lite 上构建 OpenAI 的聊天模型，使用 Next.js，TypeScript 和 Tailwind CSS。

```
主要功能：
提示模板（3/27/23）
重新生成和编辑响应（3/25/23）
文件夹（3/24/23）
搜索聊天内容（3/23/23）
停止消息生成（3/22/23）
导入/导出聊天记录（3/22/23）
自定义系统提示（3/21/23）
错误处理（3/20/23）
GPT-4支持（需要访问）（3/20/23）
搜索对话（3/19/23）
代码语法高亮（3/18/23）
切换侧边栏（3/18/23）
对话命名（3/18/23）
Github风格的标记（3/18/23）
在应用中添加OpenAI API密钥（3/18/23）
Markdown支持（3/17/23）
```

- **点评:开源 ChatGPT 用户界面，近期更新的右侧自定义提示支持变量{{}}，配合“[ChatGPT 自用 Prompt 区别于网络上大多数烂套路](https://geekbb.xlog.app/fen-xiang-ChatGPT-zi-yong-Prompt-qu-bie-yu-wang-luo-shang-da-duo-shu-lan-tao-lu)”食用，极大提升我的效率，支持导出话题记录和自定义 Prompt，目前是我的主力。**
  运行界面
  ![FtLqfuGakAEv-Y3.jpeg](https://cloudflare-ipfs.com/ipfs/bafybeigfswxffmlqgnsry5hmjymfgxa6dvdlronybzogbyv26geszbltbq)

**Github 链接：[Chatbot-ui](https://github.com/mckaywrigley/chatbot-ui)**

---

## Chatbox

![icon.png](https://cloudflare-ipfs.com/ipfs/bafkreiguggwe5eh36b33qjhi2msc7cggvofxzchbevl7lhxmbd23rctkz4)

> 开源的 ChatGPT API (OpenAI API) 桌面客户端，Prompt 的调试与管理工具，支持 Windows、Mac 和 Linux

```
和 ChatGPT Plus 一样快
数据存储在本地，不会丢失
更自由、更强大的 Prompt 能力
支持 GPT-4 和其他模型
支持自定义域名代理
更多功能：Markdown、消息引用、字数与token估算、夜间模式……
符合人体工程学的 UI 设计
提供安装包，无需部署
免费，开源
```

- **点评:快是真快，期待加入自定义 Prompt。**
  运行界面

![CleanShot 2023-04-11 at 09.22.44@2x.png](https://cloudflare-ipfs.com/ipfs/bafybeigloj5bbz3s4ucmshjhjlz5cqt6w7cbi7tghg7ofnogbz5yqkp4km)

Github 链接：[Chatboxi](https://github.com/Bin-Huang/chatbox)

---

## ChatGPT Box

![logo.png](https://cloudflare-ipfs.com/ipfs/bafkreifbsdhh7ybkwvl5kyiiegl35qrpu5ig36j642u6fzzeivhqshe3ma)

> 将 ChatGPT 深度集成到浏览器中, 你所需要的一切均在于此

```
🌈 在任何页面随时呼出聊天对话框 (Ctrl+B)
📱 支持手机等移动设备
📓 通过右键菜单总结任意页面 (Alt+B)
📖 独立对话页面 (Ctrl+Shift+H)
🔗 多种API支持 (免费用户和Plus用户可用Web API, 此外还有GPT-3.5, GPT-4, NewBing, 自托管支持, Azure等)
📦 对各种常用网站的集成适配 (Reddit, Quora, YouTube, GitHub, GitLab, StackOverflow, Zhihu, Bilibili) (受到wimdenherder启发)
🔍 对所有主流搜索引擎的适配, 并支持自定义查询以支持额外的站点
🧰 框选工具与右键菜单, 执行各种你的需求, 如翻译, 总结, 润色, 情感分析, 段落划分, 代码解释, 问询
🗂️ 静态卡片支持浮出聊天框, 进行多分支对话
🖨️ 随意保存你的完整对话记录, 或进行局部复制
🎨 强大的渲染支持, 不论是代码高亮, 还是复杂数学公式
🌍 多语言偏好支持
📝 自定义API地址支持
⚙️ 所有站点适配与工具均可自由开关, 随时停用你不需要的模块
💡 工具与站点适配开发易于扩展, 对于开发人员易于自定义, 请查看开发&贡献部分
😉 此外, 如果回答有任何不足, 直接聊天解决!
```

- **点评:此神软可代替 chathub，writely，BingGPT，openai-translator！我愿称最强**！
  运行界面
  ![CleanShot 2023-04-11 at 09.53.54@2x.png](https://cloudflare-ipfs.com/ipfs/bafybeigoczg43r3st2gtd6ddraxcpbs47fffczsqzeqrajynu6k7ykoznm)
  ![CleanShot 2023-04-11 at 09.54.41@2x.png](https://cloudflare-ipfs.com/ipfs/bafybeifvfyzl7t5fi7d6pyi3uk6vqui4urkpxt55wptx6w5i5tv3ohqtya)
  ![CleanShot 2023-04-11 at 09.57.54@2x.png](https://cloudflare-ipfs.com/ipfs/bafkreifstlkz63usuvlldwbc2qywqsaidproq4pdr3egrospd6vat35tcu)
  **Github 链接：[ChatGPT Box](https://github.com/josStorer/chatGPTBox)**

---

## BingGPT

![icon.min.2.png](https://cloudflare-ipfs.com/ipfs/bafkreiaymnzzvpxcqzd4oqhnkbskaxtd5hww43pgdz6lyfyeyg2ru3dd7i)

> 新必应人工智能聊天的桌面应用程序

```
与新的必应聊天，无需安装 Microsoft Edge 或浏览器插件
将完整对话导出为 Markdown、PNG 或 PDF
自定义外观（主题和字体大小）
键盘快捷键
多平台
```

- **点评:反映比 Edge 自带的快，并且稳如老狗**
  运行界面
  ![CleanShot 2023-04-11 at 20.07.59@2x.png](https://cloudflare-ipfs.com/ipfs/bafybeia4tjsixyeakgw5eb72tfuacy2k4uaq4z4du3s7pvwde2mhjj5onu)

**Github 链接：[BingGPT](https://github.com/dice2o/BingGPT)**

---

## ChatGPT Web

> 支持双模型，提供了两种非官方 ChatGPT API 方法

```
[✓] 双模型
[✓] 多会话储存和上下文逻辑
[✓] 对代码等消息类型的格式化美化处理
[✓] 访问权限控制
[✓] 数据导入、导出
[✓] 保存消息到本地图片
[✓] 界面多语言
[✓] 界面主题
```

- **点评:部署在 docker 超方便，接入我国内亲朋使用**
  ![c2.png](https://cloudflare-ipfs.com/ipfs/bafkreih5qbmdypmn5dabmpz5dedae2eg74arz6hxp53o4cwe4lxauq2dgq)
  ![c1.png](https://cloudflare-ipfs.com/ipfs/bafkreigf7ba36nfxs7fi5ayvtewdg4mhyuz4tq6mrqzhvc7yy36jgtmldm)

**Github 链接：[Chatgpt-web](https://github.com/Chanzhaoyu/chatgpt-web)**

---
