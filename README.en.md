# ntars (Bai Jiuxuan)

**Endless progress, endless possibility.**

[简体中文](README.md) | **English** | [日本語](README.ja.md) | [한국어](README.ko.md) | [Français](README.fr.md) | [Русский](README.ru.md) | [Español](README.es.md) | [العربية](README.ar.md)

Independent developer, founder of Ntarstudio. Building software that is local-first, data-sovereign, and auditable.

| | |
| --- | --- |
| Chinese name | 白玖玄 (Bai Jiuxuan) |
| English name | ntars |
| Role | Independent developer · Ntarstudio |
| Working on | Desktop AI companion, Chinese metaphysics corpus, studio website, cross-architecture packaging tool |
| Based in | Chengdu, China |
| Website | <https://www.ntars.cn/> |
| Email | <ntars@qq.com> · <ntarsx@163.com> |
| Sponsor | <https://ifdian.net/a/ntars/> |

---

## Projects

| Project | What it is | Stack | Status | License | Entry |
| --- | --- | --- | --- | --- | --- |
| **[Xael](https://github.com/ntars/Xael)** | Offline Chinese metaphysics corpus, 22 functions computed from first principles, no lookup tables, no network | JavaScript (zero dependencies) | 5.0.0 released | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |
| **[Ondra](https://github.com/ntars/Ondra)** | Fully pluggable AI companion, 75 loadable plugins, all data stays local, on macOS / Windows / Android | TypeScript · Rust · Tauri | Beta `1.3.0-alpha` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Webroit](https://github.com/ntars/Webroit)** | An Android toolbox in the browser: ADB and Fastboot over WebUSB, 152 features | TypeScript · Vite · WebUSB | 0.1.0 released | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | Bidirectional macOS ↔ Windows interoperability suite; all four directions complete, with MCP access | Node.js · Python · Rust | Available | MIT | [repository](https://github.com/ntars/Wacmin) |
| **[TapMC](https://github.com/ntars/TapMC)** | A multi-platform Minecraft Java Edition launcher: manage versions and mods on macOS, Windows, Linux, Android and iOS, and give Java Edition on phones the touch feel of Bedrock Edition | Rust · Tauri 2 | Early development | Apache-2.0 / MIT | [repository](https://github.com/ntars/TapMC) |
| **[Desop](https://github.com/ntars/Desop)** | Windows desktop beautification suite: dock, menu bar, widgets, dynamic island | TBD | Planned | Apache-2.0 / MIT | [repository](https://github.com/ntars/Desop) |
| **[Apex](https://github.com/ntars/Apex)** | Studio website and project index; one HTML file, one stylesheet, a few plain scripts | HTML · CSS · Vanilla JS | Live | MIT | [www.ntars.cn](https://www.ntars.cn/) |

**Seven projects = the seven cards on the official site.** The three lists (site cards, this page, each project README) stay identical; a change in one is reflected in the others.

**Status wording is strictly separated**: released, beta, available, early development and planned are never mixed, and nothing planned is described as built.

---

## Four principles

These are not slogans; each one maps to a constraint you can verify in the code.

**1. Local-first. Data never leaves the user's device.**
Ondra has no accounts, no community, no share button, no telemetry. Xael runs every computation offline and calls no third-party API. If a feature cannot meet this, it does not ship.

**2. Compute it, do not look it up.**
Xael derives the lunar calendar from astronomical series — solar longitude and true new moons — instead of shipping an almanac table, because tables are wrong on boundary days. The value of a tool is being able to point at where a result went wrong.

**3. Zero frameworks, zero build steps, zero runtime dependencies.**
Apex is a single-page static site with no framework, no build, no backend. Xael's core is plain JavaScript with no npm packages. Fewer dependencies means a higher chance it still runs three years from now.

**4. Write the conventions down. Code and documentation must not disagree.**
School choices, version semantics, and status wording (site is live ≠ software is installable) all live in files. Anywhere two sources disagree is a defect, not a style difference.

---

## Stack

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
![WeChat Mini Program](https://img.shields.io/badge/WeChat%20Mini%20Program-07C160?style=flat-square&logo=wechat&logoColor=white)

---

## Find me

| Channel | Address |
| --- | --- |
| GitHub | <https://github.com/ntars> |
| Website | <https://www.ntars.cn/> |
| Xael | <https://x.ntars.cn/> |
| Ondra | <https://ai.ntars.cn/> |
| WeChat Official Account | 玄玖灵犀 |
| Email | <ntars@qq.com> · <ntarsx@163.com> |
| Douyin | [@俟约](https://v.douyin.com/eq8QjttKQnA/) |
| Bilibili | [space.bilibili.com/499925438](https://space.bilibili.com/499925438) |
| Afdian | <https://ifdian.net/a/ntars/> |

For bugs and feature requests, open an issue on the relevant repository. For partnerships and licensing, use email with the project name in the subject (for example `[Ondra]`).

---

<sub>Ntarstudio · ICP Filing 蜀ICP备2026027050号 · ©2024–2026 Ntarstudio. All Rights Reserved.</sub>