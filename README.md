<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=FF9FBD&height=280&section=header&text=Hyein%27s%20GitHub&fontSize=64&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Backend-focused%20Full-Stack%20Developer&descAlignY=60&descSize=19"
    width="100%"
    alt="Hyein's GitHub Header"
  />
</p>

<div align="center">

## 안녕하세요, 백엔드 개발자 최혜인입니다 👋

사용자의 요구사항을 데이터와 기능으로 구체화하고,
서비스의 전체 흐름과 데이터 전달 구조를 이해하며 문제를 해결합니다.

**Spring Boot와 Node.js 기반의 백엔드 개발**을 중심으로
React·React Native를 활용한 프론트엔드 구현과
Kafka·Redis·WebSocket 기반의 실시간 데이터 처리 경험을 쌓았습니다.

<br>

<a href="mailto:hi020514@gmail.com">
  <img src="https://img.shields.io/badge/Email-hi020514%40gmail.com-FF8FA3?style=flat-square&logo=gmail&logoColor=white"/>
</a>
<a href="https://rose-day.tistory.com/">
  <img src="https://img.shields.io/badge/Tech_Blog-rose--day.tistory.com-FFB6C1?style=flat-square&logo=tistory&logoColor=white"/>
</a>

</div>

---

## 🌱 About Me

* 백엔드를 중심으로 서비스의 전체 구조를 이해하는 풀스택 개발자입니다.
* 단순한 기능 구현을 넘어 **데이터 흐름과 서비스 운영 정책**을 함께 고민합니다.
* REST API 설계, 데이터베이스 모델링, 실시간 통신 및 이벤트 처리 경험이 있습니다.
* 문제의 원인을 끝까지 추적하고 해결 과정과 검증 결과를 기록합니다.
* 팀 프로젝트에서 일정과 진행 상황을 공유하며 협업을 조율한 경험이 있습니다.

---

## 🚀 Featured Projects

### 🏭 AIMS

> **Auto Intelligence Manufacturing System**
> AI 기반 자동차 스마트팩토리 관제 시스템

자동차 제조 공정에서 발생하는 데이터를 실시간으로 수집하고,
이상 징후와 설비 상태를 분석하여 우선순위에 따라 알람을 제공하는 관제 플랫폼입니다.

#### 🔗 Repository

* [AIMS Main Dashboard — 실시간 알람 및 통합 관제](https://github.com/hyein0514/AIMS-MainDashBoard)
* [AIMS Assembly Dashboard — 제조 공정 모니터링](https://github.com/hyein0514/AIMS-AssemblyDashBoard)

#### 주요 기능

* 프레스·차체·도장·의장 공정별 실시간 대시보드
* 공정 및 설비 이상 데이터 탐지와 상태 시각화
* ML 기반 불량 전이 가능성 예측
* 이벤트 위험도 기반 우선순위 점수 산정
* Kafka 기반 이상 이벤트 발행 및 수신
* WebSocket·STOMP 기반 실시간 알람 전달
* AI 기반 이상 원인 분석 및 조치 매뉴얼 제공
* Redis 캐시를 활용한 데이터 조회 성능 개선

#### 담당 업무

* Kafka 기반 공정 이상 이벤트 처리 구조 구현
* eRPN 기반 이벤트 위험도 및 우선순위 산정 로직 구현
* WebSocket·STOMP 기반 실시간 알람 연동
* 알람 저장 조건과 실시간 전송 흐름 분석 및 개선
* 제조 분석 결과의 위험도·상태·메시지 간 판정 기준 일관성 개선
* 프론트엔드와 백엔드 간 실시간 알람 데이터 구조 연동
* 팀장으로서 데일리 스크럼 진행 및 팀·강사·멘토 간 커뮤니케이션 조율

#### 주요 기술

`Java` `Spring Boot` `MySQL` `Kafka` `Redis`
`WebSocket` `STOMP` `React` `TypeScript` `Docker`

---

### 📘 E:ON

> 학사일정과 개인 관심사를 기반으로
> 청소년의 학업·진로·사회활동을 연결하는 교육 챌린지 플랫폼

🏆 **2025 교내 소프트웨어경진대회 은상 수상**

NEIS 학사일정 API와 사용자의 관심 분야, 진로 희망 및 활동 이력을 활용해
학생과 학부모에게 적합한 활동과 챌린지를 제공하는 서비스입니다.

#### 🔗 Repository

* [E:ON GitHub Repository](https://github.com/hyein0514/E-on)

#### 주요 기능

* 학교별·지역별 학사일정 조회
* 챌린지 개설·참여·출석·리뷰 관리
* 관심 분야와 활동 이력 기반 맞춤형 추천
* 학생·학부모 대상 커뮤니티
* 관리자 승인 및 신고 관리
* 사용자 알림 기능

#### 담당 업무

* 챌린지 생성·조회·수정·삭제 REST API 구현
* 모집 마감일을 기준으로 한 챌린지 상태 자동 변경
* 최근 결석 이력을 활용한 챌린지 개설 제한 정책 구현
* Sequelize 트랜잭션 기반 다중 테이블 저장
* 관심 분야·진로 분야 다대다 관계 설계
* 다양한 검색 조건을 조합할 수 있는 동적 필터 조회
* Docker Compose 기반 프론트엔드·백엔드·DB 실행 환경 구성

#### 주요 기술

`Node.js` `Express` `Sequelize` `MySQL`
`React` `JavaScript` `NEIS Open API` `Docker`

---

### 🎯 WishBoard

> 목표를 기록하고 공유하며 함께 달성하는 버킷리스트 플랫폼

사용자가 버킷리스트를 등록하고 진행 과정을 기록하며,
같은 목표를 가진 사용자들과 경험을 공유할 수 있는 목표 관리 서비스입니다.

목표 달성 후에는 트로피와 인증 게시글로 성과를 기록하고,
완료 이력을 기반으로 AI가 새로운 목표를 추천합니다.

#### 🔗 Repository

* [WishBoard GitHub Repository](https://github.com/hyein0514/wishboard)

#### 주요 기능

* 버킷리스트 등록 및 진행률 관리
* 목표 기반 커뮤니티와 팀 활동
* 목표 달성 트로피 및 인증 게시글
* 명예의 전당 Top 10
* GPT 기반 다음 목표 추천
* 마이페이지 및 알림 기능

#### 담당 업무

* 커뮤니티 즐겨찾기, 게시글 작성·조회·검색 기능 구현
* 댓글 및 대댓글 작성 기능 구현
* `parentCommentId` 기반 계층형 댓글 구조 설계
* 지연 로딩과 부분 조회를 활용한 댓글 조회 최적화
* 키워드 기반 커뮤니티 검색 및 유형별 결과 집계
* React Native와 Spring Boot 간 REST API 연동
* Figma UI 기획부터 React Native 앱 화면 구현까지 수행

#### 주요 기술

`Java` `Spring Boot` `Spring Data JPA` `MySQL`
`Spring Security` `JWT` `React Native` `OpenAI API` `Swagger`

---

## 🗂 Other Projects

### 💬 Campus Connect

> 언어 교환을 위한 실시간 채팅 및 커뮤니티 서비스

언어를 학습하는 사용자들이 서로 연결되어
실시간으로 대화하고 학습 정보와 경험을 공유할 수 있는 서비스입니다.

---

### 🏢 Hello HR

> 연차 결재와 AI 자기소개서 분석 기능을 포함한 ERP 인사관리 시스템

기업의 인사 업무를 효율적으로 관리할 수 있도록
연차 신청·승인 프로세스와 임직원 정보 관리 기능을 구현했습니다.

---

### ✈️ COSTRIP

> 여행 지출 기록 및 소비 패턴 분석 서비스

여행 중 발생한 지출을 카테고리별로 기록하고,
예산 대비 사용 금액과 소비 패턴을 시각적으로 분석하는 서비스입니다.

---

## 🛠 Tech Stack

### Backend

<p>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
</p>

### Database & ORM

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Data_JPA-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
</p>

### Messaging & Realtime

<p>
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
  <img src="https://img.shields.io/badge/STOMP-FF6B6B?style=flat-square"/>
</p>

### Frontend

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

### Infrastructure & Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
</p>

---

## 🏆 Awards & Certifications

### 🥇 Awards

|      수상 시기      | 수상 내역                      | 주관·수여 기관 |
| :-------------: | -------------------------- | -------- |
|     2025.09     | 교내 소프트웨어경진대회 은상 — **E:ON** | 성신여자대학교  |
|     2023.09     | 교내 소프트웨어경진대회 장려상           | 성신여자대학교  |
| 3학년 1학기·4학년 1학기 | 성신장학금 성적우수 장학금 — **총 2회**  | 성신여자대학교  |

### 📜 Certifications

|     취득일    | 자격증           | 발행처        |
| :--------: | ------------- | ---------- |
| 2025.07.11 | 빅데이터분석기사      | 한국데이터산업진흥원 |
| 2025.04.04 | SQL 개발자(SQLD) | 한국데이터산업진흥원 |
| 2024.09.10 | 정보처리기사        | 한국산업인력공단   |
| 2024.03.08 | 컴퓨터활용능력 1급    | 대한상공회의소    |

---

## 🎓 Education

### 성신여자대학교

* **2021.03 - 2026.02**
* 컴퓨터공학과 졸업

### SK쉴더스 지능형 애플리케이션 개발자 양성과정 5기

* **2026.01 - 2026.07**
* 클라우드·MSA 기반 지능형 애플리케이션 개발 과정 수료
* Spring Boot, React, Kafka, Redis, Docker 및 AI 연계 프로젝트 수행

---

## 💡 How I Work

### 01. 요구사항을 데이터 흐름으로 구체화합니다

화면에 필요한 데이터가 어디에서 생성되고,
어떤 API와 서비스 로직을 거쳐 전달되는지 먼저 파악합니다.

### 02. 서비스 정책을 서버 로직으로 구현합니다

권한, 상태 변경, 개설 제한과 같은 운영 정책이
클라이언트에 의존하지 않도록 서버에서 검증합니다.

### 03. 데이터 정합성을 중요하게 생각합니다

트랜잭션과 연관관계 설계를 활용해
일부 데이터만 저장되거나 잘못 연결되는 상황을 방지합니다.

### 04. 실시간 데이터의 전달 흐름을 이해합니다

Kafka 이벤트 발행부터 데이터 저장, WebSocket 전송,
프론트엔드 화면 반영까지 전체 흐름을 추적하며 구현합니다.

### 05. 문제 해결 과정을 기록합니다

오류 현상만 수정하는 데 그치지 않고
원인, 해결 방법, 검증 결과를 정리하여 같은 문제가 반복되지 않도록 합니다.

---

## 📫 Contact

<p>
  <a href="mailto:hi020514@gmail.com">
    <img src="https://img.shields.io/badge/Email-hi020514%40gmail.com-FF8FA3?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://rose-day.tistory.com/">
    <img src="https://img.shields.io/badge/Tech_Blog-rose--day.tistory.com-FFB6C1?style=flat-square&logo=tistory&logoColor=white"/>
  </a>
</p>

---

<div align="center">

### 문제를 발견하고 데이터의 흐름을 이해하며, 끝까지 해결하는 개발자가 되겠습니다. 🌷

</div>

![footer](https://capsule-render.vercel.app/api?type=waving\&color=FF9FBD\&height=160\&section=footer)
