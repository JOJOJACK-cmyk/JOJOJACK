# 안녕하세요,  👋

업무를 이해하고, 불편함을 개선하는 개발자

박세영입니다,

홈쇼핑 분야에서 사무 업무를 하며 사용하기 편한 시스템이 업무 효율을 얼마나 바꾸는지 체감했습니다.
시스템을 쓰는 입장에서 나아가 직접 만들고 개선하는 개발자가 되기 위해 풀스택 개발을 공부하고 있습니다.

## 🙋‍♂️ About Me

- 🎯 **목표**: 백엔드(Java / Spring)와 프론트엔드(JavaScript / React)를 함께 이해하는 웹 개발자
- 🎓 **교육**: 더조은컴퓨터아카데미 「AI활용 풀스택(프론트엔드·백엔드) 부트캠프」 (Java · Python · Flutter) · 2026.05 – 2026.11
- 💼 **이전 경력**: 홈쇼핑 분야 사무 업무 — 정확한 정보 처리와 여러 부서가 얽힌 협업을 익혔습니다
- 🔍 **일하는 방식**: 기능을 만들 때는 입력값 → 저장 방식 → API 응답 → 화면 표시를 함께 보고, 오류가 나면 요청 경로 → 응답 → 서버 로그 → 데이터 상태 순으로 원인을 좁혀 갑니다

<!--
  필요하면 항목을 더 추가하세요.
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

**Mobile · Etc**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**DevOps · Tools**

![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

<!--
  배지 만들기: https://shields.io/badges  /  아이콘 이름: https://simpleicons.org
-->

## 📁 Projects

### 🌊 여행온도 — 관광지 후기 정보·커뮤니티 서비스

<img src="assets/travel-temperature/logo.png" width="280" alt="여행온도 픽셀 로고" />

> **개인 프로젝트 (1명)** · 2026.09 – 진행 중 · **AWS EC2 배포**
>
> 담당: 서비스 기획, 데이터 모델 설계, 백엔드 API, 화면 구성, 기능 검증, 서버 배포
>
> [서비스 접속](https://travelondo2026.duckdns.org) · [저장소 보기](https://github.com/JOJOJACK-cmyk/tourist-attraction) · [테스트 실행 기록](https://github.com/JOJOJACK-cmyk/tourist-attraction/actions)

여행 전에 관광지의 가격 체감·서비스·혼잡도를 살펴보고, 이용자끼리 후기와 질문을 나누는 웹 서비스입니다.
기획부터 인증·게시판·후기 관리 기능 구현, 기존 MySQL 데이터 이전과 HTTPS 배포까지 직접 진행했습니다.

> 서비스는 시연·개발 일정에 맞춰 서버를 운영하므로 접속이 제한될 수 있습니다. 화면과 구현 내용은 아래 자료 및 저장소에서 확인할 수 있습니다.

<img src="assets/travel-temperature/main.png" width="820" alt="여행온도 메인 화면 - 목적지와 후기 작성 연도를 선택해 여행 정보를 탐색하는 화면" />

- **관광지 · 연도별 종합 후기**: 9개 관광지를 지역별로 탐색하고, 선택한 연도의 칭찬·불만·주요 이슈와 식비·숙박비·서비스·혼잡도를 구분해 요약. 원문 링크로 근거 확인
- **직접 방문 후기**: 방문일·지출액·대기 시간·항목별 체감·사진 등록, 내 후기 수정·삭제, 관리자 승인·반려. 승인된 후기만 공개·집계하고 수정 시 재검토하며 버전 검사로 변경 충돌 처리
- **회원 · 인증**: 일반 회원가입·로그인, 네이버 OAuth2·구글 OIDC 로그인, 닉네임 설정. BCrypt·CSRF·세션 인증을 적용하고 본인 글·후기 및 관리자 권한을 서버에서 검증
- **커뮤니티 · 저장**: 자유·질문 게시판, 관광지 태그·검색·페이지 구분·댓글·사진 첨부. 게시글에 회원당 1회의 ‘도움됐어요’와 취소 기능, 본인만 조회할 수 있는 저장 목록 제공. 게시판·댓글에는 닉네임을 표시하고 직접 방문 후기는 익명으로 공개
- **그룹 채팅**: WebSocket 기반 채팅방 생성·초대 링크·실시간 메시지, 방 참여 권한 확인
- **AI 분석·검색 (선택 연동)**: 관리자용 Ollama 후기 구조화 및 응답 검증, Gemini API + Google Search grounding 기반 검색 구현. 외부 API 키·모델 연결 설정이 필요한 기능으로, 연결 실패·시간 초과·근거 없는 응답을 구분해 처리
- **AWS 배포**: Ubuntu EC2에 Spring Boot·MySQL·Nginx 구성, 기존 DB 이전, systemd 앱 자동 실행. Let's Encrypt HTTPS·세션 쿠키 보안 설정, Nginx WebSocket 프록시, DuckDNS IP 자동 갱신 적용
- **검증**: JUnit·MockMvc **81개 테스트 통과**와 JavaScript 화면 동작 테스트 확인. 인증·권한·후기 검토·저장 목록 격리·동시 반응 중복 방지 등을 GitHub Actions에서 검증

`Java 17` `Spring Boot 3.5` `Spring Security` `Spring Data JPA` `Thymeleaf` `WebSocket` `MySQL` `JavaScript` `OAuth2 / OIDC` `AWS EC2` `Ubuntu` `Nginx` `GitHub Actions`

<details>
<summary><b>📸 화면 더 보기</b></summary>
<br />

| 관광지 선택 | 비용과 방문 경험 상세 분석 |
| :-: | :-: |
| <img src="assets/travel-temperature/destinations.png" width="380" alt="9개 관광지를 지역별로 탐색하는 픽셀 일러스트 카드 화면" /> | <img src="assets/travel-temperature/cost-analysis.png" width="380" alt="식비, 숙박비, 서비스, 혼잡·대기 항목별 후기 분석과 칭찬·불만 집계 화면" /> |
| **관광지별 종합 후기** | **커뮤니티** |
| <img src="assets/travel-temperature/review-summary.png" width="380" alt="선택한 관광지와 연도의 후기, 칭찬 언급, 불만 언급 수를 보여 주는 화면" /> | <img src="assets/travel-temperature/community.png" width="380" alt="질문 게시판과 자유 게시판을 나눈 커뮤니티 화면" /> |

</details>

<details>
<summary><b>🏗 AWS 배포 구조 · AI 분석 흐름</b></summary>
<br />

**배포 구성**

```mermaid
flowchart TB
    browser["브라우저"] -->|HTTPS| nginx
    subgraph ec2["AWS EC2 · Ubuntu"]
        nginx["Nginx · Let's Encrypt"] --> app["Spring Boot · systemd"]
        app --> db[("MySQL")]
        app --> photos["업로드 사진 저장"]
    end
```

Nginx에서 HTTPS를 처리하고 서버 내부의 앱으로 요청을 전달합니다. MySQL과 앱의 8080 포트는 외부에 공개하지 않았습니다.
DuckDNS는 5분마다 공개 IP를 갱신하고, 인증서 자동 갱신을 예약했습니다. 네이버·구글 로그인 콜백은 HTTPS 도메인으로 연결했습니다.

**앱 구성 및 AI 모듈 연동 구조**

아래는 앱의 모듈 구성과 선택적으로 연결하는 AI 분석 흐름입니다. Ollama 분석은 모델을 실행한 별도 환경에 연결해 사용합니다.

<img src="assets/travel-temperature/architecture.png" width="760" alt="사용자 화면, Spring Boot, MySQL과 선택적으로 연결하는 Ollama·Gemini 모듈 구조" />

<img src="assets/travel-temperature/ai-review-flow.png" width="760" alt="관리자 입력, Ollama 분석, 응답 검증, 결과 반환 순서와 연결 실패 등 예외 처리 흐름" />

</details>

<details>
<summary><b>🔧 기술적 과제와 해결</b></summary>
<br />

| 과제 | 해결 |
| --- | --- |
| 도움 반응 동시 요청의 중복 집계 | 회원·게시글 유일 제약과 게시글 행 쓰기 잠금, 상태 지정형 PUT·DELETE로 반복 요청의 결과 유지 |
| 방문 후기 수정·검토 중 변경 충돌 | 버전을 검사해 오래된 요청을 거부하고, 수정한 후기는 다시 검토 대기 상태로 전환 |
| 다른 회원의 비공개 정보 노출 | 저장 목록은 로그인한 본인으로 조회 범위를 제한하고, 미승인 후기는 작성자·관리자만 열람 |
| 다른 관광지·연도의 자료 혼입 | 관광지 식별자와 작성 연도로 조회·집계 범위를 제한하고, 자료가 없으면 빈 결과 반환 |
| AI 결과의 형식·근거 불일치 | 구조화된 응답과 JSON 스키마 검증, 출처·날짜 검증으로 근거가 맞지 않는 결과 거부 |
| 서버 배포 후 인증·채팅 연결 | HTTPS 도메인에 소셜 로그인 콜백을 등록하고 프록시 전달 헤더·WebSocket 연결 설정 적용 |

</details>

**프로젝트 링크**

- **PPT**: [개인 프로젝트 발표자료](https://docs.google.com/presentation/d/1jQhYCtxxMoQSMmzNW6W8jJQHY5S5MG6g/edit?rtpof=true&sd=true)
- **AWS**: [여행온도 서비스 접속](https://travelondo2026.duckdns.org/)

### 🎧 StreamWave — 음악 스트리밍 + 라이브 방송 플랫폼

> **팀 프로젝트 (3명)** · 2026.08.24 – 2026.09.09 (본인 참여 기간) · [저장소 보기](https://github.com/JOJOJACK-cmyk/-MUSIC-main2)
>
> 담당: 라이브 방송 백엔드 · 운영 배포 환경

YouTube 음원 스트리밍과 OBS 라이브 방송을 합친 음악 플랫폼입니다.
시청자가 방송을 보며 실시간으로 채팅하고 신청곡에 투표할 수 있습니다.

<img src="assets/streamwave/live-screen.png" width="820" alt="StreamWave 라이브 시청 화면 - 방송 영상, 시청자 수, 신청곡 투표, 실시간 채팅 (데모 데이터)" />

- **라이브 방송 파이프라인**: OBS → SRS(RTMP) → HLS 구조를 Docker로 구성하고, `on_publish` / `on_unpublish` 웹훅으로 실제 송출 기준으로 방송 ON/OFF를 자동 동기화 (종료 시 투표 데이터까지 정리). HLS 조각 2초 → 1초, 윈도 10초 → 6초로 조정
- **실시간 시청자 수**: 시청 화면이 5초마다 보내는 heartbeat를 Redis Sorted Set에 기록하고, 15초 이상 응답 없는 시청자를 제거한 뒤 `ZCARD`로 집계. 탭 종료·네트워크 단절도 최대 15초 안에 반영되고, 방송 종료 후에는 키 TTL(1분)로 자동 정리
- **실시간 채팅 · 신청곡 투표 (초기 구현)**: STOMP/SockJS 경로를 설계하고, Redis Set으로 중복 투표를 막고 Sorted Set으로 득표를 집계해 상위 10곡을 실시간 전송. 다음 곡 선택은 방송 소유자만 가능하도록 검증
- **운영 배포**: MySQL·Redis·SRS·Spring Boot·Caddy를 Compose 하나로 구성 — 멀티스테이지 빌드, MySQL 헬스체크 후 백엔드 기동, Redis AOF, Caddy 자동 HTTPS. 외부에는 80/443과 OBS 송출용 1935만 공개
- **데이터 모델 · 인증**: 이용권·결제 엔티티를 User 연관관계(`@ManyToOne(LAZY)` + FK)로 전환하고, 결제 `order_id`·`payment_key` UNIQUE로 중복 처리를 DB에서 방어. Google·Kakao·Naver 로그인 사용자 식별을 `AuthenticatedUserResolver`로 공통화
- 이 밖에 YouTube 플레이어, AWS S3 파일 업로드, Redis 기반 TOP 100 차트의 초기 구현에 참여

`Java 25` `Spring Boot 4.1` `Spring Security` `JPA` `MySQL` `Redis` `SRS 6 (RTMP / HLS)` `WebSocket (STOMP)` `React 18` `hls.js` `Docker Compose` `Caddy` `AWS S3`

<details>
<summary><b>🏗 구조 다이어그램</b></summary>
<br />

**방송 송출 · 상태 동기화 · 시청 흐름**

<img src="assets/streamwave/broadcast-sequence.png" width="760" alt="방송자 OBS, SRS, Spring Boot, MySQL·Redis, 시청자 사이의 송출 시작, 시청, 송출 종료 시퀀스 다이어그램" />

**Redis Sorted Set 기반 시청자 수 집계**

<img src="assets/streamwave/viewer-count.png" width="760" alt="heartbeat를 ZADD로 기록하고 15초 지난 시청자를 ZREMRANGEBYSCORE로 지운 뒤 ZCARD로 시청자 수를 구하는 구조" />

**신청곡 투표 · 다음 곡 선택 (초기 구현 기준)**

<img src="assets/streamwave/vote-flow.png" width="760" alt="시청자 투표가 Redis Set과 Sorted Set을 거쳐 상위 10곡으로 전송되고, 방송자만 다음 곡을 선택하는 흐름" />

**운영 배포 구성 (외부 공개 포트 최소화)**

<img src="assets/streamwave/deploy.png" width="760" alt="Docker Compose 단일 서버에서 Caddy, Spring Boot, MySQL, Redis, SRS를 구성하고 443과 1935만 외부에 공개하는 배포도" />

</details>

<details>
<summary><b>🔧 트러블슈팅</b></summary>
<br />

**1. SRS 장애가 서비스 전체 장애로 번지는 문제**
- 문제: SRS가 재시작되거나 죽으면 라이브 목록 API 전체가 500 에러
- 원인: 목록이 SRS HTTP API 조회에 의존하는데, 연결 실패 예외가 그대로 전파됨
- 해결: SRS 연결 실패를 처리해 경고 로그만 남기고 빈 목록 반환
- 결과: 미디어 서버 장애가 음악 재생·로그인 등 다른 기능으로 번지지 않음

**2. 컨테이너의 SRS가 호스트의 백엔드로 웹훅을 보내야 하는 문제**
- 문제: 개발 환경에서 SRS는 컨테이너, 백엔드는 호스트(IDE)에서 실행되어 `localhost`로는 웹훅 전달 불가
- 해결: `host.docker.internal` + `extra_hosts: host-gateway`로 리눅스 Docker에서도 동작하게 하고, 운영은 Compose 서비스명 `backend:8080`으로 분리
- 결과: 개발·운영 모두 같은 훅 구조로 방송 상태 동기화

**3. 로컬 주소가 코드에 고정되어 서버 배포가 불가능한 문제**
- 문제: OAuth 리다이렉트(`localhost:3000`)와 HLS 주소(`localhost:8081`)가 코드에 하드코딩
- 해결: `app.frontend-url` · `hls.base-url` · `srs.api.base-url` · CORS origin을 설정으로 분리해 prod 프로파일에서 주입. `RestClient`를 필드 초기화 시점에 만들면 `@Value` 주입 전이라 주소가 비는 문제도 생성자 생성으로 수정
- 결과: 같은 코드로 로컬과 서버 모두 동작

</details>

**프로젝트 링크**

- **AWS**: [StreamWave 서비스 접속](http://streamwave-j.duckdns.org/)

## 📫 Contact

[![GitHub](https://img.shields.io/badge/GitHub-JOJOJACK--cmyk-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JOJOJACK-cmyk)

<!--
  이메일, 블로그, 링크드인 등을 추가하려면:
  [![Email](https://img.shields.io/badge/Email-이메일주소-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:이메일주소)
  [![Blog](https://img.shields.io/badge/Blog-블로그이름-03C75A?style=for-the-badge&logo=naver&logoColor=white)](블로그주소)
-->
