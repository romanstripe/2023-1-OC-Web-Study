# <b>HTML5</b> Hyper Text Markup Language
- 웹페이지를 기술하기 위한 마크업 언어로 골격을 담당한다. <br>

- <b>HTML 요소</b>는 시작 태그와 종료 태그 그리고 태그 사이에 위치한 content 로 구성된다. ![HTML5의 구성요소](https://user-images.githubusercontent.com/127962311/235457493-958f030a-a8a1-4044-a7fc-92301ba78a72.png)<br>

- <b>어트리뷰트(Attribute)</b>란 요소의 성질, 특징을 정의하는 명세이다. 요소는 속성을 가질 수 있고, 속성은 요소에 대한 추가적인 정보를 제공한다. 
![attribute](https://user-images.githubusercontent.com/127962311/235457631-71719c78-9d1c-4baf-831c-73a6e0d7f8ab.png)<br>

- <b>Semantic Web</b>이란 웹에 존재하는 수많은 웹페이지에 메타데이터를 부여해 웹페이지를 의미와 관련성을 가지는 거대한 데이터로 구축하는 발상이다. 의미가 없는 <u>non-semantic 요소</u>에 속하는 태그는 content 에 대한 설명이 없다. 반면 <u>semantic 요소</u>에 속하는 태그는 content의 의미를 명확히 설명한다. non sementic 요소인 b 태그와 sementic 요소인 strong 태그는 외양이 같지만, 검색엔진은 두 태그 중 후자를 의미있게 받아들인다. i(italic)과 em(emphasized)도 이와 유사하다.<br>

# <b>CSS</b> Cascading Style Sheets
- HTML 의 각 요소의 스타일을 정의해 화면에 어떻게 렌더링 하면 되는지 브라우저에게 설명하기 위한 언어이다.<br>

- 스타일을 적용하고자하는 HTML 요소를 선택하는 것이 <b>셀렉터</b>이다. 아래의 rule set 을 통해 특정 html 요소를 렌더링 할 수 있다. <u>프로퍼티, 속성(property)</u>과 <u>속성값(value)</u>을 정할 수 있다. ![css 문법](https://user-images.githubusercontent.com/127962311/235460457-015626c3-2b76-4e83-ba49-f54fcfe90df3.png)<br>

- <b>position 프로퍼티</b>는 요소의 위치를 정의한다. 
1. <b>static, 기본위치</b>는 position 프로퍼티의 기본값으로 프로퍼티를 지정하지 않았을 때와 같다. 기본적인 요소의 배치 순서에 따라 위에서 아래로, 왼쪽에서 오른쪽으로 순서에 따라 배치되며 부모 요소 내에 자식 요소로서 존재할 때는 부모 요소의 위치를 기준으로 배치된다. 좌표 프로퍼티(top, bottom, left, right)를 같이 사용할 수 없으며 사용할 경우에는 무시된다.<br>
2. <b>relative, 상대위치</b>는 기본 위치를 기준으로 좌표 프로퍼티를 사용해 위치를 이동시킨다.<br>
3. <b>absolute, 절대위치</b>는 부모 요소 또는 가장 가까이 있는 조상 요소(static 제외)를 기준으로 좌표 프로퍼티(top, bottom, left, right)만큼 이동한다.<u>relative 프로퍼티</u>는 기본 위치.(static으로 지정되었을 때의 위치)를 기준으로 좌표 프로퍼티(top, bottom, left, right)을 사용하여 위치를 이동시킨다. 따라서 무조건 부모를 기준으로 위치하게 된다. <u>absolute 프로퍼티</u>는 부모에 static 이외의 position 프로퍼티가 지정되어 있을 경우에만 부모를 기준으로 위치하게 된다. 만일 부모, 조상이 모두 static 프로퍼티인 경우, document body를 기준으로 위치하게 된다.<br>
4. <b>fixed, 고정위치</b>는 부모 요소와 관계없이 브라우저의 viewport 를 기준으로 좌표프로퍼티를 사용해 위치를 이동시킨다. 스크롤 되더라도 화면에서 사라지지 않고 항상 같은 곳에 위치한다. <br>
