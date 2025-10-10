<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/dd0f3082-61fb-44ed-8518-e6cef8754361" width="197" />
  <h3 align="center">온라인 메모장 📝</h3>
  <p align="center">
    공동 편집 가능한 경량화 메모장<br>
    <a href="https://github.com/OnlineMemo/backend"><strong>Backend Repo »</strong></a><br>
    <a href="https://github.com/OnlineMemo/frontend-web"><strong>Frontend Repo »</strong></a>
    <!-- <a href="https://github.com/orgs/OnlineMemo/repositories?q=sort%3Aname-asc"><strong>FullStack Repo »</strong></a> -->
    <!-- <a href="https://github.com/OnlineMemo/backend"><strong>Backend - Refactor Ver.2 »</strong></a> -->
  </p>
</div>
<br>

<details open>
  <summary><strong>&nbsp;📖&nbsp;목차</strong></summary>

1. &nbsp;&nbsp;[🔍 Introduction](#-introduction)
2. &nbsp;&nbsp;[📄 Documents](#-documents)
3. &nbsp;&nbsp;[📹 Demo](#-demo)
4. &nbsp;&nbsp;[💡 Tech Stack](#-tech-stack)
5. &nbsp;&nbsp;[🗂️ Database](#%EF%B8%8F-database)
6. &nbsp;&nbsp;[💻 Architecture](#-architecture)
   - &nbsp;[System](#system)
   - &nbsp;[Back Office](#back-office)
   - &nbsp;[Monitoring](#monitoring)
7. &nbsp;&nbsp;[📂 Directory Structure](#-directory-structure)
8. &nbsp;&nbsp;[👨‍👩‍👧‍👧 Team](#%E2%80%8D%E2%80%8D%E2%80%8D-team-full-stack)
</details>
<br>



## 🔍 Introduction

### 배경
기존 메모 서비스들은 다양한 기능을 추가하며, 정작 핵심인 '간편함'을 잃었습니다.<br>
'다기능 = 편리함'이라는 전제 아래 복잡해졌고, 오히려 단순한 메모 작성조차 번거로워졌습니다.<br>
심지어 일부 서비스는 다른 기기에서 열람하려면 소셜 로그인 내 본인인증까지 거쳐야 합니다.

그래서 질문했습니다. "편리함은 꼭 기능의 많음에서 오는 걸까?"<br>
이에 남녀노소 누구나 직관적으로 사용하도록, 본질에 집중한 '경량화 메모장'을 개발했습니다.<br>
어떤 기기에서든 쉽고 빠르게, 가볍지만 공동 편집까지 가능한 '진짜 편리함'을 제공합니다.

### 특징
- 빠른 로그인&nbsp;:&nbsp;&nbsp;개인정보 없이 ID·PW로만 즉시 가입/로그인, 계정별 메모 관리
- 친구 초대&nbsp;:&nbsp;&nbsp;계정 초대/수락으로 친구를 맺고, 메모에 함께 참여 가능
- 공동 메모&nbsp;:&nbsp;&nbsp;여러 사용자가 함께 메모를 관리, 권한 기반으로 편집 충돌 방지
- 메모 분류&nbsp;:&nbsp;&nbsp;전체/개인/공동/즐겨찾기 메모를 선택해 유형별로 조회 가능
- 제목 AI 생성&nbsp;:&nbsp;&nbsp;작성중인 메모 내용에 어울리는 제목을 AI가 자동으로 추천
- 직관적 UI/UX&nbsp;:&nbsp;&nbsp;복잡한 기능 및 절차 최소화, 편안한 색감과 간결한 인터페이스
- 기기/플랫폼 호환&nbsp;:&nbsp;&nbsp;PC·모바일, Android·iOS, 웹·앱 모두 지원
<br>

<!--
### 주제 선정
기존의 메모장들에는 잡다한 많은 기능들이 탑재되어있어, 사용에 어려움을 느꼈습니다. <br>
이에 본연의 기능을 살리고, 남녀노소 누구나 쉽게 이용 가능한 경량화 메모장을 제공합니다.

### 특징
- 불필요한 기능을 제거하고, 간편하고 직관적인 디자인으로 주요 기능의 접근성을 높였습니다. <br>
또한 눈이 편안한 색감을 선정하여 심플하게 디자인하였습니다.
- 개인정보 필요없이 생성할 id와 pw만 입력하여, 쉽고 빠르게 회원가입이 가능합니다. <br>
이로써 회원가입의 거부감을 줄이고, 어느 기기에서든지 접속하여 계정별로 메모를 관리할 수 있습니다.
- 여러 사람이 공동으로 메모를 편집 및 관리할 수 있는 '공동 메모' 기능을 추가하였습니다. <br>
대학생 팀플이나 회의 내용 작성으로도 적합합니다.
- 광고 삽입은 접근성을 떨어뜨리기에, 수익창출 없이 무료로 이용 가능하도록 하였습니다.
<br>
-->



## 📄 Documents

- <strong>운영</strong>&nbsp;:&nbsp;&nbsp;2023.09.03 ~ 2025 (ing)
  - Web&nbsp;:&nbsp;&nbsp;<a href="https://www.onlinememo.kr">www.OnlineMemo.kr</a>
  - App&nbsp;:&nbsp;&nbsp;<a href="https://play.google.com/store/apps/details?id=com.shj.onlinememo">Google Play 스토어</a>
  - Back Office&nbsp;:&nbsp;&nbsp;<a href="https://github.com/OnlineMemo/backend/pull/9">[PR] Admin 백오피스 구현</a><br>&nbsp;⇒&nbsp;&nbsp;2025.08)&nbsp;&nbsp;가입자 수 1200여명, 실사용자 수 월간 210명&nbsp;&nbsp;**|**&nbsp;&nbsp;現 1300여명, 240명<br>&nbsp;<img src="https://github.com/user-attachments/assets/52bf97bc-8fbf-4d35-b257-6d74a35485d4" width="73%" />

- #### [BE] API 명세서
  - Swagger API 명세서<br><img src="https://github.com/user-attachments/assets/54c9bfa6-7425-4a09-8a6a-7718cbb7bc5c" width="85%" />
  <!-- - <details open><summary>&nbsp;Swagger API 명세서</summary><img src="https://github.com/user-attachments/assets/54c9bfa6-7425-4a09-8a6a-7718cbb7bc5c" width="86%" /></details> -->

- #### [BE] 성능 개선기 📝
  - [깃허브]&nbsp;&nbsp;<a href="https://github.com/OnlineMemo/backend">Backend 대규모 리팩토링 - DB 재설계 · Query 튜닝 · API 다중호출 개선</a>
  - [블로그]&nbsp;&nbsp;<a href="https://velog.io/@tkguswls1106/JPA-Auditing-%EC%B6%94%EC%A0%81-%EB%B2%97%EC%96%B4%EB%82%98%EA%B8%B0-LastModifiedDate-%EC%97%85%EB%8D%B0%EC%9D%B4%ED%8A%B8-%EB%B0%A9%EC%A7%80">Auditing 추적 벗어나기 (@LastModifiedDate 업데이트 방지)</a>
  - [PR]&nbsp;&nbsp;<a href="https://github.com/OnlineMemo/backend/pull/5">동시성 제어 - Redis Lettuce 분산 락 · MySQL 낙관적 락 · Transaction 분리</a>
  - [PR]&nbsp;&nbsp;<a href="https://github.com/OnlineMemo/backend/pull/11">OpenAI - 메모 제목 AI 자동 생성기능 구현</a>

- #### [FE] 성능 개선기 📝
  - [깃허브]&nbsp;&nbsp;<a href="https://github.com/OnlineMemo/frontend-web">Frontend 대규모 리팩토링</a>
<br>



## 📹 Demo

### Google Play 스토어

<img width="80%" alt="플레이스토어 스크린샷" src="https://github.com/OnlineMemo/.github/assets/56509933/ab015384-804a-4bf8-9ac6-4e238623cf13">
<img width="80%" alt="플레이스토어 PC 스크린샷" src="https://github.com/OnlineMemo/.github/assets/56509933/b8d9ebd0-8afe-48a5-ab2a-7d8ea99f7065">

### PC Page

**메모 목록 조회**|**메모 내용 조회**|**친구 공동메모 초대**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/d662b9b9-4c55-4fbb-8199-b5e6dd222f0e" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/35c09de5-7f59-4e06-ab74-d9bcd6f0647e" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/2096b659-80ca-4f77-b6b7-7f4c760357e0" width="100%">

### Mobile Page

**로그인**|**메모 목록 조회**|**메모 내용 조회**|**메모 작성 (+ AI 제목)**
:-----:|:-----:|:-----:|:-----:
<img src="https://github.com/OnlineMemo/.github/assets/56509933/1f5c053b-13e5-4da2-9a4f-3db57e983611">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/6e5a4727-56b1-473f-8451-fed8864ae91a">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/7eb239e1-b338-4141-a6e6-745140167b70">|<img src="https://github.com/user-attachments/assets/0fc2e249-1883-4d1e-af16-c08c5e75f6b4"><!-- <img src="https://github.com/OnlineMemo/.github/assets/56509933/9101fd58-c90a-48dd-af24-a3693aec1b7d"> <img src="https://github.com/user-attachments/assets/f8c20ae5-6f3a-4559-bbb0-cc8a37f5b58c"> -->

**프로필 조회**|**친구 목록 조회**|**친구요청 수신 목록 조회**|**친구 공동메모 초대**
:-----:|:-----:|:-----:|:-----:
<img src="https://github.com/OnlineMemo/.github/assets/56509933/d28b8bb5-55fe-4fcf-8225-5ad557a945e3">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/981d4884-5faf-488d-9822-339fd866ce5d">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/ae8c9f27-2b47-4a9e-99e3-d1a5c8a0eb92">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/707a9527-ec8a-4863-8d12-608693bc3e8e">

<br>



<!--
## 👨‍👩‍👦‍👦 Launch

### 마케팅

**에브리타임**|**인스타그램**
-----|-----
<img src="https://github.com/tkguswls1106/tkguswls1106/assets/56509933/11fabfbd-227a-430b-a048-3c95b6f06e53" width="100%">|<img src="https://github.com/tkguswls1106/tkguswls1106/assets/56509933/420dea2c-82bf-491f-b753-847b957747eb" width="100%">
대학생 커뮤니티에 홍보글을 게시하여, HOT 게시물로 선정되었습니다.|SNS에 홍보글을 게시하여, 다양한 연령대의 접근성을 고려했습니다. 그 결과, 100명 이상의 이용자에게 서비스를 제공 중입니다.

<br>
-->



## 💡 Tech Stack
|Frontend|Backend|Back Office|Security|Other|
|:------:|:------:|:------:|:------:|:------:|
|<img src="https://img.shields.io/badge/React-61DBFB?style=flat-square&logo=React&logoColor=white"/></a><br><img src="https://smartcart-s3-bucket.s3.ap-northeast-2.amazonaws.com/badge_ReactNative.svg" alt="[ React Native ]"/></a><br><img src="https://img.shields.io/badge/JavaScript-F7DF1F?style=flat-square&logo=JavaScript&logoColor=white"/></a>|<img src="https://smartcart-s3-bucket.s3.ap-northeast-2.amazonaws.com/badge_SpringBoot.svg" alt="[ Spring Boot ]"/></a><br><img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=coffeeScript&logoColor=white"/></a><br><img src="https://img.shields.io/badge/OpenAI-74AA9C?style=flat-square&logo=OpenAI&logoColor=white"/></a><br><img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a><br><img src="https://smartcart-s3-bucket.s3.ap-northeast-2.amazonaws.com/badge_Redis.svg" alt="[ Redis ]"/></a>|<img src="https://img.shields.io/badge/GA4-E37400?style=flat-square&logo=googleanalytics&logoColor=white"/><br><img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white"/><br><img src="https://img.shields.io/badge/Cloud Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/><br><img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white"/>|<img src="https://smartcart-s3-bucket.s3.ap-northeast-2.amazonaws.com/badge_SpringSecurity.svg" alt="[ Spring Security ]"/></a><br><img src="https://smartcart-s3-bucket.s3.ap-northeast-2.amazonaws.com/badge_JSONWebToken.svg" alt="[ JSON Web Token ]"/></a>|<img src="https://smartcart-s3-bucket.s3.ap-northeast-2.amazonaws.com/badge_AmazonAWS.svg" alt="[ Amazon AWS ]"/></a><br><img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=Slack&logoColor=white"/><br><img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Swagger-85EA2E?style=flat-square&logo=Swagger&logoColor=white"/></a>

```
- Frontend : React, React Native, JavaScript
- Backend : Spring Boot, Java, Spring Security, JWT, OpenAI
- Back Office : GA4, BigQuery, Cloud Run
- Database : MySQL, Redis, MongoDB
- Deployment : Amazon AWS
- Tool : Slack, Postman, Swagger
```
<br>



## 🗂️ Database

<details open>
  <summary>&nbsp;<strong>Redis</strong>&nbsp;:&nbsp;&nbsp;<strong>서비스 데이터 (임시)</strong>&nbsp;&nbsp;⇒&nbsp;&nbsp;편집권한 Lock, 일일 AI 호출 횟수 등</summary>
<br>
  
| 항목          | Key-Value                                                                      | TTL | 설명                                                                            |
| ------------ | ------------------------------------------------------------------------------ | --- | ------------------------------------------------------------------------------ |
| 편집권한 Lock  | {`메모정보:lock` : `사용자정보`}<br>{`memoId:1200:lock` : `userId:10,userName:현진`} | 10분 | - Redis Lettuce 분산 락<br>- 편집자 외 수정접근 제한<br>&nbsp;&nbsp;(편집 중인 상대방 표시)
| 일일 AI 호출횟수  | {`사용자정보:openai_usage` : `호출횟수`}<br>{`userId:1200:openai_usage` : `3`}    | 자정  | 개인 OpenAI 호출량 검사<br>(일일 최대 10회 제한)
| JVM Heap 위험 쿨타임<br>(스케줄러 + Slack) | {`backoffice:경보종류` : `true`}<br>{`backoffice:heap_notification` : `true`} | 1시간 | - 5분마다 힙메모리 체크<br>- 70/80/90% Slack 알림<br>&nbsp;&nbsp;(1시간 내 중복알림 방지)

</details>

<details>
  <summary>&nbsp;<strong>MySQL</strong>&nbsp;:&nbsp;&nbsp;<strong>서비스 데이터 (영구)</strong>&nbsp;&nbsp;⇒&nbsp;&nbsp;사용자, 메모, 친구 관계 등</summary>
<br>
<!-- <img width="1470" alt="mysql DB ERD" src="https://github.com/OnlineMemo/.github/assets/56509933/6bf90043-9bb4-435d-9ac3-5c8e8123a34c"> -->
<!-- <img width="1470" alt="mysql DB ERD" src="https://github.com/user-attachments/assets/48beb98f-f616-4950-b1c5-05d779a90e0d"> -->
<img width="1470" alt="mysql DB ERD" src="https://github.com/user-attachments/assets/dd03f5d3-1e92-4431-b274-972fbbcc1e8c">
</details>

<details>
  <summary>&nbsp;<strong>MongoDB</strong>&nbsp;:&nbsp;&nbsp;<strong>트래픽 데이터</strong>&nbsp;&nbsp;⇒&nbsp;&nbsp;GA4 페이지뷰, 접속자 기기, 국가 등</summary>
<br>

| 구분        | 항목            | 컬럼명                | 설명                  |
| ---------- | -------------- | ------------------- | -------------------- |
| 이벤트 정보   | 이벤트 시간       | `event_datetime`    | 이벤트 발생 시각         |
|            | 활성 사용자 ID    | `user_pseudo_id`    | 익명 사용자 식별 ID      |
|            | 로그인 사용자 ID   | `login_user_id`     | 로그인한 사용자 ID       |
| 페이지 정보   | 페이지명          | `page_title`        | 브라우저 탭/문서 제목     |
|            | 유입 경로 URL     | `page_referrer`     | 이전 페이지 URL         |
|            | 현재 경로 URL     | `page_location`     | 전체 현재 페이지 URL     |
|            | 현재 경로 Path    | `page_path`         | 도메인 제외한 경로        |
| 기기 정보    | 기기 카테고리      | `device_category`   | 모바일/데스크톱 등        |
|            | 기기 브랜드명      | `device_brand`      | 기기 제조사             |
|            | 웹 브라우저        | `device_browser`   | 사용 브라우저 이름        |
| 접속 정보    | 국가             | `geo_country`       | 접속 국가              |
|            | 지역             | `geo_region`        | 접속 지역(주/도 단위)    |
|            | 도시             | `geo_city`          | 접속 도시              |

</details>

<br>



## 💻 Architecture

### System
![onlinememo_architecture drawio](https://github.com/user-attachments/assets/fdc19a6b-5b9d-46ac-882b-9d8a78eac484)

```
- Frontend Deployment : AWS Amplify
- Backend Deployment : AWS Elastic Beanstalk
- Database : AWS RDS, Upstash Redis
- DNS : AWS Route53
- Traffic : AWS Application Load Balancer, Auto Scaling (CPU 70% Out, 30% In)
- Monitoring : AWS CloudWatch, Slack, Spring Logback, ExceptionHandler
- Version control : AWS S3, GitHub
```

### Back Office
![backoffice_architecture drawio](https://github.com/user-attachments/assets/994e6a64-85c2-413e-b044-3ce614a04ded)
![backoffice_statistics drawio](https://github.com/user-attachments/assets/396aefe9-034c-4879-a1e9-c214c501994b)

```
GA4 (React : 실사용자 지표 수집)
→ BigQuery (SQL : 수집 데이터 검증)
→ Cloud Run (Serverless API : 데이터 필터링 및 제공)
→ MongoDB (Spring : 정제된 지표 저장 및 백오피스 운용)
```

### Monitoring

**테스터**|**트래픽**
:-----:|:-----:
<img src="https://github.com/tkguswls1106/tkguswls1106/assets/56509933/145aaa0c-ad71-4e16-bc80-f36a2e50b3d0" width="400px">|<img src="https://github.com/tkguswls1106/tkguswls1106/assets/56509933/deb45a45-6828-4107-be56-d011fe89d558" width="90%">
Web & App 테스터를 모집해,<br>특정 시간대 10분 동안의<br>트래픽 변화를 측정.|테스터 30명의 동시접속 결과, CPU 사용률이 0.7% → 6% 상승함을 확인.<br>초기 운영에는 충분하나, 예기치 않은 트래픽 증가 시 Burst 기능을 안정적으로 운용하고자<br>인스턴스를 `t3.nano(CPU 크레딧 6)` → `t3.micro(CPU 크레딧 12)`로 Scale Up 조치.

<table>
  <tr>
    <th><strong>Slack 경보</strong></th>
    <th><strong>CloudWatch 로깅</strong></th>
  </tr>
  <tr>
    <td><img width="781" src="https://github.com/user-attachments/assets/77fbfd4d-ba70-443d-bab7-edae81ac0a2a"></td>
    <td><img width="1470" src="https://github.com/user-attachments/assets/22721d18-6d9f-4a96-a7e3-5ccd6ad99ef7"><!-- <img width="1470" alt="AWS CloudWatch" src="https://github.com/OnlineMemo/.github/assets/56509933/266c6619-4995-479a-9cc1-b73cc4bb7544"> --></td>
  </tr>
  <tr>
    <td colspan="2">
      1.&nbsp;&nbsp;Spring ExceptionHandler : Error Handling<br>
      2.&nbsp;&nbsp;Spring Logback : Logging<br>
      3.&nbsp;&nbsp;<code>Local</code>&nbsp;&nbsp;File Storage : Save to file<br>
      4-1.&nbsp;&nbsp;<code>Prod</code>&nbsp;&nbsp;AWS CloudWatch : Monitoring<br>
      4-2.&nbsp;&nbsp;<code>Prod</code>&nbsp;&nbsp;Slack Webhook : Notification
    </td>
  </tr>
</table>

<br>



## 📂 Directory Structure

<details open>
  <summary>&nbsp;<strong>Backend</strong>&nbsp;:&nbsp;&nbsp;Open!</summary>
  <br>

```
:                                                 :
├── client                                        ├── repository
│   ├── Ga4Client.java                            │   ├── UserRepository.java
│   └── OpenAIClient.java                         │   ├── MemoRepository.java
├── config                                        │   ├── MemoBatchRepository.java
│   ├── FeignConfig.java                          │   ├── UserMemoRepository.java
│   ├── SecurityConfig.java                       │   ├── UserMemoBatchRepository.java
│   ├── SwaggerConfig.java                        │   ├── FriendshipRepository.java
│   ├── RedisConfig.java                          │   ├── FriendshipBatchRepository.java
│   └── OpenAIConfig.java                         │   ├── Ga4FilteredRepository.java
├── controller                                    │   ├── Ga4FilteredBatchRepository.java
│   ├── AuthController.java                       │   └── RedisRepository.java
│   ├── UserController.java                       ├── response
│   ├── MemoController.java                       │   ├── ResponseCode.java
│   ├── FriendshipController.java                 │   ├── ResponseData.java
│   ├── BackOfficeController.java                 │   ├── GlobalExceptionHandler.java
│   └── TestController.java                       │   ├── exception
├── domain                                        │   │   ├── CustomException.java
│   ├── User.java                                 │   │   ├── Exception400.java
│   ├── Memo.java                                 │   │   ├── Exception404.java
│   ├── Friendship.java                           │   │   ├── Exception409.java
│   ├── mapping                                   │   │   ├── Exception423.java
│   │   └── UserMemo.java                         │   │   ├── Exception429.java
│   ├── backoffice                                │   │   └── Exception500.java
│   │   └── Ga4Filtered.java                      │   └── responseitem
│   ├── common                                    │       ├── MessageItem.java
│   │   ├── BaseCreatedEntity.java                │       └── StatusItem.java
│   │   └── BaseModifiedEntity.java               ├── service
│   └── enums                                     │   ├── AuthService.java
│       ├── Authority.java                        │   ├── UserService.java
│       └── FriendshipState.java                  │   ├── MemoService.java
├── dto                                           │   ├── MemoFacade.java
│   ├── AuthDto.java                              │   ├── UserMemoService.java
│   ├── UserDto.java                              │   ├── FriendshipService.java
│   ├── MemoDto.java                              │   ├── Ga4FilteredService.java
│   ├── FriendshipDto.java                        │   ├── BackOfficeScheduler.java
│   └── Ga4FilteredDto.java                       │   └── impl
└── jwt                                           │       ├── AuthServiceImpl.java
    ├── JwtFilter.java                            │       ├── UserServiceImpl.java
    ├── TokenProvider.java                        │       ├── MemoServiceImpl.java
    ├── CustomUserDetailsService.java             │       ├── MemoFacadeImpl.java
    └── handler                                   │       ├── UserMemoServiceImpl.java
        ├── JwtExceptionFilter.java               │       ├── FriendshipServiceImpl.java
        ├── JwtAccessDeniedHandler.java           │       └── Ga4FilteredServiceImpl.java
        └── JwtAuthenticationEntryPoint.java      └── util
                                                      ├── SecurityUtil.java
                                                      └── TimeConverter.java
```
<!--
```
:
├── client
│   └── Ga4Client.java
├── config
│   ├── FeignConfig.java
│   ├── RedisConfig.java
│   ├── SecurityConfig.java
│   └── SwaggerConfig.java
├── controller
│   ├── AuthController.java
│   ├── BackOfficeController.java
│   ├── FriendshipController.java
│   ├── MemoController.java
│   ├── TestController.java
│   └── UserController.java
├── domain
│   ├── Friendship.java
│   ├── Memo.java
│   ├── User.java
│   ├── backoffice
│   │   └── Ga4Filtered.java
│   ├── common
│   │   ├── BaseCreatedEntity.java
│   │   └── BaseModifiedEntity.java
│   ├── enums
│   │   ├── Authority.java
│   │   └── FriendshipState.java
│   └── mapping
│       └── UserMemo.java
├── dto
│   ├── AuthDto.java
│   ├── FriendshipDto.java
│   ├── Ga4FilteredDto.java
│   ├── MemoDto.java
│   └── UserDto.java
├── jwt
│   ├── CustomUserDetailsService.java
│   ├── JwtFilter.java
│   ├── TokenProvider.java
│   └── handler
│       ├── JwtAccessDeniedHandler.java
│       ├── JwtAuthenticationEntryPoint.java
│       └── JwtExceptionFilter.java
├── repository
│   ├── FriendshipBatchRepository.java
│   ├── FriendshipRepository.java
│   ├── Ga4FilteredBatchRepository.java
│   ├── Ga4FilteredRepository.java
│   ├── MemoBatchRepository.java
│   ├── MemoRepository.java
│   ├── RedisRepository.java
│   ├── UserMemoBatchRepository.java
│   ├── UserMemoRepository.java
│   └── UserRepository.java
├── response
│   ├── GlobalExceptionHandler.java
│   ├── ResponseCode.java
│   ├── ResponseData.java
│   ├── exception
│   │   ├── CustomException.java
│   │   ├── Exception400.java
│   │   ├── Exception404.java
│   │   ├── Exception409.java
│   │   ├── Exception423.java
│   │   └── Exception500.java
│   └── responseitem
│       ├── MessageItem.java
│       └── StatusItem.java
├── service
│   ├── AuthService.java
│   ├── FriendshipService.java
│   ├── Ga4FilteredScheduler.java
│   ├── Ga4FilteredService.java
│   ├── MemoFacade.java
│   ├── MemoService.java
│   ├── UserMemoService.java
│   ├── UserService.java
│   └── impl
│       ├── AuthServiceImpl.java
│       ├── FriendshipServiceImpl.java
│       ├── Ga4FilteredServiceImpl.java
│       ├── MemoFacadeImpl.java
│       ├── MemoServiceImpl.java
│       ├── UserMemoServiceImpl.java
│       └── UserServiceImpl.java
└── util
    ├── SecurityUtil.java
    └── TimeConverter.java
```
-->
</details>

<details>
  <summary>&nbsp;<strong>Frontend_Web</strong>&nbsp;:&nbsp;&nbsp;Open!</summary>
  <br>

```
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── linkthumbnail.png
│   ├── manifest.json
│   ├── memoicon128.png
│   ├── memoicon192.png
│   └── memoicon512.png
└── src
    ├── assets
    │   ├── fonts
    │   │   ├── BMJUA_ttf.ttf
    │   │   ├── Kalam-Bold.ttf
    │   │   ├── Kalam-Light.ttf
    │   │   └── Kalam-Regular.ttf
    │   ├── css
    │   │   ├── confirmAlert.css
    │   │   └── mobileToast.css
    │   └── images
    │       └── user.png
    ├── apis
    │   └── Api.jsx
    ├── components
    │   ├── List
    │   │   ├── FriendList.jsx
    │   │   ├── InviteFriendList.jsx
    │   │   ├── MemoList.jsx
    │   │   ├── MemoListItem.jsx
    │   │   ├── SelectFriendList.jsx
    │   │   └── SenderList.jsx
    │   ├── Modal
    │   │   ├── ConfirmModal.jsx
    │   │   ├── FriendGroupModal.jsx
    │   │   ├── GlobalModal.jsx
    │   │   ├── NoticeModal.jsx
    │   │   └── SendFriendshipModal.jsx
    │   ├── Navigation
    │   │   ├── LoadingNav.jsx
    │   │   ├── NewMemoNav.jsx
    │   │   ├── NoLoginNav.jsx
    │   │   ├── ReadAndEditMemoNav.jsx
    │   │   └── YesLoginNav.jsx
    │   ├── Styled
    │   │   ├── BasicWrapper.jsx
    │   │   ├── HelloWrapper.jsx
    │   │   ├── NavWrapper.jsx
    │   │   └── OneMemoWrapper.jsx
    │   └── UI
    │       ├── Checkbox.jsx
    │       ├── DropdownCenter.jsx
    │       ├── DropdownLeft.jsx
    │       ├── DropdownRight.jsx
    │       ├── FriendOptionDropdownCenter.jsx
    │       ├── IsStarButton.jsx
    │       ├── MemoOptionButton.jsx
    │       ├── MemoOptionDropdownRight.jsx
    │       ├── NewMemoOptionDropdownRight.jsx
    │       ├── SearchMemo.jsx
    │       └── SortMemo.jsx
    ├── pages
    │   ├── BackOffice
    │   │   └── StatisticPage.jsx
    │   ├── Etc
    │   │   ├── DownloadPage.jsx
    │   │   ├── InformationPage.jsx
    │   │   └── NoticePage.jsx
    │   ├── Friend
    │   │   ├── FriendListPage.jsx
    │   │   └── SenderListPage.jsx
    │   ├── Memo
    │   │   ├── MemoListPage.jsx
    │   │   ├── NewMemoPage.jsx
    │   │   └── ReadAndEditMemoPage.jsx
    │   └── User
    │       ├── ChangePwPage.jsx
    │       ├── LoginPage.jsx
    │       ├── SignupPage.jsx
    │       └── UserProfilePage.jsx
    ├── hooks
    │   └── useDetectDropdown.jsx
    └── utils
        ├── lazyUtil.js
        ├── AlertUtil.js
        ├── MetaUtil.js
        ├── TimeUtil.js
        ├── ToastUtil.js
        └── TokenUtil.js
```
</details>

<details>
  <summary>&nbsp;<strong>Frontend_App</strong>&nbsp;:&nbsp;&nbsp;Open!</summary>
  <br>

```
├── App.js
├── app.json
├── assets
│   ├── adaptive-icon.png
│   ├── favicon.png
│   ├── icon.png
│   └── splash.png
├── babel.config.js
├── eas.json
├── package-lock.json
└── package.json
```
</details>
<br>



## 👨‍👩‍👧‍👧 Team (Full Stack)

|                                              [사현진](https://github.com/tkguswls1106)                                              |
| :------------------------------------------------------------------------------------------------------------------------------: |
| <img width = "300" src ="https://github.com/user-attachments/assets/cb71ee9c-c8e6-45ca-9fb8-4e9d96d0a5d5"> |
|                                                   Frontend & Backend Developer                                                    |
