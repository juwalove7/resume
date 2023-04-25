## 이력서

<img src="https://user-images.githubusercontent.com/118159213/230006689-5db532ab-b24d-4a6a-970e-8fa5ec6c289e.jpg" width="200" height="200">

### 안녕하세요 백엔드 개발자 이호승입니다. <br>
소통하는 것을 좋아하고 배워서 안 지식을 공유하는 것을 좋아합니다. <br>

  ● 이름: 이호승 <br><br>
  ● Email: juwalove7@gmail.com <br><br>
  ● GitHub: https://github.com/juwalove7 <br><br>
  ● 취미 : 한강라이딩, 통기타 연주하기 <br><br>
  
## 핵심경험
  ● JS / Express 기반의 REST API 서버 개발 <br>
  ● TS / Nest.js 기반의 REST API 서버 개발 <br>
  ● Jest 기반의 테스트코드 작성 <br>
  ● 깃헙 이슈를 사용함으로 개발 일정관리 <br>
  ● 날씨를 제공해주는 오픈 API 사용 <br>
  ● 오프셋 기반의 페이지네이션 구현 <br><br>
  
## 프로젝트 경험
### Gol:D (캠핑장 이커머스 서비스)<br>

소개: 내가 원하는 날짜에 캠핑장의 타입을 선택하고 인원수를 입력하여 캠핑장을 예약할 수 있는 서비스

기간: 23.03, 4주 <br> 
GitHub: https://github.com/juwalove7/Gol-D  <br>
프로젝트 문서: https://www.notion.so/Gol-D-70ce0153fe7e406aba77fc4667d728fc  <br>

기술: Nest.js, Type-orm

-	관리자 전용 유저/결제/주문 목록 관리 페이지에서 조회할 데이터를 가져왔지만 정돈이 되어 있지 않아 보기가 불편한 문제가 있었음. <br>
->	깔끔하고 가독성 있게 관리하고 보기 위한 오프셋 기반의 페이지 네이션 구현 <br>
-	유저와 관련된 정보 생성, 조회, 상세조회, 수정, 삭제 API 구현으로 관리자의 입장에서 유저를 관리할 수 있도록 개발 <br>
->	관리자는 유저의 정보에 대해 전반적인 관리를 할 수 있어야 한다고 팀원과 의논 후 작업함. <br>
-	데이터의 보존이 필요할 것을 대비해 softDelete를 사용하여 DB에 데이터가 남을 수 있도록 구현 <br>
->	고객의 정보는 앞으로의 서비스 방향을 결정할 수 있기에 고객이 탈퇴를 하더라도 장기적으로 정보를 수집 및 파악하여 더 좋은 서비스를 제공하기 위해 데이터의 보존이 필요하다고 판단하여 사용함. <br>
-	캠핑 프로젝트의 날씨 확인 필요성을 느낌으로 Openweathermap을 통해 날씨 API를 구현 <br>
->	위도와 경도를 지정하여 날씨의 정보를 가져올 수 있도록 함. <br>
->	당일의 날씨는 가져와서 구현하는 것이 문제없었지만 일기예보를 위해 5일 앞의 날씨 정보를 가져오는 것은 하였지만 프론트로 구현이 어려웠고 팀원들과 의논하여 예보는 빼기로 결정함. <br>
-	깃허브 이슈를 사용함으로 개발 진행 상황 파악 및 일정관리 경험 <br>
->	팀원들과 각자 맡은 개발의 일정관리를 위해 주 단위로 끊어 이슈를 등록하고 개발이 완료된 것은 closed 함으로 매주 개발의 목표를 설정하고 얼마나 완수하였는지 파악하며 개발 진행함. <br>
-	Jest 기반의 단위 테스트 코드 작성 <br>


<img src = "https://user-images.githubusercontent.com/118159213/230012876-bce6b22b-7103-44b7-80e0-f85f5b7dcdd8.png">
<br>

### Oreo (Bakery Shop 이커머스 서비스)

소개: 내가 원하는 빵을 검색하고 선택하여 주문을 할 수 있는 서비스

기간: 23.02, 1주  <br>
GitHub: https://github.com/juwalove7/oreo  <br>
프로젝트 문서: https://www.notion.so/5-8ad1de4c11734c038457829c4749ab73  <br>

기술: Node.js, Express, Sequelize, MySQL

-	팀장이 되어 팀원들과 매일 오전과 저녁 2번의 회의 시간을 통해 소통하며 프로젝트를 주도
-	팀원 모두의 공통된 데이터 흐름을 파악하기 위한 ERD 설계 및 수정 작업 담당
-	관리자를 위한 주문 및 회원 목록 조회 API 구현을 통해 유저만이 아닌 다른 측면에서 고민하고 개발

<img src = "https://user-images.githubusercontent.com/118159213/230013102-cbee014f-67fe-4770-87e9-ec1e7877293d.png">
<img src = "https://user-images.githubusercontent.com/118159213/232425137-1b6aca58-a82f-41ef-959e-05fe5c19e965.png">
<img src = "https://user-images.githubusercontent.com/118159213/232425489-4a1a1ae4-28b2-4d69-99db-3f7ee604bdaa.png">
<br>

### One-Sheep (낮잠 캠핑카 대여 서비스)

소개 : 회사의 점심시간 단잠을 자고픈 회사원들을 위한 출장 낮잠 캠핑카 서비스

기간: 23.01, 1주  <br>
GitHub: https://github.com/juwalove7/One-Sheep  <br>
프로젝트 문서: https://www.notion.so/2-29215f30511140b0aac85fff618adc03  <br>

기술: Node.js, Express, Sequelize, MySQL  <br>

-	3계층 아키텍처로 리뷰 작성 API 개발
-	회원들의 서비스 이용을 파악하기 위한 이용내역 조회 구현
-	팀 전체의 공통된 데이터베이스 참조를 위해 ERD 다이어그램 담당
<img src = "https://user-images.githubusercontent.com/118159213/230013273-310546cd-6104-4a1d-bdbc-d7ef2a639e26.png">
<br>

### 교육
’22.11 ~ ’23.04   스파르타코딩클럽 내일배움캠프 Node.js 4기
<br><br>


### 성장 목표
  ● 구현하고자 하는 것이 될 때까지 포기하지 않는 개발자가 되는 것  <br>
  ● 배움에 있어 실수와 실패를 두려워하지 않는 도전정신을 가진 개발자가 되는 것  <br><br>
  ● 항상 초심을 잃지 않고 끊임없이 배우려고 하는 개발자가 되는 것  <br>
  
### 나의 강점
  ● 배우고자 하는 것에 대한 생각만이 아닌 노력을 하는 개발자  <br>
  ● 소통의 소중함을 아는 개발자  <br>
  ● 작은 것이라도 아는 지식을 공유하는 것을 아까워하지 않는 개발자  <br>
