# ntars (백구현)

**끝없는 진보, 끝없는 가능성.**

[简体中文](README.md) | [English](README_EN.md) | [日本語](README_JA.md) | **한국어** | [Français](README_FR.md) | [Русский](README_RU.md) | [Español](README_ES.md) | [العربية](README_AR.md)

독립 개발자, 스타지우 스튜디오(Ntarstudio) 창업자. 로컬 우선, 데이터 주권, 검증 가능한 소프트웨어를 만듭니다.

| | |
| --- | --- |
| 중국어 이름 | 白玖玄 (바이주쉬안) |
| 영어 이름 | ntars |
| 역할 | 독립 개발자 · Ntarstudio |
| 진행 중 | 데스크톱 AI 컴패니언, 중화 술수 문헌 라이브러리, 스튜디오 공식 사이트, 크로스 아키텍처 패키징 도구, 중국어 우선 프로그래밍 언어 |
| 거점 | 중국 청두 |
| 사이트 | <https://www.ntars.cn/> |
| 이메일 | <ntars@qq.com> · <ntarsx@163.com> |
| 후원 | <https://ifdian.net/a/ntars/> |

## 진행 중인 프로젝트

열다섯 프로젝트를 프로젝트 이름의 라틴 문자 오름차순으로 한 줄로 배치하고 상태로 나누지 않습니다. **공식 사이트 <https://www.ntars.cn/> 는 같은 목록의 또 다른 표현**이며, 어느 한쪽을 바꾸면 다른 쪽도 동기화합니다.

| 프로젝트 | 정체 | 기술 | 상태 | 라이선스 | 입구 |
| --- | --- | --- | --- | --- | --- |
| **[Amphoreus](https://github.com/ntars/Amphoreus)** | 『붕괴: 스타레일』의 「여아소서」를 일대일로 재현해 스스로 돌아가는 세계 시뮬레이션으로 만든 것. 시드가 역사를 정하고 같은 시드면 같은 결말 | Python(표준 라이브러리) · SQLite | 개발 중 | MIT | [저장소](https://github.com/ntars/Amphoreus) |
| **[Apex](https://github.com/ntars/Apex)** | 스튜디오 공식 사이트와 프로젝트 총색인. HTML 한 장, 스타일시트 한 장, 순수 스크립트 몇 개 | HTML · CSS · Vanilla JS | 공개 중 | MIT | [www.ntars.cn](https://www.ntars.cn/) |
| **[Chiubay 玖白](https://github.com/ntars/Chiubay)** | 제로에서 지능을 기르는 AGI 기구 연구. 기성 모델을 쓰지 않고 사전 학습에도 의존하지 않으며 하위 수학 연산부터 훈련 루프까지 모두 자체 작성 | Python · NumPy | 연구 프로토타입 | Apache-2.0 / MIT | [저장소](https://github.com/ntars/Chiubay) |
| **[Desop](https://github.com/ntars/Desop)** | Windows에 macOS 스타일 데스크톱을 제공: dock, 상단 바, 위젯, 다이내믹 아일랜드. 네 부품은 개별로 켜고 끌 수 있고 시스템을 바꾸지 않음 | Python · PySide6 | 빌드 가능한 MVP `0.2.0` | Apache-2.0 / MIT | [저장소](https://github.com/ntars/Desop) |
| **[Flutter-IDE](https://github.com/ntars/Flutter-IDE)** | Flutter 비주얼 UI 도구: 캔버스에서 끌어 놓고 속성 패널에서 값을 바꾸며, 출력은 프로젝트 표준 Dart 코드 | Dart · Flutter | 사용 가능 `0.2.0` | Apache-2.0 / MIT | [저장소](https://github.com/ntars/Flutter-IDE) |
| **[Gitrule-skill](https://github.com/ntars/Gitrule-skill)** | 「프로젝트를 어떻게 끝내는가」의 규범집. 규범 68편 × 12개 언어, CLI / MCP / Skill 세 형태 동봉 | Markdown · Python CLI | 제공 완료 | MIT | [저장소](https://github.com/ntars/Gitrule-skill) |
| **[NovaKit](https://github.com/ntars/NovaKit)** | 새 PC를 맞춘 직후의 첫 도구: 압축 해제, 이미지 보기, 스크린샷 주석, 일괄 이름 변경, 중복 찾기, 해시 계산 등 서른여 개. 모두 오프라인이고 로그인 불필요 | Rust · Tauri 2 | 골격 단계 | Apache-2.0 / MIT | [저장소](https://github.com/ntars/NovaKit) |
| **[Ondra 空谷](https://github.com/ntars/Ondra)** | AI를 만나고 싶은 사람으로 바꾸는 것: 장기적 동반, 감정·기억·문맥이 축적되고 데이터는 기기 안에만 남음 | Flutter · Cordis 4.1.0 · dsh | 내부 베타 `3.0.0-alpha.22` | Apache-2.0 / MIT | [ai.ntars.cn](https://ai.ntars.cn/) |
| **[Relax 悠然](https://github.com/ntars/Relax)** | 가정용 자체 호스팅 채팅·일정·사진·네트워크 디스크. 데이터는 집의 상시 가동 PC에만 남음 | Rust · Tauri 2 · SQLite · React | 초기 개발 | Apache-2.0 / MIT | [저장소](https://github.com/ntars/Relax) |
| **[行簡 Serica](https://github.com/ntars/Serica)** | 전 중국어 범용 프로그래밍 언어: 식별자·키워드·문장부호가 모두 중국어. 설계상 자체 호스팅으로 네이티브를 직접 출력하며 C도 LLVM도 쓰지 않음 | Go(시드) · 자체 호스팅 | 사양 동결, 구현은 어휘 분석까지 | Apache-2.0 | [저장소](https://github.com/ntars/Serica) |
| **[TapMC](https://github.com/ntars/TapMC)** | 일곱 플랫폼을 대상으로 하는 『마인크래프트』 Java 에디션 런처: 인스턴스, 모드, Java 런타임을 각각 관리 | Flutter · Rust · Java 21 | 골격 단계 `0.1.0` | Apache-2.0 / MIT | [저장소](https://github.com/ntars/TapMC) |
| **[Taycho-OS 太初](https://github.com/ntars/Taycho-OS)** | 行簡(Serica)으로 제로에서 쓰는 OS. 능력 기반 부작용, 단일 스레드 UI, 메시지 전달(자리 표시자) | Serica | 설계 단계 / 자리 표시자 | Apache-2.0 / MIT | [저장소](https://github.com/ntars/Taycho-OS) |
| **[Wacmin](https://github.com/ntars/Wacmin)** | Mac과 Windows 사이의 「아키텍처 불통」 네 가지: 양방향 패키징과 양방향 실행, MCP 접속도 제공 | Node.js · Python · Rust | 세 방향 출시 가능, AppOnWin 실험적 | Apache-2.0 / MIT | [저장소](https://github.com/ntars/Wacmin) |
| **[Webroit](https://github.com/ntars/Webroit)** | 브라우저에서 돌아가는 Android 도구함: WebUSB로 ADB와 Fastboot에 직접 연결, 61개 기능, 백엔드 없음, 텔레메트리 없음 | TypeScript · Vite · WebUSB | 0.1.0 공개 중 | Apache-2.0 / MIT | [adb.ntars.cn](https://adb.ntars.cn/) |
| **[Xael 玄玖灵犀](https://github.com/ntars/Xael)** | 중국 전통 역법과 술수 문헌의 시각화 도구: 22개 기능을 기기 안에서 제로부터 계산하고 표 조회도 통신도 하지 않음 | JavaScript(의존성 없음) | 5.0.0 공개 중 | Apache-2.0 / MIT | [x.ntars.cn](https://x.ntars.cn/) |

열다섯 프로젝트와 이 프로필 저장소를 합치면 열여섯 개의 GitHub 저장소가 됩니다. 공식 사이트의 열다섯 장 카드, 이 페이지, 각 프로젝트의 README는 같은 목록을 가리키며 한 곳을 바꾸면 나머지도 동기화합니다. 새 프로젝트는 라틴 문자상 해당 위치에 삽입하고 끝에 덧붙이지 않습니다.

**상태 표기는 엄격히 구분합니다**: 공개 중, 내부 베타, 사용 가능, 빌드 가능한 MVP, 초기 개발, 골격 단계, 연구 프로토타입, 설계 단계 여덟 가지를 섞지 않으며 계획을 구현된 것으로 쓰지 않습니다.

---

## 공식 사이트와의 연동

이 페이지와 공식 사이트는 같은 프로젝트 목록을 공유하며 역할을 나눕니다.

| 위치 | 역할 | 내용 초점 |
| --- | --- | --- |
| **이 페이지(GitHub 프로필)** | 개발자를 위한 색인 | 저장소 직링크, 기술 스택, 라이선스, 하위 프로젝트 구조 |
| **[www.ntars.cn](https://www.ntars.cn/)** | 방문자를 위한 간판 | 브랜드 인지, 프로젝트 카드, 연락 창구 |

양방향 링크: 사이트의 상단과 하단은 이 저장소를 가리키고, 이 페이지의 입구 항목은 <https://www.ntars.cn/>와 각 프로젝트 사이트를 가리킵니다.

**표현을 맞추는 세 가지 규율**:

1. **계획 중인 프로젝트도 카드를 낸다. 단 상태를 명시한다** — 카드에 「계획 중」이라고 쓰면 방문자는 클릭 전에 내려받을 것이 없다는 걸 압니다. 숨기면 오히려 「이미 된다」로 오해됩니다;
2. **상태가 바뀌면 세 곳을 동시에 고친다** — 이 페이지, Apex의 `PROJECTS` 배열, 각 프로젝트의 README;
3. **종료된 프로젝트는 어떤 형태로도 다시 등장하지 않는다** — 이 페이지, 사이트, 키워드, 구조화 데이터 어디에도 올리지 않습니다.

---

## 네 가지 원칙

구호가 아니라, 각 항목 모두 코드에서 확인할 수 있는 제약입니다.

**1. 로컬 우선. 데이터는 기기 밖으로 나가지 않는다.**
Ondra에는 계정도, 커뮤니티도, 공유 버튼도, 텔레메트리도 없습니다. Xael은 모든 연산을 오프라인에서 수행하며 외부 API를 호출하지 않습니다. 이를 지킬 수 없는 기능은 만들지 않습니다.

**2. 표를 찾지 않고 계산한다.**
Xael의 달력은 천문 급수로 태양 황경과 실제 삭(朔)을 실시간 계산하며, 역표를 내장하지 않습니다. 조회표는 경계일에서 반드시 틀리기 때문입니다. 도구의 가치는 결과가 틀렸을 때 어디가 틀렸는지 짚을 수 있다는 데 있습니다.

**3. 프레임워크 없음, 빌드 없음, 런타임 의존성 없음.**
Apex는 프레임워크도 빌드도 백엔드도 없는 단일 페이지 정적 사이트입니다. Xael의 핵심은 npm 패키지를 전혀 쓰지 않는 순수 JavaScript입니다. 의존성이 적을수록 3년 뒤에도 동작할 확률이 높습니다.

**4. 규약은 문서로 남긴다. 코드와 문서는 어긋나서는 안 된다.**
유파 선택, 버전 표기 의미, 상태 서술(사이트가 돌아감 ≠ 소프트웨어가 설치됨)을 모두 파일로 남깁니다. 두 곳의 서술이 어긋나면 그것은 문체 차이가 아니라 결함입니다.

---

## 기술 스택

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

## 연락처

| 채널 | 주소 |
| --- | --- |
| GitHub | <https://github.com/ntars> |
| 공식 사이트 | <https://www.ntars.cn/> |
| Xael | <https://x.ntars.cn/> |
| Ondra | <https://ai.ntars.cn/> |
| 위챗 공식 계정 | 玄玖灵犀 |
| 이메일 | <ntars@qq.com> · <ntarsx@163.com> |
| 더우인(Douyin) | [@俟约](https://v.douyin.com/eq8QjttKQnA/) |
| 빌리빌리 | [space.bilibili.com/499925438](https://space.bilibili.com/499925438) |
| 아이파뎬(Afdian) | <https://ifdian.net/a/ntars/> |

버그와 기능 제안은 해당 저장소의 Issue로 보내 주세요. 제휴와 라이선스는 이메일로, 제목에 프로젝트 이름(예: `[Ondra]`)을 붙여 주세요.

---

<sub>星玖工作室 Ntarstudio · ICP 등록 蜀ICP备2026027050号 · ©2024–2026 Ntarstudio. All Rights Reserved.</sub>
