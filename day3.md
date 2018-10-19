#### Day 3 요약정리
## 메인메뉴 래이아웃 및 디자인
* display 속성에 flex 값을 지정해서 가로 방향으로 배치  
* 글자크기 (font-size), 굵기 (font-weight), 그림자 (text-shadow)  
* 웹폰트 활용
  * [Google Webfont](https://fonts.google.com/)
  * Noto Sans KR(Regular, Bold)
  * @import url(폰트 경로)

## 새소식 마크업 및 디자인  
이미지의 캡션을 지정할 수 있는 새로운 HTML5 요소인 figure 요소를 활용  
* h2 - 새소식 제목  
* time - 날짜 및 시간  
* p - 새소식 본문  
* figure, figcaption - 캡션 컨테이너  
* 이미지 요소에 width를 조정할 경우 반드시 height 속성의 값을 auto로 지정할 것  

## 추천 영상 마크업 및 디자인  
iframe 요소를 이용한 비디오 콘테츠 삽입  
유투브에서 원하는 동영상을 퍼가기 기능으로 복사해서 삽입한다. iframe의 경우 크기조정을 위해 컨테이너를 랩핑해서 사용한다.  
~~~ HTML
<div class="media-container">
  <div class="ifram-wrapper">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/pBuZEGYXA6E" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>
</div>
~~~

iframe 비디오의 크기를 유연하게 조절하고자 할 경우 iframe-wrapper 영역의 가로 크기는 100%로 설정하고 높이인 height 속성의 값은 0으로 할단한다. 그리고 padding-tpo 소석의 값을 비디오 킈기의 가로 세로 비율에 따른 백분율 값으로 할당한다. 만약 비디오가 4:3 비율일 경우 가로는 100% 세로는 75%로 지정한다.  

iframe 영역의 경우 position 속성의 값을 absolute로 설정하고 width와 height 를 100%로 지정한다.  

## 푸터 마크업 및 디자인 
* address - 주소영역
* small - 저작권 정보(특수문자를 사용할 경우 특수문자 이름이나 번호를 사용하여 마크업한다.)

