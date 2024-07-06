# 미래내일 일경험 프로젝트

> 프로젝트 주제 : AI 기반 사용자 맞춤 책 추천 서비스
> 서비스 명 : 북와이즈  
> 팀명 : 코아일체  
> 개발기간 : 2024.05.13 ~ 2024.07.10 (8주)  
> 배포 주소 : 

# 북와이즈란?


# 팀원 소개

|     이름      |            역할             |                  Contact                  |
| :-----------: | :-------------------------: | :---------------------------------------: |
| 김서영 (팀장) |      ML- 추천서비스, 감정분류 모델 개발       |  [Github]()   |
|    박동휘     | BE |  [Github]()  |
|    이동범     |    FE, BE     |  [Github]()  |
|    이지원     |    BE     |  [Github]()  |
|    서혜인     |          FE           | [Github]() |

# 📁프로젝트 구조

## 📃문서
<!---
📃[컨벤션 및 Git 브랜치 전략](https://www.notion.so/3c2d5bfe31a548628bdb70238f0e2b68)  
📃[회의록](https://www.notion.so/SSAFY-MEETING-fb956dfd180e49a185007fc27b67d1c5)  
📃[추천 알고리즘](https://www.notion.so/ac2bbe43b3824bceac81f3b50a5e7eda)
--->

## 📁프로젝트 실행 방법



## 📁기술 스택

|     분류      |                                                                                                                                        기술                                                                                                                                         |
| :-----------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   Front-end   |                                                                                                      <img src="https://img.shields.io/badge/Vue.js-2.6.12-green?logo=vue.js">                                                                                                       |
|   Back-end    | <img src="https://img.shields.io/badge/Java-1.8-blue?logo=java"> <img src="https://img.shields.io/badge/Python-3.7-blue?logo=python"> <img src="https://img.shields.io/badge/Spring-2.4.3-green?logo=spring">, <img src="https://img.shields.io/badge/Flask-1.1.2-blue?logo=flask"> |
|      ML       |                                                                    <img src="https://img.shields.io/badge/Pytorch-1.8.1-red?logo=pytorch"> <img src="https://img.shields.io/badge/Python-3.7-blue?logo=python">                                                                     |
|      DB       |                                                                                                         <img src="https://img.shields.io/badge/MySQL-v8.0-blue?logo=mysql">                                                                                                         |
|     CI/CD     |                                                                      <img src="https://img.shields.io/badge/Docker-blue?logo=docker"> <img src="https://img.shields.io/badge/Jenkins-lightgrey?logo=jenkins">                                                                       |
| Communication |                                                                  <img src="https://img.shields.io/badge/Mattermost-blue?logo=mattermost"> <img src="https://img.shields.io/badge/Discord-lightgrey?logo=discord">                                                                   |

## 📁시스템 아키텍쳐
<!---
![시스템구조](Document/system_architecture/system_arch.png)  
![배포과정](Document/system_architecture/배포프로세스.png)
--->

## 📁ERD
<!---
![ERD](Document/DB/ERD_message_v2.1.png)
--->
## 📁패키지 구조

### 백엔드

`spring boot`

```bash

```

`flask`

```bash
flask
├─ app.py
├─ apis        : API endpoints
│    ├─ __init__.py
│    ├─ recommendation.py
│    ├─ sentiment.py
├─ data        : 필요 데이터들
│    ├─ books.pkl
│    ├─ embedding_matrix_category.npz
│    ├─ embedding_matrix_description.npz
│    ├─ reviews.pkl
│    ├─ sentimentBert.pth
│    └─ stopwords.txt
└─ requirements.txt
```

### 프론트 엔드

```bash


```

# 📚주요 기능
<!---
## 메인 페이지(읽은 책, 선호 장르, 위시리스트 기반 추천)

### 👩유저 A (문학, 예술, 여행 관련 도서 선호)

![추천_A](Document/images/recommend_user_a.gif)

### 🧑유저 B (프로그래밍 관련 도서 선호)

![추천_B](Document/images/recommend_user_b.gif)

## 책 상세 페이지

### 키워드 분석

![상세1](Document/images/book_detail_1.gif)

### 감정 분석 + 토픽 분석

![상세2](Document/images/book_detail.gif)

### 책 비교

![상세3](Document/images/book_detail_3.gif)

## 문장 수집

![문장수집](Document/images/book_read.gif)

## 책 검색

![검색](Document/images/book_search.gif)

## 유저 페이지

### 선호 장르 분석

![선호장르](Document/images/user_genre.gif)

--->
