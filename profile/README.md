<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/dd0f3082-61fb-44ed-8518-e6cef8754361" width="210" />
  <h3 align="center">온라인 메모장 📝</h3>
  <p align="center">
    공동 작성이 가능한 메모장 서비스<br>
    <a href="https://github.com/orgs/OnlineMemo/repositories?q=sort%3Aname-asc"><strong>FullStack Repo »</strong></a><br>
    <a href="https://github.com/OnlineMemo/backend/tree/refactor/onlinememo-v2"><strong>Refactor Ver.2 »</strong></a>
  </p>
</div>
<br>

<details open>
  <summary><strong>&nbsp;📖&nbsp;목차</strong></summary>

1. &nbsp;&nbsp;[🔍 Introduction](#-introduction)
2. &nbsp;&nbsp;[📹 Demo](#-demo)
3. &nbsp;&nbsp;[👨‍👩‍👦‍👦 Launch](#-launch)
4. &nbsp;&nbsp;[💻 Architecture](#-architecture)
5. &nbsp;&nbsp;[💡 Tech Stack](#-tech-stack)
6. &nbsp;&nbsp;[🗂️ Database](#%EF%B8%8F-database)
7. &nbsp;&nbsp;[📗 API](#-api)
8. &nbsp;&nbsp;[🛠️ Log](#%EF%B8%8F-log-aws-cloudwatch)
9. &nbsp;&nbsp;[📂 Directory Structure](#-directory-structure)
10. &nbsp;&nbsp;[👨‍👩‍👧‍👧 Team](#-team-full-stack)
</details>
<br>



## 🔍 Introduction

### 주제 선정
기존의 메모장들에는 잡다한 많은 기능들이 탑재되어있어 사용에 어려움을 느꼈습니다. <br>
이에 본연의 기능을 살리고 남녀노소 누구나 쉽게 이용 가능한 메모장을 만들어보자는 생각에 아이디어를 얻었습니다.

### 특징
- 불필요한 기능을 제거하고, 간편하고 직관적인 디자인으로 주요 기능의 접근성을 높였습니다. <br>
또한 눈이 편안한 색감을 선정하여 귀엽고 심플하게 디자인하였습니다.
- 개인정보 필요없이 생성할 id와 pw만 입력하여, 쉽고 빠르게 회원가입이 가능합니다. <br>
이로써 회원가입의 거부감을 줄이고, 어느 기기에서든지 접속하여 계정별로 메모를 관리할 수 있습니다.
- 여러 사람이 공동으로 메모를 작성 및 관리할 수 있는 '공동 메모' 기능을 추가하였습니다. <br>
대학생 팀플이나 회의 내용 작성으로도 적합합니다.
- 광고 삽입은 접근성을 떨어뜨리기에, 수익창출 없이 무료로 이용 가능하도록 하였습니다.

### 운영
- Operation:&nbsp;&nbsp;2023/09/03 ~ ing
- Website link: <a href="https://www.onlinememo.kr">www.OnlineMemo.kr</a>
- Android app: <a href="https://play.google.com/store/apps/details?id=com.shj.onlinememo">Play Store Download</a>
<div align="center">
  <img width="1470" alt="플레이스토어 스크린샷" src="https://github.com/OnlineMemo/.github/assets/56509933/ab015384-804a-4bf8-9ac6-4e238623cf13">
  <img width="1470" alt="플레이스토어 PC 스크린샷" src="https://github.com/OnlineMemo/.github/assets/56509933/b8d9ebd0-8afe-48a5-ab2a-7d8ea99f7065">
</div>
<br>



## 📹 Demo

### PC Page

**Memo list**|**View memo**|**Invite friends**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/d662b9b9-4c55-4fbb-8199-b5e6dd222f0e" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/35c09de5-7f59-4e06-ab74-d9bcd6f0647e" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/2096b659-80ca-4f77-b6b7-7f4c760357e0" width="100%">
메모들 목록을 나열합니다.|메모 내용을 조회합니다.|메모에 친구들을 초대하거나, 함께 새로운 메모를 작성합니다.

### Mobile Page

**Login**|**SignUp**|**Change pw**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/1f5c053b-13e5-4da2-9a4f-3db57e983611" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/af5c6b6f-1f31-49ff-a57d-1b6f5a304032" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/b2f2b934-dec5-41f2-ba99-b070f12bf512" width="100%">
로그인 합니다.|회원가입 합니다.|계정의 비밀번호를 변경합니다.

**Memo list**|**New memo**|**View memo**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/6e5a4727-56b1-473f-8451-fed8864ae91a" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/9101fd58-c90a-48dd-af24-a3693aec1b7d" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/7eb239e1-b338-4141-a6e6-745140167b70" width="100%">
메모들 목록을 나열합니다.|새로운 개인 메모를 작성합니다.|메모 내용을 조회합니다.

**Friend list**|**Received list**|**Invite friends**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/981d4884-5faf-488d-9822-339fd866ce5d" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/ae8c9f27-2b47-4a9e-99e3-d1a5c8a0eb92" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/707a9527-ec8a-4863-8d12-608693bc3e8e" width="100%">
친구들 목록을 나열합니다.|친구요청 수신 목록을 조회합니다.|메모에 친구들을 초대하거나, 함께 새로운 메모를 작성합니다.

**User profile**|**Notice**|**App guide**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/d28b8bb5-55fe-4fcf-8225-5ad557a945e3" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/5fc7b037-2e48-4e0c-b0ce-29d89787cd50" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/419c769b-71bc-46c1-af13-f4ea16d2f93a" width="100%">
회원정보를 조회합니다.|공지사항 페이지 입니다.|모바일앱 다운로드 안내 페이지 입니다.

<br>



## 👨‍👩‍👦‍👦 Launch

### 동시접속 트래픽

**테스터**|**트래픽**
-----|-----
<img src="https://github.com/tkguswls1106/tkguswls1106/assets/56509933/145aaa0c-ad71-4e16-bc80-f36a2e50b3d0" height="40%">|<img src="https://github.com/tkguswls1106/tkguswls1106/assets/56509933/deb45a45-6828-4107-be56-d011fe89d558" width="100%">
웹과 앱 분야에 모두 테스터를 모집하여, 특정 시간대 10분 동안의 동시접속 트래픽 변화를 측정하였습니다.|테스터 30명의 동시접속 결과, CPU 사용률이 0.7%->6%까지 올랐음을 확인했습니다. 이로써 최대 500명의 동시접속 시 CPU 사용률이 100%에 도달할 것임을 알 수 있었고, 인스턴스를 확장함으로써 예방 조치를 취할 수 있었습니다.

### 마케팅

**에브리타임**|**인스타그램**
-----|-----
<img src="https://github.com/tkguswls1106/tkguswls1106/assets/56509933/11fabfbd-227a-430b-a048-3c95b6f06e53" width="100%">|<img src="https://github.com/tkguswls1106/tkguswls1106/assets/56509933/420dea2c-82bf-491f-b753-847b957747eb" width="100%">
대학생 커뮤니티에 홍보글을 게시하여, HOT 게시물로 선정되었습니다.|SNS에 홍보글을 게시하여, 다양한 연령대의 접근성을 고려했습니다. 그 결과, 100명 이상의 이용자에게 서비스를 제공 중입니다.

<br>



## 💻 Architecture
![onlinememo_architecture drawio](https://github.com/OnlineMemo/.github/assets/56509933/a0ce0ff4-a47d-4e60-84ce-02f0d5845add)

```
< Operational Architecture >
- Frontend Deployment : AWS Amplify
- Backend Deployment : AWS Elastic Beanstalk
- Database : AWS RDS
- DNS : AWS Route53
- Traffic : AWS Application Load Balancer, EC2 Auto Scaling (CPUUtil 30% ~ 70%)
- Monitoring : AWS CloudWatch, Spring Logback, ExceptionHandler
- Version control : AWS S3, Github
```
<br>



## 💡 Tech Stack
|Frontend|Backend|Security|Other|
|:------:|:------:|:------:|:------:|
|<img src="https://img.shields.io/badge/React-61DBFB?style=flat-square&logo=React&logoColor=white"/></a><br><img src="https://img.shields.io/badge/React Native-008FC7?style=flat-square&logo=React Native&logoColor=white"/></a><br><img src="https://img.shields.io/badge/JavaScript-F7DF1F?style=flat-square&logo=JavaScript&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=Spring Boot&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/></a><br><img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Spring Security-00A98F?style=flat-square&logo=Spring Security&logoColor=white"/></a><br><img src="https://img.shields.io/badge/JSON Web Token-9933CC?style=flat-square&logo=JSON Web Tokens&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=flat-square&logo=Amazon Web Services&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Swagger-85EA2E?style=flat-square&logo=Swagger&logoColor=white"/></a>

```
- Frontend : React, React Native, JavaScript
- Backend : Spring Boot, Java, Spring Security, JSON Web Token
- Database : MySQL
- Deployment : Amazon AWS
- API Tool : Postman
- API Documentation : Swagger
```
<br>



## 🗂️ Database
<!-- <img width="1470" alt="mysql DB ERD" src="https://github.com/OnlineMemo/.github/assets/56509933/6bf90043-9bb4-435d-9ac3-5c8e8123a34c"> -->
<img width="1470" alt="mysql DB ERD" src="https://github.com/user-attachments/assets/48beb98f-f616-4950-b1c5-05d779a90e0d">
<br><br>



## 📗 API
<!-- <img width="1470" alt="swagger api" src="https://github.com/OnlineMemo/.github/assets/56509933/68f1cfd3-c763-47ba-b1f9-18dfcc51e64f"> -->
<img width="1470" alt="swagger api" src="https://github.com/user-attachments/assets/4b60a166-ff46-4a0e-a14e-20bb2722273b">
<br><br>



## 🛠️ Log (AWS CloudWatch)
<img width="1470" alt="AWS CloudWatch" src="https://github.com/OnlineMemo/.github/assets/56509933/266c6619-4995-479a-9cc1-b73cc4bb7544">
<br><br>



## 📂 Directory Structure

<details open>
  <summary>&nbsp;<strong>Backend</strong>&nbsp;:&nbsp;&nbsp;Open!</summary>
  <br>

```
:
├── config
│   ├── SecurityConfig.java
│   └── SwaggerConfig.java
├── controller
│   ├── AuthController.java
│   ├── FriendshipController.java
│   ├── MemoController.java
│   ├── TestController.java
│   └── UserController.java
├── domain
│   ├── Friendship.java
│   ├── Memo.java
│   ├── User.java
│   ├── common
│   │   └── BaseEntity.java
│   ├── enums
│   │   ├── Authority.java
│   │   └── FriendshipState.java
│   └── mapping
│       └── UserMemo.java
├── dto
│   ├── AuthDto.java
│   ├── FriendshipDto.java
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
│   ├── MemoBatchRepository.java
│   ├── MemoRepository.java
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
│   │   └── Exception500.java
│   └── responseitem
│       ├── MessageItem.java
│       └── StatusItem.java
├── service
│   ├── AuthService.java
│   ├── FriendshipService.java
│   ├── MemoService.java
│   ├── UserMemoService.java
│   ├── UserService.java
│   └── impl
│       ├── AuthServiceImpl.java
│       ├── FriendshipServiceImpl.java
│       ├── MemoServiceImpl.java
│       ├── UserMemoServiceImpl.java
│       └── UserServiceImpl.java
└── util
    ├── SecurityUtil.java
    └── TimeConverter.java
```
</details>

<details>
  <summary>&nbsp;<strong>Frontend_Web</strong>&nbsp;:&nbsp;&nbsp;Open!</summary>
  <br>

```
├── package-lock.json
├── package.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── manifest.json
│   ├── memoicon128.png
│   ├── memoicon192.png
│   ├── memoicon512.png
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── assets
    │   ├── fonts
    │   │   ├── BMJUA_ttf.ttf
    │   │   ├── Kalam-Bold.ttf
    │   │   ├── Kalam-Light.ttf
    │   │   └── Kalam-Regular.ttf
    │   └── images
    │       └── user.png
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
    ├── hooks
    │   └── useDetectDropdown.jsx
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── pages
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
    ├── reportWebVitals.js
    ├── setupTests.js
    └── utils
        ├── CheckToken.js
        └── lazyUtil.js

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
| <img width = "300" src ="https://github.com/OnlineMemo/.github/assets/56509933/a13439f7-934d-41e1-be52-190e40753707"> |
|                                                   Frontend & Backend Developer                                                    |
