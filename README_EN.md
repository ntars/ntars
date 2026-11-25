# ntars (Bai Jiuxuan)

**Endless progress, endless possibility.**

[简体中文](README.md) | **English** | [日本語](README_JA.md) | [한국어](README_KO.md) | [Français](README_FR.md) | [Русский](README_RU.md) | [Español](README_ES.md) | [العربية](README_AR.md)

Independent developer, founder of Ntarstudio. Building software that is local-first, data-sovereign, and auditable.

| | |
| --- | --- |
| Chinese name | 白玖玄 (Bai Jiuxuan) |
| English name | ntars |
| Role | Independent developer · Ntarstudio |
| Working on | Desktop AI companion, Chinese metaphysics corpus, studio website, cross-architecture packaging tool, Chinese-first programming language |
| Based in | Chengdu, China |
| Website | <https://www.ntars.cn/> |
| Email | <ntars@qq.com> · <ntarsx@163.com> |
| Sponsor | <https://ifdian.net/a/ntars/> |

---

## Projects

Thirteen projects, grouped by status — released or delivered first, in development in the middle, planned last — and sorted by Latin name within each group.

| Project | What it is | Stack | Status | License | Entry |
| --- | --- | --- | --- | --- | --- |
| **[Apex](https://github.com/ntars/Apex)** | Studio website and project index; one HTML file, one stylesheet, a few plain scripts | HTML · CSS · Vanilla JS | Live | MIT | [www.ntars.cn](https://www.ntars.cn/) |
| **[Gitrule-skill](https://github.com/ntars/Gitrule-skill)** | Universal specification set covering the project lifecycle; 66 specs in Chinese and English with CLI, MCP and Skill adapters | Markdown · Python CLI | Delivered | MIT | [repository](https://github.com/ntars/Gitrule-skill) |
| **[Ondra](https://github.com/ntars/Ondra)** | Plugin-first AI companion: the UI reads only plugin projections; emotion, memory and context are the core mechanisms; all data stays local | Flutter · Cordis 4.1.0 | Beta `2.0.0-alpha` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | Bidirectional macOS ↔ Windows interoperability suite; all four directions complete, with MCP access | Node.js · Python · Rust | Available | MIT | [repository](https://github.com/ntars/Wacmin) |
| **[Webroit](https://github.com/ntars/Webroit)** | An Android toolbox in the browser: ADB and Fastboot over WebUSB, 26 features shipped, 152 planned | TypeScript · Vite · WebUSB | 0.1.0 released | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Xael](https://github.com/ntars/Xael)** | Offline Chinese metaphysics corpus, 22 functions computed from first principles, no lookup tables, no network | JavaScript (zero dependencies) | 5.0.0 released | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |
| **[Amphoreus](https://github.com/ntars/Amphoreus)** | A watch-only Amphoreus world simulator where the seed decides history, with a pure-CSS recreation of the in-game Tarot Book | Python (stdlib) · SQLite | In development | MIT | [repository](https://github.com/ntars/Amphoreus) |
| **[Flutter-IDE](https://github.com/ntars/Flutter-IDE)** | Source-first visual IDE for Flutter; canvas drag produces Dart you can maintain without the tool | Dart · Flutter | Skeleton `0.1.0` | Apache-2.0 / MIT | [repository](https://github.com/ntars/Flutter-IDE) |
| **[NovaKit](https://github.com/ntars/NovaKit)** | The one offline desktop toolkit to install on a fresh machine, covering file, image, text and system utilities | Rust · Tauri 2 | Skeleton stage | Apache-2.0 / MIT | [repository](https://github.com/ntars/NovaKit) |
| **[Relax](https://github.com/ntars/Relax)** | A self-hosted family hub for chat, schedules, files and photos, with all data staying on the home computer | Rust · Tauri 2 · SQLite · React | Skeleton stage | Apache-2.0 / MIT | [repository](https://github.com/ntars/Relax) |
| **[Serica](https://github.com/ntars/Serica)** | A Chinese-first programming language for multi-device sync apps; the seed compiler emits native executables directly, with no C and no LLVM | Go (seed) · self-hosting | Skeleton `pre-alpha` | Apache-2.0 / MIT | [repository](https://github.com/ntars/Serica) |
| **[TapMC](https://github.com/ntars/TapMC)** | A moddable multiplayer sandbox game skeleton: a Flutter front end on seven platforms plus a Java server, coupled by one JSON-RPC 2.0 contract | Flutter · Java 21 | Skeleton stage | Apache-2.0 / MIT | [repository](https://github.com/ntars/TapMC) |
| **[Desop](https://github.com/ntars/Desop)** | Windows desktop beautification suite: dock, menu bar, widgets, dynamic island | TBD | Planned | Apache-2.0 / MIT | [repository](https://github.com/ntars/Desop) |

**Thirteen projects = the thirteen cards on the official site.** The three lists (site cards, this page, each project README) stay identical; a change in one is reflected in the others.

**Status wording is strictly separated**: released, beta, available, skeleton stage and planned are never mixed, and nothing planned is described as built.

## Keeping the site in step

This page and the official site share one project list, with a division of labour:

| Place | Role | Focus |
| --- | --- | --- |
| **This page (GitHub profile README)** | An index for developers | Direct repository links, stack, licence, sub-project structure |
| **[www.ntars.cn](https://www.ntars.cn/)** | A nameplate for visitors | Brand identity, project cards, contact entry |

**Two-way links**:

- The site header and footer both point to this repository and this page;
- This page's "entry" fields point to <https://www.ntars.cn/> and to each project's own site;
- The two live products have their own sites (`ai.ntars.cn`, `x.ntars.cn`); this page and Apex link straight to them and do not duplicate their content.

**Three rules that keep the wording identical**:

1. **Planned projects still get a card, with the status stated** — the card says "Planned", so a visitor knows before clicking that there is nothing to download; hiding it invites the opposite reading;
2. **A status change is updated in three places at once** — this page, Apex's `PROJECTS` array and the project's own README;
3. **A retired project never reappears in any form** — not on this page, not on the site, not in keywords or structured data.

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