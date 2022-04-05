# Bookcat (키워드로 도서 검색 및 서평 작성 사이트)

### 참여 인원 👩‍💻
  - 🤩 [황세원](https://github.com/pabaep) : **BE** ( 회원관련 기능 담당 )
  - 🥰 [엄예솔](https://github.com/sol09) : **BE** ( 서평관련 기능 담당 )
  - 😎 [양한별](https://github.com/han-byul-yang) : **FE** ( 프론트 전체 담당 )

### 진행 기간 ⏳
`2021. 11. 28. ~ 2022. 04. 04`

### 소개 ✨
```
키워드로 책을 검색하고 그중 선택한 책에 대해서 서평을 작성할 수 있는 사이트
이후 작성한 서평을 목록 형태로 관리할 수 있다
```
### 기술 스택 🛠
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/> : 프론트 구성 <br> 

<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"/> : 백엔드 구성 <br>

<img src="https://img.shields.io/badge/Google Cloud Platform-4285F4?style=flat-square&logo=Google Cloud&logoColor=white"/> : 서버 배포 <br>

<img src="https://img.shields.io/badge/Kakao Open API-FFCD00?style=flat-square&logo=Kakao&logoColor=white"/> : 책 검색 API<br><br>

※ _현재는 서버 비용 문제로 배포하고 있지 않음_ ※

### 기능 소개 📑
  ✔ 회원가입 / **로그인** / 회원정보 관리   
  ✔ 키워드로 책 **검색**    
  ✔ 검색한 책 선택하여 **서평 작성**   
  ✔ 서평 **수정** 및 **삭제**, 별점 관리   
  ✔ 작성한 **서평 목록** 확인, 서평 **상세 내용** 조회   

### 화면 구성 🖥
< **메인 화면** > - 서버 배포 여부 확인 가능
![image](https://user-images.githubusercontent.com/55613591/161542786-3c70419b-2592-4bc3-a39b-80a5955ccf73.png)

< **로그인 화면** >
![image](https://user-images.githubusercontent.com/55613591/161543645-bd1f97d5-c5f3-4b31-8976-b7d1ea2d95c0.png)

< **회원 정보 화면** >
![image](https://user-images.githubusercontent.com/55613591/161543690-675b7fc6-7cd6-400a-8faa-249d656be055.png)

< **검색 결과 화면** > 
![image](https://user-images.githubusercontent.com/55613591/161544056-b0fe6516-4ef3-4ea9-973a-0464fb410d14.png)

< **서평 작성 화면** > 
![image](https://user-images.githubusercontent.com/55613591/161544364-4bc0f6e7-df6a-4209-88e4-dd076a30f2df.png)

< **서평 공간 (목록) 화면** > 
![image](https://user-images.githubusercontent.com/55613591/161545059-ba6a0fb6-a2d4-4f7d-aa55-8d3ade317781.png)

< **서평 상세 화면** >
![image](https://user-images.githubusercontent.com/55613591/161545094-34195beb-5fef-44b6-a0ca-5a1a1f872ced.png)

### 명세서 List 📚
```
1. 기능 명세서
2. UI 명세서
3. DB 명세서
```

_**위의 명세서는 아래 링크에서 확인 가능!**_

<a href="https://github.com/onestar31/bookcat_reademe/wiki/%EB%AA%85%EC%84%B8%EC%84%9C"><img src="https://img.shields.io/badge/명세서 List home page-e8a5a5?style=for-the-badge&logoWidth=50"/></a>

### 트러블 슈팅 🎯
* **JSON 인코딩 에러** : https://paabaep.tistory.com/30?category=1250763
* **프론트 백 연결** (Django REST framework 이용) : https://edorrr.tistory.com/19
* **CORS 오류 해결** : https://velog.io/@han-byul-yang/SOP-CORS%EB%9E%80

### 개선 사항 ❗
1. 다른 사람의 서평을 보고 이를 공유할 수 있는 기능 추가
2. 개인 정보 이용 정책 페이지 만들기
3. 구매로 이어질 수 있는 기능을 추가
4. 서평 쓰고 싶은 찜 목록 기능 추가

