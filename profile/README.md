<p align="center">
  <img width="240" alt="온라인메모장 앱아이콘" src="https://github.com/OnlineMemo/.github/assets/56509933/e8b687ce-8a21-46f9-aa6b-b62a930a2c58">
</p>
<br>

<p align="center">
  <strong> - 온라인 메모장 - <br> 공동 작성이 가능한 간편한 온라인 메모장입니다.<br> </strong>
</p>
<br>

## 📹 Demo
### PC 버전
  <img width="1470" alt="PC 버전 스크린샷" src="https://github.com/OnlineMemo/.github/assets/56509933/6c713000-e868-4420-af65-69daa292d91e">

### 테블릿 버전
  <img width="1470" alt="테블릿 버전 스크린샷" src="https://github.com/OnlineMemo/.github/assets/56509933/f550c4c9-18fb-4a45-a521-638ed12c9182">
  
### 모바일 버전
<div align="center">
  <img width="245" alt="플레이스토어 스크린샷 1" src="https://github.com/OnlineMemo/.github/assets/56509933/7d6859e4-5521-40e2-a904-9d400a11f2ae">
  <img width="245" alt="플레이스토어 스크린샷 2" src="https://github.com/OnlineMemo/.github/assets/56509933/e1792b69-225f-426e-a954-d9412ca02d96">
  <img width="245" alt="플레이스토어 스크린샷 3" src="https://github.com/OnlineMemo/.github/assets/56509933/7777a7da-3d0a-428b-8cb7-1fdaf88ebb22">
  <img width="245" alt="플레이스토어 스크린샷 4" src="https://github.com/OnlineMemo/.github/assets/56509933/f031bf2e-61ac-4343-9c83-8065c0960b84">
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

## 🚀 How to Start
### 1. Clone Repository

```
https://github.com/2022-Summer-Bootcamp-teamG/puppy-classification.git
```

### 2. Install Pacakages

```
$ cd pupppy-classification-frontend
$ yarn run build
```

### 3. Set .env file

```bash
### settings/.env
# === Database ===
RDS_HOST =
RDS_DATABASE =
RDS_USER =
RDS_PASSWORD =

# === S3Bucket ===
S3_ID =
S3_SECRET_KEY =
S3_BUCKET_REGION =
S3_BUCKET_NAME =

```

### 4. Run Docker

```
$ docker-compose up --build         # build images and run containers
$ docker-compose down               # stop running containers
$ docker-compose down -v            # stop running containers and delete its volume
```

## 📂 Frontend_Web Directory Structure

```bash
├── README.md
├── docker-compose.prod.yml
├── docker-compose.yml
├── nginx
│   ├── Dockerfile
│   └── nginx.conf
├── puppy-classification-backend
│   ├── Dockerfile
│   ├── README.md
│   ├── app.py
│   ├── config
│   │   ├── __init__.py
│   │   ├── connection.py
│   │   ├── rdsConfig.py
│   │   └── s3Config.py
│   ├── imagenet_class_index.json
│   ├── predict.py
│   ├── requirements.txt
│   ├── tasks.py
│   ├── views.py
│   ├── weights.pt
│   └── wsgi.py
├── puppy-classification-frontend
│   ├── Dockerfile
│   ├── Dockerfile.prod
│   ├── README.md
│   ├── build
│   ├── package-lock.json
│   ├── package.json
│   ├── public
│   ├── src
│   │   ├── App.css
│   │   ├── App.tsx
│   │   ├── assets
│   │   │   ├── fonts
│   │   │   └── images
│   │   ├── components
│   │   │   ├── common
│   │   │   │   ├── Button.ts
│   │   │   │   ├── Common.ts
│   │   │   │   ├── CustomAxios.ts
│   │   │   │   ├── Header.tsx
│   │   │   │   ├── Loading.tsx
│   │   │   │   ├── Logo.ts
│   │   │   │   ├── MediaQuery.ts
│   │   │   │   ├── NotFound.tsx
│   │   │   │   ├── SearchBar.tsx
│   │   │   │   ├── SearchBarStyle.ts
│   │   │   │   └── Title.ts
│   │   │   ├── detail
│   │   │   │   ├── ChartBox.tsx
│   │   │   │   ├── DetailImage.ts
│   │   │   │   ├── FeatureBox.tsx
│   │   │   │   └── ItemBox.ts
│   │   │   ├── list
│   │   │   │   ├── CardItem.tsx
│   │   │   │   ├── CardList.tsx
│   │   │   │   ├── Categories.tsx
│   │   │   │   ├── ItemImage.ts
│   │   │   │   ├── Pagination.tsx
│   │   │   │   └── pagination.module.scss
│   │   │   ├── main
│   │   │   │   ├── Dropzone.ts
│   │   │   │   ├── ImageUploader.tsx
│   │   │   │   ├── LabelButton.ts
│   │   │   │   ├── MainImage.ts
│   │   │   │   └── PuppyButton.tsx
│   │   │   ├── result
│   │   │   │   ├── Carousel.tsx
│   │   │   │   ├── CarouselBox.tsx
│   │   │   │   └── ResultImage.ts
│   │   │   └── search
│   │   │       └── SearchCardList.tsx
│   │   ├── custom.d.ts
│   │   ├── global.d.ts
│   │   ├── index.css
│   │   ├── index.tsx
│   │   ├── logo.svg
│   │   ├── pages
│   │   │   ├── DetailPage.tsx
│   │   │   ├── ListPage.tsx
│   │   │   ├── MainPage.tsx
│   │   │   ├── ResultPage.tsx
│   │   │   └── SearchPage.tsx
│   │   ├── setupTests.ts
│   ├── tsconfig.json
│   ├── yarn-error.log
│   └── yarn.lock
├── settings
    └── .env
```

## 📂 Frontend_App Directory Structure

```bash

```

## 📂 Backend Directory Structure

```bash

```

## 👨‍👩‍👧‍👧 팀원

|                                              [최지미](https://github.com/rabbit-22)                                              |                                                [김혜린](https://github.com/Kim-Hye-Lin)                                                |                                               [박희경](https://github.com/qkrgmlrud00)                                                |                                                                      [장현우](https://github.com/aswooo)                                                                      | [하도균](https://github.com/DoKyunHa) |
| :------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------: |
| <img width = "520" src ="https://user-images.githubusercontent.com/70987007/183122411-d68ed57b-8daa-4af6-8230-294cabc3b095.png"> | <img width="520" alt="ff" src="https://user-images.githubusercontent.com/70987007/183121730-dc503644-3458-4bb5-9524-78b07d7137d2.png"> | <img width="520" alt="1" src="https://user-images.githubusercontent.com/70987007/183119590-b366716b-ed52-4fcb-a774-f942718eaa15.png"> | <img width="520" alt="스크린샷 2022-08-06 오전 1 24 51" src="https://user-images.githubusercontent.com/70987007/183120176-4ea0488f-fc28-46a7-9e28-a1ded6bc1d3d.png"> |                 <img width="420" src="https://user-images.githubusercontent.com/70987007/183126855-faff052d-574c-499b-917b-a04109019c77.png">                  |
|                                                   Leader, Front-end Developer                                                    |                                                      Front-end Developer, DevOps                                                       |                                                          Back-end Developer                                                           |                                                                             AI, Backend-Developer                                                                             |          Front-end Developer          |
