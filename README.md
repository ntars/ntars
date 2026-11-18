# 白玖玄 ntars

**无限进步，无限可能。**

[简体中文](README.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Français](README.fr.md) | [Русский](README.ru.md) | [Español](README.es.md) | [العربية](README.ar.md)

独立开发者，星玖工作室（Ntarstudio）创始人。做本地优先、数据自主、结论可复核的软件。

| | |
| --- | --- |
| 中文名 | 白玖玄 |
| 英文名 | ntars |
| 身份 | 独立开发者 · 星玖工作室 Ntarstudio |
| 在做什么 | 桌面 AI 陪伴体、中华术数文献库、跨平台启动器、桌面美化、跨架构互通 |
| 常驻 | 中国成都 |
| 官网 | <https://www.ntars.cn/> |
| 邮箱 | <ntars@qq.com> · <ntarsx@163.com> |
| 赞助 | <https://ifdian.net/a/ntars/> |

---

## 在做的事

七个项目，按状态分为「已发布 / 开发中」与「排期开发」两组。**官网 <https://www.ntars.cn/> 是同一份清单的另一处呈现**——两处口径一致，任何一处变更都会同步另一处。

| 项目 | 是什么 | 技术 | 状态 | 许可 | 入口 |
| --- | --- | --- | --- | --- | --- |
| **[玄玖灵犀 Xael](https://github.com/ntars/Xael)** | 本地离线的中华文化术数文献库，22 项功能从零演算，不查表、不联网 | JavaScript（零依赖） | 5.0.0 已上线 | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |
| **[空谷 Ondra](https://github.com/ntars/Ondra)** | 全插件式 AI 陪伴体，75 个可装卸插件，数据全留本机，macOS / Windows / Android 三端 | TypeScript · Rust · Tauri | 内测 `1.3.0-alpha` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Webroit](https://github.com/ntars/Webroit)** | 浏览器里的安卓玩机工具箱，WebUSB 直连 ADB 与 Fastboot，152 项能力 | TypeScript · Vite · WebUSB | 0.1.0 已上线 | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | macOS 与 Windows 的双向互通套件，四个方向全部完成，并开放 MCP 接入 | Node.js · Python · Rust | 可用 | MIT | [仓库](https://github.com/ntars/Wacmin) |
| **[TapMC](https://github.com/ntars/TapMC)** | 一款多端 Minecraft Java 版启动器：可在 mac / win / linux / android / ios 上管理版本与模组，并赋予手机端的 Java 版拥有基岩版那样的触屏手感 | Rust · Tauri 2 | 开发初期 | Apache-2.0 / MIT | [仓库](https://github.com/ntars/TapMC) |
| **[Desop](https://github.com/ntars/Desop)** | Windows 端桌面美化套装，dock、顶部栏、小组件、灵动岛 | 待定 | 排期开发 / Planned | Apache-2.0 / MIT | [仓库](https://github.com/ntars/Desop) |
| **[Apex](https://github.com/ntars/Apex)** | 工作室官网与项目总索引，一个 HTML、一份样式表、几个原生脚本 | HTML · CSS · Vanilla JS | 已上线 | MIT | [www.ntars.cn](https://www.ntars.cn/) |

**七个项目 = 官网首页的七张卡片。** 三处清单（官网卡片、本页、各项目 README）口径一致，任一处变更都会同步其余两处。

**状态口径严格区分**：已上线、内测、可用、开发初期、排期开发五种状态不混用，不把规划说成已实现。

---

## 与官网的联动

本页与官网共用同一份项目清单，分工如下：

| 位置 | 定位 | 内容侧重 |
| --- | --- | --- |
| **本页（GitHub 自述文件）** | 给开发者的索引 | 仓库直链、技术栈、许可、子项目结构 |
| **[官网 www.ntars.cn](https://www.ntars.cn/)** | 给访客的门牌 | 品牌识别、项目卡片、联系入口 |

**双向链接**：

- 官网顶部与页脚均指向本仓库与本页；
- 本页的「官网」字段指向 <https://www.ntars.cn/>，项目卡片指向各项目独立站点；
- 两个已上线项目各有独立官网（`ai.ntars.cn`、`x.ntars.cn`），本页与 Apex 均直连该地址，不重复建设内容。

**口径一致的三条纪律**：

1. **未上线项目不进官网卡片**——排期项目只在 GitHub 侧出现，官网不展示，避免访客点进去发现没有可下载内容；
2. **状态变化三处同改**——项目上线、下线或换域名时，本页、Apex 的 `PROJECTS` 数组、项目自身的 README 必须同时更新；
3. **已下线项目不得以任何形式回流**——不出现在本页、官网页面、关键词或结构化数据里。

---

## 四条做法

这些不是口号，是每个项目里都能翻到的实际约束。

**一、本地优先，数据不离开用户的设备。**
Ondra 没有账号、没有社区、没有分享按钮、没有遥测；Xael 离线跑完全部演算，不调用任何第三方接口。做不到这一点的功能，宁可不做。

**二、不查表，能算的就算一遍。**
Xael 的农历靠天文级数实时求太阳黄经与日月合朔，不依赖历表——查表法在边界日必错。工具类软件的价值在于出错时能被指出错在哪，而不是给一个无从复核的答案。

**三、零框架、零构建、零运行时依赖。**
Apex 是单页静态站，没有框架、没有构建、没有后端；Xael 内核纯 JavaScript，不引入任何 npm 包。依赖越少，三年后还能跑的概率越高。

**四、口径写进文档，代码与文档不允许各说一套。**
流派选择、版本语义、状态口径（官网在跑 ≠ 软件能装）都落成文件。凡是两处说法不一致，就是缺陷，不是风格差异。

---

## 技术栈

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![微信小程序](https://img.shields.io/badge/微信小程序-07C160?style=flat-square&logo=wechat&logoColor=white)

---

## 找到我

| 渠道 | 地址 |
| --- | --- |
| GitHub | <https://github.com/ntars> |
| 官网（项目总览） | <https://www.ntars.cn/> |
| 玄玖灵犀 | <https://x.ntars.cn/> |
| 空谷 Ondra | <https://ai.ntars.cn/> |
| 微信公众号 | 玄玖灵犀 |
| 邮箱 | <ntars@qq.com> · <ntarsx@163.com> |
| 抖音 | [@俟约](https://v.douyin.com/eq8QjttKQnA/) |
| 哔哩哔哩 | [space.bilibili.com/499925438](https://space.bilibili.com/499925438) |
| 爱发电 | <https://ifdian.net/a/ntars/> |

项目问题请走对应仓库的 Issues；合作与授权走邮箱，主题带上项目名（如 `[Ondra]`）。**只想看有哪些项目，直接去官网 <https://www.ntars.cn/>**，那里的卡片与上面两张表同源。

---

<sub>星玖工作室 Ntarstudio · 蜀ICP备2026027050号 · ©2024–2026 Ntarstudio. All Rights Reserved.</sub>