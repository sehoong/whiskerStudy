# whiskerStudy
2022.11.14 -1일차
##HTML&CSS 기초수업 및 javascript 기초수업

2022.11.15 -2일차

-웹(Web)이란?
 W(World) W(Wide) W(Web) 

-HTML (웹의 뼈대)
Hyper text markup language

-CSS (옷입히기)
Cascading style sheet 상위에서부터 하위까지 위계질서가 있는 시트

-웹호환성
 크로스브라우징-어느 브라우저라도 호환되는지 여부!
 ex) 크롬, 사파리 ,파이어폭스, 오페라  = 이들이 왜 꼽 힐까?
 이유) 기반이 달라서 
 1.크롬 -webkit
 2.사파리 -safari
 3. 파이어폭스 -mozilia
 4. 오페라 -o-

-웹표준
 W3C에서 정한 기준을 준수하느냐 마느냐

-HTML5
 Doctype을 선언하기 시작

-meta 태그
 웹에서 해당 사이트의 정보를 알려 주는 태그 (meta태그에 웹사이트의 정보를 담을 수 있음)
 ex) charset, keyworld,description, author, viewport // 크게 검색관련 메타태그랑 오픈그래프등으로 나눔
 viewport 뷰포트는 내가 보는 디바이스의 화면설정
 http-equiv / content=IE=edge, chorme=1 기준 브라우저 설정

-웹전근성을 왜 준수해야하는가?
 웹에 접근하는데에, 차별을 두지 않기 위해서
 ex) img 에는 alt에 설명을 적어주거나 tit요소를 넣어서 설명 / 태그를 올바르게 선정

-그렇다면 웹접근성에서 가장 중요한게 무엇인가?
 구조를 잘 짜야한다. 왜냐하면, 순차적으로 읽기때문에 구조가 뒤죽박죽이거나 기준이 다르면 
 (시각장애인 등)특정 사람들에게 혼란을 줄 수 있다.
 시멘틱 마크업-의미가있는 태그들을 사용하여서 구조를 설계 
 ex) head (header nav) body (container main section) / footer
      h1~h6으로 예시를 들면 제일 중요한 부분부터 설정 h1=로고 h2=대주제 h3=소주제
     
-웹접근성 절차 ()
  wa라는 업체에서 인증마크를 따야함.
  애네가 제공하는 tool이 있는데, 그걸로 심사하면 점수가 나옴. 근데 100점이여야 합격.
  그 다음에, 장애인이 직접 검사를 한다. 그후에 1년마크를 준다.
  1년뒤에는 다시 갱신해야함.  
  크롬에서도 URLl옆에 사다리모양 클릭하면 가라로 볼수있음. 빨간불이 있으면 부적절한거임.
  background-image 와 그냥 img처리는 의미가 있냐 없냐인데, 기준치를 정확하게 잡아야함. 
  input id와 label for 연결 input박스가 무엇인지 label로 설명!

  인천지방해양수산청(focus) 참고  
      
  


  