# نتارس (باي جيو شيوان)

**تقدُّم لا ينتهي، وإمكانات لا تنتهي.**

[简体中文](README.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Français](README.fr.md) | [Русский](README.ru.md) | [Español](README.es.md) | **العربية**

<div dir="rtl">

مطوّر مستقل، ومؤسس استوديو نتارستوديو (Ntarstudio). أبني برمجيات تعمل محليًا أولًا، وتحفظ سيادة البيانات، وتتيح التحقق من النتائج.

| | |
| --- | --- |
| الاسم بالصينية | 白玖玄 (باي جيو شيوان) |
| الاسم بالإنجليزية | ntars |
| الصفة | مطوّر مستقل · Ntarstudio |
| أعمل على | رفيق ذكاء اصطناعي لسطح المكتب، مدونة الميتافيزيقا الصينية، موقع الاستوديو، أداة تجميع متعددة المعمارية |
| المقر | تشنغدو، الصين |
| الموقع | <https://www.ntars.cn/> |
| البريد | <ntars@qq.com> · <ntarsx@163.com> |
| الدعم | <https://ifdian.net/a/ntars/> |

---

## المشاريع

| المشروع | الوصف | التقنيات | الحالة | الترخيص | المدخل |
| --- | --- | --- | --- | --- | --- |
| **[Xael](https://github.com/ntars/Xael)** | مدونة الميتافيزيقا الصينية تعمل دون اتصال، 22 وظيفة تُحسب من المبادئ الأولى، دون جداول بحث ودون شبكة | JavaScript (بلا اعتماديات) | 5.0.0 صادرة | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |
| **[Ondra](https://github.com/ntars/Ondra)** | رفيق ذكاء اصطناعي مبني بالكامل على الإضافات، 75 إضافة قابلة للتحميل، وتبقى كل البيانات على الجهاز، على macOS وWindows وAndroid | TypeScript · Rust · Tauri | إصدار تجريبي `1.3.0-alpha` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Webroit](https://github.com/ntars/Webroit)** | صندوق أدوات أندرويد داخل المتصفح: ADB وFastboot عبر WebUSB، و152 وظيفة | TypeScript · Vite · WebUSB | 0.1.0 صادرة | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | حزمة تشغيل متبادل ثنائي الاتجاه بين macOS وWindows؛ الاتجاهات الأربعة مكتملة، مع وصول MCP | Node.js · Python · Rust | متاح | MIT | [المستودع](https://github.com/ntars/Wacmin) |
| **[TapMC](https://github.com/ntars/TapMC)** | مشغّل Minecraft Java Edition متعدد المنصات على macOS / Windows / Linux / Android / iOS، يمنح الهاتف إحساس اللمس في Bedrock | Rust · Tauri 2 | تطوير مبكر | Apache-2.0 / MIT | [المستودع](https://github.com/ntars/TapMC) |
| **[Desop](https://github.com/ntars/Desop)** | حزمة تجميل سطح مكتب Windows: dock وشريط قوائم وودجات وجزيرة ديناميكية | غير محدد | مخطط / Planned | Apache-2.0 / MIT | [المستودع](https://github.com/ntars/Desop) |
| **[Apex](https://github.com/ntars/Apex)** | موقع الاستوديو وفهرس المشاريع؛ ملف HTML واحد، ورقة أنماط واحدة، وبضعة سكربتات أصلية | HTML · CSS · Vanilla JS | يعمل | MIT | [www.ntars.cn](https://www.ntars.cn/) |

**سبعة مشاريع = البطاقات السبع في الموقع الرسمي.** القوائم الثلاث (بطاقات الموقع، هذه الصفحة، README كل مشروع) متطابقة؛ وأي تغيير في واحدة ينعكس على الأخريين.

**الحالات متميزة بدقة**: صادر، تجريبي، متاح، تطوير مبكر، ومخطط — لا تُخلط أبدًا، ولا يُوصف المخطط كمنجَز.

## أربعة مبادئ

هذه ليست شعارات، بل كل مبدأ منها يقابل قيدًا يمكن التحقق منه في الشيفرة.

**١. المحلية أولًا. لا تغادر البيانات جهاز المستخدم.**
لا يضم Ondra حسابات ولا مجتمعًا ولا زر مشاركة ولا قياسًا عن بُعد. ينفّذ Xael جميع حساباته دون اتصال ولا يستدعي أي واجهة برمجية خارجية. وأي وظيفة لا تحقق هذا الشرط لا تُصدَر.

**٢. الحساب بدل البحث في الجداول.**
يُشتق تقويم Xael من متسلسلات فلكية — الطول الشمسي والاقترانات الحقيقية — بدلًا من تضمين جدول تقويمي، لأن الجداول تخطئ في الأيام الحدّية. وقيمة الأداة في القدرة على تحديد موضع الخطأ في النتيجة.

**٣. بلا أطر عمل، وبلا خطوة بناء، وبلا اعتماديات وقت التشغيل.**
Apex موقع ثابت من صفحة واحدة، بلا إطار عمل ولا بناء ولا خادم خلفي. ونواة Xael جافاسكربت خالصة بلا أي حزمة npm. وكلما قلّت الاعتماديات ارتفعت احتمالية استمرار العمل بعد ثلاث سنوات.

**٤. تدوين الاصطلاحات كتابةً. لا يجوز أن تتناقض الشيفرة مع الوثائق.**
اختيار المدارس، ودلالة أرقام الإصدارات، وصياغة الحالات (الموقع يعمل ≠ البرنامج قابل للتثبيت) كلها مسجلة في ملفات. وأي تعارض بين مصدرين يُعدّ عيبًا لا اختلافًا في الأسلوب.

---

## التقنيات

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

## للتواصل

| القناة | العنوان |
| --- | --- |
| GitHub | <https://github.com/ntars> |
| الموقع الرسمي | <https://www.ntars.cn/> |
| Xael | <https://x.ntars.cn/> |
| Ondra | <https://ai.ntars.cn/> |
| حساب WeChat الرسمي | 玄玖灵犀 |
| البريد | <ntars@qq.com> · <ntarsx@163.com> |
| دوين | [@俟约](https://v.douyin.com/eq8QjttKQnA/) |
| بيليبيلي | [space.bilibili.com/499925438](https://space.bilibili.com/499925438) |
| Afdian | <https://ifdian.net/a/ntars/> |

للأخطاء والاقتراحات، افتح تذكرة في مستودع المشروع المعني. وللتعاون والترخيص، أرسل بريدًا مع اسم المشروع في الموضوع (مثل `[Ondra]`).

</div>

---

<sub>Ntarstudio · تسجيل ICP 蜀ICP备2026027050号 · ©2024–2026 Ntarstudio. All Rights Reserved.</sub>