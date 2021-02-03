# Javascript Interview Questions

## 목차

1. [이벤트 위임에 대해 설명하세요](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q1-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EC%9C%84%EC%9E%84%EC%97%90-%EB%8C%80%ED%95%B4-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
2. [이벤트 버블링에 대해 설명하세요](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q2-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%B2%84%EB%B8%94%EB%A7%81%EC%97%90-%EB%8C%80%ED%95%B4-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
3. [이벤트 캡처링에 대해 설명하세요](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q2-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%B2%84%EB%B8%94%EB%A7%81%EC%97%90-%EB%8C%80%ED%95%B4-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
4. [this가 Javascript에서 어떻게 작동하는 지 설명하세요](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q4-this%EA%B0%80-javascript%EC%97%90%EC%84%9C-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%9E%91%EB%8F%99%ED%95%98%EB%8A%94-%EC%A7%80-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
5. [프로토타입 상속이 어떻게 작동하는지 설명하세요](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q5-%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85-%EC%83%81%EC%86%8D%EC%9D%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%9E%91%EB%8F%99%ED%95%98%EB%8A%94%EC%A7%80-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
6. [AMD vs CommonJS에 대해 어떻게 생각하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q6-amd-vs-commonjs%EC%97%90-%EB%8C%80%ED%95%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%83%9D%EA%B0%81%ED%95%98%EB%82%98%EC%9A%94)
7. [다음이 IIFE로 작동하지 않는 이유를 설명하세요: function foo(){ }();를 IIFE로 만들기 위해서는 무엇을 바꿔야하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q7-%EB%8B%A4%EC%9D%8C%EC%9D%B4-iife%EB%A1%9C-%EC%9E%91%EB%8F%99%ED%95%98%EC%A7%80-%EC%95%8A%EB%8A%94-%EC%9D%B4%EC%9C%A0%EB%A5%BC-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94-function-foo-%EB%A5%BC-iife%EB%A1%9C-%EB%A7%8C%EB%93%A4%EA%B8%B0-%EC%9C%84%ED%95%B4%EC%84%9C%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%84-%EB%B0%94%EA%BF%94%EC%95%BC%ED%95%98%EB%82%98%EC%9A%94)
8. [null, undefined, undeclared의 차이점은 무엇인가요? 어떻게 이 상태들에 대한 확인을 할 것인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q8-null-undefined-undeclared%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%9D%B4-%EC%83%81%ED%83%9C%EB%93%A4%EC%97%90-%EB%8C%80%ED%95%9C-%ED%99%95%EC%9D%B8%EC%9D%84-%ED%95%A0-%EA%B2%83%EC%9D%B8%EA%B0%80%EC%9A%94)
9. [클로저는 무엇이며, 어떻게/왜 사용하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q9-%ED%81%B4%EB%A1%9C%EC%A0%80%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B4%EB%A9%B0-%EC%96%B4%EB%96%BB%EA%B2%8C%EC%99%9C-%EC%82%AC%EC%9A%A9%ED%95%98%EB%82%98%EC%9A%94)
10. [Curry 함수의 예를 들어 줄 수 있나요? 그리고 이 문법은 어떤 이점을 가지고 있나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q10-curry-%ED%95%A8%EC%88%98%EC%9D%98-%EC%98%88%EB%A5%BC-%EB%93%A4%EC%96%B4-%EC%A4%84-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EC%9D%B4-%EB%AC%B8%EB%B2%95%EC%9D%80-%EC%96%B4%EB%96%A4-%EC%9D%B4%EC%A0%90%EC%9D%84-%EA%B0%80%EC%A7%80%EA%B3%A0-%EC%9E%88%EB%82%98%EC%9A%94)
11. [forEach 루프와 map() 루프 사이의 주요 차이점을 설명할 수 있나요? 왜 둘 중 하나를 선택할 것인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q11-foreach-%EB%A3%A8%ED%94%84%EC%99%80-map-%EB%A3%A8%ED%94%84-%EC%82%AC%EC%9D%B4%EC%9D%98-%EC%A3%BC%EC%9A%94-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%84-%EC%84%A4%EB%AA%85%ED%95%A0-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94-%EC%99%9C-%EB%91%98-%EC%A4%91-%ED%95%98%EB%82%98%EB%A5%BC-%EC%84%A0%ED%83%9D%ED%95%A0-%EA%B2%83%EC%9D%B8%EA%B0%80%EC%9A%94)
12. [익명 함수의 일반적인 사용 사례는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q12-%EC%9D%B5%EB%AA%85-%ED%95%A8%EC%88%98%EC%9D%98-%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9D%B8-%EC%82%AC%EC%9A%A9-%EC%82%AC%EB%A1%80%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
13. [호스트 객채와 네이티브(내장, 빌트인) 객체의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q13-%ED%98%B8%EC%8A%A4%ED%8A%B8-%EA%B0%9D%EC%B1%84%EC%99%80-%EB%84%A4%EC%9D%B4%ED%8B%B0%EB%B8%8C%EB%82%B4%EC%9E%A5-%EB%B9%8C%ED%8A%B8%EC%9D%B8-%EA%B0%9D%EC%B2%B4%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
14. [function Person(){}, var person = Person(), var person = new Person() 의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q14-function-person-var-person--person-var-person--new-person-%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
15. [call과 apply의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q15-call%EA%B3%BC-apply%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
16. [Funtion.prototype.bind에 대해 설명하세요](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q16-functionprototypebind%EC%97%90-%EB%8C%80%ED%95%B4-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
17. [언제 document.write()를 사용하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q17-%EC%96%B8%EC%A0%9C-documentwrite%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%82%98%EC%9A%94)
18. [Feature detection, Feature inference의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q18-feature-detection-feature-inference%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
19. [AJAX에 대해 가능한 한 자세히 설명하세요.](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q19-ajax%EC%97%90-%EB%8C%80%ED%95%B4-%EA%B0%80%EB%8A%A5%ED%95%9C-%ED%95%9C-%EC%9E%90%EC%84%B8%ED%9E%88-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
20. [AJAX를 사용하는 것의 장단점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q20-ajax%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EA%B2%83%EC%9D%98-%EC%9E%A5%EB%8B%A8%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
21. [JSONP가 어떻게 동작하는지(그리고 Ajax와 어떻게 다른지)를 설명하세요](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q21-jsonp%EA%B0%80-%EC%96%B4%EB%96%BB%EA%B2%8C-%EB%8F%99%EC%9E%91%ED%95%98%EB%8A%94%EC%A7%80%EA%B7%B8%EB%A6%AC%EA%B3%A0-ajax%EC%99%80-%EC%96%B4%EB%96%BB%EA%B2%8C-%EB%8B%A4%EB%A5%B8%EC%A7%80%EB%A5%BC-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
22. [Javascript 템플릿을 사용한 적이 있나요? 사용해봤다면, 어떤 라이브러리를 사용했나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q22-javascript-%ED%85%9C%ED%94%8C%EB%A6%BF%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%9C-%EC%A0%81%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94-%EC%82%AC%EC%9A%A9%ED%95%B4%EB%B4%A4%EB%8B%A4%EB%A9%B4-%EC%96%B4%EB%96%A4-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%96%88%EB%82%98%EC%9A%94)
23. [호이스팅에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q23-%ED%98%B8%EC%9D%B4%EC%8A%A4%ED%8C%85%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
24. [속성(Attribute)와 속성(Property)의 차이가 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q24-%EC%86%8D%EC%84%B1attribute%EC%99%80-%EC%86%8D%EC%84%B1property%EC%9D%98-%EC%B0%A8%EC%9D%B4%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
25. [내장 Javascript 객체를 확장하는 것이 좋은 생각이 아닌 이유는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q25-%EB%82%B4%EC%9E%A5-javascript-%EA%B0%9D%EC%B2%B4%EB%A5%BC-%ED%99%95%EC%9E%A5%ED%95%98%EB%8A%94-%EA%B2%83%EC%9D%B4-%EC%A2%8B%EC%9D%80-%EC%83%9D%EA%B0%81%EC%9D%B4-%EC%95%84%EB%8B%8C-%EC%9D%B4%EC%9C%A0%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
26. [document load 이벤트와 document DOMContentLoaded 이벤트의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q27-document-load-%EC%9D%B4%EB%B2%A4%ED%8A%B8%EC%99%80-document-domcontentloaded-%EC%9D%B4%EB%B2%A4%ED%8A%B8%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
27. [왜 load 이벤트와 같은 것을 사용하나요? 이 이벤트에는 단점이 있나요? 다른 대안을 알고 있나요? 알고 있다면 왜 그것을 사용할 건가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-%EC%99%9C-load-%EC%9D%B4%EB%B2%A4%ED%8A%B8%EC%99%80-%EA%B0%99%EC%9D%80-%EA%B2%83%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EB%82%98%EC%9A%94-%EC%9D%B4-%EC%9D%B4%EB%B2%A4%ED%8A%B8%EC%97%90%EB%8A%94-%EB%8B%A8%EC%A0%90%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94-%EB%8B%A4%EB%A5%B8-%EB%8C%80%EC%95%88%EC%9D%84-%EC%95%8C%EA%B3%A0-%EC%9E%88%EB%82%98%EC%9A%94-%EC%95%8C%EA%B3%A0-%EC%9E%88%EB%8B%A4%EB%A9%B4-%EC%99%9C-%EA%B7%B8%EA%B2%83%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%A0-%EA%B1%B4%EA%B0%80%EC%9A%94)
28. [==와 ===의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q28-%EC%99%80-%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
29. [JavaScript와 관련하여 same-origin 정책을 설명하세요.](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q29-javascript%EC%99%80-%EA%B4%80%EB%A0%A8%ED%95%98%EC%97%AC-same-origin-%EC%A0%95%EC%B1%85%EC%9D%84-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
30. [왜 Ternary expression이라고 부르고, "Ternary"라는 단어는 무엇을 나타내나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q30-%EC%99%9C-ternary-expression%EC%9D%B4%EB%9D%BC%EA%B3%A0-%EB%B6%80%EB%A5%B4%EA%B3%A0-ternary%EB%9D%BC%EB%8A%94-%EB%8B%A8%EC%96%B4%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%84-%EB%82%98%ED%83%80%EB%82%B4%EB%82%98%EC%9A%94)
31. ["use strict"; 이 무엇인가요? 사용시 장단점이 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-use-strict-%EC%9D%B4-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94-%EC%82%AC%EC%9A%A9%EC%8B%9C-%EC%9E%A5%EB%8B%A8%EC%A0%90%EC%9D%B4-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
32. [일반적으로 웹 사이트의 전역 스코프를 그대로 두고 건드리지 않는 것이 좋은 이유는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-%EC%9D%BC%EB%B0%98%EC%A0%81%EC%9C%BC%EB%A1%9C-%EC%9B%B9-%EC%82%AC%EC%9D%B4%ED%8A%B8%EC%9D%98-%EC%A0%84%EC%97%AD-%EC%8A%A4%EC%BD%94%ED%94%84%EB%A5%BC-%EA%B7%B8%EB%8C%80%EB%A1%9C-%EB%91%90%EA%B3%A0-%EA%B1%B4%EB%93%9C%EB%A6%AC%EC%A7%80-%EC%95%8A%EB%8A%94-%EA%B2%83%EC%9D%B4-%EC%A2%8B%EC%9D%80-%EC%9D%B4%EC%9C%A0%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
33. [SPA가 무엇인지 설명하고 SEO-friendly하게 만드는 방법을 설명하세요.](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-spa%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EC%A7%80-%EC%84%A4%EB%AA%85%ED%95%98%EA%B3%A0-seo-friendly%ED%95%98%EA%B2%8C-%EB%A7%8C%EB%93%9C%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%84-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
34. [Promise와 그 Polyfill에 대한 당신의 경험은 어느 정도인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-promise%EC%99%80-%EA%B7%B8-polyfill%EC%97%90-%EB%8C%80%ED%95%9C-%EB%8B%B9%EC%8B%A0%EC%9D%98-%EA%B2%BD%ED%97%98%EC%9D%80-%EC%96%B4%EB%8A%90-%EC%A0%95%EB%8F%84%EC%9D%B8%EA%B0%80%EC%9A%94)
35. [Callback 대신에 Promise를 사용할 때의 장점과 단점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-callback-%EB%8C%80%EC%8B%A0%EC%97%90-promise%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%A0-%EB%95%8C%EC%9D%98-%EC%9E%A5%EC%A0%90%EA%B3%BC-%EB%8B%A8%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
36. [Polyfill이란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-polyfill%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
37. [JavaScript로 컴파일되는 언어로 JavaScript 코드를 작성하는 경우의 장단점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-javascript%EB%A1%9C-%EC%BB%B4%ED%8C%8C%EC%9D%BC%EB%90%98%EB%8A%94-%EC%96%B8%EC%96%B4%EB%A1%9C-javascript-%EC%BD%94%EB%93%9C%EB%A5%BC-%EC%9E%91%EC%84%B1%ED%95%98%EB%8A%94-%EA%B2%BD%EC%9A%B0%EC%9D%98-%EC%9E%A5%EB%8B%A8%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
38. [JavaScript 코드를 디버깅하기 위해 어떤 도구와 기술을 사용하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-javascript-%EC%BD%94%EB%93%9C%EB%A5%BC-%EB%94%94%EB%B2%84%EA%B9%85%ED%95%98%EA%B8%B0-%EC%9C%84%ED%95%B4-%EC%96%B4%EB%96%A4-%EB%8F%84%EA%B5%AC%EC%99%80-%EA%B8%B0%EC%88%A0%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EB%82%98%EC%9A%94)
39. [오브젝트 속성이나 배열 항목을 반복할 때 사용하는 언어 구문은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-%EC%98%A4%EB%B8%8C%EC%A0%9D%ED%8A%B8-%EC%86%8D%EC%84%B1%EC%9D%B4%EB%82%98-%EB%B0%B0%EC%97%B4-%ED%95%AD%EB%AA%A9%EC%9D%84-%EB%B0%98%EB%B3%B5%ED%95%A0-%EB%95%8C-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EC%96%B8%EC%96%B4-%EA%B5%AC%EB%AC%B8%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
40. [mutable 객체와 immutable 객체 사이의 차이점을 설명하세요.](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-mutable-%EA%B0%9D%EC%B2%B4%EC%99%80-immutable-%EA%B0%9D%EC%B2%B4-%EC%82%AC%EC%9D%B4%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%84-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
41. [동기 함수와 비동기 함수의 차이점을 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-%EB%8F%99%EA%B8%B0-%ED%95%A8%EC%88%98%EC%99%80-%EB%B9%84%EB%8F%99%EA%B8%B0-%ED%95%A8%EC%88%98%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%84-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
42. [이벤트 루프란 무엇인가요? 콜 스택과 태스크 큐의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%A3%A8%ED%94%84%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94-%EC%BD%9C-%EC%8A%A4%ED%83%9D%EA%B3%BC-%ED%83%9C%EC%8A%A4%ED%81%AC-%ED%81%90%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
43. [function foo(){}와 var foo = function(){} 사이에서 foo 사용의 차이에 대해 설명하세요.](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-function-foo%EC%99%80-var-foo--function-%EC%82%AC%EC%9D%B4%EC%97%90%EC%84%9C-foo-%EC%82%AC%EC%9A%A9%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%97%90-%EB%8C%80%ED%95%B4-%EC%84%A4%EB%AA%85%ED%95%98%EC%84%B8%EC%9A%94)
44. [var, let, const를 사용하여 생성된 변수들의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-var-let-const%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC-%EC%83%9D%EC%84%B1%EB%90%9C-%EB%B3%80%EC%88%98%EB%93%A4%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
45. [ES6 클래스와 ES5 함수 생성자의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-es6-%ED%81%B4%EB%9E%98%EC%8A%A4%EC%99%80-es5-%ED%95%A8%EC%88%98-%EC%83%9D%EC%84%B1%EC%9E%90%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
46. [새 화살표 => 함수 문법에 대한 사용 예시를 들 수 있나요? 이 새로운 문법은 다른 함수와 어떻게 다른가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-%EC%83%88-%ED%99%94%EC%82%B4%ED%91%9C--%ED%95%A8%EC%88%98-%EB%AC%B8%EB%B2%95%EC%97%90-%EB%8C%80%ED%95%9C-%EC%82%AC%EC%9A%A9-%EC%98%88%EC%8B%9C%EB%A5%BC-%EB%93%A4-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94-%EC%9D%B4-%EC%83%88%EB%A1%9C%EC%9A%B4-%EB%AC%B8%EB%B2%95%EC%9D%80-%EB%8B%A4%EB%A5%B8-%ED%95%A8%EC%88%98%EC%99%80-%EC%96%B4%EB%96%BB%EA%B2%8C-%EB%8B%A4%EB%A5%B8%EA%B0%80%EC%9A%94)
47. [생성자의 메서드에 화살표 문법을 사용하면 어떤 이점이 있나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q-%EC%83%9D%EC%84%B1%EC%9E%90%EC%9D%98-%EB%A9%94%EC%84%9C%EB%93%9C%EC%97%90-%ED%99%94%EC%82%B4%ED%91%9C-%EB%AC%B8%EB%B2%95%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EB%A9%B4-%EC%96%B4%EB%96%A4-%EC%9D%B4%EC%A0%90%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
48. [고차 함수(higher-order function)의 정의는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q48-%EA%B3%A0%EC%B0%A8-%ED%95%A8%EC%88%98higher-order-function%EC%9D%98-%EC%A0%95%EC%9D%98%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
49. [객체나 배열에 대한 디스트럭쳐링 예시를 들 수 있나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q50-es6-%ED%85%9C%ED%94%8C%EB%A6%BF-%EB%A6%AC%ED%84%B0%EB%9F%B4%EC%9D%80-%EB%AC%B8%EC%9E%90%EC%97%B4%EC%9D%84-%EC%83%9D%EC%84%B1%ED%95%98%EB%8A%94%EB%8D%B0-%EB%A7%8E%EC%9D%80-%EC%9C%A0%EC%97%B0%EC%84%B1%EC%9D%84-%EC%A0%9C%EA%B3%B5%ED%95%A9%EB%8B%88%EB%8B%A4-%EC%9D%B4%EC%97%90-%EB%8C%80%ED%95%9C-%EC%98%88%EB%A5%BC-%EB%93%A4-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94)
50. [ES6 템플릿 리터럴은 문자열을 생성하는데 많은 유연성을 제공합니다. 이에 대한 예를 들 수 있나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q50-es6-%ED%85%9C%ED%94%8C%EB%A6%BF-%EB%A6%AC%ED%84%B0%EB%9F%B4%EC%9D%80-%EB%AC%B8%EC%9E%90%EC%97%B4%EC%9D%84-%EC%83%9D%EC%84%B1%ED%95%98%EB%8A%94%EB%8D%B0-%EB%A7%8E%EC%9D%80-%EC%9C%A0%EC%97%B0%EC%84%B1%EC%9D%84-%EC%A0%9C%EA%B3%B5%ED%95%A9%EB%8B%88%EB%8B%A4-%EC%9D%B4%EC%97%90-%EB%8C%80%ED%95%9C-%EC%98%88%EB%A5%BC-%EB%93%A4-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94)
51. [spread 문법을 사용할 때의 이점은 무엇이며 rest 문법과 다른 점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q52-%ED%8C%8C%EC%9D%BC-%EA%B0%84%EC%97%90-%EC%BD%94%EB%93%9C%EB%A5%BC-%EA%B3%B5%EC%9C%A0%ED%95%98%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%ED%95%98%EB%82%98%EC%9A%94)
52. [파일 간에 코드를 공유하려면 어떻게 해야하나요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q52-%ED%8C%8C%EC%9D%BC-%EA%B0%84%EC%97%90-%EC%BD%94%EB%93%9C%EB%A5%BC-%EA%B3%B5%EC%9C%A0%ED%95%98%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%ED%95%98%EB%82%98%EC%9A%94)
53. [정적 클래스 멤버를 만드는 이유는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q53-%EC%A0%95%EC%A0%81-%ED%81%B4%EB%9E%98%EC%8A%A4-%EB%A9%A4%EB%B2%84%EB%A5%BC-%EB%A7%8C%EB%93%9C%EB%8A%94-%EC%9D%B4%EC%9C%A0%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
54. [JAVA와 Javascript의 다른점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q54-java%EC%99%80-javascript%EC%9D%98-%EB%8B%A4%EB%A5%B8%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
55. [Typescript을 사용해 본 적이 있나요? 어떤지 말씀해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q56-require%EC%99%80-import%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
56. [require와 import의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/blob/master/Javascript/Javascript.md#q56-require%EC%99%80-import%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)

## 질문 및 답변

### Q1. 이벤트 위임에 대해 설명하세요.

<details>
<summary>Answer</summary>

이벤트 위임은 이벤트 버블링 특성을 이용하여 이벤트 리스너를 하위요소에 추가하는 대신 상위요소에 추가하는 기법입니다.

이벤트 위임의 장점으로는 새 요소에 대해 이벤트를 바인딩할 필요가 없습니다.
상위 요소 하나의 단일 핸들러만 필요하기 때문에 메모리 사용공간이 줄어듭니다.

</details>

### Q2. 이벤트 버블링에 대해 설명하세요.

<details>
<summary>Answer</summary>

이벤트 버블링은 특정 요소에서 이벤트가 발생했을 때 해당 이벤트가 상위의 요소들로 전달되어가는 특성입니다.

```javascript
// 1.
addEventListener(type, listener);

// 2.
addEventListener(type, listener, false);
```

</details>

### Q3. 이벤트 캡처링에 대해 설명하세요.

<details>
<summary>Answer</summary>

이벤트 캡처링은 이벤트 버블링과 반대로 최상위 요소에서 이벤트가 발생한 태그를 탐색하는 특성입니다.

```javascript
// 1.
addEventListener(type, listener, { capture: true });

// 2.
addEventListener(type, listener, true);
```

</details>

### Q4. `this`가 Javascript에서 어떻게 작동하는 지 설명하세요.

<details>
<summary>Answer</summary>

1. 함수를 호출할 때 new 키워드를 사용하는 경우, 함수 내부에 있는 this는 완전히 새로운 객체입니다.
2. apply, call, bind가 함수의 호출/생성에 사용되는 경우, 함수 내의 this는 인수로 전달된 객체입니다.
3. obj.method()와 같이 함수를 메서드로 호출하는 경우, this는 함수가 프로퍼티인 객체입니다.
4. 함수가 자유함수로 호출되는 경우, 즉, 위의 조건 없이 호출되는 경우 this는 전역 객체입니다. 브라우저에서는 window 객체입니다. 엄격 모드('use strict') 일 경우, this는 전역 객체 대신 undefined가 됩니다.
5. 위의 규칙 중 다수가 적용되면 더 상위 규칙이 승리하고 this값을 설정합니다.
6. 함수가 ES2015 화살표 함수인 경우 위의 모든 규칙을 무시하고 생성된 시점에서 주변 스코프의 this값을 받습니다.

</details>

### Q5. 프로토타입 상속이 어떻게 작동하는지 설명하세요.

<details>
<summary>Answer</summary>

</details>

### Q6. AMD vs CommonJS에 대해 어떻게 생각하나요?

<details>
<summary>Answer</summary>
두 가지 모두 ES6이전에 모듈 시스템을 구현하는 방식입니다.

AMD는 비동기식으로 동작되며 CSR에 적합하다고 생각합니다.

CommonJS는 동기식으로 동작되며 SSR에 적합하다고 생각합니다.

ES6 이후로는 Import와 Export 키워드를 이용하여 모듈 시스템을 구현할 수 있습니다.

</details>

### Q7. 다음이 IIFE로 작동하지 않는 이유를 설명하세요: function foo(){ }();를 IIFE로 만들기 위해서는 무엇을 바꿔야하나요?

<details>
<summary>Answer</summary>

function foo(){}(); 함수 선언과 동시에 호출이 이루어졌기 때문입니다.

javscript parser는 이 구문을 아래와 같이 해석합니다.

```javascript
function foo(){} // 함수 선언
() 				 // 함수 호출 <-- 호출할 함수의 이름이 지정되지 않았다.

// error : Uncaught SyntaxError: Unexpected token ')'
```

IIFE로 만들기 위한 방법은 총 2가지가 있다.

```javascript
// 1
(function foo() {
  console.log("IIFE 작동");
})()(
  // result : IIFE 작동

  // 1
  function foo() {
    console.log("IIFE 작동");
  }
)();

// result : IIFE 작동
```

IIFE(즉시 함수 호출 표현식)을 사용하는 이유는 private 변수를 생성하기 위함이다.

</details>

### Q8. `null`, `undefined`, `undeclared`의 차이점은 무엇인가요? 어떻게 이 상태들에 대한 확인을 할 것인가요?

<details>
<summary>Answer</summary>

`undeclared`는 변수 선언 조차 되지 않은 상태입니다.

`undefined`는 변수는 선언했지만 값을 할당하지 않은 상태입니다.

```javascript
var foo;
console.log(foo); // undefined
console.log(foo === undefined); // true
console.log(typeof foo === "undefined"); // true

console.log(foo == null); // true. 옳지않습니다. 이렇게 사용하지 마세요.

function bar() {}
var baz = bar();
console.log(baz); // undefined
```

`null`는 변수를 선언하고 `null`이라는 값을 할당한 상태입니다.

```javascript
var foo = null;
console.log(foo === null); // true

console.log(foo == undefined); // true. 옳지않습니다. 이렇게 사용하지 마세요.
```

`undefined`와 `null`의 상태를 확인할 때에는 완전 항등 연산자(===)를 사용하여 확인합니다.

저는 주로 ESLinter를 사용하여 `undeclared` 변수를 참조하는지 확인합니다.

</details>

### Q9. 클로저는 무엇이며, 어떻게/왜 사용하나요?

<details>
<summary>Answer</summary>

**클로저(Closure)**는 자신을 포함하고 있는 외부함수보다 내부함수가 더 오래 유지될 경우 외부 함수 밖에서 내부함수가 호출되었을 때 외부함수의 지역변수에 접근할 수 있는 함수입니다.

클로저를 어떻게 사용하는지 코드로 설명해주세요.

```javascript
function outerFunc() {
  const x = 10;

  function innerFunc() {
    return x + 10;
  }

  return innerFunc;
}
// 함수 outerFunc()를 호출하면 내부 함수 innerFunc가 반환된다
// 함수 outerFunc()의 실행 컨텍스트는 소멸한다.

const inner = outerFunc();

console.log(inner()); // 20
```

클로저를 사용하는 이유는 3가지가 있습니다.

1. **상태 유지** : 현재 상태를 기억하고 변경된 최신의 상태를 유지하기 위해서입니다.
2. **전역변수의 사용을 억제**하기 위해서입니다.
3. **정보 은닉**의 목적이 있습니다.

클로저를 사용할 때에 주의점으로는 **메모리 누수** 를 신경써야 합니다.

</details>

### Q10. Curry 함수의 예를 들어 줄 수 있나요? 그리고 이 문법은 어떤 이점을 가지고 있나요?

<details>
<summary>Answer</summary>

**Curying**은 둘 이상의 매개 변수가 있는 함수가 여러 함수로 분리되는 문법입니다.

이 문법을 사용함으로써 장점은 2가지 정도가 있습니다.

1. 함수의 실행을 마지막 매개 변수가 주어질 때까지 미룰 수 있습니다.
2. 특정 값을 고정한 채 함수 재활용을 할 수 있습니다.

Curry 함수의 예: 3개의 숫자의 합 구하는 함수

```javascript
// 기본 함수
function addDef(x, y, z) {
  return x + y + z;
}

console.log(addDef(2, 3, 5)); // 10

// Currying 함수
function addCurry(x) {
  return function add_2(y) {
    return function add_3(z) {
      return x + y + z;
    };
  };
}

console.log(addCurry(2)(3)(5)); // 10
```

</details>

### Q11. `forEach` 루프와 `map()` 루프 사이의 주요 차이점을 설명할 수 있나요? 왜 둘 중 하나를 선택할 것인가요?

<details>
<summary>Answer</summary>

forEach와 map 사이의 주요 차이점은 **반환 값의 존재 여부**입니다.

forEach는 반환 값이 존재하지 않지만 map은 새로운 배열을 반환합니다.

단순히 배열을 반복해야한다면 `forEach`를 사용할 것이고, 원본 배열을 변경하지 않으면서 새로운 배열을 생성해야한다면 `map`을 사용할 것입니다.

`forEach`
배열의 요소를 순회하면서 각 요소에 대해 Callback를 실행합니다.

```javascript
const array = [1, 2, 3, 4, 5];
const double = array.forEach((num, idx) => {
  // num과 idx를 이용하여 작업을 합니다.
});
console.log(double); // undefined
```

`map`
배열의 요소를 순회하면서 각 요소에 대하여 함수를 호출하고 그 결과를 새 배열에 작성합니다.

```javascript
const array = [1, 2, 3, 4, 5];
const double = array.map((num) => {
  return num * 2;
});

console.log(double); // [2,4,6,8,10]
```

</details>

### Q12. 익명 함수의 일반적인 사용 사례는 무엇인가요?

<details>
<summary>Answer</summary>

1. private한 변수를 생성할 때 사용됩니다.

```javascript
(function () {
  // 코드
})();
```

2. 한 번 사용되거나 다른 곳에서는 사용할 필요가 없는 콜백으로 사용됩니다

```javascript
setTimeout(function () {
  console.log("Hello world!");
}, 1000);
```

3. 함수형 프로그래밍에서 사용됩니다.

```javascript
const arr = [1, 2, 3];
const double = arr.map(function (el) {
  return el * 2;
});
console.log(double); // [2, 4, 6]
```

</details>

### Q13. 호스트 객채와 네이티브(내장, 빌트인) 객체의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

호스트 객체는 `window`, `XMLHTTPRequest`, `HTTPElement` 등의 DOM 노드 객체와 같이 브라우저 환경에서 정의된 객체입니다.

네이티브(내장, 빌트인) 객체는 `String`, `Math`, `Object` 등과 같이 ECMA Script에 명세에 정의된 객체입니다.

</details>

### Q14. `function Person(){}`, `var person = Person()`, `var person = new Person()` 의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

1. function Persion(){}는 Person이라는 함수 선언식입니다.
2. var person = Person()는 person 변수에 Person()을 호출함으로써 반환되는 값을 할당한다는 의미입니다.
3. var person = new Person()는 person 변수에 Person() 함수 객체를 생성하여 할당한다는 의미입니다.

```javascript
function Person(name) {
  this.name = name;
}

var person = Person("John");
console.log(person); // undefined
console.log(person.name); // Uncaught TypeError: Cannot read property 'name' of undefined

var person = new Person("John");
console.log(person); // Person { name: "John" }
console.log(person.name); // "john"
```

</details>

### Q15. `call`과 `apply`의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

call과 apply는 함수를 호출하는데 사용되며, 첫 번째 매개변수는 함수 내에서 `this`의 값으로 사용됩니다.

차이점으로는 두번째 인자를 받는 방식입니다.

`.call`은 두번째 인자를 `,`를 이용하여 받습니다.

`.apply`은 두번째 인자를 `[]`를 이용하여 받습니다.

```javascript
function add(a, b) {
  return a + b;
}

// call 방식
console.log(add.call(this, 2, 3));

// apply 방식
console.log(add.apply(this, [2, 3]));
```

</details>

### Q16. Function.prototype.bind에 대해 설명하세요.

<details>
<summary>Answer</summary>

`Function.prototype.bind` 는 `this`를 임의로 할당 해주는 방법입니다.

`bind()` 메소드는 호출될 때, this 키워드가 주어진 인자 값으로 설정되고, 새로운 함수가 호출될 때, 앞쪽의 매개변수도 자신의 인자를 사용해 미리 순서대로 채워놓은 새로운 함수를 반환합니다.

```javascript
this.x = 9; // 'this' 는 window를 참조합니다.

const module = {
  x: 81,
  getX: function () {
    return this.x;
  },
};

module.getX(); // 81

const retrieveX = module.getX;

retrieveX(); // 9; 전역 범위에 존재하는 x를 가져옵니다.

// bind() 메소드를 이용하여 this를 module의 범위로 할당합니다.
const boundGetX = retrieveX.bind(module);
boundGetX(); // 81
```

</details>

### Q17. 언제 `document.write()`를 사용하나요?

<details>
<summary>Answer</summary>

document.write()는 document.open()에 의해 열린 문서 스트림에 텍스트 문자열을 쓰거나 디버깅할 때 사용됩니다.

`document.write()` 메소드를 실행하면, 웹 페이지 내에 로딩된 모든 데이터를 지우고 자신의 데이터를 출력하는 특성이 있기 때문에 주의해야합니다.

</details>

### Q18. Feature detection, Feature inference의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

기능 검출(Feature detection)

브라우저가 특정 기능을 지원하는지에 따라 다른 코드를 실행하도록 하여, 일부 브라우저에서 항상 오류 대신 무언가 작동하도록 합니다.

```javascript
// GPS 기능을 지원하는지 확인

if ("geolocation" in navigator) {
  // navigator.geolocation를 사용할 수 있습니다
} else {
  // 부족한 기능 핸들링
}
```

기능 추론(Feature inference)

기능 검출과 마찬가지로 기능이 존재하는지 확인한다. 다만, A기능을 지원하면 B기능도 지원할 것이라는 추론 바탕입니다. 추론이 바탕이기 때문에 권장되지 않습니다.

```javascript
// getElementsByTagName가 있다면?
if (document.getElementsByTagName) {
  // getElementById도 있을 것이다.
  element = document.getElementById(id);
}
```

</details>

### Q19. AJAX에 대해 가능한 한 자세히 설명하세요.

<details>
<summary>Answer</summary>

AJAX는 Javascript를 이용한 클라이언트와 서버간의 비동기 통신 기술입니다.

동작방식

1. 사용자가 AJAX가 적용되어있는 기능을 클릭하면, 서버에 AJAX 요청을 보냅니다.
2. 서버는 DB에서 데이터를 가져와서 XML 또는 JSON형식으로 데이터를 보낸다.
3. 클라이언트는 전체 페이지를 변경하는 것이 아닌 일부분만 변경한다.

`XMLHTTPRequest`, `fetch API` 등이 사용되고 있습니다.

</details>

### Q20. AJAX를 사용하는 것의 장단점은 무엇인가요?

<details>
<summary>Answer</summary>

장점

1. 서버의 새로운 컨텐츠를 전체 페이지를 다시로드할 필요 없이 동적으로 변경할 수 있습니다.
2. 스크립트나 스타일 시트는 한 번만 요청하므로 서버 요청을 줄여줍니다.

단점

1. 브라우저에서 javascript가 비활성화된 경우 실행되지 않습니다.
2. 동일 출처 정책(same-origin public) 문제가 발생할 수 있습니다.

</details>

### Q21. JSONP가 어떻게 동작하는지(그리고 Ajax와 어떻게 다른지)를 설명하세요.

<details>
<summary>Answer</summary>

JSON(JSON with Padding)은 HTML의 `<script>` 요소로부터 요청되는 호출안에는 보안상 정책이 적용되지 않는 점을 이용한 우회방법입니다.

동작방식

1. JSONP는 `<script>` 태그를 통해 cross-origin 도메인에 callback 쿼리 매개변수로 요청을 보냅니다.

2. 서버는 callback 함수명으로 데이터를 감싸서 클라이언트로 반환합니다.

3. 클라이언트는 cross-origin domain 으로부터 응답이 수신될 때 함수가 클라이언트에 의해 실행됩니다.

주의점은 서버에서 JSONP Callback을 처리하는 기능을 지원해줘야 합니다..

요즘에는 CORS가 권장되는 접근 방식이며 JSONP는 해킹으로 간주되고 있습니다.

</details>

### Q22. Javascript 템플릿을 사용한 적이 있나요? 사용해봤다면, 어떤 라이브러리를 사용했나요?

<details>
<summary>Answer</summary>

React 라이브러리를 사용해본 경험이 있습니다.

React에서는 JSX 문법을 지원하고 있으며 Javascript에 가깝고 익숙한 특성으로 인해서 배우기 쉬웠습니다.

</details>

### Q23. 호이스팅에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

호이스팅이란 함수 안에 존재하는 선언들을 함수의 유효 범위의 최상단까지 끌어올리는 것입니다.

var 변수/함수의 선언만 끌어올려지며, 할당은 끌어올려지지 않습니다.

코드의 가독성과 유지보수를 위해 `let`, `const` 키워드를 이용하여 호이스팅을 방지합니다.

호이스팅을 알아야하는 이유는 아직까지도 ES6를 지원하지 않는 웹브라우저가 존재하기 때문에 Babel을 이용하여 ES5로 변환해줘야 하기 때문입니다.

```javascript
// 1. 호이스팅 발생 O
console.log(foo); // undefined
var foo = 1;
console.log(foo); // 1

// 자바스크립트 엔진에서 인식하는 법
// var foo;
// console.log(foo);
// foo = 1;
// console.log(foo);

// 2. 호이스팅 발생 X
console.log(bar); // ReferenceError: bar is not defined
let bar = 2;
console.log(bar); // 2
```

</details>

### Q24. 속성(Attribute)와 속성(Property)의 차이가 무엇인가요?

<details>
<summary>Answer</summary>

가장 큰 차이점은 **값이 바뀌느냐** 입니다.

속성(Attribute)은 HTML 태그에 정의되며, 값이 바뀌지 않습니다.

속성(Property)은 DOM 노드에 정의되며, 값이 바뀝니다.

예시 : `<input type="text" value="Hello">`

```javascript
const input = document.querySelector("input");
console.log(input.getAttribute("value")); // Hello
console.log(input.value); // Hello
```

Text안에 'World!'를 입력한다면?

```javascript
// 속성(Attribute)
console.log(input.getAttribute("value")); // Hello

// 속성(Property)
console.log(input.value); // Hello World!
```

</details>

### Q25. 내장 Javascript 객체를 확장하는 것이 좋은 생각이 아닌 이유는 무엇인가요?

<details>
<summary>Answer</summary>

내장 Javascript 객체를 확장하는 것은 prototype에 속성/함수를 추가한다는 것을 의미합니다. 이러한 행위는 참조무결성을 위반하게 됩니다.

해당 prototype을 참조하는 모든 객체에게 영향을 미치게되고 그럼으로 인해 프로그램을 예측할 수 없기 때문입니다.

내장 Javascript 객체를 확장해야하는 유일한 경우는 **Polyfil**을 만들때입니다.

</details>

### Q26. `document load` 이벤트와 `document DOMContentLoaded` 이벤트의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

가장 큰 차이점은 **실행 순서**입니다.

`load` 이벤트는 모든 리소스(스타일시트, 이미지 등)가 로딩되어야 실행됩니다.
`DOMContentLoaded` 이벤트는 스타일시트, 이미지 등 리소스를 기다리지 않으며, DOM이 생성된 후에 실행됩니다.

</details>

### Q27. 왜 load 이벤트와 같은 것을 사용하나요? 이 이벤트에는 단점이 있나요? 다른 대안을 알고 있나요? 알고 있다면 왜 그것을 사용할 건가요?

<details>
<summary>Answer</summary>

`load` 이벤트는 모든 리소스(스타일시트, 이미지, 스크립트 등)가 로드되어야 작동되는 이벤트입니다.

그렇기 때문에 리소스와 관련된 작업을 할 때 사용되어야합니다.

이벤트의 단점으로는 모든 리소스가 로드될때까지 발생하지 않는다는 점입니다.

다른 대안으로는 `DOMContentLoadED` 이벤트가 있으며 페이지의 DOM이 생성된 후에 실행합니다.

초기화 되기 이전에 전체 페이지가 로드될 필요가 없는 경우에 사용된다.

</details>

### Q28. `==`와 `===`의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

가장 큰 차이점은 **타입 변환의 유무** 입니다.

`==`(추상 동등 연산자)는 타입 변환이 동적으로 일어나며 값을 비교합니다.

```javascript
1 == "1"; // true
1 == [1]; // true
1 == true; // true
0 == ""; // true
0 == "0"; // true
0 == false; // true
```

`===`(완전 동등 연산자)는 타입 변환이 일어나지 않고 값을 비교합니다.

```javascript
1 === "1"; // false : number vs string
1 === [1]; // false : number vs object
1 === true; // false : number vs boolean
0 === false; // false : number vs boolean
0 === ""; // false : number vs string
0 === "0"; // false : number vs string
```

개발할 때 완전 동등 연산자를 이용하거나 Typescript를 이용하여 타입에 관한 오류를 방지합니다.

</details>

### Q29. JavaScript와 관련하여 same-origin 정책을 설명하세요.

<details>
<summary>Answer</summary>

동일 출처 정책(same-origin public)은 현재 출처와 다른 출처에서 가져온 리소스에 접근하는 것을 방지하는 중요한 보안 방식입니다.

origin은 프로토콜, 호스트, 포트번호로 조합됩니다.

이 정책은 한 페이지의 악의적인 스크립트가 해당 페이지의 DOM을 통해 다른 웹 페이지의 중요한 데이터에 접근하는 것을 방지합니다.

예시 : 현재 출처 - http://store.company.com/dir/page.html

```
http://store.company.com/dir2/other.html          // 성공
http://store.company.com/dir/inner/another.html   // 성공
https://store.company.com/secure.html             // 실패 : 프로토콜이 다릅니다.
http://store.company.com:81/dir/etc.html          // 실패 : 포트번호가 다릅니다.
http://news.company.com/dir/other.html            // 실패 : 호스트가 다릅니다.
```

</details>

### Q30. 왜 Ternary expression이라고 부르고, "Ternary"라는 단어는 무엇을 나타내나요?

<details>
<summary>Answer</summary>

Ternary expression는 **삼항표현식**이라고 하며 Javascript에서 유일하게 3개의 피연산자를 받을 수 있는 연산자입니다.

보통 if문을 축약할 때 사용합니다.

Tenary는 삼항이라는 뜻을 가지고 있습니다.

```javascript
// 문법 = 조건 ? 참 : 거짓

const number = 10;
const ternary = number > 10 ? "10보다 큽니다." : "10보다 작거나 같습니다.";

console.log(ternary); // 10보다 작거나 같습니다.
```

</details>

### Q31. `"use strict";` 이 무엇인가요? 사용시 장단점이 무엇인가요?

<details>
<summary>Answer</summary>

`use strict`는 전체 스크립트 또는 개별 함수에 **엄격모드**를 실행하기위한 명령어입니다.

장점으로는 전역변수의 생성을 막으며 호이스팅을 방지합니다.

단점으로는 서로 다른 엄격한 모드로 작성된 스크립트를 병합할 때 문제가 발생할 수 있습니다.

</details>

### Q32. 일반적으로 웹 사이트의 전역 스코프를 그대로 두고 건드리지 않는 것이 좋은 이유는 무엇인가요?

<details>
<summary>Answer</summary>

전역 스코프란 어디에서든 접근할 수 있는 스코프이기 때문에 **변수명 또는 함수명이 겹칠수 있고 그 결과 오류가 발생**할 수 있습니다.

**모듈 패턴(IIFE 등)**을 이용하여 전역 스코프를 보호해야합니다.

</details>

### Q33. SPA가 무엇인지 설명하고 SEO-friendly하게 만드는 방법을 설명하세요.

<details>
<summary>Answer</summary>

SPA(Single Page Application)는 서버로부터 완전한 새로운 페이지를 불러오지 않고 현재의 페이지를 동적으로 다시 작성함으로써 사용자와 소통하는 웹 애플리케이션입니다.

SEO 친화적이게 만드는 방법은 아래와 같습니다.

1. Server-side rendering or Prerendering 적용
2. SEO 친화적 URLs 설정

</details>

### Q34. Promise와 그 Polyfill에 대한 당신의 경험은 어느 정도인가요?

<details>
<summary>Answer</summary>

Proimise는 비동기 처리를 위한 하나의 패턴입니다.

상태로는 3가지가 있습니다.

1. pending : 비동기 처리가 아직 수행되지 않은 상태
2. fulfilled : 비동기 처리가 수행된 상태 (성공)
3. rejected : 비동기 처리가 수행된 상태 (실패)

```javascript
const $result = document.querySelector(".result");
const render = (content) => {
  $result.textContent = JSON.stringify(content, null, 2);
};

const promiseAjax = (method, url, payload) => {
  return new Promise((resolve, reject) => {
    const xhr = new XMLHttpRequest();
    xhr.open(method, url);
    xhr.setRequestHeader("Content-type", "application/json");
    xhr.send(JSON.stringify(payload));

    xhr.onreadystatechange = function () {
      if (xhr.readyState !== XMLHttpRequest.DONE) return;

      if (xhr.status >= 200 && xhr.status < 400) {
        resolve(xhr.response); // Success!
      } else {
        reject(new Error(xhr.status)); // Failed...
      }
    };
  });
};

const url = "http://jsonplaceholder.typicode.com/posts";

// 포스트 id가 1인 포스트를 검색하고 프로미스를 반환합니다. (메소드 체이닝)
promiseAjax("GET", `${url}/1`)
  // 포스트 id가 1인 포스트를 작성한 사용자의 아이디로 작성된 모든 포스트를 검색하고 프로미스를 반환합니다.
  .then((res) => promiseAjax("GET", `${url}?userId=${JSON.parse(res).userId}`))
  .then(JSON.parse)
  .then(render)
  .catch(console.error);
```

Promise의 정적 메소드는 총 3가지가 있습니다.

1. Promise.resolve() & Promise.reject()

```javascript
const promise = new Promise((resolve, reject) => {
  if (/* 비동기 작업 수행 성공 */){
    resolve()
  }
  else{ /* 비동기 작업 수행 실패 */
    reject()
  }
})
```

2. Promise.all()
   Promise.all()을 사용하여 처리 순서가 보장되는 비동기 코드를 쉽게 작성할 수 있다.

```javascript
// resolve
// 처리 순서 보장

Promise.all([
  new Promise((resolve) => setTimeout(() => resolve(1), 3000)), // 1
  new Promise((resolve) => setTimeout(() => resolve(2), 2000)), // 2
  new Promise((resolve) => setTimeout(() => resolve(3), 1000)), // 3
])
  .then(console.log) // [ 1, 2, 3 ]
  .catch(console.log);

// reject
// 프로미스의 처리가 하나라도 실패하면 가장 먼저 실패한 프로미스가
// reject한 에러를 reject하는 새로운 프로미스를 즉시 반환한다.

Promise.all([
  new Promise((resolve, reject) =>
    setTimeout(() => reject(new Error("Error 1!")), 3000)
  ),
  new Promise((resolve, reject) =>
    setTimeout(() => reject(new Error("Error 2!")), 2000)
  ),
  new Promise((resolve, reject) =>
    setTimeout(() => reject(new Error("Error 3!")), 1000)
  ),
])
  .then(console.log)
  .catch(console.log); // Error: Error 3!
```

3. Promise.race()
   Promise.race()는 가장 먼저 처리된 프로미스가 resolve한 처리 결과를 resolve하는 새로운 프로미스를 반환합니다.

```javascript
// resolve
Promise.race([
  new Promise((resolve) => setTimeout(() => resolve(1), 3000)), // 1
  new Promise((resolve) => setTimeout(() => resolve(2), 2000)), // 2
  new Promise((resolve) => setTimeout(() => resolve(3), 1000)), // 3
])
  .then(console.log) // 3
  .catch(console.log);

// reject
// 프로미스의 처리가 하나라도 실패하면 가장 먼저 실패한 프로미스가
// reject한 에러를 reject하는 새로운 프로미스를 즉시 반환합니다.
Promise.race([
  new Promise((resolve, reject) =>
    setTimeout(() => reject(new Error("Error 1!")), 3000)
  ),
  new Promise((resolve, reject) =>
    setTimeout(() => reject(new Error("Error 2!")), 2000)
  ),
  new Promise((resolve, reject) =>
    setTimeout(() => reject(new Error("Error 3!")), 1000)
  ),
])
  .then(console.log)
  .catch(console.log); // Error: Error 3!
```

Promise에 대한 Polyfill은 CDN이나 NPM을 사용해봤습니다.

</details>

### Q35. Callback 대신에 Promise를 사용할 때의 장점과 단점은 무엇인가요?

<details>
<summary>Answer</summary>

장점은 아래와 같습니다.

1. Callback을 이용한 것에 비해 가독성이 좋습니다.
2. `then()`을 이용하여 연속적으로 비동기 처리를 할 수 있습니다.
3. `catch()`를 이용하여 손쉽게 에러를 처리할 수 있습니다.
4. `Promise.all()`을 이용하여 여러 개의 비동기 처리를 동기적으로 처리할 수 있습니다.

단점은 아래와 같습니다.

1. ES6를 지원하지 않는 브라우저에서는 작동하지 않습니다. 사용하기 위해서는 Polyfill을 로드해야합니다.

</details>

### Q36. Polyfill이란 무엇인가요?

<details>
<summary>Answer</summary>

**Polyfill**은 기본적으로 지원하지 않은 이전 브라우저에서 최신 기능을 제공하는데 필요한 코드입니다.

Babel을 이용하면 되지만 ES5에 존재하지 않는 ES6의 `Map`, `Promise`, `Set`, `Object.assign()` 등은 번역이 되지 않습니다. 이러한 기능을 제공하기 위해 polyfill을 이용합니다.

</details>

### Q37. JavaScript로 컴파일되는 언어로 JavaScript 코드를 작성하는 경우의 장단점은 무엇인가요?

<details>
<summary>Answer</summary>

저는 Typescript를 경험해봄으로써 느낀 장단점을 설명해보겠습니다.

장점은 아래와 같습니다.

1. javascript의 동적 타입을 정적 타입으로 바꿔줌으로써 오류를 방지할 수 있고, 대규모 프로젝트에 어울리다고 생각합니다.

단점은 아래와 같습니다.

1. 브라우저는 오직 JavaScript만 실행하기 때문에 빌드/컴파일 프로세스가 필요하며 브라우저에 제공되기 전에 JavaScript로 코드를 컴파일해야 합니다.

</details>

### Q38. JavaScript 코드를 디버깅하기 위해 어떤 도구와 기술을 사용하나요?

<details>
<summary>Answer</summary>

javascript 코드에서는 Chrome Devtools와 `console.log()`를 자주 이용했습니다.

React & Redux 코드에서는 Redux Devtools를 이용하여 디버깅했습니다.

</details>

### Q39. 오브젝트 속성이나 배열 항목을 반복할 때 사용하는 언어 구문은 무엇인가요?

<details>
<summary>Answer</summary>

</details>

### Q40. mutable 객체와 immutable 객체 사이의 차이점을 설명하세요.

<details>
<summary>Answer</summary>

</details>

### Q41. 동기 함수와 비동기 함수의 차이점을 설명해주세요.

<details>
<summary>Answer</summary>

가장 큰 차이점은 **블로킹의 유무**입니다.

동기 함수는 현재 명령문이 완료되어야 다음 명령문을 실행할 수 있습니다.

동기 함수를 이용하면 명령문의 순서를 파악할 수 있지만, 명령문이 오래 걸린다면 다음 명령들이 멈춰진다는 단점이 있습니다.

비동기 함수는 명령문의 응답과 관계없이 호출된 후 즉시 다음 줄 실행이 계속됩니다 비동기 함수는 콜 스택이 비어 있을 때만 호출됩니다.

</details>

### Q42. 이벤트 루프란 무엇인가요? 콜 스택과 태스크 큐의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

**이벤트 루프(Event Loop)**

javascript는 싱글 스레드 언어임에도 불구하고 마치 멀티 스레드 언어처럼 느껴집니다. 이처럼 **javascript에 동시성을 지원**해주는 것이 이벤트 루프입니다.

이벤트 루프는 콜 스택과 태스크 큐를 모니터하면서 콜 스택이 비어있는 동시에 태스크 큐에 콜백 함수가 있을 경우, 작업을 태스크 큐에서 제거하여 콜 스택에 보냅니다.

**콜 스택(Call Stack)**

작업이 요청되면 콜 스택에 순서대로 쌓이게 되며 순차적으로 실행됩니다.
단일 스레드 언어답게 콜 스택이 하나입니다.

**태스크 큐(Task Queue)**

비동기 처리함수의 콜백 함수, 비동기 처리식 이벤트 핸들러, Timer 함수의 콜백 함수가 보관되는 영역입니다.

</details>

### Q43. `function foo(){}`와 `var foo = function(){}` 사이에서 foo 사용의 차이에 대해 설명하세요.

<details>
<summary>Answer</summary>

가장 큰 차이점은 **호이스팅**입니다.

`function foo(){}`는 **함수 선언식**이며 `var foo = function(){}`는 **함수 표현식**입니다.

```javascript
// 함수 선언식
foo(); // 테스트입니다.
function foo() {
  console.log("테스트입니다.");
}
```

```javascript
// 함수 표현식
foo(); // Uncaught TypeError: foo는 함수가 아닙니다.
var foo = function () {
  console.log("테스트입니다.");
};
```

</details>

### Q44. `var`, `let`, `const`를 사용하여 생성된 변수들의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

가장 큰 차이점은 **스코프**, **재선언**, **재할당** 3가지 입니다.

`var`는 함수 스코프이며 재선언 및 재할당이 가능합니다.

`let`는 블록 스코프이며 재선언은 불가능하지만 재할당이 가능합니다.

`const`는 블록 스코프이며 재선언 및 재할당이 불가능합니다.

</details>

### Q45. ES6 클래스와 ES5 함수 생성자의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

주요 차이점은 **상속을 사용할 때**입니다.
ES5에서는 `prototype`을 이용하여 상속 관계를 형성합니다.
ES6에서는 `class`와 `extends`를 사용하여 상속 관계를 형성합니다.

```javascript
// ES5

function Person(name) {
  this.name = name;
}

function Student(name, studentId) {
  // 슈퍼 클래스의 생성자를 호출합니다.
  // 슈퍼 클래스에서 상속된 멤버 초기화
  Person.call(this, name);

  // 서브 클래스의 멤버 초기화
  this.studentId = studentId;
}

Student.prototype = Object.create(Person.prototype);
Student.prototype.constructor = Student;
```

```javascript
// ES6

class Person {
  constructor(name) {
    this.name = name;
  }
}

class Student extends Person {
  constructor(props, studentId) {
    super(props);
    this.studentId = studentId;
  }
}
```

</details>

### Q46. 새 화살표 => 함수 문법에 대한 사용 예시를 들 수 있나요? 이 새로운 문법은 다른 함수와 어떻게 다른가요?

<details>
<summary>Answer</summary>

화살표 함수와 일반 함수의 차이점은 아래와 같습니다.

1. `function` 키워드를 사용하지 않고 함수를 생성합니다.
2. `this` 바인딩이 주변 스코프에게 묶입니다.

화살표 함수를 사용하면 안되는 경우는 아래와 같습니다.

1. 생성자 함수로 사용하는 경우
2. 객체 또는 프로토타입 메서드에서 객체를 참조해야하 하는 경우
3. DOM 이벤트 핸들러에서 Element에 접근해야 하는 경우

</details>

### Q47. 생성자의 메서드에 화살표 문법을 사용하면 어떤 이점이 있나요?

<details>
<summary>Answer</summary>

함수 생성시 `this`의 값이 설정되고 그 이후에는 변경할 수 없다는 것입니다.

따라서, 생성자가 새로운 객체를 생성하는데 사용될 때, `this`는 항상 그 객체를 참조할 것입니다.

</details>

### Q48. 고차 함수(higher-order function)의 정의는 무엇인가요?

<details>
<summary>Answer</summary>

고차함수는 다른 함수를 매개 변수로 사용하여 어떤 데이터를 처리하거나 결과로 함수를 반환하는 함수입니다.

예를 들면, `map()`, `filter()`, `reduce()` 가 있습니다.

```javascript
// 고차함수가 아닌 함수로 작성
const arr1 = [1, 2, 3];
const arr2 = [];

for (let i = 0; i < arr1.length; i++) {
  arr2.push(arr1[i] * 2);
}

console.log(arr2); // prints [2, 4, 6]
```

```javascript
// 고차함수로 작성
const arr1 = [1, 2, 3];
const arr2 = arr1.map((item) => item * 2);

console.log(arr2); // prints [2, 4, 6]
```

</details>

### Q49. 객체나 배열에 대한 디스트럭쳐링 예시를 들 수 있나요?

<details>
<summary>Answer</summary>

디스트럭쳐링은 ES6에서 지원하는 표현식으로 객체나 배열의 값을 추출하여 다른 변수에 배치하는 간결하고 편리한 방법입니다.

배열에 대한 디스트럭쳐링 예시

```javascript
// 변수 할당
const arr = ["A", "B", "C"];
const [a, b, c] = arr;

console.log(a); // A
console.log(b); // B
console.log(c); // C

// 변수 교환
let d = 1;
let e = 2;

[d, e] = [e, d];

console.log(d); // 2
console.log(e); // 1
```

객체에 대한 디스트럭쳐링 예시

```javascript
// 객체 할당
const object = { a: 42, b: true, c: false };
const { a, b, c } = object;

console.log(a); // 42
console.log(b); // true
console.log(c); // false
```

</details>

### Q50. ES6 템플릿 리터럴은 문자열을 생성하는데 많은 유연성을 제공합니다. 이에 대한 예를 들 수 있나요?

<details>
<summary>Answer</summary>

ES6 템플릿 리터럴은 `(백틱)을 이용하여 문자열 및 다수의 행 문자열을 생성할 때 유연성을 제공합니다.

```javascript
var student = { name: "John", age: 27 };

// ES5
var tempStr = "Hello, My name is " + student.name + " age is " + student.age;
console.log(tempStr); // Hello, My name is John age is 27

// ES6
var tempStr = `Hello, My name is ${student.name} age is ${student.age}`;
console.log(tempStr); // Hello, My name is John age is 27
```

```javascript
// ES5
var multiStr = "First Line \nSecond Line \nThree Line";
console.log(multiStr);

// Result
// First Line
// Second Line
// Three Line

// ES6
var multiStr = `First Line 
Second Line 
Three Line
`;
console.log(multiStr);

// Result
// First Line
// Second Line
// Three Line
```

</details>

### Q51. spread 문법을 사용할 때의 이점은 무엇이며 rest 문법과 다른 점은 무엇인가요?

<details>
<summary>Answer</summary>

spread 문법을 사용하면 `Object.assign()`, `slice` 문법을 사용하지 않고도 손쉽게 배열 및 객체를 복사할 수 있습니다.

```javascript
const arr = ["A", 1, "B", 2];

// Object.assign()
const copyArr1 = Object.assign([], arr);

// Slice
const copyArr2 = arr.slice();

// spread
const copyArr3 = [...arr];

console.log(copyArr1); // ["A", 1, "B", 2]
console.log(copyArr2); // ["A", 1, "B", 2]
console.log(copyArr3); // ["A", 1, "B", 2]
```

rest 문법은 2개 이상의 매개변수를 약식으로 표현하는 방법입니다.

```javascript
function testRest(a, b, ...other) {
  console.log(a); // 1
  console.log(b); // 2
  console.log(other); // [3, 4, 5]
}

testRest(1, 2, 3, 4, 5);
```

</details>

### Q52. 파일 간에 코드를 공유하려면 어떻게 해야하나요?

<details>
<summary>Answer</summary>

파일 간에 코드를 공유하려면 자바스크립트 환경에 따른 `모듈 시스템`을 구축하면 됩니다.

모듈 시스템 구축방법으로는 AMD, CommonJS, ES6 (import, export) 등
이 있습니다.

</details>

### Q53. 정적 클래스 멤버를 만드는 이유는 무엇인가요?

<details>
<summary>Answer</summary>

정적 클래스 멤버(속성/메서드)는 클래스의 특정 인스턴스와 묶이지 않으며, 어떤 인스턴스가 이를 참조하는지에 관계없이 동일한 값을 가집니다.

정적 속성은 일반적으로 설정 변수이며, 정적 메서드는 일반적으로 인스턴스의 상태에 의존하지 않는 순수 유틸리티 함수입니다.

정적 메서드는 클래스 인스턴스에서 호출할수 없다는 점을 기억해야합니다.

</details>

### Q54. JAVA와 Javascript의 다른점은 무엇인가요?

<details>
<summary>Answer</summary>

가장 큰 차이점은 `타입`과 `기반`입니다.

Java는 정적타입을 사용하는 클래스기반 컴파일 인터프린터 언어입니다.

Javascript는 동적타입을 사용하는 프로토타입 기반 인터프린터 언어입니다.

</details>

### Q55. Typescript을 사용해 본 적이 있나요? 어떤지 말씀해주세요.

<details>
<summary>Answer</summary>

간단한 토이프로젝트를 진행해보면서 TS를 사용해본 적이 있습니다.

Typescript를 사용하면 동적 타입을 정적 타입으로 바꿔줄 수 있기 때문에 타입에 대한 오류를 방지 및 발견과 유지보수 측면에서 강점을 느꼈습니다.

</details>

### Q56. require와 import의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

둘다 모듈 시스템을 구축할 때 쓰는 방법입니다.

`require`는 ES5에서 사용되는 모듈시스템 구현 방식으로 동기식으로 작동됩니다.

`import`는 ES6에서 사용되는 모듈시스템 구현 방식으로 비동기식으로 작동됩니다.

ES6를 지원하지 않는 브라우저가 있기 때문에 Babel을 이용하여 ES5로 바꿔줘야합니다.

</details>
