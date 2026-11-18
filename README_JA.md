# ntars（白玖玄）

**限りなき前進、限りなき可能性。**

[简体中文](README.md) | [English](README_EN.md) | **日本語** | [한국어](README_KO.md) | [Français](README_FR.md) | [Русский](README_RU.md) | [Español](README_ES.md) | [العربية](README_AR.md)

独立開発者。星玖工作室（Ntarstudio）創業者。ローカル優先・データ主権・検証可能なソフトウェアを作っています。

| | |
| --- | --- |
| 中国語名 | 白玖玄（バイ・ジウシュエン） |
| 英語名 | ntars |
| 立場 | 独立開発者 · 星玖工作室 Ntarstudio |
| 取り組み | デスクトップ AI コンパニオン、中華術数文献ライブラリ、スタジオ公式サイト、クロスアーキテクチャ用パッケージングツール |
| 拠点 | 中国・成都 |
| サイト | <https://www.ntars.cn/> |
| メール | <ntars@qq.com> · <ntarsx@163.com> |
| 支援 | <https://ifdian.net/a/ntars/> |

## 制作中のプロジェクト

| プロジェクト | 内容 | 技術 | 状態 | ライセンス | 入口 |
| --- | --- | --- | --- | --- | --- |
| **[Xael（玄玖霊犀）](https://github.com/ntars/Xael)** | オフライン動作する中華文化術数文献ライブラリ。22 機能をゼロから演算、表引きなし、通信なし | JavaScript（依存ゼロ） | 5.0.0 公開済み | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |
| **[Ondra（空谷）](https://github.com/ntars/Ondra)** | 全プラグイン方式の AI コンパニオン。UI はプラグインの投影だけを読み、感情・記憶・文脈が中核、データはすべて端末内 | Flutter · Cordis 4.1.0 | ベータ `2.0.0-alpha` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Webroit](https://github.com/ntars/Webroit)** | ブラウザで動く Android 玩机ツールボックス。WebUSB で ADB と Fastboot に直接接続、152 機能 | TypeScript · Vite · WebUSB | 0.1.0 公開済み | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | macOS と Windows の双方向相互運用スイート。4 方向すべて完了、MCP 接続も提供 | Node.js · Python · Rust | 利用可能 | MIT | [リポジトリ](https://github.com/ntars/Wacmin) |
| **[Gitrule-skill](https://github.com/ntars/Gitrule-skill)** | プロジェクト全ライフサイクルを覆う汎用規範テンプレート。規範 66 篇を中英二言語で提供し、CLI・MCP・Skill の三形態を同梱 | Markdown · Python CLI | 提供済み | MIT | [リポジトリ](https://github.com/ntars/Gitrule-skill) |
| **[TapMC](https://github.com/ntars/TapMC)** | モジュール化可能なマルチプレイ砂場ゲームの骨組み。Flutter の 7 端末フロントエンドと Java サーバーを 1 本の JSON-RPC 2.0 契約でつなぐ | Flutter · Java 21 | 骨組み段階 | Apache-2.0 / MIT | [リポジトリ](https://github.com/ntars/TapMC) |
| **[Desop](https://github.com/ntars/Desop)** | Windows 向けデスクトップ美化スイート：dock、メニューバー、ウィジェット、ダイナミックアイランド | 未定 | 計画中 / Planned | Apache-2.0 / MIT | [リポジトリ](https://github.com/ntars/Desop) |
| **[Apex](https://github.com/ntars/Apex)** | スタジオ公式サイトとプロジェクト総索引。HTML 一枚、スタイルシート一枚、素のスクリプト数本 | HTML · CSS · Vanilla JS | 公開中 | MIT | [www.ntars.cn](https://www.ntars.cn/) |
| **[Flutter-IDE](https://github.com/ntars/Flutter-IDE)** | ソース優先の Flutter ビジュアル構築 IDE。キャンバス操作から、ツールなしでも保守できる Dart を出力 | Dart · Flutter | 骨組み段階 `0.1.0` | Apache-2.0 / MIT | [リポジトリ](https://github.com/ntars/Flutter-IDE) |

**9 プロジェクト = 公式サイトの 9 枚のカード。** 3 か所のリスト（サイトのカード、本ページ、各プロジェクトの README）は同一で、1 か所を変えれば残りも同期します。

**状態の表現は厳密に区別します**：公開済み、提供済み、ベータ、利用可能、骨組み段階、計画中の 6 つを混用せず、計画を実装済みとして書きません。

---

## 公式サイトとの連動

本ページと公式サイトは同じプロジェクト一覧を共有し、役割を分けています。

| 場所 | 役割 | 内容の重点 |
| --- | --- | --- |
| **本ページ（GitHub プロフィール）** | 開発者向けの索引 | リポジトリ直リンク、技術スタック、ライセンス、サブプロジェクト構成 |
| **[www.ntars.cn](https://www.ntars.cn/)** | 訪問者向けの看板 | ブランド認知、プロジェクトカード、連絡入口 |

双方向リンク：サイトのヘッダーとフッターは本リポジトリを指し、本ページの入口欄は <https://www.ntars.cn/> と各プロジェクトのサイトを指します。

**表現を揃える三つの規律**：

1. **計画中のプロジェクトもカードを出す。ただし状態を明記する**——カードに「計画中」と書けば、訪問者はクリック前にダウンロードできるものが無いと分かります。隠すとかえって「もう使える」と誤読されます；
2. **状態が変わったら三か所を同時に更新**——本ページ、Apex の `PROJECTS` 配列、各プロジェクトの README；
3. **終了したプロジェクトはどの形でも再登場させない**——本ページ、サイト、キーワード、構造化データのいずれにも載せません。

---

## 四つの方針

スローガンではなく、いずれもコード上で確認できる制約です。

**一、ローカル優先。データは端末から出さない。**
Ondra にはアカウントもコミュニティも共有ボタンもテレメトリもありません。Xael は全演算をオフラインで実行し、外部 API を一切呼びません。これを満たせない機能は実装しません。

**二、表を引かず、計算する。**
Xael の暦は天文級数から太陽黄経と真の朔をその場で求め、暦表を持ちません。表引きは境界日で必ず誤るからです。道具の価値は、結果が誤ったときにどこが誤りか指せることにあります。

**三、フレームワークなし、ビルドなし、実行時依存なし。**
Apex はフレームワークもビルドもバックエンドも持たない単一ページの静的サイトです。Xael の中核は npm パッケージを一切使わない素の JavaScript です。依存が少ないほど、三年後も動く確率が上がります。

**四、取り決めは文書に落とす。コードと文書は食い違ってはならない。**
流派の選択、バージョンの意味、状態の書き方（サイトが動く ≠ ソフトが入る）はすべてファイルに残します。二か所で記述が食い違えば、それは様式の差ではなく不具合です。

---

## 技術スタック

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

## 連絡先

| 窓口 | アドレス |
| --- | --- |
| GitHub | <https://github.com/ntars> |
| 公式サイト | <https://www.ntars.cn/> |
| Xael | <https://x.ntars.cn/> |
| Ondra | <https://ai.ntars.cn/> |
| WeChat 公式アカウント | 玄玖灵犀 |
| メール | <ntars@qq.com> · <ntarsx@163.com> |
| 抖音（Douyin） | [@俟约](https://v.douyin.com/eq8QjttKQnA/) |
| ビリビリ | [space.bilibili.com/499925438](https://space.bilibili.com/499925438) |
| 愛発電（Afdian） | <https://ifdian.net/a/ntars/> |

不具合や要望は各リポジトリの Issue へ。提携・ライセンスについてはメールで、件名にプロジェクト名（例：`[Ondra]`）を付けてください。

---

<sub>星玖工作室 Ntarstudio · ICP 備案 蜀ICP备2026027050号 · ©2024–2026 Ntarstudio. All Rights Reserved.</sub>
