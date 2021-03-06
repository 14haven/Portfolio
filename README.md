# Portfolio


## 🥚 팀 프로젝트
|<center>프로젝트 명</center>| <center>Repository</center> |<center>서비스</center>|
|:--------:|:--------: |:--------:|
|CookCook Recipe | <center>[Link](https://github.com/CookAndHerb/SemiProject.git)</center> | 레시피 공유|
|어른허브 | <center>[Link](https://github.com/CookAndHerb/herb.git)</center> | 영양제 쇼핑몰|


## 🐣 세미 프로젝트
> CookCook Recipe

#### 기간
* 2021.01.24 ~ 2021.02.18

#### 학습 목표
* 웹 서버를 구현해 HTTP를 이해하고, 서블릿 컨테이너의 동작 원리를 이해한다.
* JDBC 라이브러리, MVC 패턴 구현을 통해 동작 원리를 이해한다.
* 각 게시판(조원)별 CRUD 구현

#### 구현 기능
* 회원가입(이메일 인증), 카테고리별 게시글 목록, 게시글 상세보기, 답글 기능, 페이징, 메인페이지, 아이디 찾기, 비밀번호 찾기(이메일 인증), 개인 정보 수정, 회원 탈퇴, 로그아웃, 검색(분류별), 카테고리 기능, 게시글 상세 수정, 게시글 등록, 게시글 삭제

#### 담당 역할
*  DB 및 ERD 설계, Ajax를 이용한 회원 정보 수정, 회원 탈퇴, 레시피 공유 게시판 UI 설계 및 구현, 레시피 공유 게시판 CRUD, 레시피 공유 게시판 페이징 및 검색, 파일 업로드 처리, 카테고리별 기능 처리

#### 담당 기능 리뷰
1. 레시피 게시판 카테고리 기능

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|게시판 첫 화면 JSP | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/rBoard/RboardCategoryPage.jsp)</center> | 
|등록된 게시물이 없는 경우 JSP | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/61aee482246e437009dbf1e62bf826cd2ec098b0/0_semiProject/WebContent/rBoard/RboardAllListPage.jsp#L139)</center> | 


![레시피게시판 카테고리](https://user-images.githubusercontent.com/73207547/114968587-a2a42b00-9eb1-11eb-8d8b-cc61dd5eb62a.gif)

<br>

2. 레시피 게시판 페이징 기능

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|카테고리 페이지로 이동, 페이징 Servlet | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/rboard/controller/RboardAllSelectServlet.java)</center> | 
|게시물 있는 경우, 페이징 JSP | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/61aee482246e437009dbf1e62bf826cd2ec098b0/0_semiProject/WebContent/rBoard/RboardAllListPage.jsp#L199)</center> | 

![페이징](https://user-images.githubusercontent.com/73207547/114968677-cd8e7f00-9eb1-11eb-8b69-6a8ad0edf058.gif)

<br>

3. 레시피 공유 게시판 검색 기능

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|검색 Servlet | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/rboard/controller/RboardSearchServlet.java)</center> | 
|검색 결과 JSP | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/rBoard/RboardSearchListPage.jsp)</center> | 
|검색 상세페이지 JSP | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/rBoard/RboardSearchPost.jsp)</center> | 

![검색](https://user-images.githubusercontent.com/73207547/114968679-d0896f80-9eb1-11eb-84de-ca26ad951fca.gif)

<br>

4. 레시피 공유 게시판 상세 페이지

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|상세페이지로 가기 Servlet | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/rboard/controller/RboardPostServlet.java)</center> | 
|상세페이지 JSP | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/rBoard/RboardPost.jsp)</center> | 

![상세페이지](https://user-images.githubusercontent.com/73207547/114968698-d97a4100-9eb1-11eb-89a8-f4b49be3afa1.gif)

<br>

5. 레시피 공유 게시판 글 작성

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|글 작성 JSP | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/rBoard/RboardInsertPage.jsp)</center> | 
|글 작성 Servlet | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/rboard/controller/RboardInsertServlet.java)</center> | 


![글 작성](https://user-images.githubusercontent.com/73207547/114968704-dd0dc800-9eb1-11eb-8a31-a222d8748153.gif)

<br>

6. 레시피 공유 게시판 글 수정

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|글 수정 JSP | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/rBoard/RboardUptPage.jsp)</center> | 
|글 수정 Servlet | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/rboard/controller/RboardUptServlet.java)</center> | 

![글 수정](https://user-images.githubusercontent.com/73207547/114968709-ded78b80-9eb1-11eb-8590-7c23f23770d3.gif)

<br>

7. 레시피 공유 게시판 글 삭제

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|글 삭제 JSP | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/rBoard/RboardPost.jsp)</center> | 
|글 삭제 Servlet | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/rboard/controller/RboardDelServlet.java)</center> | 

![글 삭제](https://user-images.githubusercontent.com/73207547/114968713-e0a14f00-9eb1-11eb-86c3-6add2d68f032.gif)

<br>

8. 레시피 공유 게시판 개인정보 수정

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|개인정보 수정 전 비밀번호 확인 폼 JSP | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/views/memberMyPage.jsp)</center> | 
|개인정보 수정 비밀번호 확인 Servlet | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/member/cotroller/MemberMyPagePwServlet.java)</center> | 
|개인정보 수정 폼 JSP | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/member/memberMyPageForm.jsp)</center> | 
|Ajax 사용한 닉네임 중복 Servlet | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/member/cotroller/MemberNickCheckServlet.java)</center> | 
|개인정보 수정 Servlet | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/member/cotroller/MemberUpdateServlet.java)</center> |

![개인정보수정](https://user-images.githubusercontent.com/73207547/114968724-e5fe9980-9eb1-11eb-93a6-5e4a124785bd.gif)

<br>

9. 레시피 공유 게시판 탈퇴 

|<center>JSP & Servlet</center>| <center>Link</center> |
|:--------:|:--------: |
|탈퇴 폼 JSP | <center>[링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/WebContent/member/memberDelForm.jsp)</center> | 
|탈퇴 Servlet | <center> [링크](https://github.com/CookAndHerb/SemiProject/blob/master/0_semiProject/src/com/recipe/member/cotroller/MemberDeleteServlet.java)</center> | 

![탈퇴](https://user-images.githubusercontent.com/73207547/114968730-e8f98a00-9eb1-11eb-9b90-9882d39270d5.gif)

<br>

## 🐥 파이널 프로젝트
> 어른허브

#### 기간
* 2021.03.11 ~ 2021.04.06

#### 학습 목표
* Spring 프레임워크 기반으로 웹 애플리케이션을 개발하는 경험을 한다.
* Mybatis, Spring MVC 패턴 구현을 통해 동작 원리를 이해한다.
* 쇼핑몰로서의 제 기능을 수행하도록 한다.
* 여러가지 API를 적용해본다.

#### 구현 기능
* 메인 - 판매량 TOP4 조회
* 회원가입, 로그인&로그아웃, 네이버 소셜 로그인, 회원 정보 수정, 탈퇴
* 상품 게시판- 리뷰 많은 순, 가격 낮은 순 등으로 상품 조회 기능, 상품 상세페이지(리뷰 기능, 별점 기능, 장바구니 담기 기능)  
* 고객센터 - 공지사항, 자주 묻는 질문(검색, 카테고리, 페이징 기능), 비회원 질문 게시판(답글 기능)
* 회사 소개 페이지- 지도api 사용
* 관리자 페이지 - 상품 관리(다중파일 첨부하여 상품 등록, 수정, 삭제, 검색 기능), 주문 관리(주문 조회, 배송상태 변경), 회원 조회
* 마이 페이지 - 주문 조회(페이징 기능), 주문 상세 조회, 내가 작성한 리뷰 내역 조회(리뷰 삭제), 회원 정보 수정, 탈퇴
* 장바구니 기능
* 상품 결제 기능
* 오픈 채팅 기능

#### 담당 역할
* 팀장, DB 설계, 메인 - 판매 TOP4 조회, 회원관리 - 우편번호API, 이메일 인증API, 비밀번호 암호화를 사용한 회원가입,
로그인&로그아웃, 아이디 및 비밀번호 찾기, 네이버 소셜 로그인 API 적용, 마이페이지 - 회원정보 수정, 회원 탈퇴, 
주문 내역, 주문 상세 내역(주문 취소하기), 내가 작성한 리뷰 내역(리뷰 삭제 가능), Ajax를 이용한 장바구니 기능 구현

#### 담당 기능 리뷰

1. 네이버 소셜 로그인 기능 - 네이버 소셜 로그인 api 사용


|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|네이버 소셜 로그인 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/webapp/WEB-INF/views/member/memberLoginForm.jsp#L87)</center> | 
|네이버 소셜 로그인 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/member/controller/MemberController.java#L59)</center> | 
|네이버 소셜 로그인 Controller2| <center> [링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/java/com/kh/herb/member/controller/NaverController.java)</center> | 

![네이버 로그인api](https://user-images.githubusercontent.com/73207547/114972328-4513dc80-9eb9-11eb-96a6-b5a18dc645e3.gif)

<br>

2. 회원가입 - 이메일 인증 api, daum 우편번호  api 사용, ajax를 이용한 아이디 중복 확인, 정규식 사용

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|회원가입 폼 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/member/memberJoinForm.jsp)</center> | 
|회원가입 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/member/controller/MemberController.java#L178)</center> | 
|비밀번호 암호화 | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/java/com/kh/herb/member/controller/Sha256Util.java)</center> | 
|회원가입 mapper | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/mapper/member-mapper.xml#L30)</center> | 


![회원가입](https://user-images.githubusercontent.com/73207547/114972348-49d89080-9eb9-11eb-8660-e361523e9776.gif)

<br>

3. 로그인

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|로그인 폼 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/member/memberLoginForm.jsp)</center> | 
|로그인 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/member/controller/MemberController.java#L139)</center> | 
|아이디 찾기 폼 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/member/memberIdSearch.jsp)</center> | 
|아이디 찾기 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/member/controller/MemberController.java#L263)</center> | 
|비밀번호 찾기 폼 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/member/memberPwSearch.jsp)</center> | 
|비밀번호 변경 폼 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/member/memberPwUpdateForm.jsp)</center> | 
|비밀번호 찾기 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/member/controller/MemberController.java#L286)</center> | 

![로그인](https://user-images.githubusercontent.com/73207547/114972329-45ac7300-9eb9-11eb-87ea-c87ce8502f08.gif)

<br>

4. 개인 정보 수정

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|개인정보 수정 폼 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/myHerb/memberUpdateForm.jsp)</center> | 
|개인정보 수정 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/myherb/model/controller/MyHerbController.java#L47)</center> | 

![개인정보수정](https://user-images.githubusercontent.com/73207547/114972321-434a1900-9eb9-11eb-8609-0844c38eee42.gif)

<br>

5. 탈퇴

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|탈퇴 폼 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/myHerb/memberDeleteForm.jsp)</center> | 
|탈퇴 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/myherb/model/controller/MyHerbController.java#L70)</center> | 


![탈퇴](https://user-images.githubusercontent.com/73207547/114972347-493ffa00-9eb9-11eb-9b67-0c6cd47139bb.gif)

<br>


6. 장바구니 비었을 경우

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|장바구니 비었을 경우 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/cart/controller/CartController.java#L76)</center> | 
|장바구니 비었을 경우 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/cart/noCart.jsp)</center> | 


![장바구니 비었을경우](https://user-images.githubusercontent.com/73207547/114972338-47763680-9eb9-11eb-931a-1dbf7aa5c392.gif)

<br>

7. 장바구니 담기 - ajax 이용하여 카트 담기, 로그인 안했을 경우, 이미 카트에 담겼을 경우 alert 창 띄우기

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|장바구니 담기 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/webapp/WEB-INF/views/product/productInfo.jsp#L362)</center> | 
|장바구니 담기 ajax | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/webapp/WEB-INF/views/product/productInfo.jsp#L192)</center> | 
|장바구니 담기 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/cart/controller/CartController.java#L29)</center> | 


![장바구니 담기](https://user-images.githubusercontent.com/73207547/114972336-46dda000-9eb9-11eb-846b-cabc374d24dc.gif)

<br>

8. 장바구니 페이지 - 체크박스 이용하여 모두 선택 가능,  선택하여 ajax로 상품 삭제 가능, 개별 삭제 가능, 수량 변경 가능

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|장바구니 페이지 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/cart/cartList.jsp)</center> | 
|장바구니 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/cart/controller/CartController.java#L76)</center> | 
|장바구니 목록 불러오기 mapper | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/mapper/cart-mapper.xml#L48)</center> | 

![장바구니페이지](https://user-images.githubusercontent.com/73207547/114972340-47763680-9eb9-11eb-8c0b-f37bb20a9e7e.gif)

<br>

9. 주문조회 페이지 - 주문 조회해오기, 페이징 기능

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|주문 조회 페이지 JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/myHerb/memberOrder.jsp)</center> | 
|주문 조회 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/myherb/model/controller/MyHerbController.java#L93)</center> | 
|주문 조회 mapper | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/mapper/myherb-mapper.xml#L92)</center> | 

![주문조회 페이징](https://user-images.githubusercontent.com/73207547/114972343-48a76380-9eb9-11eb-9ff3-679a325bf04a.gif)

<br>

10. 주문조회 페이지 - 주문 상세 페이지

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|주문 상세 페이지  JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/myHerb/memberOrderDetail.jsp)</center> | 
|주문 상세 페이지 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/myherb/model/controller/MyHerbController.java#L145)</center> | 
|주문 상세 페이지 mapper | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/mapper/myherb-mapper.xml#L110)</center> | 

![주문상세페이지](https://user-images.githubusercontent.com/73207547/114972342-480ecd00-9eb9-11eb-9a1a-903ef942a7e0.gif)

<br>

11. 주문조회 페이지 - 주문 취소하기

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|주문 취소하기  JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/webapp/WEB-INF/views/myHerb/memberOrderDetail.jsp#L190)</center> | 
|주문 취소하기 Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/myherb/model/controller/MyHerbController.java#L168)</center> | 

![주문취소하기](https://user-images.githubusercontent.com/73207547/114972345-48a76380-9eb9-11eb-8dfe-4708ea3adfc1.gif)

<br>

12. 주문 조회 페이지 - 배송 완료된 상태만 리뷰 달기 가능

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|배송 완료된 상태만 리뷰 달기 가능  JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/webapp/WEB-INF/views/product/productInfo.jsp#L652)</center> | 

![배송완료되고 리뷰](https://user-images.githubusercontent.com/73207547/114972334-46dda000-9eb9-11eb-8fae-376d1173e3e6.gif)

<br>

13. 내가 작성한 리뷰 목록 조회 & 삭제하기

|<center>JSP & Controller & mapper</center>| <center>Link</center> |
|:--------:|:--------: |
|내가 작성한 리뷰 목록  JSP | <center>[링크](https://github.com/CookAndHerb/herb/blob/master/herb/src/main/webapp/WEB-INF/views/myHerb/reviewList.jsp)</center> | 
|내가 작성한 리뷰 목록  Controller | <center>[링크](https://github.com/CookAndHerb/herb/blob/baddba216926911edaa52ee6eb951b88ede4572a/herb/src/main/java/com/kh/herb/myherb/model/controller/MyHerbController.java#L189)</center> | 

![리뷰목록](https://user-images.githubusercontent.com/73207547/114972331-45ac7300-9eb9-11eb-8219-73bae8259851.gif)
