<p align="center">
  <img width="240" alt="온라인메모장 앱아이콘" src="https://github.com/OnlineMemo/.github/assets/56509933/e8b687ce-8a21-46f9-aa6b-b62a930a2c58">
</p>
<br>

<p align="center">
  <strong>
    - 온라인 메모장 -
    <br>
    공동 작성이 가능한 간편한 온라인 메모장입니다.
  </strong>
</p>
<br>

## 🖱️ Access
- Website link: <a href="https://www.onlinememo.kr">www.OnlineMemo.kr</a>
- Android app: <a href="https://play.google.com/store/apps/details?id=com.shj.onlinememo">Play Store Download</a>
<br>

## 📹 Demo
### PC 버전
  <img width="1470" alt="PC 버전 스크린샷" src="https://github.com/OnlineMemo/.github/assets/56509933/6c713000-e868-4420-af65-69daa292d91e">

### 테블릿 버전
  <img width="1470" alt="테블릿 버전 스크린샷" src="https://github.com/OnlineMemo/.github/assets/56509933/f550c4c9-18fb-4a45-a521-638ed12c9182">
  
### 모바일 버전
<div align="center">
  <img width="240" alt="플레이스토어 스크린샷 1" src="https://github.com/OnlineMemo/.github/assets/56509933/7d6859e4-5521-40e2-a904-9d400a11f2ae">
  <img width="240" alt="플레이스토어 스크린샷 2" src="https://github.com/OnlineMemo/.github/assets/56509933/e1792b69-225f-426e-a954-d9412ca02d96">
  <img width="240" alt="플레이스토어 스크린샷 3" src="https://github.com/OnlineMemo/.github/assets/56509933/7777a7da-3d0a-428b-8cb7-1fdaf88ebb22">
  <img width="240" alt="플레이스토어 스크린샷 4" src="https://github.com/OnlineMemo/.github/assets/56509933/f031bf2e-61ac-4343-9c83-8065c0960b84">
</div>
<br>

## 💡Tech Stack
|Frontend|Backend|Security|Other|
|:------:|:------:|:------:|:------:|
|<img src="https://img.shields.io/badge/React.js-61DBFB?style=flat-square&logo=React&logoColor=white"/></a><br><img src="https://img.shields.io/badge/React Native-008FC7?style=flat-square&logo=React Native&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=Spring Boot&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/></a><br><img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Spring Security-00A98F?style=flat-square&logo=Spring Security&logoColor=white"/></a><br><img src="https://img.shields.io/badge/JSON Web Token-9933CC?style=flat-square&logo=JSON Web Tokens&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Github-111011?style=flat-square&logo=Github&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/></a><br><img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat-square&logo=IntelliJ IDEA&logoColor=white"/></a>

```
- Frontend : React.js, React Native
- Backend : Spring Boot, Java
- Database: MySQL
- Frontend Deployment: AWS Amplify
- Backend Deployment: AWS Elastic Beanstalk
- API Test : Postman
- API Documentation : Swagger
- Version control: Github
- Development Environment : Visual studio code, IntelliJ IDEA
```
<br>

## 💻 Architecture
![onlinememo_architecture drawio](https://github.com/OnlineMemo/.github/assets/56509933/a0ce0ff4-a47d-4e60-84ce-02f0d5845add)
<br>

## 📗 API
![image](https://user-images.githubusercontent.com/70987007/183114204-c5d0f50f-79e8-420a-aa42-4d0c34d14b36.png)
<br>

## 📂 Frontend_Web Directory Structure
```bash
├── README.md
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

## 📂 Frontend_App Directory Structure
```bash
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

## 📂 Backend Directory Structure
```bash
└── src
    ├── main
    │   ├── generated
    │   ├── java
    │   │   └── com
    │   │       └── shj
    │   │           └── onlinememospringproject
    │   │               ├── OnlinememoSpringProjectApplication.java
    │   │               ├── config
    │   │               │   ├── JwtSecurityConfig.java
    │   │               │   └── WebSecurityConfig.java
    │   │               ├── controller
    │   │               │   ├── AuthController.java
    │   │               │   ├── FriendshipController.java
    │   │               │   ├── MemoController.java
    │   │               │   ├── TestController.java
    │   │               │   └── UserController.java
    │   │               ├── domain
    │   │               │   ├── DefaultFriendshipEntity.java
    │   │               │   ├── DefaultMemoEntity.java
    │   │               │   ├── friendship
    │   │               │   │   ├── Friendship.java
    │   │               │   │   └── FriendshipJpaRepository.java
    │   │               │   ├── memo
    │   │               │   │   ├── Memo.java
    │   │               │   │   └── MemoJpaRepository.java
    │   │               │   ├── user
    │   │               │   │   ├── Authority.java
    │   │               │   │   ├── User.java
    │   │               │   │   └── UserJpaRepository.java
    │   │               │   └── userandmemo
    │   │               │       ├── UserAndMemo.java
    │   │               │       └── UserAndMemoJpaRepository.java
    │   │               ├── dto
    │   │               │   ├── friendship
    │   │               │   │   ├── FriendshipRequestDto.java
    │   │               │   │   ├── FriendshipResponseDto.java
    │   │               │   │   ├── FriendshipSendRequestDto.java
    │   │               │   │   ├── FriendshipSendResponseDto.java
    │   │               │   │   └── FriendshipUpdateRequestDto.java
    │   │               │   ├── memo
    │   │               │   │   ├── MemoInviteResponseDto.java
    │   │               │   │   ├── MemoResponseDto.java
    │   │               │   │   ├── MemoSaveRequestDto.java
    │   │               │   │   ├── MemoSaveResponseDto.java
    │   │               │   │   ├── MemoUpdateRequestDto.java
    │   │               │   │   └── MemoUpdateStarRequestDto.java
    │   │               │   ├── token
    │   │               │   │   └── TokenDto.java
    │   │               │   ├── user
    │   │               │   │   ├── UserIdResponseDto.java
    │   │               │   │   ├── UserLoginRequestDto.java
    │   │               │   │   ├── UserRequestDto.java
    │   │               │   │   ├── UserRequestDtos.java
    │   │               │   │   ├── UserResponseDto.java
    │   │               │   │   ├── UserSignupRequestDto.java
    │   │               │   │   ├── UserUpdateNameRequestDto.java
    │   │               │   │   └── UserUpdatePwRequestDto.java
    │   │               │   └── userandmemo
    │   │               │       ├── UserAndMemoRequestDto.java
    │   │               │       └── UserAndMemoResponseDto.java
    │   │               ├── jwt
    │   │               │   ├── JwtAccessDeniedHandler.java
    │   │               │   ├── JwtAuthenticationEntryPoint.java
    │   │               │   ├── JwtFilter.java
    │   │               │   └── TokenProvider.java
    │   │               ├── response
    │   │               │   ├── GlobalExceptionHandler.java
    │   │               │   ├── ResponseCode.java
    │   │               │   ├── ResponseData.java
    │   │               │   ├── exception
    │   │               │   │   ├── FriendshipBadRequestException.java
    │   │               │   │   ├── FriendshipDuplicateException.java
    │   │               │   │   ├── LoginIdDuplicateException.java
    │   │               │   │   ├── MemoSortBadRequestException.java
    │   │               │   │   ├── NoSuchFriendshipException.java
    │   │               │   │   ├── NoSuchMemoException.java
    │   │               │   │   ├── NoSuchUserException.java
    │   │               │   │   └── UserAndMemoDuplicateException.java
    │   │               │   └── responseitem
    │   │               │       ├── MessageItem.java
    │   │               │       └── StatusItem.java
    │   │               ├── service
    │   │               │   ├── FriendshipService.java
    │   │               │   ├── MemoService.java
    │   │               │   ├── UserAndMemoService.java
    │   │               │   ├── UserService.java
    │   │               │   ├── auth
    │   │               │   │   ├── AuthService.java
    │   │               │   │   └── CustomUserDetailsService.java
    │   │               │   └── logic
    │   │               │       ├── FriendshipServiceLogic.java
    │   │               │       ├── MemoServiceLogic.java
    │   │               │       ├── UserAndMemoServiceLogic.java
    │   │               │       └── UserServiceLogic.java
    │   │               └── util
    │   │                   └── SecurityUtil.java
    │   └── resources
    │       ├── application-jwt.properties
    │       ├── application-mysql.properties
    │       ├── application.properties
    │       ├── logback-spring.xml
    │       ├── static
    │       └── templates
    └── test
        └── java
            └── com
                └── shj
                    └── onlinememospringproject
                        ├── OnlinememoSpringProjectApplicationTests.java
                        └── service
                            ├── MemoServiceTest.java
                            ├── UserAndMemoServiceTest.java
                            └── UserServiceTest.java
```
<br>

## 👨‍👩‍👧‍👧 팀원

|                                              [사현진](https://github.com/tkguswls1106)                                              |
| :------------------------------------------------------------------------------------------------------------------------------: |
| <img width = "300" src ="https://github.com/OnlineMemo/.github/assets/56509933/a13439f7-934d-41e1-be52-190e40753707"> |
|                                                   Frontend & Backend Developer                                                    |
