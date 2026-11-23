<div align="center">

  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:103B2F,100:328566&amp;height=210&amp;section=header&amp;text=Kanghyun%20Kim&amp;fontSize=46&amp;fontColor=FFFFFF&amp;fontAlignY=37&amp;desc=Java%20%7C%20Spring%20Boot%20%7C%20Backend%20Development&amp;descSize=17&amp;descAlignY=58" alt="Kanghyun Kim — Backend Development" />

  <a href="mailto:com0ze@naver.com"><img src="https://img.shields.io/badge/Email-com0ze%40naver.com-185442?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email: com0ze@naver.com" /></a>
  <a href="https://github.com/com0ze"><img src="https://img.shields.io/badge/GitHub-com0ze-24292F?style=flat-square&amp;logo=github&amp;logoColor=white" alt="GitHub: com0ze" /></a>

</div>

## 👋 About Me

###**Java와 Spring Boot로 인증과 매칭 기능을 구현하는 백엔드 개발자 김강현입니다.**

- 🎓 동국대학교 컴퓨터공학 전공
- 🌱 GDGoC DGU Core Member · 홈페이지 백엔드 및 인증 기능 개발
- 🔐 Google 로그인·JWT 발급, 위치 기반 매칭, REST API 구현 경험
- 🔎 기능의 실행 흐름과 예외 상황을 이해하고, 동작의 근거를 설명하는 개발을 지향합니다.

<br>

## 🛠 Tech Stack

프로젝트에서 사용한 기술과 도구입니다.

| 구분 | 기술 |
| :--- | :--- |
| **Backend** | <img src="https://img.shields.io/badge/Java-437291?style=for-the-badge" alt="Java" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&amp;logo=springboot&amp;logoColor=white" alt="Spring Boot" /> <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&amp;logo=springsecurity&amp;logoColor=white" alt="Spring Security" /> |
| **Database** | <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" alt="MySQL" /> <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge" alt="Oracle" /> <img src="https://img.shields.io/badge/Cloud_Firestore-DD8A00?style=for-the-badge&amp;logo=firebase&amp;logoColor=white" alt="Cloud Firestore" /> |
| **Cloud** | <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&amp;logo=googlecloud&amp;logoColor=white" alt="Google Cloud" /> |
| **Game Development** | <img src="https://img.shields.io/badge/C%23-684D95?style=for-the-badge" alt="C#" /> <img src="https://img.shields.io/badge/Unity-343434?style=for-the-badge&amp;logo=unity&amp;logoColor=white" alt="Unity" /> |
| **Tools** | <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git" /> <img src="https://img.shields.io/badge/GitHub-24292F?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="GitHub" /> <img src="https://img.shields.io/badge/Notion-343434?style=for-the-badge&amp;logo=notion&amp;logoColor=white" alt="Notion" /> |

<br>

## 🏫 Experience

| 기간 | 활동 | 주요 내용 |
| :--- | :--- | :--- |
| 2026.09 – 현재 | **GDGoC DGU Core Member** | 기술 세션·세미나 진행, 동아리 홈페이지 백엔드 및 인증 기능 개발 |
| 2025.09 – 2025.12 | **FarmSystem UNION** | 코딩 스터디 참여 및 팀 프로젝트 개발 |
| 2025.09 – 2025.12 | **HI-SW 봉사단 SW멘토** | 광희중학교 특수학급 학생 대상 코딩·AI·교구 활용 교육 지원 |

<br>

## 📌 Projects

### 01. GDGoC DGU 홈페이지

**동아리 소개와 활동 아카이브, 커뮤니티·모집 관리를 위한 웹 서비스**

`2026.09 – 현재` · `6인 팀` · **백엔드 및 인증·보안 담당**

- **Google 로그인·JWT 발급:** Google 로그인 토큰을 검증하고, 회원·세션 정보를 포함한 서비스 Access Token 발급 흐름을 구현했습니다.
- **인증 세션 처리:** Refresh Token 생성·해시 처리와 Cloud Firestore 기반 회원·세션 데이터 처리를 구현했습니다.
- **입력 검증·예외 처리:** 잘못된 인증 요청과 서버 설정 오류를 구분하도록 처리 순서를 개선하고, API 응답을 확인했습니다.

**Tech** · Java, Spring Boot, Spring Security, JWT, Cloud Firestore, Google Cloud

[🌐 서비스](https://gdgoc-dgu.com/) · [💻 Repository](https://github.com/GDSC-DGU/GDGoC-DGU-Homepage/tree/develop) · [🔎 인증 기능 PR](https://github.com/GDSC-DGU/GDGoC-DGU-Homepage/pull/30)

---

### 02. 빌릿 · Villit

**교내에서 물품이 필요한 학생과 가까운 공급자를 연결하는 위치 기반 대여 매칭 서비스**

`2026.03 – 2026.06` · `4인 팀` · **팀장 및 백엔드 개발**

- **위치 갱신 API:** 팀에서 적용한 지오펜싱 방식에 맞춰, 건물·구역 경계를 통과할 때 위치를 갱신하는 API를 구현했습니다. 주기적인 위치 전송 대신 구역 변경을 기준으로 통신하도록 구성했습니다.
- **BFS 기반 매칭:** 건물 간 인접 관계를 그래프로 표현하고, 요청 후 경과 시간에 따라 탐색 범위를 단계적으로 확장하며 사용자 조건에 맞는 후보를 선별하는 로직을 구현했습니다.
- **설계·협업:** 상태값 정의, ERD 설계, API 명세 작성에 참여하고 위치 갱신·물품 전달·거래 완료 API를 개발했습니다.

**Tech** · Java, Spring Boot, MySQL, JPA, REST API

[💻 Backend Repository](https://github.com/com0ze/Villit_Backend/tree/develop) · [📝 본인 커밋](https://github.com/com0ze/Villit_Backend/commits/develop/?author=com0ze)

---

### 03. Re:Launch

**제한된 배터리로 행성을 탐험하고, 모듈과 부품을 모아 UFO를 수리하는 2D 퍼즐 액션 게임**

`2026.08` · `3인 팀` · **게임플레이 시스템 및 UI 개발**

- **배터리 시스템:** 배터리 소모·회복, 플레이어 상태 연동 및 잔량 UI를 구현했습니다.
- **모듈·상호작용:** 모듈 공통 클래스와 축소·파괴·수중 탐사 기능, 모듈 획득·장착 UI를 개발했습니다.
- **플레이 흐름 개선:** 시작·옵션·부활 화면을 구현하고, 지형 충돌·익사 판정·모듈과 배터리 연동 오류를 수정했습니다.

팀원들과 기능을 통합해 **WebGL 플레이 버전과 시연 영상**을 완성했습니다.

**Tech** · C#, Unity, WebGL

[🎮 브라우저에서 플레이](https://water03262.itch.io/relaunch) · [🎬 시연 영상](https://www.youtube.com/watch?v=38fNRsUtwfU)

<br>

## 📜 Certificates

| 자격 | 취득일 | 발급기관 |
| :--- | :--- | :--- |
| **SQL 개발자 · SQLD** | 2026.09.11 | 한국데이터산업진흥원 |
| **프로그래밍기능사** | 2023.09.20 | 한국산업인력공단 |

<br>

## 🏆 Awards

| 수상 | 기관 |
| :--- | :--- |
| **2022 어드벤처디자인 경진대회 최우수상** | 동국대학교 |
| **2025학년도 2학기 학기우등생** | 동국대학교 |

<br>

## ✉️ Contact

- **Email** · [com0ze@naver.com](mailto:com0ze@naver.com)
- **GitHub** · [github.com/com0ze](https://github.com/com0ze)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:103B2F,100:328566&amp;height=85&amp;section=footer" alt="Dark green wave footer" />
