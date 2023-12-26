# 🧸아이들 체험학습 중개 프로젝트 - '아기자기'

### 📆개발 기간

🕓 23.04.15 ~ 23.05.25


### 💡서비스 제작배경 및 필요성
<div dir="auto" style="display: flex;">
<img width="1180" alt="스크린샷 2022-12-27 오전 12 09 34" src="https://github.com/dev-typelym/baby-baby/assets/122762472/8bbd166c-3344-4f5e-abb4-228e40d1224e" style = "width: 45%; height : 45%">
</div>


<div dir="auto" style="display: flex;">
<img width="1180" alt="스크린샷 2022-12-27 오전 12 09 34" src="https://github.com/dev-typelym/baby-baby/assets/122762472/e9d13ed5-20ca-4133-a73f-6ed1945bd4c8" style = "width: 45%; height : 45%">
</div>


<div dir="auto" style="display: flex;">
<img width="1180" alt="스크린샷 2022-12-27 오전 12 09 34" src="https://github.com/dev-typelym/baby-baby/assets/122762472/ac30b23d-46a8-4f76-8185-ccf3b5734384" style = "width: 45%; height : 45%">
</div>




### 🛠️프로젝트 사용 툴
<img width="1160" alt="스크린샷 2022-12-27 오전 12 23 33" src="https://github.com/dev-typelym/baby-baby/assets/122762472/d82ba185-03e3-44df-9ac5-41a9ec34ba7c" style = "width: 45%; height : 45%">

----------------------------------------------------------------------------------------------------------------------

### 🏆프로젝트 전체적인 타임라인<br>
|일자|내용|구체적인 활동|
|:---------:|:--------:|:-------:|
|4월 13일 ~ 4월 15일 | 주제 선정|주제 선정 및 메뉴트리 작성, ERD 설계 |
|4월 15일 ~ 4월 15일 | 역할 분담 | 퍼블리싱 역할 분담 |
|4월 15일 ~ 4월 28일 퍼블리싱 작업 및 DB| 퍼블리싱 작업 시작, DB 작업 |
|4월 29일 ~ 4월 30일 |설계| 백엔드 사전 설계 작업 |
|5월 01일 ~ 5월 25일|Back 작업|백엔드 역할 분담 및 백 작업|

----------------------------------------------------------------------------------------------------------------------

### 🏆나의 프로젝트 타임라인<br>
|일자|담당 파트|작업 내용|
|:---------:|:---------:|:-----------:|
|4월 13일 ~ 4월 28일|Front-end| 메인페이지, 부모님마당, 리뷰게시판 퍼블리싱 작업 완료 |
|3월 25일 ~ 3월 28일|Back-end| 회원가입 (정규식) 완료 |
|3월 26일 ~ 4월 2일|Back-end| 회원가입 (중복검사, DB저장) 완료 |
|3월 29일 ~ 4월 2일|Back-end| 로그인 (아이디 저장, 로그인 구현) 완료 |
|4월 2일 ~ 4월 3일|Back-end| 로그인 (간편로그인 - 카카오, 간편로그인 - 네이버) 완료 |
|3월 26일 ~ 4월 4일|Back-end| 메인페이지 (지역별 최근 게시물, 별점 인기순) |
|4월 3일 ~ 4월 4일|Back-end| 메인페이지 (랜덤 추천 게시물) |
|4월 5일 ~ 4월 6일|Back-end | 마무리 작업 |

----------------------------------------------------------------------------------------------------------------------

### 🏷️담당 업무
Front-end<br>
  - 마이페이지

Back-end<br>
1. 로그인
  - 로그인 기능 구현
  - 쿠키를 사용한 아이디 저장 
  - OAuth를 활용한 카카오 간편 로그인
  - OAuth를 활용한 네이버 간편 로그인
  
2. 회원가입
  - 회원가입 기능 구현
  - 필수사항 및 형식 입력 검사
  - 중복 검사

3. 아이디/비밀번호 찾기 
  - 계정 검사
  - 형식 입력 검사
  - 구글 mail API를 활용한 메일 전송
  - 비밀번호 변경


4. 메인페이지
  - 지역별 최신 게시물
  - 별점 인기순
  - 랜덤 추천 게시물

----------------------------------------------------------------------------------------------------------------------

### DB - ERD

![neighbor-erd](https://github.com/dev-typelym/baby-baby/assets/122762472/5e384f34-a28b-4571-b48f-8df36f00cf45)

----------------------------------------------------------------------------------------------------------------------
  
### 🌟느낀점
<h3>1. 어려웠던 부분</h3><br>
메인페이지의 지역별 최신 게시물을 구현할 때 서울시 지역 버튼을 클릭시 그 지역에만 있는 최신 게시물을 띄어줘야 하는 부분이 있었습니다.
이때 최신 게시물을 ajax를 통해 페이지 이동없이 띄어줘야 했었는데 

<h3>2. 문제를 해결했던 부분</h3>
메인페이지의 지역별 최신 게시물을 구현할 때 서울시 지역 버튼을 클릭시 그 지역에만 있는 최신 게시물을 띄어줘야 하는 부분이 있었습니다.
이때 최신 게시물을 javascript에서 ajax를 통해 페이지 이동없이 띄어줘야 했었는데 이때 기능 중 하나인 게시물에 마우스 오버시 게시물의 
간단한 정보와 작성자의 프로필이 나오는 after요소로 나오는 부분이 
<h3>3. 총평</h3>


