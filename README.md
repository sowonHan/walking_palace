# 🌺 고궁 산책

jQuery 기반의 고궁 행사 안내 사이트

## 🐲 프로젝트 소개

고궁 산책은 한국을 대표하는 4대 궁궐과 그곳에서 열리는 각종 행사를 홍보하는 웹사이트입니다.

고궁 산책에서 소개하는 궁은 서울에 위치한 조선시대 궁궐 중 경복궁 · 창덕궁 · 창경궁 · 덕수궁 총 4곳입니다.

이미 고궁을 몇 차례 방문하고 사랑하는 사람들에게는 형태와 시기가 다른 여러 가지 행사를 한 번에 모아서 확인할 수 있는 편의성을 제공하고,

그 동안 고궁에 관심이 없었던 사람들에게는 '한번 가볼까?' 같이 가벼운 호기심과 흥미를 느낄 수 있도록 다채로운 색감과 이미지, 간략하지만 핵심만을 추린 정보를 제공합니다.

사이트명 '고궁 산책'은 사람들이 궁을 따분하고 어려워하여 외국인들이나 관광하는 곳으로 치부하기보다는, 거창한 목적 없이도 가볍게 산책과 나들이를 즐기러 오면서 친숙한 장소로 여기기를 바란다는 의미를 담고 있습니다.

> **개발 기간** : 2022년 4월 1일 ~ 2022년 5월 2일

## ⚙ 기술 스택

`언어`

- Javascript
- HTML5
- CSS3

`라이브러리`

- jQuery
- FullCalendar
- **스타일도구**
  - Swiper
  - fullPage.js
  - Backstretch
  - Animate.css
  - AOS
  - Font Awesome

## 🪁 소스

`OPEN API`

- Kakao 지도 API

`데이터 및 이미지 소스`

- [문화재청 궁능유적본부 공식 인스타그램](https://www.instagram.com/royalpalaces_tombs/)
- [문화재청 공식 트위터](https://twitter.com/chlove_u)
- [문화재청 공식 블로그](https://blog.naver.com/chagov)
- [창경궁 홈페이지](http://cgg.cha.go.kr/agapp/main/index.do?siteCd=CGG)
- [창경궁 공식 트위터](https://twitter.com/cgglove)
- [경복궁 홈페이지](http://www.royalpalace.go.kr/)
- [경복궁 공식 트위터](https://twitter.com/royalpalacego)
- [창덕궁 홈페이지](http://www.cdg.go.kr/default.jsp)
- [덕수궁 홈페이지](https://deoksugung.go.kr/)
- [한국문화재재단 홈페이지](https://www.chf.or.kr/chf)
- [궁중문화축전 홈페이지](https://www.chf.or.kr/fest)

## 🗂 디렉터리 구조

<details>
  <summary>접기/펼치기</summary>

    📦walking_palace
    ┣ 📂css
    ┃ ┣ 📜all_time.css
    ┃ ┣ 📜common.css
    ┃ ┣ 📜detail.css
    ┃ ┣ 📜main.css
    ┃ ┗ 📜reset.css
    ┣ 📂images
    ┃ ┣ 📜2021 Twitter logo - blue.png
    ┃ ┣ 📜changdeok.jpg
    ┃ ┣ 📜changgyeong.jpg
    ┃ ┣ 📜changgyeong_all.jpg
    ┃ ┣ 📜chilgung.jpg
    ┃ ┣ 📜deoksu.jpg
    ┃ ┣ 📜deoksu_all.jpg
    ┃ ┣ 📜GitHub-Mark-120px-plus.png
    ┃ ┣ 📜GitHub-Mark-Light-120px-plus.png
    ┃ ┣ 📜gyeongbok_bridge.jpg
    ┃ ┣ 📜huwon_final.jpg
    ┃ ┣ 📜Instagram_Glyph_Gradient_RGB.png
    ┃ ┣ 📜seokjojeon1.jpg
    ┃ ┣ 📜seokjojeon2.jpg
    ┃ ┣ 📜seokjojeon3.jpg
    ┃ ┣ 📜slide_background.png
    ┃ ┣ 📜slide_dalbit.png
    ┃ ┣ 📜slide_festival.png
    ┃ ┣ 📜slide_gyeong_night.png
    ┃ ┣ 📜slide_hoeru.png
    ┃ ┣ 📜slide_main.png
    ┃ ┣ 📜slide_moran.png
    ┃ ┣ 📜slide_saeng.png
    ┃ ┣ 📜slide_spring.png
    ┃ ┗ 📜slide_tree.png
    ┣ 📂javascript
    ┃ ┣ 📜all_time.js
    ┃ ┣ 📜common.js
    ┃ ┗ 📜main.js
    ┣ 📂library
    ┃ ┣ 📂aos
    ┃ ┣ 📂fontawesome-free-6.1.1-web
    ┃ ┣ 📂fullcalendar-5.10.2
    ┃ ┣ 📂fullpage
    ┃ ┗ 📂jquery
    ┣ 📂pages
    ┃ ┣ 📜all_time.html
    ┃ ┣ 📜changdeok.html
    ┃ ┣ 📜changgyeong.html
    ┃ ┣ 📜deoksu.html
    ┃ ┗ 📜gyeongbok.html
    ┣ 📜index.html
    ┣ 📜memo.txt
    ┗ 📜README.md

</details>

## 🌲 주요 기능

고궁 산책 웹서비스의 핵심 기능은 공식 플랫폼의 정보 접근성을 보완하는 것에 있습니다. 따라서 고궁 산책 웹사이트에서는 4대 궁궐 및 행사의 개략적인 정보만을 확인할 수 있도록 페이지를 설계했으며, 사용자가 더 자세한 내용을 살피고자 할 경우 관련 페이지로 이동하도록 연결되어 있습니다.

#### 소개마당 페이지

- 슬라이드
  - 페이지 상단에 가로형 슬라이드로 당월에 진행 중인 행사를 안내. 총 9개의 이미지로 구성.
  - 가로 767px 이하의 화면부터는 세로형 슬라이드로 표시.
  - 이미지에 마우스를 올릴 시 슬라이드 진행이 멈추고, 이미지를 클릭 시 행사 관련 페이지로 이동.
- 스케줄러
  - 행사마다 색이 다르게 지정돼있어 월별 스케줄러를 통해 각 행사의 기간, 진행 요일, 행사가 겹치는 시기 등을 한 번에 모아서 확인 가능.
  - 일별 스케줄러인 '행사목록' 탭은 원하는 특정 날짜에 어떤 행사가 진행되는지만을 보고 싶은 사용자에게 용이함.
  - 행사 예매일은 시간 스케줄로 설정하여 구분하기 쉽게 표시.
  - 모든 스케줄은 클릭 시 행사 관련 페이지로 이동.
- 스케줄러와 선착순 예매를 보고 피로감을 느낄 사용자를 자연스럽게 상설 행사 페이지로 유도.
- 문화재청 공식 트위터 콘텐츠를 가져와 관람 팁을 소개하고 공식 SNS로의 유입을 유도.

#### 상설 행사 페이지

- 상시 진행되어 비교적 예매가 쉽거나, 예매하지 않고도 시간만 맞추면 해설 또는 이벤트를 즐길 수 있는 행사를 소개.
- 전체 화면 스크롤로 구성되어 있으며 총 4페이지. 1, 3페이지는 backstretch 라이브러리를 이용하여 3초마다 배경 이미지를 전환.
- 행사 또는 해당 궁에 대해 소개하고 행사 예매처와 예약 방법, 휴궁일 등을 안내. 버튼 클릭 시 관련 페이지로 이동.

#### 4대 궁궐 페이지

- 각 궁궐의 역할에 대해 먼저 간단하게 소개하고, 읽는 이가 해당 궁에 대해 흥미를 가질 만한 내용 위주로 정보를 제공.
- 브라우저 화면 전체를 할애하여 최대한 가독성을 확보할 수 있는 텍스트 크기를 출력하고 배경으로 각 궁궐 사진을 넣어 사용자의 이목을 집중.
- 궁궐 위치 안내
  - 좌측에는 궁궐 주소, 대표 번호, 지하철 교통편을 안내.
  - 우측에는 Kakao 지도 API를 연동하여 시각적으로 표시하는 동시에 사용자가 직접 화면을 조절해가며 위치와 경로를 확인할 수 있도록 제공.
- 각 궁궐의 공식 홈페이지와 트위터, 인스타그램을 버튼과 아이콘으로 연결.

#### 메뉴

- 가로 767px 이하부터 모바일용 메뉴로 전환. 햄버거 버튼 클릭 시 화면 전체에 드롭다운 메뉴가 표시.

## 🌸 개발 계기

고궁 산책 웹사이트는 '고궁 행사를 이것저것 즐겨보고 싶은데 찾아보기 불편하네. 궁궐 정보와 행사 내용까지 한 번에 모아서 볼 수 있는 웹서비스가 있었으면 좋겠다.'라는, 지극히 개인적인 바람에서 시작된 프로젝트입니다.

평소에 관심 있던 행사를 참여하고자 몇 차례의 시도와 실패를 반복하면서, 스스로 체감했던 불편 사항은 다음과 같습니다.

**불규칙하고 산재된 정보**

1. 행사에 대한 안내가 예매일과 굉장히 밭은 날짜 혹은 시간에 올라온다.
2. 공지 사항이 동시에 업데이트되지 않아 여러 플랫폼을 모두 체크해야 한다.
3. 궁궐마다 정보를 따로따로 찾아봐야 한다. 한국문화재재단과 궁중문화축전 홈페이지에서 전담받은 행사를 관리하고 문화재청 홈페이지에서도 홍보를 해주지만, 달력 형태의 통합적인 행사 조회 시스템은 정보가 업데이트되지 않거나 UI 사용성이 좋지 못하다. (2022년 4월 기준)

1,2번 문제점이 겹쳐 심하게는 이미 매진된 상황에서 SNS로 예매 공지가 올라오는 경우도 있었습니다😂. 거듭된 예매 실패로 정보를 한데 모아 직관적으로 정리해주는 서비스의 필요성을 절절히 느끼던 끝에 원하던 콘텐츠, UI, 컨셉의 웹사이트를 직접 만들어보고 싶어 고궁 산책 프로젝트를 진행하게 되었습니다.

현재는 [문화재청 궁능유적본부 행사 달력](http://royal.cha.go.kr/public/EVENT/RptcEventCalendar.do?pageNo=2100000&siteCd=RPTC)과 [한국문화재재단 문화달력](https://www.chf.or.kr/cont/calendar/all/month/menu/363) 페이지에서 고궁 산책 프로젝트의 월간, 일간 스케줄러와 동일한 서비스를 이용하실 수 있습니다.

## 🏹 트러블 슈팅

<details>
  <summary>모바일 드롭다운 메뉴 강제 비활성화 문제</summary>
  
  - 모바일 드롭다운 메뉴를 활성화시킨 상태에서 브라우저 너비를 768px 이상으로 늘렸을 때, 드롭다운 메뉴가 계속 활성화된 채로 유지되는 오류를 발견했습니다.
  - window에서 resize 이벤트가 발생할 때마다 브라우저 창 내부의 너비를 확인하고 768 이상이 될 경우 드롭다운 메뉴를 사라지게 하는 jQuery 함수를 만들어 문제를 해결했습니다.

  </details>
