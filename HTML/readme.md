# HTML Interview Questions

## 목차

1. `<iframe>`이란 무엇이고 어떻게 동작하나요?
2. `<meta>`에 대해서 설명해주세요.
3. `<img>`에 alt 속성을 정의해야하는 이유는 무엇인가요?
4. `<span>` 과 `<div>`의 차이는 무엇인가요?
5. 검색엔진에 의해 더 잘 찾게 하려면 어떻게 해야하나요?
6. html5 규격에 대한 주요 목표와 동기는 무엇인가요?
7. text안에 highlight를 넣는 방법은 무엇인가요?
8. 문자 인코딩이란?
9. HTML `<small>`은 언제 사용되나요?
10. 표준모드와 쿼크모드에 대해서 설명해주세요.
11. 여러 언어로 되어 있는 콘텐츠의 페이지를 어떻게 제공하나요?
12. 다국어 사이트를 디자인하거나 개발할 때 주의해야할 사항은 무엇인요?
13. `<script>`, `<script async>`, `<script defer>` 사이의 차이점을 설명하세요.
14. rel= "noopener", "nofollow", "noreferrer" 은 언제 어디에 사용되나요?
15. WebSQL이란 무엇인가요?
16. DOCTYPE은 무엇을 하나요?
17. cookie, sessionStorage, localStorage 사이의 차이점을 설명하세요.
18. DOM이란 무엇인가요?
19. DOM과 HTML의 차이점은 무엇인가요?
20. `<header>` `<section>` `<article>` `<aside>` `<nav>` `<footer>`의 적절한 사용법은 무엇인가요?
21. data-속성은 무엇에 좋은가요?
22. HTML5를 개방형 웹 플랫폼으로 간주할 때, HTML5의 구성 요소는 무엇인가요?
23. `<main>`의 주요 목적은 무엇인가요?
24. HTML5 에서 시맨틱 태그를 사용하는 이유에 대해서 설명하세요.
25. 시멘틱 웹이란 무엇인지 설명하세요.
26. 왜 일반적으로 CSS `<link>` 태그를 `<head></head>` 태그 사이에 위치시키고, JS `<script>` 태그를 `</body>` 직전에 위치시키는 것이 좋은 방법인가요? 다른 예외적인 상황을 알고있나요?
27. 프로그레시브 렌더링이 무엇인가요?
28. 이미지 태그에 srcset 속성을 사용하는 이유는 무엇인가요? 이 속성의 컨텐츠를 실행할 때 브라우저의 프로세스를 설명하세요.
29. 이전에 HTML templating 언어를 사용해본 경험이 있나요?
30. `<canvas>`와`<svg>` 중 어떤 것을 선택할 것인가요?
31. Indexed DB는 무엇인가요?

## 질문 및 답변

### Q1. `<iframe>`이란 무엇이고 어떻게 동작하나요?

<details>
<summary>Answer</summary>

`<iframe>`은 현재 웹페이지에 다른 웹페이지의 문서를 불러와서 삽입하는 태그입니다.

```html
<iframe src="삽입할 페이지 주소" width="너비" height="높이"></iframe>
```

하지만 `<iframe>`은 사용하지 않는 것이 좋습니다.

이유는 아래와 같습니다.

1. 반응협 웹사이트를 구축할 때 불편합니다.
2. 웹 접근성의 저해 요인이 됩니다.

</details>

### Q2. `<meta>`에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

`<meta>`는 문서의 정보를 담고있는 태그입니다.

검색엔진에 의해 검색되는 단어를 지정할 수 있습니다.

```html
<meta name="keyword" content="검색되는 단어" />
```

검색 결과에 표시되는 문자를 지정할 수 있습니다.

```html
<meta name="description" content="검색 결과에 표시되는 단어" />
```

검색 엔진에 의한 검색을 피할 수 있습니다.

- noindex : 웹 크롤러가 수집을 할 때 index 하지 않도록 하는 작업
- nofollow : 웹 크롤러가 수집을 할 때 문서에 링크된 다른 문서를 긁어가는 것을 건너뛴다.

```html
<meta name="robots" content="noindex, nofollow" />
```

</details>

### Q3. `<img>`에 alt 속성을 정의해야하는 이유는 무엇인가요?

<details>
<summary>Answer</summary>

이미지가 렌더링 되지 않았을 때 어떠한 이미지인지 정보를 알려주기 위함입니다.

검색 엔진은 이미지에 대한 정보를 `alt` 속성을 참조합니다.

시각 장애인을 위해 사용되는 스크린리더는 `alt`속성을 읽어줍니다.

</details>

### Q4. `<span>` 과 `<div>`의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

차이는 **element, margin, width, height** 가 있습니다.

`<span>`은 아래와 같습니다.

- inline 요소입니다.
- margin은 좌,우 만 적용됩니다.
- width, height 값이 무시됩니다.

`<div>`은 아래와 같습니다.

- block 요소입니다.
- margin은 상, 하, 좌, 우 적용됩니다.
- width, height 값에 영향을 받습니다.

</details>

### Q5. 검색엔진에 의해 더 잘 찾게 하려면 어떻게 해야하나요?

<details>
<summary>Answer</summary>

`<meta>` 속성에 `keyword`, `description`을 추가하면 됩니다.

```html
<meta name="keyword" content="검색되는 단어" />
<meta name="description" content="검색 결과에 표시되는 단어" />
```

</details>

### Q6. html5 규격에 대한 주요 목표와 동기는 무엇인가요?

<details>
<summary>Answer</summary>

1. 구체적인 문맥요소 : 시멘틱 태그를 사용하여 태그를 구체화한다.
2. 서버와의 연결 : socket등을 이용하여 서버와의 통신을 한다.
3. 오프라인과 저장소 : localStorage, sessionStorage 등
4. 2D/3D 그래픽 효과 : `<canvas>`
5. 멀티미디어 기능 향상 : `<audio>`
6. 다양한 입출력 기능 추가

</details>

### Q7. text안에 highlight를 넣는 방법은 무엇인가요?

<details>
<summary>Answer</summary>

방법은 2가지가 있습니다

1. `<mark>` 를 사용하는 방법

```html
<mark>하이라트를 할 문자입니다.</mark>
```

2. css를 이용하는 방법

```html
<span style="background:yellow">하이라트를 할 문자입니다.</span>
```

</details>

### Q8. 문자 인코딩이란?

<details>
<summary>Answer</summary>

HTML 페이지를 올바르게 렌더링하기 위해 **웹브라우저에게 사용할 문자열을 알려주는 것**입니다.

```html
<meta charset="UTF-8" />
```

</details>

### Q9. HTML `<small>`은 언제 사용되나요?

<details>
<summary>Answer</summary>

`<small>`은 저작권, 회사소개, 약관 등에 사용됩니다.

</details>

### Q10. 표준모드와 쿼크모드에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

웹 브라우저는 **표준모드와 쿼크모드** 두 가지 렌더링 모드가 있습니다.

브라우저는 선언된 **DOCTYPE**에 따라 렌더링할 모드를 결정하는데 이를 **doctype switching**이라고합니다.

표준모드는 하위호환성을 배재하고 현재 표준 형식만을 인정하는 렌더링 모드입니다.

쿼크모드는 하위호한성을 유지하기위해 현재 표준에 어긋나는 형식을 지원하는 렌더링 모드입니다.

</details>

### Q11. 여러 언어로 되어 있는 콘텐츠의 페이지를 어떻게 제공하나요?

<details>
<summary>Answer</summary>

1. 클라이언트는 헤더에 `accept-language` 속성을 이용하여 기본 언어에 대한 설정 정보를 서버로 요청합니다.

2. 응답받은 서버는 이 정보를 사용하여 해당 언어가 제공 가능한 경우, 클라이언트로 해당 언어 버전의 문서를 반환합니다.

3. 클라이언트는 반환된 문서를 보여줍니다.

</details>

### Q12. 다국어 사이트를 디자인하거나 개발할 때 주의해야할 사항은 무엇인요?

<details>
<summary>Answer</summary>

1. html lang 속성을 사용합니다.
2. 국가/언어를 쉽게 변경할 수 있도록 디자인합니다.
3. 날짜와 통화 형식을 고려합니다.
4. 텍스트를 포함한 이미지를 사용하지 않습니다.
5. 국가마다 단어를 표현하는 글자 수를 고려하여 레이아웃이 깨지지 않도록 디자인합니다.

</details>

### Q13. `<script>`, `<script async>`, `<script defer>` 사이의 차이점을 설명하세요.

<details>
<summary>Answer</summary>

`<script>`는 HTML 파싱을 중단하고 스크립트를 실행한다. 실행이 완료되면 HTML 파싱을 재시작합니다.

`<script async>`는 HTML과 Script를 비동기적으로 가져오며, 실행이 가능할 때 즉시 실행됩니다.

스크립트가 다른 페이지의 스크립트들과 독립적일 때 사용하면 좋습니다.

`<script defer>`는 `<script async>`와 같이 HTML과 Script를 비동기적으로 가져오지만, 페이지가 모두 로드된 후에 실행됩니다.

</details>

### Q14. rel= "noopener", "nofollow", "noreferrer" 은 언제 어디에 사용되나요?

<details>
<summary>Answer</summary>

`noopener`은 보안을 위한 속성입니다.

`target = _blank`인 링크를 클릭하면 새 탭에서 페이지가 열립니다.

이 때 열린 쪽에서 자바스크립트를 이용(`window.opener`)하면 window 객체에 접근할 수 있게 됩니다. 이러한 접근으로 인하여 악의적으로 사용되는 것을 방지하기 위해 쓰입니다.

`nofollow`은 검색 엔진이 해당 링크를 크롤링하지 않기 위한 속성입니다.

일반적으로 댓글 또는 포럼의 링크에서 사용됩니다.

`noreferrer`은 현재 요청이 어디에서 왔는지 감추는 속성입니다.

요청을 받는 쪽에서 해당 요청이 어디에서 왔는지를 알 필요가 없을 때 사용됩니다.

</details>

### Q15. WebSQL이란 무엇인가요?

<details>
<summary>Answer</summary>

WebSQL 구조적이고 체계화된 관계형 데이터를 저장하는데 쓰이는 DB입니다.

현재는 독립 구현체의 부족으로 인해 사용되지 않습니다.

</details>

### Q16. DOCTYPE은 무엇을 하나요?

<details>
<summary>Answer</summary>

DOCTYPE은 Document Type의 약자입니다.

DTD(Document Type Definition)을 통해 현재의 웹 문서가 어떠한 HTML 버전으로 작성되어있는지 웹 브라우저에게 전달하는 역할을 합니다.

</details>

### Q17. `cookie`, `sessionStorage`, `localStorage` 사이의 차이점을 설명하세요.

<details>
<summary>Answer</summary>

`cookie`는 클라이언트, 서버에 의해 생성되며 수동으로 만료기간을 설정할 수 있습니다.

`sessionStorage`는 클라이언트에 의해 생성되며 탭을 닫을 때 만료됩니다.

`localStorage`는 클라이언트에 의해 생성되며 영구적으로 보존됩니다.

</details>

### Q18. DOM이란 무엇인가요?

<details>
<summary>Answer</summary>

DOM은 HTML문서에 대한 인터페이스입니다.

- 페이지의 콘텐츠 및 구조와 스타일 접근 및 조작을 할 수 있는 API를 제공합니다.

</details>

### Q19. DOM과 HTML의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

DOM은 HTML을 이용하여 실제로 화면에 나타내는 인터페이스입니다.

- HTML 문서의 내용과 구조 -> 객체모델로 변환 -> 다양한 프로그램에서 사용 방식입니다.

HTML은 최초의 화면을 그릴 때 사용하는 설계도와 비슷합니다.

- 화면에 보이고자하는 모양과 구조를 문서로 단순한 텍스트로 구성하여 만드는 것입니다.

</details>

### Q20. `<header>` `<section>` `<article>` `<aside>` `<nav>` `<footer>`의 적절한 사용법은 무엇인가요?

<details>
<summary>Answer</summary>

`<header>` : 제목

`<section>` : 본문의 종류 (ex: 연애, 뉴스 등과 같은 대분류)

`<article>` : 본문 실질적인 내용

`<aside>` : 본문 이외의 내용

`<nav>` : 메뉴

`<footer>` : 회사소개, 저작권 등

</details>

### Q21. `data-` 속성은 무엇에 좋은가요?

<details>
<summary>Answer</summary>

`data-`는 특정한 데이터를 DOM요소에 저장해두기 위해 사용됩니다.

이전과 같이 hidden으로 태그를 숨겨두고 데이터를 저장할 필요가 없습니다.

그로 인한 장점은 아래와 같습니다.

1. HTML 스크립트가 훨씬 간결해졌습니다.
2. HTML 요소에 여러 `data-`속성을 동시에 사용할 수 있습니다.

요즘에는, `data-` 속성을 사용하는 것을 권장하지 않습니다. 그 이유 중 하나는 사용자가 브라우저의 inspect 기능를 사용하여 데이터 속성을 쉽게 수정할 수 있다는 것입니다.

데이터 모델은 JavaScript 자체에 더 잘 저장되며, 라이브러리나 프레임워크의 데이터 바인딩을 통해 DOM을 업데이트된 상태로 유지하는 것이 더 낫습니다.

</details>

### Q22. HTML5를 개방형 웹 플랫폼으로 간주할 때, HTML5의 구성 요소는 무엇인가요?

<details>
<summary>Answer</summary>

1. 의미 - 콘텐츠를 보다 더 정확하게 설명할 수 있도록 허용합니다.
2. 연결 - 새롭고 혁신적인 방법으로 서버와 통신할 수 있도록 허용합니다.
3. 오프라인과 저장소 - 웹 페이지가 클라이언트 측에서 데이터를 로컬로 저장하여, 오프라인에서보다 효율적으로 작동하도록 허용합니다.
4. 멀티미디어 - 개방형 웹에서 비디오와 오디오를 일급으로 만듭니다.
5. 2D/3D 그래픽과 효과 - 훨씬 다양한 프레젠테이션 옵션을 허용합니다.
6. 성능과 통합 - 컴퓨터 하드웨어의 성능 최적화와 개선으로 더 나은 사용을 제공합니다.
7. 장치 접근 - 다양한 입출력 장치의 사용을 허용합니다.
8. 스타일링 - 사용자가 더 세련된 테마를 사용하게 합니다.

</details>

### Q23. `<main>`의 주요 목적은 무엇인가요?

<details>
<summary>Answer</summary>

`<main>`태그는 해당 문서의 `<body>`요소의 주 콘텐츠를 정의할 때 사용합니다.

단 하나의 `<main>` 요소 만이 존재해야 합니다.

</details>

### Q24. HTML5 에서 시맨틱 태그를 사용하는 이유에 대해서 설명하세요.

<details>
<summary>Answer</summary>

**문서에 의미를 부여하는 행위**로써, 개발자가 의도한 요소의 의미가 명확히 드러납니다.

그 결과 코드의 **가독성을 높이며 유지보수를 쉽게**합니다.

</details>

### Q25. 시멘틱 웹이란 무엇인지 설명하세요.

<details>
<summary>Answer</summary>

웹 문서에 `<meta>` 정보를 추가함으로써 관계와 의미를 부여하고 이를 통해 거대한 데이터베이스를 구축하려고하는 발상입니다.

</details>

### Q26. 왜 일반적으로 CSS `<link>` 태그를 `<head></head>` 태그 사이에 위치시키고, JS `<script>` 태그를 `</body>` 직전에 위치시키는 것이 좋은 방법인가요? 다른 예외적인 상황을 알고있나요?

<details>
<summary>Answer</summary>

`<head>` 안에 `<link>`를 넣는 이유

1. 최적화된 페이지를 구축하기 위한 명세에 포함되어있기 때문입니다.
2. HTML은 DOM을 생성하고 CSS는 CSSOM을 생성합니다. DOM과 CSSOM을 이용하여 `first meaningful paint`를 가능하게 합니다. 이 점진적인 렌더링은 사이트의 성능 점수에서 측정되는 사이트 최적화의 범주입니다.

`</body>` 직전에 `<script>`를 넣는 이유

`<script>`태그는 html파싱을 중단시키고 스크립트를 실행하는 특성이 있습니다.

`<script>`태그를 `</body>` 직전에 위치시킴으로써 전체 문서가 파싱될 때까지 스크립트는 실행되지 않고 이렇게 함으로써 DOM요소를 조작해야하는 코드가 오류가 생기지 않습니다.

대안으로는 `<script defer>`을 이용하는 것입니다.

</details>

### Q27. 프로그레시브 렌더링이 무엇인가요?

<details>
<summary>Answer</summary>

사용자에게 의미있는 컨텐츠를 빠르게 보여주기 위한 성능 향상 기술입니다.

관련 기술로는 아래와 같습니다.

1. 이미지 지연로딩

   페이지의 이미지를 한꺼번에 로딩하지 않습니다.

   JS를 사용하여 사용자가 이미지를 표시하는 페이지 부분으로 스크롤할 때 이미지를 로드할 수 있습니다.

2. 콘텐츠의 우선순위 설정

   브라우저는 중요한 콘텐츠를 먼저 보여주고 중요하지 않은 콘텐츠는 나중에 렌러딩합니다.

</details>

### Q28. 이미지 태그에 srcset 속성을 사용하는 이유는 무엇인가요? 이 속성의 컨텐츠를 실행할 때 브라우저의 프로세스를 설명하세요.

<details>
<summary>Answer</summary>

기기의 디스플레이어의 크기에 따라 다른 이미지를 보여주기 위해서 사용됩니다.

1. 해상도가 레티나(2.x)인 경우 고품질 이미지를 제공함으로써 UX가 향상됩니다.
2. 저사양기기의 경우 저품질 이미지를 제공함으로써 메모리를 절약할 수 있습니다.

`srcset` 속성의 콘텐츠를 실행할 때 브라우저의 프로세스는 아래와 같습니다.

```html
<!-- 이미지의 width : 320px 이라고 가정 -->
<img srcset="small.jpg 500w medium.jpg 1000w large.jpg 2000w" />

<!-- 500/320 : 1.5625 -->
<!-- 1000/320 : 3.125 -->
<!-- 2000/320 : 6.25 -->
```

클라이언트 해상도가 1.x 일 때 1.5625가 가장 작기 때문에 500w인 small.jpg가 선택됩니다.

클라이언트 해상도가 2.x 일 때 브라우저는 최소값에 가장 위로 가까운 해상도를 사용하게 됩니다.

비율값이 2에 가까운 1000w인 medium.jpg가 선택됩니다.

</details>

### Q29. 이전에 HTML templating 언어를 사용해본 경험이 있나요?

<details>
<summary>Answer</summary>

</details>

### Q30. `<canvas>`와`<svg>` 중 어떤 것을 선택할 것인가요?

<details>
<summary>Answer</summary>

작업의 종류에 따라 선택할 것입니다.

`canvas`는 픽셀 기반으로써 고성능 애니메이션이나 동영상 작업을 할 때 선택할 것입니다.

`svg`는 모양 기반으로써 깨지지 않는 특성이 있기 때문에 정적이미지나 인쇄용 고품질 문서 작성을 할 때 선택할 것입니다.

</details>

### Q31. Indexed DB는 무엇인가요?

<details>
<summary>Answer</summary>

**javascript 기반의 객체지향 트랜잭션 데이터베이스 시스템**입니다.

특징은 아래와 같습니다.

1. 키와 값 한쌍으로 저장합니다.
2. 트랜잭션 데이터베이스 모델을 기반으로 만들어졌습니다.
3. 비동기 방식으로 이루어집니다.

</details>
