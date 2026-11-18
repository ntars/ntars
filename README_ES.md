# ntars（Bai Jiuxuan）

**Progreso sin fin, posibilidad sin fin.**

[简体中文](README.md) | [English](README_EN.md) | [日本語](README_JA.md) | [한국어](README_KO.md) | [Français](README_FR.md) | [Русский](README_RU.md) | **Español** | [العربية](README_AR.md)

Desarrollador independiente, fundador de Ntarstudio. Creo software local-first, con soberanía de datos y resultados verificables.

| | |
| --- | --- |
| Nombre en chino | 白玖玄 (Bai Jiuxuan) |
| Nombre en inglés | ntars |
| Rol | Desarrollador independiente · Ntarstudio |
| Trabajando en | Compañero de IA de escritorio, corpus de metafísica china, sitio del estudio, herramienta de empaquetado multiarquitectura |
| Ubicación | Chengdu, China |
| Sitio | <https://www.ntars.cn/> |
| Correo | <ntars@qq.com> · <ntarsx@163.com> |
| Apoyo | <https://ifdian.net/a/ntars/> |

## Proyectos

| Proyecto | Qué es | Tecnologías | Estado | Licencia | Entrada |
| --- | --- | --- | --- | --- | --- |
| **[Xael](https://github.com/ntars/Xael)** | Corpus sin conexión de metafísica china, 22 funciones calculadas desde los principios primeros, sin tablas de consulta, sin red | JavaScript (sin dependencias) | 5.0.0 publicada | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |
| **[Ondra](https://github.com/ntars/Ondra)** | Compañero de IA totalmente modular: la interfaz solo lee la proyección de los complementos; emoción, memoria y contexto en el núcleo; datos locales | Flutter · Cordis 4.1.0 | Beta `2.0.0-alpha` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Webroit](https://github.com/ntars/Webroit)** | Una caja de herramientas Android en el navegador: ADB y Fastboot por WebUSB, 152 funciones | TypeScript · Vite · WebUSB | 0.1.0 publicada | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | Suite de interoperabilidad bidireccional macOS ↔ Windows; las cuatro direcciones terminadas, con acceso MCP | Node.js · Python · Rust | Disponible | MIT | [repositorio](https://github.com/ntars/Wacmin) |
| **[TapMC](https://github.com/ntars/TapMC)** | Esqueleto de juego sandbox multijugador modular: front Flutter en siete plataformas y servidor Java, unidos por un único contrato JSON-RPC 2.0 | Flutter · Java 21 | Etapa de esqueleto | Apache-2.0 / MIT | [repositorio](https://github.com/ntars/TapMC) |
| **[Desop](https://github.com/ntars/Desop)** | Suite de personalización del escritorio de Windows: dock, barra de menús, widgets, isla dinámica | Por definir | Planificado | Apache-2.0 / MIT | [repositorio](https://github.com/ntars/Desop) |
| **[Apex](https://github.com/ntars/Apex)** | Sitio del estudio e índice de proyectos; un archivo HTML, una hoja de estilos, unos pocos scripts nativos | HTML · CSS · Vanilla JS | En línea | MIT | [www.ntars.cn](https://www.ntars.cn/) |

**Siete proyectos = las siete tarjetas del sitio oficial.** Las tres listas (tarjetas del sitio, esta página, README de cada proyecto) coinciden; un cambio en una se refleja en las demás.

**Los estados se distinguen estrictamente**: publicado, beta, disponible, desarrollo inicial y planificado nunca se mezclan, y nada planificado se describe como construido.

---

## En sintonía con el sitio

Esta página y el sitio oficial comparten una misma lista de proyectos, con roles separados.

| Lugar | Papel | Enfoque |
| --- | --- | --- |
| **Esta página (perfil de GitHub)** | Un índice para desarrolladores | Enlaces directos a repositorios, pila técnica, licencia, estructura de subproyectos |
| **[www.ntars.cn](https://www.ntars.cn/)** | Un rótulo para visitantes | Identidad de marca, tarjetas de proyectos, contacto |

Enlaces bidireccionales: la cabecera y el pie del sitio apuntan a este repositorio, y los campos de entrada de esta página apuntan a <https://www.ntars.cn/> y al sitio de cada proyecto.

**Tres reglas para que la redacción coincida**:

1. **Un proyecto planificado también tiene tarjeta, con su estado** — la tarjeta dice «Planificado», así el visitante sabe antes de hacer clic que no hay nada que descargar; ocultarlo sugiere lo contrario;
2. **Un cambio de estado se actualiza en tres sitios** — esta página, el arreglo `PROJECTS` de Apex y el README del proyecto;
3. **Un proyecto retirado no reaparece de ninguna forma** — ni aquí, ni en el sitio, ni en palabras clave o datos estructurados.

---

## Cuatro principios

No son eslóganes: cada uno corresponde a una restricción verificable en el código.

**1. Local primero. Los datos nunca salen del equipo.**
Ondra no tiene cuentas, ni comunidad, ni botón de compartir, ni telemetría. Xael ejecuta todos sus cálculos sin conexión y no llama a ninguna API de terceros. Una función que no cumpla esta regla no se publica.

**2. Calcular en lugar de consultar.**
El calendario de Xael se deriva de series astronómicas —longitud solar y novilunios verdaderos— en lugar de incluir una tabla de almanaque, porque las tablas fallan en los días límite. El valor de una herramienta está en poder señalar dónde se originó un resultado erróneo.

**3. Sin frameworks, sin compilación, sin dependencias en tiempo de ejecución.**
Apex es un sitio estático de una sola página, sin framework, sin compilación y sin backend. El núcleo de Xael es JavaScript puro, sin ningún paquete npm. Menos dependencias significa más probabilidades de que todo siga funcionando dentro de tres años.

**4. Dejar las convenciones por escrito. El código y la documentación no deben contradecirse.**
Las decisiones de escuela, la semántica de versiones y la redacción de estados (el sitio funciona ≠ el programa se puede instalar) quedan registradas en archivos. Cualquier discrepancia entre dos fuentes es un defecto, no una diferencia de estilo.

---

## Tecnologías

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

## Contacto

| Canal | Dirección |
| --- | --- |
| GitHub | <https://github.com/ntars> |
| Sitio oficial | <https://www.ntars.cn/> |
| Xael | <https://x.ntars.cn/> |
| Ondra | <https://ai.ntars.cn/> |
| Cuenta oficial de WeChat | 玄玖灵犀 |
| Correo | <ntars@qq.com> · <ntarsx@163.com> |
| Douyin | [@俟约](https://v.douyin.com/eq8QjttKQnA/) |
| Bilibili | [space.bilibili.com/499925438](https://space.bilibili.com/499925438) |
| Afdian | <https://ifdian.net/a/ntars/> |

Para errores y sugerencias, abre un issue en el repositorio correspondiente. Para colaboraciones y licencias, escribe un correo con el nombre del proyecto en el asunto (por ejemplo `[Ondra]`).

---

<sub>Ntarstudio · Registro ICP 蜀ICP备2026027050号 · ©2024–2026 Ntarstudio. All Rights Reserved.</sub>
