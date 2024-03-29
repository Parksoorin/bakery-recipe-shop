# BAKERY RECIPE & SHOP
홈베이킹을 위한 베이커리 레시피를 찾을 수 있고, 재료를 구매할 수 있는 홈페이지<br><br>

### 1. 개요<br>
현재 코로나로 인해 외부에서 즐길 수 있는 취미 활동이 아닌, 집에서 즐길 수 있는 취미 활동이 증가하고 있는 추세이다.<br>
또한 코로나에 이어 버터와 밀가루 등 물가상승까지 겹치면서, 집에서 할 수 있는 냉동생지나 홈베이킹의 수요가 증가하고 있다. <br>
이처럼 현대인들은 여가 및 취미 생활에 관하여 관심을 보이고 있으며, 그 대표적인 예시로 홈베이킹이 있다. 하지만 베이킹의 재료를 구매할 수 있는 사이트는 많지만, 베이킹의 레시피를 찾아볼 수 있는 사이트는 많지 않다. 베이킹의 재료를 구매할 수 있는 사이트의 경우, 박력분을 구매하기 위한 페이지를 들어가면 박력분을 사용한 대표적인 레시피가 언급될 뿐, 원하는 레시피를 찾기 어려운 경우가 많다.<br>
베이킹 레시피 & 구매 사이트의 경우 다양한 레시피 중 원하는 레시피를 선택하고 그에 필요한 재료를 한 번에 선택하여 구매할 수 있다. 또한, 재료의 양에 따라 달라지는 결과물을 알려주어 사용자가 원하는 맛과 식감의 레시피를 선택할 수 있으며, 레시피 저장도 가능하다. 이는 바쁜 현대인이 베이킹을 취미생활로 함에 있어 편리하게 이용할 수 있다. <br><br>

### 2. 개발 환경 및 주요 기능<br>
개발 환경 : VS code - html, css, js
주요 기능 : 로그인, 로그아웃, 회원가입, 구매, 리뷰, 댓글, 레시피 제공, 레시피 선택, 레시피 저장, 게시판, 원데이클래스 장소 제공(지도 API)<br><br>

### 2. USECASE<br>
![USECASE](https://user-images.githubusercontent.com/101718825/207908862-969ead92-20ec-4f0b-b504-7f7fe4f909d9.png)<br>
비회원 사용자 : 회원가입<br>
회원 사용자 : 상품 리뷰, 상품 주문, 충전, 장바구니 상품 담기, 장바구니 상품 삭제, 회원정보 수정, 회원정보 조회, 레시피 변경, 레시피 저장<br>
회원, 비회원 사용자 : 레시피 목록 조회, 레시피 선택, 레시피 상세 조회<br>
관리자 : 레시피 등록, 레시피 수정, 레시피 삭제, 회원 조회, 회원 삭제, 상품 도매, 상품 등록, 상품 수정, 상품 삭제, 공지사항 등록, 공지사항 수정, 공지사항 삭제<br><br>

### 3. 클래스 다이어그램<br>
![USECASE](https://user-images.githubusercontent.com/101718825/213232949-6bcc5444-3ba9-4d5f-bc0b-41dd64feafec.png)<br><br>

### 4. E-R 다이어그램<br>
![USECASE](https://user-images.githubusercontent.com/101718825/213233620-b2ea2a21-062c-49e2-bc35-756089bb91b5.png)<br><br>

## 구현결과 및 아쉬운 점
+ ### 구현결과<br>
  + 메인페이지(main.html)<br>
  ![main_-_Trim_AdobeExpress](https://user-images.githubusercontent.com/101718825/215677625-f3dd8a05-e98f-434f-b8ea-cd9deeb803ca.gif)<br>
  
  + 로그인, 회원가입 페이지(login.html, join.html)<br>
  ![login_join](https://user-images.githubusercontent.com/101718825/215683348-c47b301f-2f0a-485d-8a0b-1f0940e9193c.gif)<br>

  + 게시판, 게시글 작성 페이지(notice.html, noticeWrite.html)<br>
  ![notice](https://user-images.githubusercontent.com/101718825/215684311-95aa5899-b4f6-494e-875c-00c9768968f5.gif)<br>

  + 레시피 페이지(bread2.html, cookie2.html, cake2.html)<br>
  ![recipe2](https://user-images.githubusercontent.com/101718825/215688057-cac929f8-2b55-438e-86fd-b0aab85562b5.gif)<br>

  + 레시피 페이지 상세(cake2.html)<br>
  ![recipemenu](https://user-images.githubusercontent.com/101718825/215689190-bbc8f73c-dbff-46b7-a68b-f04c8d4b3c6b.gif)<br>

  + 상세 레시피 페이지(cakerecipe.html)<br>
  ![cakerecipe](https://user-images.githubusercontent.com/101718825/215690037-40a88fe2-5fe3-41cd-86fb-14b81d0d0ee4.gif)<br>

  + 장바구니 페이지(cart.html)<br>
  ![cart](https://user-images.githubusercontent.com/101718825/215691700-ee289ca6-c78d-42bd-bc0f-957e3d6b81ab.gif)<br>

  + 마이페이지, 포인트 충전 페이지, 회원정보 수정 페이지(mypage.html, coin.html, member.html)<br>
  ![mypage](https://user-images.githubusercontent.com/101718825/215692547-3e2bf05d-eb27-409d-84fa-49617afad8b0.gif)<br>

  + 저장한 레시피 페이지(myrecipe.html)<br>
  ![myrecipe2](https://user-images.githubusercontent.com/101718825/215693766-3ed974e7-5d62-4d60-b4bd-370f7a1ad9ee.gif)<br>

<br><br>

+ ### 아쉬운 점<br>
 이번 캡스톤 프로젝트는 팀이 아닌 개인이 맡아서 진행했습니다. 혼자서 보고서를 작성하는 것은 처음이었지만. 모르는 것이 있으면 인터넷에 검색을 해서 찾아보고, 다른 홈페이지들의 코드와 CSS를 보면서 따라해보기도 하고, 최대한 원하는 결과물을 만들기 위해 배우고 도전했던 것 같습니다. <br>
 이번 프로젝트는 실제로 제가 홈베이킹을 하고 재료 구매 사이트를 이용하면서 불편했던 점들을 생각하며 구성하고 만들었습니다. 때문에 완성도를 높여서 홈페이지를 개설하게 된다면 저 뿐만 아니라 취미생활로 홈베이킹을 하는 사람들에게 편리성을 제공할 수 있을 것이라고 생각합니다. 또한, 이번 프로젝트는 html로 작성하였는데 react를 공부하고, react로 작성해서 조금 더 사용하기 편리한 웹사이트를 만드는 것이 목표입니다. <br><br>
