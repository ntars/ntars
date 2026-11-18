# ntars (Bai Jiuxuan)

**Progrès sans fin, possibilité sans fin.**

[简体中文](README.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | **Français** | [Русский](README.ru.md) | [Español](README.es.md) | [العربية](README.ar.md)

Développeur indépendant, fondateur de Ntarstudio. Je conçois des logiciels local-first, souverains en matière de données et vérifiables.

| | |
| --- | --- |
| Nom chinois | 白玖玄 (Bai Jiuxuan) |
| Nom anglais | ntars |
| Rôle | Développeur indépendant · Ntarstudio |
| En cours | Compagnon IA de bureau, corpus de métaphysique chinoise, site du studio, outil d'empaquetage multi-architecture |
| Basé à | Chengdu, Chine |
| Site | <https://www.ntars.cn/> |
| Courriel | <ntars@qq.com> · <ntarsx@163.com> |
| Soutien | <https://ifdian.net/a/ntars/> |

---

## Projets

| Projet | Description | Technologies | État | Licence | Entrée |
| --- | --- | --- | --- | --- | --- |
| **[Xael](https://github.com/ntars/Xael)** | Corpus hors ligne de métaphysique chinoise, 22 fonctions calculées depuis les principes premiers, sans tables de correspondance, sans réseau | JavaScript (aucune dépendance) | 5.0.0 publiée | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |
| **[Ondra](https://github.com/ntars/Ondra)** | Compagnon IA entièrement modulaire, 75 plugins chargeables, toutes les données restent en local, sur macOS / Windows / Android | TypeScript · Rust · Tauri | Bêta `1.3.0-alpha` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Webroit](https://github.com/ntars/Webroit)** | Une boîte à outils Android dans le navigateur : ADB et Fastboot en WebUSB, 152 fonctions | TypeScript · Vite · WebUSB | 0.1.0 publiée | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | Suite d'interopérabilité bidirectionnelle macOS ↔ Windows ; les quatre directions terminées, avec accès MCP | Node.js · Python · Rust | Disponible | MIT | [dépôt](https://github.com/ntars/Wacmin) |
| **[TapMC](https://github.com/ntars/TapMC)** | Lanceur Minecraft Java Edition multiplateforme sur macOS / Windows / Linux / Android / iOS, offrant le toucher de Bedrock sur mobile | Rust · Tauri 2 | Développement initial | Apache-2.0 / MIT | [dépôt](https://github.com/ntars/TapMC) |
| **[Desop](https://github.com/ntars/Desop)** | Suite de personnalisation du bureau Windows : dock, barre de menus, widgets, îlot dynamique | À définir | Planifié | Apache-2.0 / MIT | [dépôt](https://github.com/ntars/Desop) |
| **[Apex](https://github.com/ntars/Apex)** | Site du studio et index des projets ; un fichier HTML, une feuille de style, quelques scripts natifs | HTML · CSS · Vanilla JS | En ligne | MIT | [www.ntars.cn](https://www.ntars.cn/) |

**Sept projets = les sept cartes du site officiel.** Les trois listes (cartes du site, cette page, README de chaque projet) restent identiques ; toute modification de l'une se répercute sur les autres.

**Les états sont strictement distingués** : publié, bêta, disponible, développement initial et planifié ne sont jamais mélangés, et rien de planifié n'est décrit comme réalisé.

---

## Quatre principes

Ce ne sont pas des slogans : chacun correspond à une contrainte vérifiable dans le code.

**1. Local-first. Les données ne quittent jamais l'appareil.**
Ondra n'a ni compte, ni communauté, ni bouton de partage, ni télémétrie. Xael exécute tous ses calculs hors ligne et n'appelle aucune API tierce. Une fonctionnalité qui ne respecte pas cette règle n'est pas livrée.

**2. Calculer plutôt que consulter.**
Le calendrier de Xael est dérivé de séries astronomiques — longitude solaire et vraies nouvelles lunes — au lieu d'embarquer une table d'almanach, car les tables se trompent aux jours limites. La valeur d'un outil réside dans la capacité à désigner l'origine d'un résultat erroné.

**3. Aucun framework, aucune étape de build, aucune dépendance d'exécution.**
Apex est un site statique d'une seule page, sans framework, sans build, sans backend. Le cœur de Xael est du JavaScript pur, sans aucun paquet npm. Moins de dépendances, c'est plus de chances que tout fonctionne encore dans trois ans.

**4. Consigner les conventions par écrit. Le code et la documentation ne doivent pas se contredire.**
Les choix d'école, la sémantique des versions et la formulation des états (le site est en ligne ≠ le logiciel est installable) figurent tous dans des fichiers. Toute divergence entre deux sources est un défaut, pas une différence de style.

---

## Technologies

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

## Me contacter

| Canal | Adresse |
| --- | --- |
| GitHub | <https://github.com/ntars> |
| Site officiel | <https://www.ntars.cn/> |
| Xael | <https://x.ntars.cn/> |
| Ondra | <https://ai.ntars.cn/> |
| Compte officiel WeChat | 玄玖灵犀 |
| Courriel | <ntars@qq.com> · <ntarsx@163.com> |
| Douyin | [@俟约](https://v.douyin.com/eq8QjttKQnA/) |
| Bilibili | [space.bilibili.com/499925438](https://space.bilibili.com/499925438) |
| Afdian | <https://ifdian.net/a/ntars/> |

Pour les anomalies et les demandes de fonctionnalités, ouvrez une issue dans le dépôt concerné. Pour les partenariats et les licences, écrivez un courriel en indiquant le nom du projet dans l'objet (par exemple `[Ondra]`).

---

<sub>Ntarstudio · Enregistrement ICP 蜀ICP备2026027050号 · ©2024–2026 Ntarstudio. All Rights Reserved.</sub>