# ntars（Бай Цзюсюань）

**Бесконечное движение вперёд, бесконечные возможности.**

[简体中文](README.md) | [English](README_EN.md) | [日本語](README_JA.md) | [한국어](README_KO.md) | [Français](README_FR.md) | **Русский** | [Español](README_ES.md) | [العربية](README_AR.md)

Независимый разработчик, основатель студии Ntarstudio. Создаю программы, работающие локально, с полным контролем над данными и проверяемыми результатами.

| | |
| --- | --- |
| Имя на китайском | 白玖玄 (Бай Цзюсюань) |
| Имя на английском | ntars |
| Роль | Независимый разработчик · Ntarstudio |
| Над чем работаю | Настольный ИИ-компаньон, корпус китайской метафизики, сайт студии, инструмент кросс-архитектурной упаковки |
| Нахожусь | Чэнду, Китай |
| Сайт | <https://www.ntars.cn/> |
| Почта | <ntars@qq.com> · <ntarsx@163.com> |
| Поддержка | <https://ifdian.net/a/ntars/> |

## Проекты

| Проект | Описание | Технологии | Состояние | Лицензия | Вход |
| --- | --- | --- | --- | --- | --- |
| **[Xael](https://github.com/ntars/Xael)** | Автономный корпус китайской метафизики: 22 функции вычисляются с нуля, без таблиц поиска и без сети | JavaScript (без зависимостей) | 5.0.0 выпущена | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |
| **[Ondra](https://github.com/ntars/Ondra)** | Полностью модульный ИИ-компаньон: интерфейс читает только проекции плагинов; эмоция, память и контекст — ядро; данные на устройстве | Flutter · Cordis 4.1.0 | Бета `2.0.0-alpha` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Webroit](https://github.com/ntars/Webroit)** | Инструментарий для Android в браузере: ADB и Fastboot через WebUSB, 152 функции | TypeScript · Vite · WebUSB | 0.1.0 выпущена | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | Набор двусторонней совместимости macOS ↔ Windows; все четыре направления завершены, есть доступ через MCP | Node.js · Python · Rust | Доступно | MIT | [репозиторий](https://github.com/ntars/Wacmin) |
| **[TapMC](https://github.com/ntars/TapMC)** | Каркас многопользовательской песочницы с поддержкой модов: фронтенд Flutter на семи платформах и сервер на Java, связанные одним контрактом JSON-RPC 2.0 | Flutter · Java 21 | Этап каркаса | Apache-2.0 / MIT | [репозиторий](https://github.com/ntars/TapMC) |
| **[Desop](https://github.com/ntars/Desop)** | Набор для оформления рабочего стола Windows: dock, строка меню, виджеты, dynamic island | Не определён | Запланировано | Apache-2.0 / MIT | [репозиторий](https://github.com/ntars/Desop) |
| **[Apex](https://github.com/ntars/Apex)** | Сайт студии и индекс проектов; один HTML-файл, одна таблица стилей, несколько нативных скриптов | HTML · CSS · Vanilla JS | Работает | MIT | [www.ntars.cn](https://www.ntars.cn/) |

**Семь проектов = семь карточек на официальном сайте.** Три списка (карточки сайта, эта страница, README каждого проекта) совпадают; изменение в одном отражается в остальных.

**Состояния строго различаются**: выпущено, бета, доступно, ранняя разработка и запланировано никогда не смешиваются, и запланированное не описывается как готовое.

---

## Синхронность с сайтом

Эта страница и официальный сайт используют один список проектов, разделяя роли.

| Место | Роль | Акцент |
| --- | --- | --- |
| **Эта страница (профиль GitHub)** | Указатель для разработчиков | Прямые ссылки на репозитории, стек, лицензия, структура подпроектов |
| **[www.ntars.cn](https://www.ntars.cn/)** | Вывеска для посетителей | Идентичность бренда, карточки проектов, контакт |

Двусторонние ссылки: шапка и подвал сайта ведут в этот репозиторий, а поля «вход» здесь ведут на <https://www.ntars.cn/> и на сайты проектов.

**Три правила единых формулировок**:

1. **Запланированный проект тоже получает карточку, но со статусом** — на карточке написано «Запланировано», и посетитель до клика знает, что скачивать нечего; скрывать — значит намекать на обратное;
2. **Смена статуса правится в трёх местах сразу** — эта страница, массив `PROJECTS` в Apex и README проекта;
3. **Снятый проект не возвращается ни в каком виде** — ни здесь, ни на сайте, ни в ключевых словах и структурированных данных.

---

## Четыре принципа

Это не лозунги: каждый принцип соответствует ограничению, которое можно проверить в коде.

**1. Локальность прежде всего. Данные не покидают устройство.**
В Ondra нет учётных записей, сообщества, кнопки «поделиться» и телеметрии. Xael выполняет все вычисления офлайн и не обращается к сторонним API. Функция, нарушающая это правило, не выпускается.

**2. Вычислять, а не искать в таблице.**
Календарь Xael выводится из астрономических рядов — истинной долготы Солнца и истинных новолуний, — а не из встроенной таблицы, поскольку таблицы ошибаются в пограничные дни. Ценность инструмента в том, чтобы указать, где именно возникла ошибка.

**3. Без фреймворков, без сборки, без зависимостей времени выполнения.**
Apex — одностраничный статический сайт без фреймворка, сборки и серверной части. Ядро Xael — чистый JavaScript без единого пакета npm. Чем меньше зависимостей, тем выше шанс, что всё заработает и через три года.

**4. Фиксировать договорённости в документах. Код и документация не должны расходиться.**
Выбор школ, семантика версий и формулировки состояний (сайт работает ≠ программу можно установить) закреплены в файлах. Любое расхождение между двумя источниками — дефект, а не различие в стиле.

---

## Технологии

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

## Связаться

| Канал | Адрес |
| --- | --- |
| GitHub | <https://github.com/ntars> |
| Сайт | <https://www.ntars.cn/> |
| Xael | <https://x.ntars.cn/> |
| Ondra | <https://ai.ntars.cn/> |
| Официальный аккаунт WeChat | 玄玖灵犀 |
| Почта | <ntars@qq.com> · <ntarsx@163.com> |
| Douyin | [@俟约](https://v.douyin.com/eq8QjttKQnA/) |
| Bilibili | [space.bilibili.com/499925438](https://space.bilibili.com/499925438) |
| Afdian | <https://ifdian.net/a/ntars/> |

Об ошибках и предложениях пишите в Issues соответствующего репозитория. По вопросам сотрудничества и лицензирования — на почту, с названием проекта в теме (например, `[Ondra]`).

---

<sub>Ntarstudio · Регистрация ICP 蜀ICP备2026027050号 · ©2024–2026 Ntarstudio. All Rights Reserved.</sub>
