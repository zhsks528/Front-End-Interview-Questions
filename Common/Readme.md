# 공통 질문

## 목차

1. 개발자로써의 목표는 무엇인가
2. 개발을 하면서 삶에 바뀐점이 있다면 무엇인가
3. 브라우저의 렌더링 과정에 대해서 상세하게 설명해달라
4. 당신에게 5가지 다른 stylesheet가 있습니다. 어떤 방법으로 사이트에 제공하는 게 가장 효과적일까요?
5. 점진적 향상법(progressive enhancement)과 우아한 성능저하법(graceful degradation)의 차이를 설명하실 수 있습니까?
6. 웹사이트에서 assets/resources를 최적화하는 방법에 관해 설명해주세요.
7. 당신이 프로젝트에 합류했습니다. 근데 그들은 Tab을 이용하고, 당신은 Space를 사용했습니다. 어떻게 하실 건가요?
8. MVC, MVVM 패턴에 대해서 설명해주세요.
9. 표준의 중요성에 관해 설명해주세요.
10. CORS는 무엇의 약자이고 어떤 문제에 대해서 언급하는 것인가요?
11. CORS란? CORS를 해결하기 위한 방법을 아는 대로 모두 설명해 주시고 보통 어떤 방식으로 해결하는지 자주 사용하는 방법 1가지와 함께 실제 해결하신 경험을 공유해 주세요.
12. CSS 애니메이션과 JavaScript 애니메이션의 차이점에 관해 설명해주세요.
13. 페이지 로드 시간을 줄이는 세 가지 방법에 관해서 이야기 해 보세요.
14. 선호하는 개발 환경에 대해 자유롭게 이야기해 주세요.
15. CI/CD란?
16. 버전 관리 시스템은 어떤 것들을 사용해보셨습니까?
17. 당신이 웹 페이지를 만들 때의 과정을 설명해주실 수 있을까요?
18. 브라우저가 한 번에 1개의 도메인에서 내려받는 자원은 몇 개인가요?
19. Restful API에서의 URL과 일반적인 HTTP에서의 URL의 차이는?
20. REST API로 받은 객체와 배열은 보통 어떤 자바스크립트 API나 로직을 이용해서 화면에 맞게 가공을 하는지?
21. ARIA와 screenreader에 대해 설명해주세요. 또 접근성을 지원하는 웹사이트를 어떻게 만드는지에 대해도 설명해주세요.
22. HTTP 0.9 / 1.0의 차이를 말씀해주세요.
23. HTTP 1.1 / 2.0의 차이를 말씀해주세요.
24. SSL 인증서를 설정하는 법에 알려주세요.
25. OOP에 특징에 대해 설명해달라(상속, 캡슐화 등등...)
26. 함수형 프로그래밍(Function Programming)
27. 웹 프로토콜에 대해서 설명해주세요.
28. CSR과 SSR를 설명해주세요.
29. 프런트엔드 성능 최적화란? 프런트엔드 성능 최적화 경험이 있다면 자세하게 설명해달라.
30. “기획 - 디자인 - API 개발 - 프런트엔드 개발”의 서비스 절차에서 프런트엔드 개발자의 역할은 무엇이라고 생각하는지?
31. 자바스크립트 프레임워크를 써봤는지? 써봤다면 어떤 걸 쓰는지? 만약 쓴다면 쓰는 이유와 썼을 때의 장점?
32. 백엔드 개발 경험이 있나요?
33. REST API 구축 경험과 구현 관점에서의 간단한 REST API 설계 방식 설명해 보세요.
34. URI 과 URL의 차이점은?

## 질문 및 답변

### Q. 브라우저의 렌더링 과정에 대해서 상세하게 설명해주세요.

<details>
<summary>Answer</summary>

1. HTML을 파싱하여 DOM 트리를 생성합니다.
2. `<link>`태그를 만나면 CSS를 파싱하여 CSSOM 트리를 생성합니다.
3. DOM트리와 CSSOM트리를 이용하여 Render 트리를 생성합니다.
4. Render 트리를 배치합니다
5. 화면에 보여줍니다.
6. 이 과정 중 `<script>` 태그를 만나게되면 파싱을 중단하고 스크립트를 실행합니다.

</details>

### Q. 당신에게 5가지 다른 stylesheet가 있습니다. 어떤 방법으로 사이트에 제공하는 게 가장 효과적일까요?

<details>
<summary>Answer</summary>

Webpack과 같은 모듈 번들러를 이용하여 하나의 파일로 만든다음 minifying 하여 제공합니다.

</details>

### Q. 점진적 향상법(progressive enhancement)과 우아한 성능저하법(graceful degradation)의 차이를 설명하실 수 있습니까?

<details>
<summary>Answer</summary>

차이점은 **기준을 어디에 맞추느냐** 입니다.

점진적 향상법은 낮은 브라우저에 기준을 맞춰 다양한 테스트를 통해 점진적으로 성능을 개선시키는 방법입니다.

우아한 성능 저하법은 최신 기술에 기준을 두고 낮은 브라우저에서도 작동할 수 있도록 Babel과 같은 컴파일러를 통해 버전을 낮춰가는 방법입니다.

</details>

### Q. 웹사이트에서 assets/resources를 최적화하는 방법에 관해 설명해주세요.

<details>
<summary>Answer</summary>

1. CSS 스프라이트를 이용하여 이미지를 하나의 파일로 만들어 요청 수를 줄입니다.
2. Webpack과 같은 모듈러를 이용하여 의존성을 고려하여 파일의 수를 최대한 줄이고 minifying을 진행하여 최적화시킵니다.
3. CDN을 이용합니다.

</details>

### Q. 당신이 프로젝트에 합류했습니다. 근데 그들은 Tab을 이용하고, 당신은 Space를 사용했습니다. 어떻게 하실 건가요?

<details>
<summary>Answer</summary>

Tab을 이용하는 이유에 대해서 듣고 의견을 제시하되 기존에 사용해온 개발자들에게 맞춰나갈 생각입니다.
다른 방법으로는, vscode는 tab -> space 또는 space -> tab으로 바꿔주는 기능을 이용할 것입니다.

</details>

### Q. MVC 패턴에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

Model, View, Controller로 구성되어 있습니다.

1. Model : 애플리케이션에서 사용되는 데이터와 그 데이터를 처리하는 부분입니다.
2. View : 사용자에게 보여지는 UI부분입니다.
3. Controller : 사용자의 입력을 받고 처리하는 부분입니다.

동작원리는 아래와 같습니다.

1. 사용자의 Actions을 Controller가 입력받습니다.
2. Controller는 사용자의 Action을 확인하고 Model을 업데이트합니다.
3. Controller는 Model을 나타내줄 View를 선택합니다.
4. View는 Model을 이용하여 화면을 보여줍니다.

장점은 보편적으로 널리사용되고 있습니다.

단점은 View와 Model사이의 의존성이 높아 대규모 애플리케이션에서는 복잡하여 유지보수가 어려워질 수 있습니다.

</details>

### Q. MVVM 패턴에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

Model, View, ViewModel로 구성되어 있습니다.

1. Model : 애플리케이션에서 사용되는 데이터와 그 데이터를 처리하는 부분입니다.
2. View : 사용자에게 보여지는 UI부분입니다.
3. ViewModel : View를 표현하기 위해 만든 View를 위한 Model입니다.

동작원리는 아래와 같습니다.

1. 사용자의 Actions은 View를 통해 들어옵니다.
2. View에 Action이 들어오면 Command 패턴으로 ViewModel에 전달합니다.
3. ViewModel은 Model에게 데이터를 요청합니다.
4. Model은 ViewModel에게 요청받은 데이터를 응답합니다.
5. ViewModel은 응답받은 데이터를 가공하여 저장합니다
6. View는 ViewModel과 Data Binding하여 화면에 보여줍니다.

장점은 View와 Model, View와 ViewModel의 의존성이 없습니다.

단점은 ViewModel의 설계가 쉽지 않습니다.

</details>

### Q. 표준의 중요성에 관해 설명해주세요.

<details>
<summary>Answer</summary>

#### 1. 웹 페이지 수정 및 운영 관리에 용이

온라인 콘텐츠의 올바른 구조화와 CSS로 시각 표현을 통일해 제작 부담을 줄입니다.

#### 2. 웹 접근성 향상

여러 브라우저에서 호환이 가능하고, 표준이 정해져 있다보니 대중성을 지닙니다.

#### 3. 다양한 디바이스와 호환

웹 표준으로 제작하면 별도의 웹 페이지 제작 없이 호환 가능합니다.

</details>

### Q. CORS는 무엇의 약자이고 어떤 문제에 대해서 언급하는 것인가요?

<details>
<summary>Answer</summary>

CORS는 Cross-Origin-Resources-Sharing의 약자입니다.

동일 출처 정책(Same-origin Policy)을 위배했을 때 생기는 이슈입니다.

</details>

### Q. CORS를 해결하기 위한 방법을 아는 대로 모두 설명해 주시고 보통 어떤 방식으로 해결하는지 자주 사용하는 방법 1가지와 함께 실제 해결하신 경험을 공유해 주세요.

<details>
<summary>Answer</summary>

#### 1. Django에서 처리하는 방법

`django-cors-headers` 라이브러리를 사용

```python
미들웨어에 'corsheaders.middleware.CorsMiddleware' 를 추가

# 방법 1
CORS_ORIGIN_ALLOW_ALL = True
CORS_ALLOW_CREDENTIALS = True

# 방법 2
CORS_ORIGIN_ALLOW_ALL = True
CORS_ORIGIN-WHITELIST =[
	'허락할 주소',
	...
]
```

#### 2. Node.js에서 처리하는 방법

`cors` 라이브러리를 사용

```javascript
var express = require("express");
var cors = require("cors");
var app = express();

// CORS 생성
app.use(cors());
```

</details>

### Q. CSS 애니메이션과 JavaScript 애니메이션의 차이점에 관해 설명해주세요.

<details>
<summary>Answer</summary>

#### 1. CSS애니메이션

CSS애니메이션은 마우스를 올렸을 때나 메뉴 버튼 전환과 같은 간단한 애니메이션의 경우에 사용됩니다.

장점은 아래와 같습니다.

1. **미디어쿼리를 사용하여 반응형 애플리케이션을 쉽게 구현**할 수 있습니다.
2. 메인 스레드가 아닌 별도의 **컴포지터의 스레드에서 그려지기 때문에 메인 스레드에서 작업하는 JS보다 효율적**입니다.

#### 2. JS애니메이션

JS애니메이션은 CSS보다 무겁고 세밀하게 조정해야하는 애니메이션의 경우에 사용됩니다.

장점은 아래와 같습니다.

1. 요소의 스타일이 변하는 순간마다 제어할 수 있기 때문에 애니메이션의 세밀한 구성이 가능합니다
2. 브라우저 호환성 측면에서 `transition`/`animation` 속성보다 뛰어납니다.

</details>

### Q. 페이지 로드 시간을 줄이는 세 가지 방법에 관해서 이야기 해 보세요.

<details>
<summary>Answer</summary>

#### 1. 이미지 용량을 줄이기

이미지 파일의 요청을 줄이기 위해 스프라이트나 포토샵 등을 이용하여 하나의 파일로 만들어서 이용합니다.

#### 2. 서버로부터 보내는 데이터를 최대한 작게 만들어서 보내주기

개발이 완료된 소스코드의 들여쓰기나 빈 여백공간과 같이 개발자의 가독성을 위한 데이터 부분들을 minifying을 이용하여 제거해줍니다.

#### 3. gzip을 이용한 전송데이터 압축

전송하고자 하는 데이터를 압축시켜서 전송시켜주고 이를 클라이언트가 받아서 압축을 풀어 사용하는 방식입니다.

이 방식은 데이터 크기 자체를 줄여 전송시켜주기 때문에 도착까지 걸리는 시간이 적습니다. 하지만 클라이언트가 압축을 해제후 사용해야 하기 때문에 크기다 다소 작은 데이터를 보낼때는 효율이 좋지 않을 수 있습니다.

</details>

### Q. 선호하는 개발 환경에 대해 자유롭게 이야기해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q. CI/CD란?

<details>
<summary>Answer</summary>

CI는 Continuous Integration 즉, **지속적인 통합**이라는 의미입니다.

어플리케이션의 **새로운 코드 변경 사항이 정기적으로 빌드 및 테스트 되어 공유 레포지토리에 통합되는 것을 의미**합니다.

핵심 목표는 아래와 가틋빈다.

1. 버그를 신속하게 찾아 해결
2. 소프트웨어 품질 개선
3. 새로운 업데이트의 검증 및 릴리즈의 시간을 단축

CD는 Continuous Delivery 혹은 Continuous Depolyment 즉, **지속적인 서비스 제공** 또는 **지속적인 배포**라는 의미입니다.

**개발자의 변경 사항이 레포지토리를 넘어, 고객의 프로덕션(Production) 환경까지 릴리즈 되는 것을 의미합니다.**

</details>

### Q. 버전 관리 시스템은 어떤 것들을 사용해보셨습니까?

<details>
<summary>Answer</summary>

버전 관리 시스템은 SVN과 GIT 등이 있습니다.

SVN의 특성은 아래와 같습니다.

1. 클라이언트/서버 구조로 되어있습니다.
2. commit한 내용에 실수가 있을 시에 다른 개발자에게 바로 영향을 미칩니다.
3. 개발자가 자신만의 version history를 가질 수 없습니다.

   local History를 이용하면 되지만 일시적이고, 버전 관리가 되지 않습니다.

저는 GIT을 이용합니다.

1. fork를 이용하여 저만의 history를 가질 수 있어서, 서버와 독릭접으로 관리가 가능하기 때문입니다.
2. commit한 내용에 실수가 있더라도 바로 서버에 영향을 미치지 않습니다.

</details>

### Q. 당신이 웹 페이지를 만들 때의 과정을 설명해주실 수 있을까요?

<details>
<summary>Answer</summary>

</details>

### Q. 브라우저가 한 번에 1개의 도메인에서 내려받는 자원은 몇 개인가요?

<details>
<summary>Answer</summary>

브라우저마다 다르기는 하지만 평균 6~8개의 리소스를 동시에 받을 수 있습니다.

</details>

### Q. Restful API에서의 URL과 일반적인 HTTP에서의 URL의 차이는?

<details>
<summary>Answer</summary>

</details>

### Q. REST API로 받은 객체와 배열은 보통 어떤 자바스크립트 API나 로직을 이용해서 화면에 맞게 가공을 하는지?

<details>
<summary>Answer</summary>

JSON형식으로 데이터를 어떻게 활용할 것인가에 따라 다르게 활용합니다.

#### 1. `map`

조건없이 정보를 보여줄 때는 `map` API를 사용합니다.

```js
var arr = [1, 2, 3, 4, 5];
var result = arr.map((item) => item + 1);

console.log(result); //[2,3,4,5,6]
```

#### 2. `filter`

정보를 어떠한 조건에 맞게 가공해야할 때 `filter` API를 사용합니다.

```js
var arr = [1, 2, 3, 4, 5];
var result = arr.filter((item) => item > 3);

console.log(result); // [4,5]
```

#### 3. `reduce`

누산기가 필요할 때 `reduce` API를 사용합니다.

```javascript
var arr = [1, 2, 3, 4, 5];
var result = arr.reduce((prev, current, idx, arr) => prev + current);

console.log(result); // 15
```

</details>

### Q. ARIA와 screenreader에 대해 설명해주세요. 또 접근성을 지원하는 웹사이트를 어떻게 만드는지에 대해도 설명해주세요.

<details>
<summary>Answer</summary>

</details>

### Q. HTTP 0.9 / 1.0의 차이를 말씀해주세요.

<details>
<summary>Answer</summary>

#### 1. HTTP 0.9

1. GET Method만 존재합니다
2. 상태 및 오류 코드가 없습니다.
3. 헤더가 없어서 오로지 html문서만 받을 수 있습니다.

#### 2. HTTP 1.0

1. GET, POST, HEAD가 존재합니다. 10
2. 상태 및 오류 코드가 있습니다.
3. 헤더가 존재하여 HTML문서뿐만 아니라 이미지 등도 받을 수 있습니다.

</details>

### Q. HTTP 1.1 / 2.0의 차이를 말씀해주세요.

<details>
<summary>Answer</summary>

가장 큰 차이점은 **속도**입니다.

HTTP 2.0은 특징은 아래와 같습니다.

1. **한 번의 연결로 여러 개의 데이터를 전송**할 수 있습니다.
2. **헤더 정보를 HPACK 압축 방식을 이용하여 압축 전송**합니다.
3. 요청이 커넥션 상에서 다중화되므로 **HOL(Header Of Line) Blocking이 발생하지 않습니다**.

</details>

### Q. SSL 인증서를 적용하는 방법에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

</details>

### Q. OOP에 특징에 대해 설명해달라(상속, 캡슐화 등등...)

<details>
<summary>Answer</summary>

</details>

### Q. 함수형 프로그래밍(Function Programming)

<details>
<summary>Answer</summary>

</details>

### Q. 웹 프로토콜

<details>
<summary>Answer</summary>

</details>

### Q. CSR과 SSR의 차이?

<details>
<summary>Answer</summary>

</details>

### Q. 프런트엔드 성능 최적화란? 프런트엔드 성능 최적화 경험이 있다면 자세하게 설명해달라.

<details>
<summary>Answer</summary>

</details>

### Q. “기획 - 디자인 - API 개발 - 프런트엔드 개발”의 서비스 절차에서 프런트엔드 개발자의 역할은 무엇이라고 생각하는지?

<details>
<summary>Answer</summary>

</details>

### Q. 자바스크립트 프레임워크를 써봤는지? 써봤다면 어떤 걸 쓰는지? 만약 쓴다면 쓰는 이유와 썼을 때의 장점?

<details>
<summary>Answer</summary>

</details>

### Q. 백엔드 개발 경험이 있나요?

<details>
<summary>Answer</summary>

</details>

### Q. REST API 구축 경험과 구현 관점에서의 간단한 REST API 설계 방식 설명해 보세요.

<details>
<summary>Answer</summary>

</details>

### Q. URI 과 URL의 차이점은?

<details>
<summary>Answer</summary>

**URI**은 Uniform Resources Identifier로 **인터넷 상의 자원을 식별할기 위한 문자열의 구성**을 의미합니다.

**URL**은 Uniform Resources Locator로 **인터넷 상의 자원의 위치**를 의미합니다.

URI가 URL에 비해 포괄적인 범위입니다.

</details>
