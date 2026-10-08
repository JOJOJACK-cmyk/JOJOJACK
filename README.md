# 안녕하세요, JOJOJACK입니다 👋

**Java/Spring 백엔드와 React 프론트엔드를 다루는 웹 개발자**를 목표로 준비하고 있습니다.

<!--
  ✏️ 이 README는 초안입니다. 아래 주석 안내에 따라 본인 정보를 채워 주세요.
  (예: 한 줄 소개에 본인만의 강점이나 관심 분야를 한 문장 더 추가)
-->

## 🙋 About Me

- 🎯 목표: 백엔드(Java / Spring)와 프론트엔드(JavaScript / React)를 함께 이해하는 웹 개발자
- 📍 현재: 취업 준비 중

<!--
  필요하면 항목을 더 추가하세요.
  - 🌱 요즘 공부하는 것: ...
  - 🎓 학력 / 교육과정: ...
  - 🏆 자격증 / 수상: ...
-->

## 🛠 Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)

**Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

**Database · Infra**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

<!--
  배지 만들기: https://shields.io/badges  /  아이콘 이름: https://simpleicons.org
-->

## 📁 Projects

### 🌊 여행온도 — 관광지 후기·가격 정보 탐색기

> **개인 프로젝트** · 2026.09 – 2026.10 · [저장소 보기](https://github.com/JOJOJACK-cmyk/tourist-attraction)

관광지와 연도를 고르면 온라인에 올라온 후기에서 가격·만족·불만 언급을 모아 보여 주는 웹 서비스입니다.
기획부터 백엔드·프론트엔드·테스트까지 혼자 만들었습니다.

- **AI 웹 검색**: Gemini API + Google Search grounding으로 후기를 검색하고, 출처가 연결되지 않은 응답은 서버에서 오류로 처리
- **로컬 LLM 후기 분석**: Ollama(Gemma)에 시스템 프롬프트와 JSON 스키마를 넘겨 후기 속 비용·혼잡·응대 경험을 구조화해 추출 (관리자 전용)
- **커뮤니티**: 질문·자유 게시판, 익명 글·댓글, 사진 첨부, 관리자 숨김 처리 — Spring Security 세션 로그인, CSRF, BCrypt
- **소셜 로그인 · 채팅 · 결제**: 카카오·구글 OAuth2 로그인, WebSocket 그룹 채팅방, 카카오페이 후원 결제(서버에서 금액·주문 검증)
- **테스트**: JUnit 테스트 51개를 GitHub Actions로 push·PR마다 실행, 화면 로직은 Node 테스트로 검증

`Java 17` `Spring Boot 3.5` `Spring Security` `Spring Data JPA` `Thymeleaf` `WebSocket` `MySQL` `JavaScript` `GitHub Actions`

### 🎧 StreamWave — 음악 스트리밍 + 라이브 방송 플랫폼

> **팀 프로젝트 (3명)** · 2026.08 – 2026.10 · [저장소 보기](https://github.com/JOJOJACK-cmyk/-MUSIC-main2)

YouTube 음원 스트리밍과 OBS 라이브 방송을 합친 음악 플랫폼입니다.
시청자가 방송을 보며 신청곡에 투표하고, 후원하고, 듣던 곡의 음반을 바로 살 수 있습니다.

**담당: 라이브 방송 서버 연동 · 운영 배포 환경**

- **라이브 송출**: SRS 미디어 서버로 OBS의 RTMP 송출을 받아 HLS로 재생하도록 구성하고, SRS 콜백으로 방송 시작·종료 처리
- **방송 상태 · 시청자 수**: SRS HTTP API로 송출 중인 스트림을 감지하고, Redis Sorted Set 하트비트로 실시간 시청자 수 집계
- **라이브 화면**: 방송 상세 페이지(React) 구현, 채팅 신청곡 투표·방송자 컨트롤 초기 구현
- **운영 배포**: MySQL·Redis·SRS·Spring·Caddy를 Docker Compose로 묶은 운영 환경과 Caddy 리버스 프록시(자동 HTTPS) 구성
- 이 밖에 YouTube 플레이어, AWS S3 파일 업로드, Redis 기반 TOP 100 차트의 초기 구현에 참여

`Java` `Spring Boot` `React` `Redis` `MySQL` `SRS (RTMP / HLS)` `Docker Compose` `Caddy`

## 📫 Contact

[![GitHub](https://img.shields.io/badge/GitHub-JOJOJACK--cmyk-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JOJOJACK-cmyk)

<!--
  이메일, 블로그, 링크드인 등을 추가하려면:
  [![Email](https://img.shields.io/badge/Email-이메일주소-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:이메일주소)
  [![Blog](https://img.shields.io/badge/Blog-블로그이름-03C75A?style=for-the-badge&logo=naver&logoColor=white)](블로그주소)
-->
