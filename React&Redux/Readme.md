# React&Redux

## 목차

1. [Virtual DOM이란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q1-virtual-dom%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
2. [Virtual DOM의 동작방식에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q2-virtual-dom%EC%9D%98-%EB%8F%99%EC%9E%91%EB%B0%A9%EC%8B%9D%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
3. [React.JS란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q3-reactjs%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
4. [React의 장점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q4-react%EC%9D%98-%EC%9E%A5%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
5. [React에서 컴포넌트를 어떻게 생성하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q5-react%EC%97%90%EC%84%9C-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%EB%A5%BC-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%83%9D%EC%84%B1%ED%95%98%EB%82%98%EC%9A%94)
6. [왜 Component의 이름은 대문자로 표기해야 하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q6-%EC%99%9C-component%EC%9D%98-%EC%9D%B4%EB%A6%84%EC%9D%80-%EB%8C%80%EB%AC%B8%EC%9E%90%EB%A1%9C-%ED%91%9C%EA%B8%B0%ED%95%B4%EC%95%BC-%ED%95%98%EB%82%98%EC%9A%94)
7. [React에서 `elemen`t와 `component`의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q7-react%EC%97%90%EC%84%9C-element%EC%99%80-component%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
8. [state와 props의 정의와 차이점에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q8-state%EC%99%80-props%EC%9D%98-%EC%A0%95%EC%9D%98%EC%99%80-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
9. [state를 직접 업데이트하면 안되는 이유는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q9-state%EB%A5%BC-%EC%A7%81%EC%A0%91-%EC%97%85%EB%8D%B0%EC%9D%B4%ED%8A%B8%ED%95%98%EB%A9%B4-%EC%95%88%EB%90%98%EB%8A%94-%EC%9D%B4%EC%9C%A0%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
10. [setState에서 callback의 역할은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q10-setstate%EC%97%90%EC%84%9C-callback%EC%9D%98-%EC%97%AD%ED%95%A0%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
11. [this를 바인딩하는 방법은 어떤 것들이 있나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q11-this%EB%A5%BC-%EB%B0%94%EC%9D%B8%EB%94%A9%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%80-%EC%96%B4%EB%96%A4-%EA%B2%83%EB%93%A4%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
12. [ref의 용도는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q12-ref%EC%9D%98-%EC%9A%A9%EB%8F%84%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
13. [`forwardRef`란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q13-forwardref%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
14. [controlled component와 uncontrolled component 에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q14-controlled-component%EC%99%80-uncontrolled-component-%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
15. [createElement와 cloneElement의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q15-createelement%EC%99%80-cloneelement%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
16. [React에서 Lifting State Up은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q16-react%EC%97%90%EC%84%9C-lifting-state-up%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
17. [라이프 사이클 단계와 메소드에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q17-%EB%9D%BC%EC%9D%B4%ED%94%84-%EC%82%AC%EC%9D%B4%ED%81%B4-%EB%8B%A8%EA%B3%84%EC%99%80-%EB%A9%94%EC%86%8C%EB%93%9C%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
18. [props argument와 함께 super constructor를 사용하는 목적은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q18-props-argument%EC%99%80-%ED%95%A8%EA%BB%98-super-constructor%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EB%AA%A9%EC%A0%81%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
19. [`<Fragement>`는 무엇이고 장점에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q19-fragement%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B4%EA%B3%A0-%EC%9E%A5%EC%A0%90%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
20. [componentWillMount에서 setState를 사용하는게 좋나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q20-componentwillmount%EC%97%90%EC%84%9C-setstate%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94%EA%B2%8C-%EC%A2%8B%EB%82%98%EC%9A%94)
21. [React에서 context는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q21-react%EC%97%90%EC%84%9C-context%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
22. [React에서 `portal`은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q22-react%EC%97%90%EC%84%9C-portals%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
23. [CRA는 무엇이고 사용함으로써 이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q23-cra%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B4%EA%B3%A0-%EC%82%AC%EC%9A%A9%ED%95%A8%EC%9C%BC%EB%A1%9C%EC%8D%A8-%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
24. [Switching Component란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q24-switching-component%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
25. [React Fiber란 무엇이고 주요 목표에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q24-switching-component%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
26. [list에서 `key`를 사용했을 때의 이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q26-list-%EC%97%90%EC%84%9C-key%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%96%88%EC%9D%84-%EB%95%8C%EC%9D%98-%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
27. [React DOM의 `render()` 메서드의 목적은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q27-react-dom%EC%9D%98-render%EB%A9%94%EC%84%9C%EB%93%9C%EC%9D%98-%EB%AA%A9%EC%A0%81%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
28. [constructor에서 setState를 사용하면 무슨일이 생기나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q28-constructor%EC%97%90%EC%84%9C-setstate%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%A9%B4-%EB%AC%B4%EC%8A%A8%EC%9D%BC%EC%9D%B4-%EC%83%9D%EA%B8%B0%EB%82%98%EC%9A%94)
29. [조건에 따른 component 렌더링은 어떻게 해야하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q29-%EC%A1%B0%EA%B1%B4%EC%97%90-%EB%94%B0%EB%A5%B8-component-%EB%A0%8C%EB%8D%94%EB%A7%81%EC%9D%80-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%ED%95%98%EB%82%98%EC%9A%94)
30. [Server Side Rendering(SSR) 을 어떻게 구현하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q30-server-side-renderingssr-%EC%9D%84-%EC%96%B4%EB%96%BB%EA%B2%8C-%EA%B5%AC%ED%98%84%ED%95%98%EB%82%98%EC%9A%94)
31. [왜 Reacat에서 props를 update 할 수 없나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q31-%EC%99%9C-reacat%EC%97%90%EC%84%9C-props%EB%A5%BC-update-%ED%95%A0-%EC%88%98-%EC%97%86%EB%82%98%EC%9A%94)
32. [어떻게 페이지 로드시에 input element 에 focus 하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q32-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%8E%98%EC%9D%B4%EC%A7%80-%EB%A1%9C%EB%93%9C%EC%8B%9C%EC%97%90-input-element-%EC%97%90-focus-%ED%95%98%EB%82%98%EC%9A%94)
33. [state의 object 를 update 할 수 있는 방법은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q33-state%EC%9D%98-object-%EB%A5%BC-update-%ED%95%A0-%EC%88%98-%EC%9E%88%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
34. [어떻게 매 초 마다 component 를 업데이트 하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/React%26Redux#q34-%EC%96%B4%EB%96%BB%EA%B2%8C-%EB%A7%A4-%EC%B4%88-%EB%A7%88%EB%8B%A4-component-%EB%A5%BC-%EC%97%85%EB%8D%B0%EC%9D%B4%ED%8A%B8-%ED%95%98%EB%82%98%EC%9A%94)

## 질문 및 답변

### Q1. Virtual DOM이란 무엇인가요?

<details>
<summary>Answer</summary>

실제 DOM의 가벼운 사본과 비슷합니다.

Virtual DOM을 사용하면 실제 DOM에 접근하여 조작하지 않고, DOM을 추상화 한 자바스크립트 객체를 구성하여 사용합니다.

</details>

### Q2. Virtual DOM의 동작방식에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

1. 브라우저에서 변경이 일어나면 전체 UI를 Virtual DOM에 리렌더링합니다.
2. 변경되기전 실제 DOM과 새로 변경된 Virtual DOM을 비교합니다.
3. 바뀐 부분만 실제 DOM에 업데이트합니다.

</details>

### Q3. React.JS란 무엇인가요?

<details>
<summary>Answer</summary>

SPA를 구현하는데 있어 VIEW에 집중되어있는 자바스크립트 오픈소스 라이브러리입니다.

</details>

### Q4. React의 장점은 무엇인가요?

<details>
<summary>Answer</summary>

1. Virtual DOM을 이용하기때문에 DOM의 부담을 줄여준다.
2. SSR를 지원합니다.
3. UI 구성 요소를 재사용할 수 있도록 개발할 수 있습니다.
4. Jest 와 같은 도구를 사용하여 단위 및 통합테스트를 쉽게 작성할 수 있습니다.

</details>

### Q5. React에서 컴포넌트를 어떻게 생성하나요?

<details>
<summary>Answer</summary>

방법은 2가지가 있습니다.

1. class components

```jsx
class Test extends Component {
  construtor(props) {
    super(props);
  }

  render() {
    return <div>컴포넌트 형입니다. {props.message}</div>;
  }
}
```

2. function components

```jsx
function Test(props) {
  return <div>함수형입니다. {props.message}</div>;
}
```

</details>

### Q6. 왜 Component의 이름은 대문자로 표기해야 하나요?

<details>
<summary>Answer</summary>

Component 들은 **DOM element가 아니기 때문에 대문자 표기가 필요**합니다.

component들은 constructors입니다. 또한 JSX 에서의 소문자 태그 이름은 component가 아닌 HTML 요소를 나타내기 때문입니다.

</details>

### Q7. React에서 `element`와 `component`의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

element는 화면에 표시할 내용을 가지는 객체입니다.

component는 element를 반환하는 함수 또는 클래스입니다.

</details>

### Q8. state와 props의 정의와 차이점에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

state는 **components의 lifecycle 동안 변경될 수 있는 정보를 가지고 있는 객체**입니다.

props는 **components에 전달되는 값을 포함하는 단일 값 또는 객체**입니다.

- 부모 **component에서 자식 component로 전달되는 데이터**입니다.

state와 props는 **기능면에서 차이**가 있습니다.

- state는 component안에서 관리되고 사용할 변수 선언과 비슷합니다.
- props는 함수 매개변수와 같이 component 요소로 전달됩니다.

</details>

### Q9. state를 직접 업데이트하면 안되는 이유는 무엇인가요?

<details>
<summary>Answer</summary>

state를 직접 업데이트 하면 **component는 리렌더링을 실시**하지 않습니다.

```jsx
// Wrong!!
this.state.message = "Hello world";
```

state를 업데이트 하려면 `setState()` 메소드를 이용해야합니다.

```jsx
// Good!!
setState({
  message: "Hello world",
});
```

</details>

### Q10. setState에서 callback의 역할은 무엇인가요?

<details>
<summary>Answer</summary>

callback 함수는 setState가 끝난 후 그리고 component가 리렌더링된 후에 호출됩니다.

- setState는 비동기적으로 동작합니다.
- callback 함수는 모든 작업이 마무리된 후 사용됩니다.

```jsx
setState({ name: "John" }, () =>
  console.log("The name has updated and component re-rendered")
);
```

**callback 함수를 이용하는 것보단 lifecycle 메서드를 이용하는 것이 좋습니다.**

</details>

### Q11. this를 바인딩하는 방법은 어떤 것들이 있나요?

<details>
<summary>Answer</summary>

3가지 방법이 있습니다.

#### 1. 생성자에서의 바인딩

- JS 의 Class 에서 메서드는 기본적으로 바인딩 되지 않습니다.
- 클래스 메서드로 지정된 React의 event handlers 에서도 마찬가지 입니다.
- 일반적으로 다음과같이 constructor 바인딩합니다.

```jsx
constructor(props) {
  super(props);
  this.handleClick = this.handleClick.bind(this);
}

handleClick() {
  // Perform some logic
}
```

#### 2. 공통 클래스 필드 구문

- 생성자에서의 바인딩 방법을 원하지 않는다면, 공용 클래스 필드 구문을 이용하여 callback 을 올바르게 바인딩할 수 있습니다.

```jsx
handleClick = () => {
  console.log("this is:", this);
};

<button onClick={this.handleClick}> Click me </button>;
```

#### 3. 화살표함수를 이용한 바인딩

- 아래와 같이 바로 화살표 함수를 이용하여 바인딩 해줄 수 있습니다.

```jsx
<button onClick={(e) => this.handleClick(e)}>Click me</button>
```

</details>

### Q12. ref의 용도는 무엇인가요?

<details>
<summary>Answer</summary>

DOM의 요소나 컴포넌트에 직접 접근해야 될 경우 사용됩니다.

</details>

### Q13. `forwardRef`란 무엇인가요?

<details>
<summary>Answer</summary>

`forwardRef`는 ref를 받아 자식 컴포넌트에게 전달하는 기능입니다.

```jsx
const ButtonElement = React.forwardRef((props, ref) => (
  <button ref={ref} className="CustomButton">
    {props.children}
  </button>
));

// Create ref to the DOM button:
const ref = React.createRef();
<ButtonElement ref={ref}>{"Forward Ref"}</ButtonElement>;
```

</details>

### Q14. controlled component와 uncontrolled component 에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

controlled components는 **입력 요소를 제어**하는 component입니다.

모든 상태 변경에는 연관된 handler funciton 이 있습니다.
예를 들어, 이름을 대문자로 쓰려면 아래 handleChange을 이용할 수 있습니다.

```javascript
handleChange(event) {
  this.setState({value: event.target.value.toUpperCase()})
}
```

uncontrolled components는 **내부적으로 자기 자신의 state를 가지고** 있는 component입니다.

현재 필요한 값을 찾기 위해 `ref`를 사용하여 DOM query를 할 수 있습니다. 이것은 전통적인 HTML 과 비슷합니다.

```javascript
class UserProfile extends React.Component {
  constructor(props) {
    super(props);
    this.handleSubmit = this.handleSubmit.bind(this);
    this.input = React.createRef();
  }

  handleSubmit(event) {
    alert("A name was submitted: " + this.input.current.value);
    event.preventDefault();
  }

  render() {
    return (
      <form onSubmit={this.handleSubmit}>
        <label>
          {"Name:"}
          <input type="text" ref={this.input} />
        </label>
        <input type="submit" value="Submit" />
      </form>
    );
  }
}
```

</details>

### Q15. createElement와 cloneElement의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

createElement는 UI에 나타낼 요소를 생성할 때 사용합니다.

cloneElement는 요소를 복사하고 요소에 새로운 props를 전달하는데 사용합니다.

</details>

### Q16. React에서 Lifting State Up은 무엇인가요?

<details>
<summary>Answer</summary>

여러 component 들이 동일한 변경 데이터를 공유해야하는 경우 가까운 부모 component 로 state를 올리는 것입니다.

즉, 두개의 자식 component가 부모의 있는 동일한 데이터를 공유할 때 두개의 자식 component 들은 부모로 state를 올리는 대신 local state를 유지해야합니다.

예를 들면, 값을 입력받으면 섭씨 -> 화씨, 화씨 -> 섭씨로 변경하는 프로그램을 짤 때 유용합니다.

</details>

### Q17. 라이프 사이클 단계와 메소드에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

</details>

### Q18. props argument와 함께 super constructor를 사용하는 목적은 무엇인가요?

<details>
<summary>Answer</summary>

**자식 클래스의 constructor 는 super() 메서드가 호출되기 전까지 this 참조 사용할 수 없습니다.**

super()에 props를 파라미터로 전달하는 이유는 자식 constructors에서 this.props로 접근하기 위해서입니다.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props);

    console.log(this.props); // Prints { name: 'sudheer',age: 30 }
  }
}
```

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super();

    console.log(this.props); // Prints undefined

    // But Props parameter is still available
    console.log(props); // Prints { name: 'sudheer',age: 30 }
  }

  render() {
    // No difference outside constructor
    console.log(this.props); // Prints { name: 'sudheer',age: 30 }
  }
}
```

</details>

### Q19. `<Fragement>`는 무엇이고 장점에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

`<Fragement>`는 여러 컴포넌트를 반환하는데 사용되는 일반적인 패터입니다.

장점은 아래와 같습니다.

- DOM 노드를 생성하지 않기 때문에 `<div>`에 비해 메모리가 절약됩니다.
- flex, grid와 같은 레이아웃을 짤 때 좀 더 유연합니다.

```jsx
<Fragement>
  <A_Component />
  <B_Component />
  <C_Component />
</Fragement>
```

</details>

### Q20. componentWillMount에서 setState를 사용하는게 좋나요?

<details>
<summary>Answer</summary>

`componentWillMount` 안에서는 **리렌더링이 되지않기 때문에** 비동기적 초기화는 피하는게 좋습니다.

사용하려면 `componentDidMount`에서 사용해야합니다.

</details>

### Q21. React에서 context는 무엇인가요?

<details>
<summary>Answer</summary>

Context는 모든 레벨에 수동으로 props를 전달하지 않고 component tree를 통해 데이터를 전달할 수 있도록 제공해줍니다.

예를 들어, 인증된 유저, locale 설정, UI 테마는 많은 application 들에서 접근해야합니다.

```jsx
const { Provider, Consumer } = React.createContext(defaultValue);
```

</details>

### Q22. React에서 portals은 무엇인가요?

<details>
<summary>Answer</summary>

portals은 상위 Component 의 DOM 계층 구조 외부에 존재하는 DOM 노드로 자식을 render 하는데 권장되는 방법입니다.

```jsx
// child : element, 문자열 등 모든 종류
// container : DOMElement
ReactDOM.createPortal(child, container);
```

</details>

### Q23. CRA는 무엇이고 사용함으로써 이점은 무엇인가요?

<details>
<summary>Answer</summary>

CRA는 Create-React-App CLI의 약자입니다.

CRA를 사용함으로써 쉽고 빠르게 리액트 애플리케이션을 생성할 수 있습니다.

```
npm install -g create-react-app
```

</details>

### Q24. Switching Component란 무엇인가요?

<details>
<summary>Answer</summary>

switching component는 여러 component 중 하나를 렌더링 하는 component 입니다.

- props 값을 매핑하기 위해 object를 사용해야합니다.

```jsx
import HomePage from "./HomePage";
import AboutPage from "./AboutPage";
import ServicesPage from "./ServicesPage";
import ContactPage from "./ContactPage";

const PAGES = {
  home: HomePage,
  about: AboutPage,
  services: ServicesPage,
  contact: ContactPage,
};

const Page = (props) => {
  const Handler = PAGES[props.page] || ContactPage;

  return <Handler {...props} />;
};
```

</details>

### Q25. React Fiber란 무엇이고 주요 목표에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

React Fiber란 React v16 이후 새로운 재조정 알고리즘입니다.

React Fiber의 목표는 아래와 같습니다.

- 애니메이션, 레이아웃, 제스처등의 성능을 높이는 것입니다.
- 렌더링 작업을 청크로 쪼개고 여러 프레임으로 분산 시키는 것입니다.
</details>

### Q26. list 에서 key를 사용했을 때의 이점은 무엇인가요?

<details>
<summary>Answer</summary>

`Key`는 목록을 만들때 포함시켜야하는 특수한 속성입니다.

`Key`는 목록의 변경사항, 추가 또는 제거된 항목을 분별할 수 있도록 도와줍니다.

예를 들어, 데이터의 키를 자주 목록의 `Key`로 사용합니다.

```jsx
const todoItems = todos.map((todo) => <li key={todo.id}>{todo.text}</li>);
```

렌더링 된 목록에 안정적인 ID가 없을 경우 마지막 수단으로 index 값을 이용할 수 있습니다.

```jsx
const todoItems = todos.map((todo, index) => <li key={index}>{todo.text}</li>);
```

항목 순서가 변경 될 가능성이 있는 경우 index를 이용하는 것은 좋지 않습니다.

- 성능에 부정적인 영향을 미치고 component state에 문제가 발생할 수 있습니다.

list를 별도의 component로 뽑아 사용하는 경우 `<li>`태그 대신 list component 요소에 key를 적용해야 합니다.

</details>

### Q27. React DOM의 render메서드의 목적은 무엇인가요?

<details>
<summary>Answer</summary>

render 메서드는 제공된 컨테이너의 DOM에 React element를 render하고 Component에 대한 참조를 반환하는데 사용됩니다.

React element가 이전에 렌더링 되었다면 update 를 수행하고 최근의 변경사항을 반영하기 위해 필요에 따라 DOM을 변경합니다.

```jsx
ReactDOM.render(element, container[, callback])

```

</details>

### Q28. constructor에서 setState를 사용하면 무슨일이 생기나요?

<details>
<summary>Answer</summary>

`setState()`를 사용할 때 객체 상태가 할당되고 또한 component 와 모든 자식들을 재렌더링합니다.

`Can only update a mounted or mounting component.` 에러가 발생합니다.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props);

    this.state = {
      records: [],
      inputValue: this.props.inputValue,
    };
  }

  render() {
    return <div>{this.state.inputValue}</div>;
  }
}
```

그래서 우리는 this.state 를 사용하여 constructor 내부의 변수를 초기화 해야합니다.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props)

    this.state = {
      record: []
    }
  }

  render() {
    return <div>{this.props.inputValue}</div>
  }
```

</details>

### Q29. 조건에 따른 component 렌더링은 어떻게 해야하나요?

<details>
<summary>Answer</summary>

JSX는 `false` 또는 `undefined` 때는 렌더링하지 않습니다.

- 조건을 사용하여 특정 조건이 `true` 인 경우에만 component의 특정 부분을 렌더링 할 수 있습니다.

```jsx
// 방법1
const MyComponent = ({ name, address }) => (
  <div>
    <h2>{name}</h2>
    {address && <p>{address}</p>}
  </div>
);

// 방법2
const MyComponent = ({ name, address }) => (
  <div>
    <h2>{name}</h2>
    {address ? <p>{address}</p> : <p>{"Address is not available"}</p>}
  </div>
);
```

</details>

### Q30. Server Side Rendering(SSR) 을 어떻게 구현하나요?

<details>
<summary>Answer</summary>

`ReactDOMServer`을 이용합니다.

```jsx
import ReactDOMServer from "react-dom/server";
import App from "./App";

ReactDOMServer.renderToString(<App />);
```

</details>

### Q31. 왜 Reacat에서 props를 update 할 수 없나요?

<details>
<summary>Answer</summary>

React의 철학은 props는 immutable(불변) 이어야하고 top-down (부모 -> 자식) 방식입니다.

부모는 모든 props 값을 자식에게 보낼 수 있지만, 자식은 받은 props 를 변경할 수 없습니다.

</details>

### Q32. 어떻게 페이지 로드시에 input element 에 focus 하나요?

<details>
<summary>Answer</summary>

```jsx
class App extends React.Component {
  componentDidMount() {
    this.nameInput.focus();
  }

  render() {
    return (
      <div>
        <input defaultValue={"Won't focus"} />
        <input
          ref={(input) => (this.nameInput = input)}
          defaultValue={"Will focus"}
        />
      </div>
    );
  }
}

ReactDOM.render(<App />, document.getElementById("app"));
```

</details>

### Q33. state의 object 를 update 할 수 있는 방법은 무엇인가요?

<details>
<summary>Answer</summary>

#### 1. Object.assign() 을 사용

```jsx
const user = Object.assign({}, this.state.user, { age: 42 });
this.setState({ user });
```

#### 2. spread operator 를 사용

```jsx
const user = { ...this.state.user, age: 42 };
this.setState({ user });
```

#### 3. function 을 이용하여 setState() 호출

```jsx
this.setState((prevState) => ({
  user: {
    ...prevState.user,
    age: 42,
  },
}));
```

</details>

### Q34. 어떻게 매 초 마다 component 를 업데이트 하나요?

<details>
<summary>Answer</summary>

`setInterval()`를 사용하여 변경을 트리거해야합니다.

오류 및 메모리 누수를 방지하려면 component unmount 시 타이머를 제거해야합니다.

```jsx
componentDidMount() {
  this.interval = setInterval(() => this.setState({ time: Date.now() }), 1000)
}

componentWillUnmount() {
  clearInterval(this.interval)
}
```

</details>
