# introduction
html5와 css3를 공부하면서 기억하고 싶은 코드

<br />

# contents
- [contact us](#contact-us-example)
- [video background](#video-background-example)
- [sticky](#sticky-example)
- [layout](#layout-example)
<br />
<br />
<br />

<a name="contact-us-example"></a>

# contact us
간단한 contact us form 구현

### > 기억하고 싶은 부분
공통된 스타일은 클래스를 지정해 코드의 중복 사용을 줄인다.

<br />

<a name="video-background-example"></a>

# video background
비디오 배경 기능 구현

### > 기억하고 싶은 부분
비디오가 로딩되기까지 시간이 걸리므로 썸네일 작업이 필요하다. 모바일에선 사진으로 대체하는 것도 방법이다.
- video 태그의 poster 속성 이용
- css 속성 background-image 이용

<br />

<a name="sticky-example"></a>

# sticky
position의 sticky 속성을 활용해 스크롤시 요소가 화면에 고정되는 기능 구현

### > 기억하고 싶은 부분
- sticky 속성을 적용할 요소에 top, bottom, left, right 속성을 지정해주어야 적용된다.
- 해당 코드는 뷰포트 200px 위치가 되면 고정되다가 부모 요소와 함께 스크롤되어 사라진다.

<br />

<a name="layout-example"></a>

# layout
float 속성을 이용해 layout 설계

### > 기억하고 싶은 부분
- 시맨틱 태그를 적극 활용한다.
- 전체를 감싸는 container 박스를 만들고 이곳에 width 속성을 부여한다.
(👉🏻 축소 시 내부 요소들이 찌그러지지 않음)
- float 속성을 이용해 가로 정렬 레이아웃을 만들 때, 이들을 감싸는 div 태그를 만들고 폭을 지정하는 게 좋다.
(👉🏻 모바일에서 흘러넘치지 않음)
- float 속성으로 요소가 부유하므로 height 속성을 요소에 직접 지정해야 한다.

<br />

# layout - flex
flex 속성을 이용해 layout 설계

### > 기억하고 싶은 부분
- margin-left 속성값을 auto로 지정하면 해당 요소가 오른쪽 정렬된다. (navbar.html)
  ```css
  .nav-right {
    margin-left: auto;
  }
  ```

<br />

# layout - grid
grid-template-areas 속성을 이용해 layout 설계

### > 기억하고 싶은 부분
각 구역에 grid-area 속성값으로 이름을 지정하고, 부모 요소의 grid-template-areas 속성에 지정한 이름을 각 자리에 적용해준다.