# 🎈 프로젝트 기획
기간 : 2022/09/02 - 2022/09/25 (3주간)

## 1) 프로젝트 소개🎖️ 
<br>
전국 구석구석에 있는 다양한 여행 장소에 대해 소개하고, <br>
인기 여행지를 추천하여 주는 서비스입니다.<br>
<br>
여행 지도를 통해 전국에 있는 여행지를 한눈에 검색해 볼 수 있고,<br>
게시판을 통해 유저들끼리 커뮤니케이션을 하며 정보를 공유합니다.<br>

## 2) 핵심 기능 소개🎈
#### ⭐<b>사용자 페이지</b>⭐
**🔖 멤버 기능**
- 회원가입 및 로그인
- 마이페이지 회원 정보 조회/수정/탈퇴 
- 찜한 여행지 조회 
<br>

**🔖 메인 페이지 기능**
- 인기 여행지 추천 BEST 10 조회   
- 관심있는 여행지 찜(하트)하기
<br>

**🔖 여행 페이지 기능**
- 전국 인기 여행지 조회/조회수  
- 여행지 상세 정보 조회 
- 관심있는 여행지 찜(하트)하기
- 여행톡 댓글 작성/수정/삭제/목록 조회
<br>

**🔖 게시판 페이지 기능**
- 리뷰 이미지 게시판 목록 조회/작성/수정/삭제/조회수
- 리뷰글 상세보기 및 여행톡 작성/수정/삭제/목록 조회

- 자유게시판 목록 조회/작성/수정/삭제/조회수
- 자유게시판 상세보기 및 여행톡 작성/수정/삭제/목록 조회
- 공지사항 조회 
- 인기글, 최신글 정렬 기능
<br>

**🔖 여행 지도 기능**
- 지도API로 여행지 검색, 지역별 여행지 추천

## 3) 프로토타입🎈
[LOOKPLACE](https://ovenapp.io/view/aDPoiCGk5gW6Qf5lavPODGeLxzcuvYFr/ )
<br><br><br>
<hr>


# 🎈 설계 및 구현
## 1) 개발환경
<br>

* [x] JAVA 11
* [x] Spring Framework 5.2.8
* [x] HikariCP 커넥션 풀, Lombok 1.18.24, MyBatis 3.5.3
* [x] MySQL 8.0.30
* [x] Apache Tomcat 9.0
* [x] HTML, CSS, JavaScript, Jquery, BootStrap
* [x] IDE : Eclipse 
<br>

## 2) ERD / 테이블 정의서
<br>
![erd](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/f252346c-1efb-49dc-aa66-053db4a24e59)

<br>

## 3) UseCaseDiagram
![usecase](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/2869cb17-eae9-4bee-9f03-e880b3dc97c4)


<br>

## 4) 결과물 소개
<br>
🪄 메인 화면

![rs1](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/7b36b13d-a4f6-4208-9105-7ae13fccf77f)
🪄 여행지도 화면
![rs2](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/8d0b3c10-4002-4025-acaf-131f245476d9)
🪄 멤버 서비스 화면
![rs3](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/eb739d79-bc1d-44d3-9dec-f2bad557a517)

![rs4](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/545dfb2b-82ee-401e-8399-1a6c1d6239b0)

![rs5](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/7d3a94f7-e387-441f-8c26-9675fe0c4172)

![rs6](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/1cd844be-05d7-4cfd-84a9-5dbd47422c18)

![rs7](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/e2c0a2a4-81a1-4692-875f-b24b6fe096cc)

🪄 인기 지역 화면
![rs8](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/e39ce2c4-e8a3-4bcd-9d3c-cc4b974362ed)

![rs9](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/64f8f090-e60d-4a1b-a0fc-02f86ea26909)

🪄 지역 상세 화면
![rs10](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/f09dc9be-801c-400c-9de5-817468e29cf5)

🪄 게시판 화면
![rs11](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/1556d725-357c-4fbc-9e99-450805f68290)

![rs12](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/87ced1d8-2a93-4c62-a1a3-7de52f81bb91)

![rs13](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/3093ecdb-c877-42db-b681-ece1902c695c)


🪄 게시판 상세글 화면
![rs14](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/0d6e701d-4eaa-4cb4-9c46-d45b3f2cad4e)

![rs15](https://github.com/ChoiEuiCheon/lookplace/assets/103105033/49c1c607-0a9b-45c5-b5af-fcd8a5b5ab94)

<br>

## 5) 배포
### 헤로쿠를 이용하여 배포
[Lookplace 배포 사이트 클릭!](https://lookplacesite.herokuapp.com/
).
but 문제상황 발생
문제 1) 헤로쿠는 DB에 저장된 이미지 파일 경로를 불러오지 못함.
문제 2) 이미지 파일 업로드시 DB 저장 불가
->> 문제 해결방안을 서치 중.
