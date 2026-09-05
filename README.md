# Hi，我是晶晶 👋

**中文（默认）** · [English](README.en.md)

前端开发工程师，也是 **vibe coding** 的忠实实践者。我始终相信「代码是自我表达的一种媒介」——借助 Coding Agent 的帮助，把一个个想法变成真正能用的产品：浏览器插件、DSH 插件、Agent Skills、微信小程序……持续捣鼓，持续发布。

---

## 🎮 your life story · 林间拾忆

<p align="center">
  <a href="https://xiaojing-511.github.io/your-life-story/">
    <img src="https://raw.githubusercontent.com/Xiaojing-511/Xiaojing-511/main/assets/your-life-story-hero.jpg" width="340" alt="your life story 游戏实机画面" />
  </a>
</p>

> **把人生经历，走成一场游戏。** 一款纯前端的步行叙事小游戏——AI 把你真实的人生素材生成专属故事，你沿着林间小路拾起散落的回忆，走到尽头，未完待续。零依赖、零后端、双击即玩，整个项目由 Coding Agent 协作构建。

- 🤖 **AI 生成人生故事**：接入智谱 GLM（`glm-4-flash` 免费）把口述素材整理成按年龄排列的叙事；固定 JSON Schema 输出、emoji / 颜色受控、输出不合规自动重试，AI 生成质量全程可控
- 🎙️ **语音输入素材**：浏览器原生语音识别，边说边生成，不用打字
- 🧭 **创新的叙事玩法**：「人生」被做成一条可以走进去的路——拾起路边物品读回忆、打字机叙事、程序化 Web Audio 背景音乐与风声音效，零音频素材文件
- ✨ **双模式创作**：AI 智能生成（免费 GLM Key）与 ✍️ 手动创作随时切换、默认智能匹配——没配 Key 打开就能写，非技术用户零门槛
- 🖼️ **回忆多媒体**：每段回忆可配照片 / 小视频（照片自动压缩、本地存储），内置旅程自带插画与短视频示例
- 🎵 **角色与专属 BGM**：每个故事有自己的角色（👦 / 👧）和专属背景音乐，游玩时自动启用；不配则用内置抒情 BGM
- 🔗 **分享即游戏 · 两代方案**：文字版把故事压缩进链接、开链接即玩；再配 CloudBase 可发**云端完整版**——照片 / 视频 / BGM 一起打包、短 ID 链接、打开即完整体验、随时可撤回
- 🌍 **多语言 · 纯本地**：中英界面一键切换并记住偏好；数据全部存本机（localStorage + IndexedDB），隐私优先

▶️ [**your-life-story**](https://github.com/Xiaojing-511/your-life-story) · 开源仓库
🕹️ [**在线试玩**](https://xiaojing-511.github.io/your-life-story/) · GitHub Pages 部署

---

## ☕ 疯狂咖啡 · 饮品点单 SaaS

<p align="center">
  <a href="https://crazy-coffee-landing-cloud1-7gjfr85i3b664708.webapps.tcloudbase.com/">
    <img src="https://raw.githubusercontent.com/Xiaojing-511/Xiaojing-511/main/assets/coffee-landing-hero.jpg" width="300" alt="疯狂咖啡官网首页" />
  </a>
</p>

> **让每一杯咖啡，都拥有自己的小程序。** 一套代码、一个云环境，承载多家咖啡店的多店铺点单 SaaS——顾客扫码即点单，商家在手机后台接单、制作、核销，全流程开箱即用。

- 🏪 **多店铺 SaaS**：一个云环境承载多家店，商家白名单（openid）一键开通，随开随用
- 📱 **双模式点单**：顾客扫码自点 / 前台代客下单，订单统一管理
- ✅ **订单全流程**：接单 → 制作 → 核销，状态实时同步
- ☁️ **腾讯云 TCB 云开发**：云函数 + 云数据库 + 云存储，无服务器架构，低成本快速上线
- 💳 **支付即插即用**：内置模拟支付跑通全流程，接入微信支付只需替换一个动作

▶️ [**coffee-order-wechat-miniprogram**](https://github.com/Xiaojing-511/coffee-order-wechat-miniprogram) · 开源仓库
🌐 [**SaaS 售卖官网**](https://crazy-coffee-landing-cloud1-7gjfr85i3b664708.webapps.tcloudbase.com/) · 宣传落地页（首页扫码即可体验点单）

---

## 📝 footprint-daily · 每日足迹日报

> **把一天的学习与思考，自动沉淀成可检索的个人档案。** 基于 ActivityWatch + LLM（默认 DeepSeek），每天 21:00 自动生成当日「足迹」日报并写入 Notion——今天学习了什么、实践了什么、从一个小问题如何延伸到其他问题、效率与学习质量如何优化。零第三方依赖（Node 18+ 内置 fetch）、本地聚合、密钥不入库。

- 📊 **客观数据驱动**：从 ActivityWatch 拉取当日时间线，本地聚合应用 / 内容 / 会话 / 活跃时长；数据面板本地计算，不靠 AI 编造
- 🧩 **思路延伸还原**：LLM 根据带时间戳的时间线，重建「小问题 → 延伸问题」的完整思考链条
- 📝 **随手记零格式**：在 Notion 固定页面随手记，按创建时间自动归到当天
- ⏰ **全自动沉淀**：macOS launchd / Linux cron 定时 21:00，错过自动补跑，按日期查重
- 🔒 **隐私优先**：ActivityWatch 数据仅本地处理，只发送聚合文本给 LLM

🔗 [**footprint-daily**](https://github.com/Xiaojing-511/footprint-daily) · 开源仓库

---

## ⭐ 更多精选项目

🧩 [**wordwise-extension**](https://github.com/Xiaojing-511/wordwise-extension) - 划词翻译助手：中英互译、网络翻译、点击朗读、已学习标记（Manifest V3）

📚 [**reading-list-extension**](https://github.com/Xiaojing-511/reading-list-extension) - 阅读列表插件：一键把任意网页 / 链接加入「稍后读」，数据纯本地存储

🔁 [**dsh-web-restart**](https://github.com/Xiaojing-511/dsh-web-restart) - DSH Web 一键重启插件对：浏览器里一个可拖拽按钮，点一下重启 DeepSeek Harness Web GUI

📦 [**my-skills**](https://github.com/Xiaojing-511/my-skills) - 个人编写的 Coding Agent Skill 集合（Agent-neutral，可复用、可验证、可迭代）

🧭 [**awesome-skills**](https://github.com/Xiaojing-511/awesome-skills) - 收藏的 Cursor Agent Skill 链接清单（awesome list 风格，持续更新）

---

## 🧩 浏览器插件

为日常浏览体验打磨的小工具：全部 Manifest V3、原生 JavaScript、零依赖零构建。

🧩 [**wordwise-extension**](https://github.com/Xiaojing-511/wordwise-extension) - 划词即译：中英互译 + 网络翻译双源对照、点击朗读、重复选词标记「已学习 N 次」，Shadow DOM 注入不受页面样式干扰

📚 [**reading-list-extension**](https://github.com/Xiaojing-511/reading-list-extension) - 一键收藏网页 / 链接到阅读列表：右键菜单添加、已读 / 未读管理、自动去重、一键清空，数据保存在本地

## 🤖 DSH 插件

为 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)（DSH）生态贡献的插件。

🔁 [**dsh-web-restart**](https://github.com/Xiaojing-511/dsh-web-restart) - DSH Web 一键重启插件对：host 插件注册重启 API + client 插件注入**可拖拽**悬浮按钮（位置自动记忆）；仅接受本机回环请求，零配置挂载，纯本地不联网

## 🎓 Coding Agent Skills

与 Coding Agent 协作的经验沉淀。

📦 [**my-skills**](https://github.com/Xiaojing-511/my-skills) - 个人编写的各类 Coding Agent Skill 集合：渐进式加载、自检清单、结构化分层，Agent-neutral 设计，适配 Cursor / Claude Code / Codex 等

🧭 [**awesome-skills**](https://github.com/Xiaojing-511/awesome-skills) - 收藏的 Cursor Agent Skill 链接清单：官方资源、社区合集、单点 Skill、编写指南，方便查找与对比

## 🛠️ 小程序 & 个人项目

从「想做一个东西」到「真的能用」的日常项目。

💼 [**qiuzhidi-app**](https://github.com/Xiaojing-511/qiuzhidi-app) - 求职帝小程序

🎬 [**mobile-media**](https://github.com/Xiaojing-511/mobile-media) - 集剧集、书籍浏览、音乐播放、智能机器人闲聊于一体的移动端 APP

✍️ [**myBlog**](https://github.com/Xiaojing-511/myBlog) - 个人技术博客

## 📚 学习与练习

一路走来的脚印：毕业设计、前后端贯通、微前端、数据可视化等。

🎓 [**campus-website**](https://github.com/Xiaojing-511/campus-website) - 毕业设计：大学生校园网站（前端）

🔗 [**nodeTestProject**](https://github.com/Xiaojing-511/nodeTestProject) - Node（Koa）服务 + Vue-CLI 前端项目，打通前后端通信

📋 [**kanban**](https://github.com/Xiaojing-511/kanban) - 需求看板

🏗️ [**qiankun-main**](https://github.com/Xiaojing-511/qiankun-main) - qiankun 微前端主应用（配套 [qiankun-micro-react](https://github.com/Xiaojing-511/qiankun-micro-react) / [qiankun-micro-vue](https://github.com/Xiaojing-511/qiankun-micro-vue) 微应用）

📊 [**test-project**](https://github.com/Xiaojing-511/test-project) - ECharts 与 Ant G2Plot 图表库示例、按需引入实践

---

## 🧰 技术栈

TypeScript · JavaScript · Vue 3 · React · Node.js · Manifest V3 浏览器扩展 · 微信小程序 · qiankun 微前端 · Vite · 腾讯云 TCB 云开发 · Canvas 游戏 / Web Audio · Coding Agent / AI 编程

---

<p align="center"><i>持续构建，持续发布 ✨ —— 欢迎 Star ⭐ 或提 Issue 交流</i></p>
