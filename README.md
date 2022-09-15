# 2차 프로젝트 "FREEPASS"
> JEJUPASS 웹 사이트를 모티브하여 만든 항공권 구메 사이트 </br>
> [FREEPASS 영상](https://youtu.be/S5ElqSBUMzM)
<img width="689" alt="스크린샷 2022-08-12 오후 12 34 06" src="https://user-images.githubusercontent.com/83544570/184546628-78accbd5-dc81-4f0f-9276-f19eabdba1d3.png">

#### [노정은 기술 블로그](https://jeongeuni.tistory.com/)

## 1. 제작 기간 & 참여 인원
-  2022년 8월 1일(월) ~ 2022년 8월 12일(금) : 총 10일
- Front-End : 🐥 노정은, 🐶 엄성훈, 🐱 이현주, 🦆 이혜진</br>
Back-end : ⚽️ 손찬규, 🦅 박정용


## 2. 사용 기술
- React
- Javascript
- Styled-component
- AWS (배포하였지만 요금부과 문제로 내린 상태)
- 라이브러리 : 카카오 로그인 (OAuth2.0), 카카오 맵 API, swiper, datePicker, react modal, anti desigh, react spinner


## 3. 핵심 기술

#### `JEJUPASS 웹 싸이트를 모티브한 팀 프로젝트`
- 제주패스는 제주 여행의 슈퍼 앱으로 전세계 실시간 최저가 항공, 제주 맛집까지 제주도 여행의 모든 것을 확인할 수 있는 웹 사이트 입니다.
- 저희는 그 중에서도 '항공 페이지'에 집중하여 구현하였습니다.
- 또한 '깨깨오항공', '코팡항공' 등으로 정해놓고 이 기업들을 향해 날아가는 컨셉으로 재미있게 구성해보았습니다.

#### `구현 기능`
- 구현한 기능을 간략하게 소개하자면<br />
카카오 로그인 -> 항공권 옵선 선택 후 조회 -> 항공권 선택 후 예약<br />
항공 사이트의 기본적인 FLOW를 갖추고 있습니다.

#### `개발 내용`
- Navigation Bar
- Footer
- 회원가입, 로그인 페이지
- 메인 페이지 
- 지도 페이지
- ESG 페이지
- 항공 메인 페이지
- 항공 모달 (항공권 옵션 선택) ▶️ FE노정은
- 항공권 리스트 페이지 ▶️ FE노정은
- 항공권 예약 및 결제 페이지
- 로딩 페이지 ▶️ FE노정은
<img width="508" alt="스크린샷 2022-08-14 오후 11 55 48" src="https://user-images.githubusercontent.com/78889402/184542683-c3a14f20-1d11-4c4b-9a67-5d0e811c48aa.png">

#### `프론트, 백엔드 깃허브`
> [팀 프로젝트 프론트엔드 GitHub](https://github.com/wecode-bootcamp-korea/35-2nd-FREEPASS-frontend)<br/>
> [팀 프로젝트 백엔드 GitHub](https://github.com/wecode-bootcamp-korea/35-2nd-FREEPASS-backend)


#### `구체적인 구현기능`
- 카카오 맵 API를 이용해서 backEnd와 통신해서 data로 화면에 렌더링 <br />
- 모달창에서 선택된 항공권 리스트를 화면에 렌더링 <br />
- react swiper, anti design 라이브러리를 사용해서 mock data로 화면 렌더링 <br />
- fetch로 backEnd와 통신하여 항공 모달 도시 검색기능 구현 ▶️ FE노정은 <br /> 
- query parameter, navigate, location로 항공 모달에서 항공 리스트 data로 데이터 전송 ▶️ FE노정은 <br /> 
- 항공 리스트 페이지 query parameter로 필터링 기능 ▶️ FE노정은 <br /> 
- 항공 모달 5개의 tap menu안에 각각 4개의 tap menu 기능 ▶️ FE노정은 <br /> 
- datapicker로 탑승일 tap 구현  ▶️ FE노정은 <br />
- OAuth 2.0을 이용한 소셜 로그인 구현 <br />
- git, 오픈소스에 올리면 안되는 값들을 외부파일 (.env)에 환경변수를 정의하여 로그인 구현에 사용 <br />

## 4. 문제 해결 경험
#### 4-1. 항공모달은 menu Tap 지옥
- 항공모달에서 항공권의 옵션들(출발지, 도착지, 탑습일, 인원 및 좌석등급)을 선택하여 항공권을 검색하는 것이기 때문에 어찌보면 내가 기능의 시작이라고 할 수 있어서 그래서 책임감을 가지고 구현해냈다! 
그래서 책임감을 가지고 구현해냈다! 

<details>
<summary><b>구현한 코드</b></summary>
<div markdown="1">
  
~~~javascript
~~~
  
</div>
</details>

### 🎥 각 페이지별 View
> [유튜브 데모 영상](https://youtu.be/S5ElqSBUMzM)

<table>
  <thead>
    <tr>
      <th>
        메인페이지
      </th>
      <th>
        ESG페이지
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184546658-d0c71996-a9b8-442d-9f75-5b6d8e1f181a.png">
      </td>
      <td align="center">
          <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184546668-7a340397-a975-4c72-814a-fc2712aa13ce.jpg">
      </td>
    </tr>
  </tbody>
</table>
<table>
  <thead>
    <tr>
      <th>
        항공페이지
      </th>
      <th>
        로그인
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184546670-cbb90d9f-48aa-4314-afe6-416e5ecb2c75.png">
      </td>
      <td align="center">
          <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184546648-cc5bb318-8140-42f6-9b6e-a89846432c57.png">
      </td>
    </tr>
  </tbody>
</table>
<table>
  <thead>
    <tr>
      <th>
        모달페이지
      </th>
      <th>
        로딩페이지
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184546674-a3361803-8c5d-4f0c-9a17-221d7bb3fc1d.jpg">
      </td>
      <td align="center">
          <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184546671-c30e9cc7-c935-4c2b-9437-86395d88c62c.jpg">
      </td>
    </tr>
  </tbody>
</table>
<table>
  <thead>
    <tr>
      <th>
        리스트페이지
      </th>
      <th>
        예약결제페이지
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
     <td align="center">
        <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184546675-8d41aa39-efb4-4730-96ca-98072b710934.png">
      </td>
      <td align="center">
        <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184546676-34799bdc-3032-49cd-a688-dfa1f13e7ad0.png">
      </td>
    </tr>
  </tbody>
</table>

# 

### 💫 프로젝트 협업 Tool

- GitHub : 각 페이지별 branch 관리.

- Slack : 팀원간의 실시간 소통 창구.

- Trello : 기능 단위로 카드를 생성, Sprint 단위로 진행했는지와 Stand up 미팅 툴로 활용.

- Notion : 회의정리 기록, 오늘의 공유/질문 사항, 현재 진행 사항, blocker 공유, 기능 단위 페이지 셍성 후 공유 및 기록.

<table>
  <thead>
    <tr>
      <th>
        트렐로
      </th>
      <th>
        노션
      </th>
    </tr>
       <tr>
      <th>
        깃허브
      </th>
      <th>
        슬랙
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184545309-14792748-ce97-449d-a619-dc1f60c80590.jpg">      
        </td>
      <td align="center">
        <img width="789" alt=image" src="https://user-images.githubusercontent.com/83544570/184545339-9336d126-243e-4daa-85b1-fb4044844dbd.jpg">      
        </td>
    </tr>
      <tr>
      <td align="center">
        <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184545347-3833d8a5-a195-49a1-8b1a-d83af5fb4db7.jpg">      
        </td>
      <td align="center">
        <img width="789" alt="image" src="https://user-images.githubusercontent.com/83544570/184545358-21bbb0dc-754b-4b96-b8d3-1acd53719fcb.png">      
        </td>
    </tr>
  </tbody>
</table>

#

### ✈️ 회고록
- [🐥 노정은님 회고록(1) - 기능 구현에 대한 회고](https://jeongeuni.tistory.com/53)  <br />
- [🐥 노정은님 회고록(2) - 팀 프로젝트에 대한 회고](https://jeongeuni.tistory.com/54)  <br />

#

### Reference

- 이 프로젝트는 제주패스를 참조하여 학습목적으로 만들었습니다.
- 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
