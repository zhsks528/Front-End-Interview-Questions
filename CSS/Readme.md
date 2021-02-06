# CSS Interview Questions

## 목차

1. class와 id의 차이점에 관해서 설명해주세요.
2. Reset.css과 Normalize.css의 차이점은 무엇인가요? 당신은 무엇을 선택할 것이며, 그 이유는 무엇인가요?
3. `float`가 어떻게 동작하는지 설명해주세요.
4. `z-index`와 스택 컨텍스트(stacking context)가 어떻게 형성되는지 설명하세요.
5. BFC(Block Formatting Context)에 관해 설명해주세요
6. 클리어링(Clearing) 기술에는 어떤 것들이 있으며, 어떨 때 어떻게 사용하는 것이 적절한지 설명하세요.
7. CSS 스프라이트(CSS Sprites)를 설명하고, 페이지나 사이트를 어떻게 향상하는지 설명하세요.
8. Image Replacement를 사용해야 할 때, 선호하는 기술과 언제 사용하는지를 설명해주세요.
9. 브라우저 스펙 차이에 따른 스타일링 이슈를 수정하기 위해서 어떻게 접근하나요?
10. 기능이 제약된 브라우저를 위해서 어떤 방식으로 페이지를 만드나요?
11. 시각적으로 숨기는(그리고 스크린 리더에서만 사용할 수 있게 만드는) 다양한 방법은 무엇인가요?
12. 그리드 시스템(Grid system)을 사용한 적이 있나요? 있다면 어떠한 것을 선호하나요?
13. 미디어 쿼리(media queries)를 사용한 적이 있나요? 혹은 모바일에 맞는 layout과 CSS를 사용한 적이 있나요?
14. 미디어 쿼리 속성의 예를 들어줄 수 있나요?
15. SVG를 스타일링하는데 익숙하신가요?
16. 인쇄하기 위해 웹페이지를 어떻게 최적화 하나요?
17. 효율적인 CSS를 작성하기 위한 "비법(gotchas)"은 어떤 게 있나요?
18. CSS 전처리(CSS preprocessors)를 사용해보셨나요?
19. 그렇다면, 사용 경험에 기반을 둬 좋았던 점과 나빴던 점을 설명해주세요.
20. 페이지에서 표준 폰트가 아닌 폰트 디자인을 사용할 때 어떤 방식으로 처리하시나요? (웹폰트를 제외하고)
21. CSS 선택자가 어떠한 원리로 동작하는지 설명해주세요.
22. pseudo-elements에 관해서 설명하고 어디에서 사용되는지 이야기해보세요.
23. box model에 관해 설명하고 브라우저에서 어떻게 동작하는지 설명해주세요.
24. `* { box-sizing: border-box; }`은 무엇이고 사용했을때 이점은 무엇인가요?
25. 기억나는 `display` 속성에 대한 값들을 나열해보세요.
26. `inline`과 `inline-block`의 차이점은 무엇인가요?
27. 요소를 배치하는 방법(relative, fixed, absolute, static) 간의 차이는 무엇인가요?
28. CSS에서 'C’는 Cascading을 의미합니다. Cascading에 관해서 설명해주세요. 또 cascading system의 장점은 무엇인가요?
29. CSS framework를 사용해본 적이 있으신가요? 실무에서 사용해보았다면 어떤 이점이 있었나요?
30. 새로운 CSS Flexbox 혹은 Grid 스펙을 사용해 보신 적 있나요?
31. 반응형(Responsive) 디자인은 적응형(Adaptive) 디자인과 어떤 차이점이 있나요?
32. 절대 좌표대신 `translate()` 혹은 반대로 사용하는 이유가 있나요? 있다면 이유에 관해서 설명해주세요.
33. Flash of Unstyled Content에 관해 설명해주세요. 또 FOUC를 피하기 위해선 어떻게 해야 하나요?

## 질문과 답변

### Q1. class와 id의 차이점에 관해서 설명해주세요.

<details>
<summary>Answer</summary>

id 선택자와 class 선택자의 차이는 문서 안의 **복수**의 요소에 스타일을 적용하는 것인가 아니면 **유일**한 요소에 스타일을 적용하는 것인가 입니다.

</details>

### Q2. Reset.css과 Normalize.css의 차이점은 무엇인가요? 당신은 무엇을 선택할 것이며, 그 이유는 무엇인가요?

<details>
<summary>Answer</summary>

`Reset.css`는 요소의 모든 기본 스타일을 제거하는 방법입니다.

`Normalizing.css`는 요소의 유용한 기본 스타일을 보존하는 방법입니다.

</details>

### Q3. `float`가 어떻게 동작하는지 설명해주세요.

<details>
<summary>Answer</summary>

`float`는 위치를 정의하는 속성입니다.

`float`가 적용된 요소는 페이지의 흐름의 일부가 되며, 페이지의 흐름에서 제거되는 `position:absolute` 요소와 달리 다른 요소(ex: 플로팅 요소 주위로 흐르는 텍스트)의 위치에 영향을 줍니다.

</details>

### Q4. `z-index`와 스택 컨텍스트(stacking context)가 어떻게 형성되는지 설명하세요.

<details>
<summary>Answer</summary>

`z-index` 속성은 **겹치는 요소의 쌓이는 순서를 제어**합니다. `z-index`는 `position`에 `static`이 아닌 값을 갖는 요소에만 영향을 줍니다.

스택컨텍스트는 **레이어들을 포함하는 요소**입니다.

지역 스택 컨텍스트 내에서, 자식의 `z-index`값은 문서 루트가 아닌 해당 요소를 기준으로 설정됩니다. 해당 컨텍스트 외부 레이어(ex. 지역 스택 컨텍스트의 형제 요소)는 그 사이의 레이어에 올 수 없습니다.

각각의 스택 컨텍스트는 자체적으로 포함되어 있습니다.

- 요소의 내용이 쌓인 후에는 전체 요소를 스택 컨텍스트의 쌓인 순서로 고려합니다.

</details>

### Q5. BFC(Block Formatting Context)에 관해 설명해주세요

<details>
<summary>Answer</summary>

BFC(Block Formatting Context)는 **블록박스의 레이아웃이 발생하는 지점과 플로팅 요소의 상호작용 범위를 결정하는 범위**입니다.

BFC가 생성되는 경우는 아래와 같습니다.

1. float 요소
2. 절대 위치를 지정한 요소 (position:fixed, absolute)
3. display : inline-block, table, table-cell, table-caption
4. overflow: visible을 제외한 모든 값

</details>

### Q6. 클리어링(Clearing) 기술에는 어떤 것들이 있으며, 어떨 때 어떻게 사용하는 것이 적절한지 설명하세요.

<details>
<summary>Answer</summary>

`clearing`기술은 이 float 속성이 주변 요소의 배치에 더 이상 영향을 미치지 않도록 해제시키는 속성입니다.

#### 1. 빈 div를 생성하는 방법이 있습니다.

이 방법은 아주 쉽고 단순하지만 빈 요소를 사용했다는 것과 내용 표현의 분리라는 측면에서 권장하는 방법이 아닙니다.

```html
<div style="clear:left / right / both"></div>
```

#### 2. 부모요소에 `overflow:hidden` 또는 `overflow:auto`을 이용하는 방법이 있습니다.

다만 `hidden`은 내용이 길 경우 내용이 잘립니다. `auto`의 경우에는 스크롤이 생깁니다.

```css
.container {
  border: 5px solid black;
  background: yellow;
  overflow: hidden; // or overflow:auto
  ...;
}
.content {
  float: left;
  ...;
}
```

```html
<div class="container">
  <div class="content">자식 div</div>
</div>
```

#### 3. `:before` 또는 `:after` 가상 선택자를 이용하는 방법이 있습니다.

```css
.container {
  border: 5px solid black;
  background: yellow...;
  ...;
}
.content {
  float: left;
}

.container:before {
  content: " ";
  clear: both;
}

.container:after {
  content: " ";
  clear: both;
}
```

```html
<div class="container">
  <div class="content">자식 div</div>
</div>
```

</details>

### Q7. CSS 스프라이트(CSS Sprites)를 설명하고, 페이지나 사이트를 어떻게 향상하는지 설명하세요.

<details>
<summary>Answer</summary>

CSS 스프라이트는 2개 이상의 이미지를 하나의 이미지 파일로 만들어 background 속성을 이용하여 불러오는 방법입니다.

CSS 스프라이트를 사용하는 방법은 아래와 같습니다.

1. 스프라이트 생성기를 이용하거나 포토샵을 이용하여 여러 이미지를 하나의 파일로 만듭니다.
2. `background-image`, `background-position`, `background-size` 등을 이용하여 이미지를 불러오는 클래스를 생성합니다.
3. 해당 이미지가 필요한 요소에 해당 클래스를 추가합니다.

스프트라이트를 사용함으로써 장점은 아래와 같습니다.

1. 여러 이미지에 대한 HTTP 요청 수를 줄일 수 있습니다.
2. `:hover`의 상태에서만 나타내지는 이미지가 필요할 때, 다운로드 되지 않은 이미지를 미리 다운로드하여 깜박임이 보이지 않습니다.

</details>

### Q8. Image Replacement를 사용해야 할 때, 선호하는 기술과 언제 사용하는지를 설명해주세요.

<details>
<summary>Answer</summary>

IR(Image Replacement)은 이미지를 볼 수 없는 사용자에게 대체된 텍스트를 제공하는 것입니다.

1. `text-indent`를 활용한 방법입니다.

```css
span {
  text-indent: -9999px;
}
```

2. `width : 0`, `height : 0`, `font-size : 0` 을 이용하는 방법입니다.

먼저, 대체할 텍스트 요소에 background 이미지를 설정한 다음 대체 텍스트가 포함되는 요소의 높이와 너비를 0으로 지정합니다.

</details>

### Q9. 브라우저 스펙 차이에 따른 스타일링 이슈를 수정하기 위해서 어떻게 접근하나요?

<details>
<summary>Answer</summary>

- 문제와 그 문제를 일으키는 브라우저를 식별한 후, 해당 브라우저가 사용 중일 때만 로드되는 별도의 스타일 시트를 사용합니다. 하지만 이 방식을 사용하려면 **서버사이드 렌더링이 필요**합니다.
- **Bootstrap** 같은 라이브러리를 사용합니다.
- `autoprefixer`를 사용하여 벤더 프리픽스를 코드에 자동으로 추가합니다.
- `Reset.css` 또는 `Normalize.css`를 사용합니다.

</details>

### Q10. 기능이 제약된 브라우저를 위해서 어떤 방식으로 페이지를 만드나요? 어떤 기술과 프로세스를 사용할껀가요?

<details>
<summary>Answer</summary>

아직까지 기능이 제약된 브라우저를 생각해보고 개발해본적은 없지만 해야한다면 아래와 같이 진행할 예정입니다.

- `caniuse.com`에 접속하여 기능을 지원하는지 확인합니다.
- 자동 벤더 프리픽스를 위해 `autoprefixer`를 사용합니다.
- css `@supports`를 이용합니다.

```css
@supports (display: grid) {
  div {
    display: grid;
  }
}

@supports not (display: grid) {
  div {
    float: right;
  }
}
```

</details>

### Q11. 시각적으로 숨기는(그리고 스크린 리더에서만 사용할 수 있게 만드는) 다양한 방법은 무엇인가요?

<details>
<summary>Answer</summary>

콘텐츠를 시각적으로 숨기는 방법은 5가지가 있습니다.

1. display : none;
2. visible : hidden;
3. width : 0, height : 0, font-size : 0;
4. text-indent : -9999px;
5. position : absolute, left: -9999px;

접근성을 고려하여 숨기는 방법은 `clip` 속성을 이용하는 것입니다.

```css
/* BFC */

.hidden {
  overflow: hidden;
  border: 0;
  margin: -1px;
  width: 1px;
  height: 1px;
  clip: rect(1px, 1px, 1px, 1px);
  clip-path: inset(50%);
}

/* IFC */

.hidden {
  overflow: hidden;
  display: inline-block;
  border: 0;
  margin: -1px;
  width: 1px;
  height: 1px;
  clip: rect(1px, 1px, 1px, 1px);
  clip-path: inset(50%);
}
```

</details>

### Q12. 그리드 시스템(Grid system)을 사용한 적이 있나요? 있다면 어떠한 것을 선호하나요?

<details>
<summary>Answer</summary>

TODO...

</details>

### Q13. 미디어 쿼리(media queries)를 사용한 적이 있나요? 혹은 모바일에 맞는 layout과 CSS를 사용한 적이 있나요?

<details>
<summary>Answer</summary>

TODO...

</details>

### Q14. 미디어 쿼리 속성의 예를 들어줄 수 있나요?

<details>
<summary>Answer</summary>

`@media` 속성은 총 4가지가 있습니다.

- all : 모든 미디어 기기 장치
- print : 프린터
- speech : 스크린리더
- screen : 컴퓨터, 태블릿, 스마트폰 등

</details>

### Q15. SVG를 스타일링하는데 익숙하신가요?

<details>
<summary>Answer</summary>

익숙하지는 않지만 기본적으로 작성하는 방법은 알고 있습니다.

기본적인 채색은 `fill`과 `stroke` 두 속성을 이용하여 정할 수 있습니다.

선들은 `path`태그를 이용하여 그릴 수 있습니다.

SVG를 이용하여 간단한 정사각형을 그리는 방법입니다.

```
<svg width="100" height="100">
  <path d="M10 10 H 90 V 90 H 10 L 10 10" />
</svg>
```

</details>

### Q16. 인쇄하기 위해 웹페이지를 어떻게 최적화 하나요?

<details>
<summary>Answer</summary>

미디어 쿼리의 속성 중 `print`를 사용하여 인쇄를 위한 페이지 디자인을 작성합니다.

```css
@media print {
  header,
  footer,
  aside,
  form,
  … {
    display: none;
  }
}
```

</details>

### Q17. 효율적인 CSS를 작성하기 위한 "비법(gotchas)"은 어떤 게 있나요?

<details>
<summary>Answer</summary>

#### 1. 선택자는 상위 선택자를 포함하여 3개 이상 작성되지 않게 합니다.

```css
.select-1,
.select-2,
.select-3 {
  ...;
}
section div span {
  ...;
}
```

#### 2. 전체 선택자를 사용하지 않습니다.

브라우저는 선택자를 오른쪽에서 왼쪽으로 읽기 때문에 마지막에 전체 선택자를 사용한 경우 최초 문서 내의 모든 요소에 대응하고 그 이후 상위 클래스로 해당 요소를 선택하는지 확인하는 과정을 거치게 됩니다. 따라서 요소를 선택하는 CSS 규칙이 깊어지는 경우와 전체 선택자를 마지막 부분에 작성하는 경우 브라우저의 성능 저하가 발생하기 때문에 사용을 지양해야 합니다.

```css
/* bad */
* {
  ...;
}
.selector * {
  ...;
}

/* better */
.selector * th {
  ...;
}
```

#### 3. 아이디 선택자를 사용하지 않습니다.

ID는 하나의 HTML 파일에 **유일하게 존재해야 하는 값**입니다. ID 선택자를 사용한 다는 것은 그 스타일을 한 요소에만 사용하게 된다는 것을 의미하게 됩니다. 이러한 구조는 스타일 규칙의 재 사용이 불가능하게 만들어 CSS 파일 사이즈를 크게 만들고, 유지 보수와 확장성에 불편함을 가져오게 됩니다.

```css
/* bad */
#container {
  ...;
}
```

</details>

#### 4. !important의 사용과 인라인 스타일의 사용을 최대한 지양합니다.

#### 5. CSS 엔진의 색인 속도를 높이도록 우선순위를 고려하여 스타일 합니다.

### Q18. CSS 전처리(CSS preprocessors)를 사용해보셨나요?

<details>
<summary>Answer</summary>

SCSS를 사용해본 경험이 있습니다.

</details>

### Q19. 그렇다면, 사용 경험에 기반을 둬 좋았던 점과 나빴던 점을 설명해주세요.

<details>
<summary>Answer</summary>

장점은 아래와 같습니다.

1. 코드를 여러 파일로 나누기 때문에 **CSS의 유지보수성이 향상**됩니다.
2. **중첩 선택자를 작성**하기가 쉽습니다.
3. **일관된 테마를 위한 변수를 사용**할 수 있습니다.

단점은 아래와 같습니다.

1. **Webpack을 이용한 구조화 작업**이 번거롭습니다.
2. 다시 컴파일하는데 드는 시간이 느릴수가 있습니다.

</details>

### Q20. 페이지에서 표준 폰트가 아닌 폰트 디자인을 사용할 때 어떤 방식으로 처리하시나요? (웹폰트를 제외하고)

<details>
<summary>Answer</summary>

`@font-face`, `font-family`을 이용합니다.

```css
@font-face {
  font-family: "폰트명";
  src: url("폰트를 다운 받을 위치") format("포맷명 (ex: woff2");
}

html {
  font-family: "폰트명", "폰트명2", "폰트명3"...;
}
```

</details>

### Q21. CSS 선택자가 어떠한 원리로 동작하는지 설명해주세요.

<details>
<summary>Answer</summary>

브라우저는 선택자를 오른쪽에서부터 왼쪽으로 이동하며 선택자에 따라 DOM의 요소를 필터링하고 부모요소를 검사하여 일치를 판정합니다.

선택자 체인의 길이가 짧을수록, 브라우저가 해당 요소가 일치하는지 여부를 더 빠르게 파악할 수 있습니다.

</details>

### Q22. pseudo-elements에 관해서 설명하고 어디에서 사용되는지 이야기해보세요.

<details>
<summary>Answer</summary>

**선택자에 추가되는 키워드**로, 선택한 요소의 특정 부분을 스타일링 할 수 있습니다.

아래와 같이 사용할 수 있습니다.

1. 요소의 첫 번째 문자 또는 선 스타일 지정 (`::first-letter`, `::first-line`)
2. 요소의 내용 앞이나 뒤에 내용 삽입 (`:before`, `:after`, `content: " "`)

</details>

### Q23. box model에 관해 설명하고 브라우저에서 어떻게 동작하는지 설명해주세요.

<details>
<summary>Answer</summary>

HTML의 모든 엘리먼트는 width(너비)와 height(높이)를 가지는 사각형 박스이며 안쪽에서 부터 바깥쪽으로 content(컨텐츠) -> padding(패딩) -> border(보더) -> margin(마진)으로 구성되어 있습니다.

엘리먼트에서 실제너비는 마진을 제외한 (content width) + (padding left) + (padding right) + (border left) + (border right)값입니다.

실제 높이 역시 (content height) + (padding top) + (padding bottom) + (border top) + (border bottom)값이 됩니다.

</details>

### Q24. `* { box-sizing: border-box; }`은 무엇이고 사용했을때 이점은 무엇인가요?

<details>
<summary>Answer</summary>

기본적으로는 **box-sizing : content-box;** 가 적용되어있습니다.

**box-sizing : border-box** 박스의 크기를 테두리 기준으로 정합니다.

장점으로는 다른 속성값(`margin`, `padding` 등)에 영향을 받지 않기 때문에 반응형 웹을 구현하는데 있어 좀 더 쉽게 구현할 수 있습니다.

</details>

### Q25. 기억나는 display 속성에 대한 값들을 나열해보세요.

<details>
<summary>Answer</summary>

`none`, `inline`, `block`, `inline-block`, `table`, `flex`, `grid` 등이 있습니다.

</details>

### Q26. inline과 inline-block의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

차이점은 `width`, `height`, `margin` 속성에 있습니다.

inline은 `width`, `height` 속성을 무시하며 `margin` 은 좌 우만 적용이됩니다.

inline-block은 block과 마찬가지로 `width`, `height` 속성이 적용되며 `margin이` 상, 하, 좌, 우 방향으로 적용이됩니다.

</details>

### Q27. 요소를 배치하는 방법(relative, fixed, absolute, static) 간의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

- static : 기본위치로써 평소와 같이 페이지에 위치시킵니다.
- relative : top, bottom, left, right 값을 통해 요소의 위치를 변경할 수 있습니다.
- absolute : `position:static` 이 아닌 부모를 기준으로 움직입니다.
- fixed : 지정된 위치에 배치되며, 스크롤할 때 이동하지 않습니다.
- stickey : `relative + fixed`로써 지정된 임계값을 넘을 때까지는 `relative`가 적용되고 넘게되면 `fixed`가 적용됩니다.

</details>

### Q28. CSS에서 'C’는 Cascading을 의미합니다. Cascading에 관해서 설명해주세요. 또 cascading system의 장점은 무엇인가요?

<details>
<summary>Answer</summary>

Cascading은 계단모양의 폭포를 의미하며 CSS에서 스타일 시트의 우선순위를 지정하는 방식이 폭포수와 닮아 붙여진 의미 입니다.

cascading system을 사용하였을 때의 장점은 HTML Element마다 일일이 스타일을 지정하지 않아도 되므로 렌더링 속도와 코드의 양을 줄여 성능 향상에 기여할 수 있습니다.

</details>

### Q29. CSS framework를 사용해본 적이 있으신가요? 실무에서 사용해보았다면 어떤 이점이 있었나요?

<details>
<summary>Answer</summary>

Bootstrap, MaterialUI를 사용해본 적이 있습니다.

장점으로는 빠르게 반응형 웹사이트 프로토타입을 개발할 수 있습니다.

</details>

### Q30. 새로운 CSS Flexbox 혹은 Grid 스펙을 사용해 보신 적 있나요?

<details>
<summary>Answer</summary>

주로 Flexbox를 사용합니다.

</details>

### 31. 반응형(Responsive) 디자인은 적응형(Adaptive) 디자인과 어떤 차이점이 있나요?

<details>
<summary>Answer</summary>

반응형 디자인은 기기별 사이즈에 따라 알맞은 크기로 콘텐츠를 제공하고, 사이즈별 제공하는 콘텐츠의 차이가 없는 디자인 입니다.

반면에 적응형 디자인은 미리 정해진 몇 가지 화면 크기를 기준으로 두고 비율에 맞춰 페이지를 구성하는 방식입니다.

</details>

### Q32. `position:absolute`대신 `translate()` 혹은 반대로 사용하는 이유가 있나요? 있다면 이유에 관해서 설명해주세요.

<details>
<summary>Answer</summary>

**reflow, repainting**와 관련이 있습니다.

`position : absolute`는 다른 요소에 영향을 끼치게 때문에 reflow, repainting이 발생합니다. 또한 CPU를 사용합니다.

`translate()`는 다른 요소에 영향을 끼치지 않기 때문에 reflow, repainting이 발생하지 않습니다. 또한 GPU를 사용합니다.

그러므로 애니메이션의 경우에는 translate()를 사용해야 성능에 좋습니다.

</details>

### Q32. Flash of Unstyled Content에 관해 설명해주세요. 또 FOUC를 피하기 위해선 어떻게 해야 하나요?

<details>
<summary>Answer</summary>

FOUC는 외부의 CSS가 불러오기 전에 잠시 스타일이 적용되지 않은 웹 페이지가 나타나는 현상입니다.

`<link>` 태그를 `<head></head>`안에 포함시키고, @import의 사용을 자제해야 합니다.

</details>
