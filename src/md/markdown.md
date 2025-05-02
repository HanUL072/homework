# 마크다운 문법

용어정리
HTML : HyperText Markup Language, 웹 페이지의 구조를 만드는 언어
(기본 구성 - <html>, <head>, <body>)

웹 접근성 : 누구든지 원활하게 웹 페이지를 이용하는 것
(ex. 유튜브 자막, 시각장애인을 위한 음성지원 등)

마크업(Markup) : 텍스트에 추가적인 정보를 덧붙여 문서의 구조, 의미, 서식 등을 나타내는 것

요소(element) : 웹 페이지를 구성하는 기본적인 단위
(ex. <p>Hello</p>)

속성(Attribute) : 요소(element)에 추가적인 정보,속성 제공
(ex. <a hef="" alt="">)

- hef : hypertext reference의 줄임말로, 연결할 링크 주소(URL)
- alt : alternative text의 줄임말로, 이미지가 로드되지 않을 때 대체로 보여주는 텍스트(대체 텍스트)
  (**_ 대체 텍스트는 맥락에 맞게 사용 // 중요함 _**)

인라인 요소(inline) : 자기 콘텐츠의 크기만큼만 공간을 차지하고, 줄 바꿈이 일어나지 않는 요소
(ex. <span>, <a>, <img>,)

- 이미지 태그 방식

1. <img src="./src/assets/svg/chitchat.svg" alt="" width="100" height="100" /> - 이미지 자원 요청
2. svg = 코드 너무 기니까 패스 - 이미지가 코드화 되어있어서 성능이 더 좋음
   - svg 의 장점 : 색 지정 가능한데, css 에서 태그에 접근해서 색 변경 가능
     (이외 <object> <embed> 도 가능 한데 <object>는 이미지 뿐 아닌 다양한 객체 삽입 가능 (ex. pdf ))

블럭 요소(block) : 한 줄 전체를 차지하고, 항상 줄 바꿈이 일어나는 요소
(ex. <div>, <p>, <ul>,<section> )

<figure> : 이미지, 차트, 코드 블록, 영상 등과 같은 콘텐츠 덩어리를 의미 있게 묶어주는 태그
→ 주로 그에 대한 설명을 담는 <figcaption>과 함께 사용

-<div> vs <figure> : <div> 는 단순한 구조적 컨테이너 스크린리더로는 그 안에 뭐가든지 알수없으나 <figure> 는 주석이 붙는 시각 콘텐츠를 위한 의미있는 요소로 <figcaption> 을 통해 설명을 함께 제공할 수 있다는 점에서 이점이 있음.

루트 : 최상위 위치
절대경로 : 루트 부터 시작해 특정 디렉토리까지의 전체 경로
상대경로 : 현재 작업 디렉토리의 위치 기준 다른 디렉토리의 위치 경로

간단한 단축키
ctrl + p : 파일명을 일부만 입력해도 자동 완성 (빠른 파일탐색)
ctrl + shift + p : 명령 팔레트(Command Palette) ↑상위호환
ctrl + f : 검색한 코드가 존재하는 줄 탐색
ctrl + w : 창 닫기
ctrl + / : 주석
ctrl + , : Settings
ctrl + shift + k : 한 줄 삭제
! : HTML 기본 골격 생성

익스텐션 단축키
ctrl + alt + n : advanced-new-file
alt + w : 주석 (htmltagwrap)
