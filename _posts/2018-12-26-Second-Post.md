---
title: 1주차 포스팅
---

# 주제 아이디어톤

아이디어톤

문제의 시작 : 선물을 주기 위해 고르기 어렵고 받는 사람도 만족도가 높지 않을 수 있다.

다양한 해결 방법 모색
<table>
 <thread>
   <tr>
     <th>해결 방법</th>
     <th>내용</th>
  </tr>
</thread>
<tbody>
  <tr>
   <td>기부</td>
   <td>선물을 주는 사람도 받는 사람도 뿌듯할 수 있도록 선물할 때 좋은 곳에 사용할 수 있는 물품을 기부한다</td>
 </tr>
 <tr>
  <td>위치정보에 기반한 추천</td>
  <td>선물 받는 사람의 위치정보에 기반하여 그 사람의 주변에 있는 브랜드 이름을 추천하여 해당 상품을 선물하도록 유도한다</td>
 </tr>
 <tr>
  <td>크라우드펀딩</td>
  <td>재미있는 크라우드펀딩을 받는사람의 이름으로 후원하여 크라우드 펀딩 상품을 받을 수 있는 크라우드 펀딩 선물하기</td>
 </tr>
 <tr>
  <td>현금 선물</td>
  <td>대부분의 사람이 좋아하는 현금을 선물</td>
 </tr>
</tbody>
</table>

가장 현실성 있고 주는사람과 받는 사람의 만족도가 가장 높은 "위치정보에 기반한 추천"을 해결책으로 선택<br>

또한 선물을 활용하는 방법으로 KakaoGo라는 게임 아이디어 제시<br>

카카오고란?<br>

포켓몬고에서 아이디어를 따와서 단톡방에 게임을 만들면<br>
포켓몬고처럼 상품이 나타나고 그것을 찾는 게임<br>
증강현실을 기반으로 특정 위치에 상품을 숨기면 <br>
참여자들은 스마트폰의 카메라를 이용해 AR상품을 찾는 게임 <br>
선물도 주면서 게임도 즐길 수 있다.<br>

**선물을 주는 색다른 방식 제안으로 반 아이디어톤 대회 1등**


# 주제 로봇 Quest

로봇을 통해 농구,마라톤, 골프, 씨름

<h1 id="1주차-로봇퀘스트">[1주차 Reflection] Robot Quest</h1>

<table>
<thead>
  <tr>
    <th>미션</th>
    <th>규칙</th>
    <th>내용</th>
    <th>구현방법</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>농구</td>
    <td>누가 공을 골대에 더 많이 넣는가</td>
    <td>라인 별로 점수를 달리해서 정해진 시간내에 가장 많은 점수를 획득하는 팀이 우승 </td>
    <td>인원과 시간의 부족으로 인해서 실제 경기에 출전은 실패하였지만 알고리즘은 구현</br>
       알고리즘도 중요하지만 하드웨어 디자인이 중요했던 종목</td>
  </tr>
  <tr>
    <td>마라톤</td>
    <td>누가 더 빨리 들어오는가</td>
    <td>각 반별로 팀을 짜서 정해진 구간만큼 주행하고 바톤터치를 한다. 이때 코스를 얼마나 정확하게 주행하는지, 얼마나 빨리 결승점에 도착하는지가 우승의 포인트이다.</td>
    <td>센서를 좌우로 흔들면서 라인을 벗어나지 않도록 한 기초적인 라인트레이서지만 준수한 성능으로 완주함 </br>
  </tr>
  <tr>
    <td>골프</td>
    <td>누가 홀에 공을 넣는가 </td>
    <td>골프처럼 홀이 있고 로봇이 골프공을 홀에 넣는다. 많은 점수를 획득한 팀이 우승한다.</td>
    <td>농구와 마찬가지로 하드웨어의 설계가 중요했던 요소로 자동 반복 기능을 탑재</br>
         공이 힘을 최대한 많이 받을 수 있도록 하드웨어 설계</td>
  </tr>
  <tr>
    <td>씨름</td>
    <td>정해진 필드에서 상대 봇을 밀어내기</td>
    <td>1대1로 진행되며 서로 부딪히거나 피하면서 상대방의 로봇을 경기장 밖으로 밀어내면 점수를 획득한다. 정해진 시간 동안 결과가 나오지 않을 경우 무승부 처리를 한다.</td>
    <td>하드웨어적인 요소보다 다양한 공격패턴을 통하여 상대방을 경기장 밖으로 밀어내는 전략을 구사 했으나 대부분의 게임이 하드웨어 대결 양상으로 흘러 준수한 성적을 내지는 못함</td>
  </tr>
</tbody>
</table>
<h1 id="1주차-reflection-design-thinking-방법론">[1주차 Reflection] Design Thinking 방법론</h1>

<table>
<thead>
 <tr>
   <th>단계</th>
   <th>정의</th>
   <th>활용 Tool</th>
 </tr>
</thead>
<tbody>
 <tr>
   <td>공감<br />(empathize)</td>
   <td>관찰, 인터뷰, 체험으로 문제점을 발견하는 단계</td>
   <td>1.공감지도:<br />사용자와의 인터뷰를 통해 사용자 입장에서의 생각을 6가지항목으로 정리하는 기법<br />2.페르소나:<br />특정 사용자를 대표하는 가상인물을 정해 그 사용자의 입장을 분석하는 기법<br />3.고객여정맵:<br />고객이 서비스를 이용하는 과정을 그림이나 사진, 도표 등으로 나타내어 시각화하는 기법</td>
 </tr>
 <tr>
   <td>문제 정의</td>
   <td>문제점에 대해 정의하고 분석하는 단계</td>
   <td>관점서술문 작성:<br />공감단계를 통해 분석한 데이터를 활용해 사용자의 불편함, 니즈나 목표를 서술하는 기법</td>
 </tr>
 <tr>
   <td>아이디어 도출</td>
   <td>아이디어를 자유롭게 발산하는 단계</td>
   <td>1.마인드맵:<br />중심이미지에서 가지연결을 통해 가지 위 키워드를 늘려가는 기법<br />2.브레인라이팅:<br />마인드맵에서 도출된 대표 아이디어중 3개를 선정해 발전시키는 기법, 마지막까지 진행후 괜찮은 아이디어에 체크를 한다<br />3.스캠퍼(SCAMPER):<br />마인드맵, 브레인라이팅에서 얻은 다양한 아이디어를 조합하고 개발하여 새로운 아이디어를 도출하는 기법<br />4.아이디어보드:<br />스캠퍼를 통해 개발된 아이디어를 선정하여 구체화하고 시각화하여 문제해결책을 설명하는 기법<br />5.PMI피드백:<br />아이디어의 장점(Plus), 단점(Minus), 흥미로운 점(Interesting)을 중심으로 피드백하는 기법</td>
 </tr>
 <tr>
   <td>시제품 제작</td>
   <td>아이디어를 구현하는 단계</td>
   <td>프로토타입:<br />성능 검증 및 개선을 위하여 상품화에 앞서 제작하는 시제품</td>
 </tr>
 <tr>
   <td>테스트</td>
   <td>피드백을 통해 아이디어를 개선하는 단계</td>
   <td>월드카페:<br />제작한 프로토타입을 예비사용자들에게 피드백을 받는 기법, 호스트와 서기로 역할나누어 수행한다.</td>
 </tr>
</tbody>
</table>
