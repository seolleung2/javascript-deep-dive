# 모던 자바스크립트 딥 다이브 🏊🏻‍♀️
![KakaoTalk_Photo_2023-08-16-20-43-14](https://github.com/seolleung2/javascript-deep-dive/assets/69143207/98e02e2f-5123-40bb-b943-c2fa8d37066a)

## ⏰ 총 예상 학습 기간 : 23.08.17 (목) ~ 23.11.12 (일)
> 나홀로(?) 모던 자바스크립트 딥 다이브 `3개월 코스`

> 민족의 대명절 추석 주는 제외했습니다. (성심당 빵먹으러 ㄱㄱ🥯)

```text
Javascript 를 좀 더 Deep!! 하게 정리해 봅시다.

주요 작성 내용은 다음을 지키려 합니다.
1️⃣ 이전 Javascript를 공부하며 놓치고 무심코 넘어갔던 내용을 깊게 이해하도록 노력합니다.
2️⃣ 책을 읽고 다 적으려 하지 말고 그 날 읽었으면 목차로 돌아가 뭘 공부했는지, 혹은 이해했는지 생각해 본 내용을 정리합니다.
3️⃣ 회사에서 개발 면접관으로 참여했을 때, 이 장에서는 어떤 질문을 할 수 있을지 역으로 생각해 봅니다.
```

## 📆 정리 현황 테이블

아래 테이블에 각 장별로 작성한 README.md 를 링크 (연결) 합니다.

<table>
  <thead>
    <tr>
      <th>주차</th>
      <th>내용</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4">1주차 : 변수 <br>(230817 ~ 230820)</br></td>
      <td><a href="/04장-변수/README.md">04장: 변수</a></td>
    </tr>
    <tr><td><a href="/13장-스코프/README.md">13장: 스코프</a></td></tr>
    <tr><td><a href="/14장-전역_변수의_문제점/README.md">14장: 전역 변수의 문제점</a></td></tr>
    <tr><td><a href="/15장-let,const키워드와_블록_레벨_스코프/README.md">15장: let, const 키워드와 블록 레벨 스코프</a></td></tr>
    <tr>
      <td rowspan="2">2주차 : 타입과 실행 컨텍스트 (1) <br>(230821 ~ 230827)</br></td>
      <td><a href="/06장-데이터타입/README.md">6장: 데이터 타입</a></td>
    </tr>
    <tr><td><a href="/09장-타입 변환과 단축평가/README.md">09장: 타입 변환과 단축 평가</a></td></tr>
    <tr>
      <td rowspan="2">3주차 : 타입과 실행 컨텍스트 (2) <br>(230828 ~ 230903)</br></td>
      <td><a href="/11장-원시 값과 객체의 비교/README.md">11장: 원시 값과 객체의 비교</a></td>
    </tr>
    <tr><td><a href="/23장-실행_컨택스트/README.md">23장: 실행 컨텍스트</a></td></tr>
    <tr>
      <td rowspan="3">4주차 : JavaScript 기초 함수 (1) <br>(230904 ~ 230910)</br></td>
      <td><a href="/05장-표현식과_문/README.md">5장: 표현식과 문</a></td>
    </tr>
    <tr><td><a href="/08장-제어문/README.md">08장: 제어문</a></td></tr>
    <tr><td><a href="/10장-객체 리터럴/README.md">10장: 객체 리터럴</a></td></tr>
    <tr>
      <td rowspan="4">5주차 : JavaScript 기초 함수 (2) <br>(230911 ~ 230917)</br></td>
      <td><a href="/12장-함수/README.md">12장: 함수</a></td>
    </tr>
    <tr><td><a href="/16장-프로퍼티_어트리뷰트/README.md">16장: 프로퍼티 어트리뷰트</a></td></tr>
    <tr><td><a href="/17장-생성자 함수에 의한 객체 생성/README.md">17장: 생성자 함수에 의한 객체 생성</a></td></tr>
    <tr><td><a href="/18장-함수와 일급 객체/README.md">18장: 함수와 일급 객체</a></td></tr>
    <tr>
      <td rowspan="3">6주차 : 프로토타입, strict mode, 빌트인 객체 <br>(230918 ~ 230924)</br></td>
      <td><a href="/19장-프로토타입/README.md">19장: 프로토타입</a></td>
    </tr>
    <tr><td><a href="/20장-strict mode/README.md">20장: strict mode</a></td></tr>
    <tr><td><a href="/21장-빌트인객체/README.md">21장: 빌트인 객체</a></td></tr>
    <tr>
      <td rowspan="2">7주차 : this, 클로저 <br>(231002 ~ 231008)</br></td>
      <td><a href="/22장-this/README.md">22장: this</a></td>
    </tr>
    <tr><td><a href="/24장-클로저/README.md">24장: 클로저</a></td></tr>
    <tr>
      <td rowspan="2">8주차 : 클래스, ES6 함수 <br>(231009 ~ 231015)</br></td>
      <td><a href="/25장-클래스/README.md">25장: 클래스</a></td>
    </tr>
    <tr><td><a href="/26장 ES6 함수의 추가 기능/README.md">26장: ES6 함수의 추가 기능</a></td></tr>
    <tr>
      <td rowspan="5">9주차 : Symbol 이터러블 스프레드 디스트럭처링 Set Map <br>(231016 ~ 231022)</br></td>
      <td><a href="/33장-7번째_데이터_타입_Symbol/README.md">33장: 7번째 데이터 타입 Symbol</a></td>
    </tr>
    <tr><td><a href="/34장-이터러블/README.md">34장: 이터러블</a></td></tr>
    <tr><td><a href="/35장-스프레드 문법/README.md">35장: 스프레드 문법</a></td></tr>
    <tr><td><a href="/36장-디스트럭처링 할당/README.md">36장: 디스트럭처링 할당</a></td></tr>
    <tr><td><a href="/37장-Set과 Map/README.md">37장: Set과 Map</a></td></tr>
    <tr>
      <td rowspan="3">10주차 : 브라우저의 렌더링 과정 DOM 이벤트 <br>(231023 ~ 231029)</br></td>
      <td><a href="/38장-브라우저의_렌더링_과정/README.md">38장: 브라우저의 렌더링 과정</a></td>
    </tr>
    <tr><td><a href="/39장-DOM/READNE.md">39장: DOM</a></td></tr>
    <tr><td><a href="/40장-이벤트/README.md">40장: 이벤트</a></td></tr>
    <tr>
      <td rowspan="4">11주차 : 비동기 프로그래밍 <br>(231030 ~ 231105)</br></td>
      <td><a href="/41장-타이머/README.md">41장: 타이머</a></td>
    </tr>
    <tr><td><a href="/42장-비동기_프로그래밍/README.md">42장: 비동기 프로그래밍</a></td></tr>
    <tr><td><a href="/43장-Ajax/README.md">43장: Ajax</a></td></tr>
    <tr><td><a href="/44장-REST_API/README.md">44장: REST API</a></td></tr>
    <tr>
      <td rowspan="4">12주차 : 프로미스 제네레이터 async/await 모듈 <br>(231106 ~ 231112)</br></td>
      <td><a href="/45장-프로미스/README.md">45장: 프로미스</a></td>
    </tr>
    <tr><td><a href="/46장-제너레이터와_async_await/README.md">46장: 제너레이터와 async/await</a></td></tr>
    <tr><td><a href="/47장-에러 처리/README.md">47장: 에러 처리</a></td></tr>
    <tr><td><a href="/48장-모듈/README.md">48장: 모듈</a></td></tr>
  </tbody>
</table>

<br>
