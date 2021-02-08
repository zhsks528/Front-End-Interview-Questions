# Network Interview Questions

## 목차

1. OSI 7계층에 대해서 설명해주세요.
2. TCP/IP 4계층에 대해서 설명해주세요.
3. DNS가 무엇인가요?
4. 도메인 이름으로 실제 IP를 어떻게 찾을 수 있는지 흐름을 설명해 주세요.
5. TCP와 UDP의 차이에 대해서 설명해 주세요.
6. TCP 헤더에 대해서 설명해 주세요.
7. MTU가 무엇인가요?
8. 3-way hand shake, 4-way hand shake 흐름에 대해서 설명해주세요.
9. HTTP 프로토콜에 대해서 아는대로 말해주세요.
10. HTTP와 HTTPS 의 차이는 무엇인가요?
11. HTTPS가 동작하는 방식에 대해서 설명해 주세요.
12. HTTP 1.0과 1.1의 차이는 무엇인가요?
13. HTTP2와 그 특징에 대해서 설명해 주세요.
14. HTTP 헤더의 구조에 대해서 설명해 주세요.
15. keep-alive 헤더에 대해서 설명해 주세요.
16. HTTP GET과 POST의 차이는 무엇인가요?
17. 쿠키와 세션에 대해서 설명해 주세요

## 질문 및 답변

### Q1. OSI 7계층에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

ISO에서 제안한 통신 규약으로써 컴퓨터 네트워크 프로토콜 디자인과 통신 계층으로 나누어 설명한 것입니다.

OSI 계층 순서는 아래와 같습니다.

물리층 - 데이터링크층 - 네트워크층 - 전송층 - 세션층 - 표현층 - 응용층

#### 1. 물리층

데이터를 전기신호로 변환해서 전송하는 층입니다.

관련장비로는 리피터와 허브가 있습니다.

#### 2. 데이터 링크층

신뢰성있고 효율적인 정보 전송을 할 수 있도록 도와주는 층입니다.

- 흐름제어, 오류제어, 순서제어, 프레임의 동기화를 제공합니다.

관련장비로는 스위치가 있습니다.

#### 3. 네트워크층

네트워크 연결을 관리하는 기능과 데이터의 교환 및 중계 기능을 하는 층입니다.

관련장비로는 라우터, IP가 있습니다.

#### 4. 전송층

종단시스템간에 투명한 데이터 전송을 가능하게 하는 층입니다.

- 흐름제어, 오류제어, 주소설정, 다중화를 제공합니다.

관련장비로는 게이트웨이가 있습니다.

#### 5. 세션층

송 수신측 간의 관련성을 유지하고 대화 제어를 담당하는 층입니다.

#### 6. 표현층

통신에 적당한 형태로 변환하는 기능을 담당하는 층입니다.

- 코드 변환, 암호화, 문맥관리 기능을 제공합니다.

#### 7. 응용층

사용자가 OSI 환경에 접근할 수 있도록 서비스를 제공하는 층입니다.

</details>

### Q2. TCP/IP 4계층에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

TCP/IP 계층의 순서는 아래와 같습니다.

네트워크 액세스층 - 인터넷층 - 전송층 - 응용층

#### 1. 네트워크 액세스층

OSI 7계층에서 물리계층 + 데이터 링크 계층에 해당되는 계층입니다.

네트워크 드라이버와 같은 물리적인 TCP/IP 패킷의 전달 및 수신 과정에 대해 당담하고 있는 계층입니다.

#### 2. 인터넷층

OSI 7계층에서 네트워크층과 대응되는 계층입니다.

패킷을 목적지까지 효율적으로 전달하는 것만 고려하는 계층입니다.

#### 3. 전송층

OSI 7계층에서 전송계층과 동일한 역할을 하는 계층입니다.

전달되는 패킷의 오류를 검사하고 재 전송을 요구하는 등의 전반적인 제어를 담당하는 계층입니다.

#### 4. 응용층

OSI 세션, 표현, 응용층을 포함하는 계층입니다.

사용자의 응용 프로그램 레벨에서 데이터를 처리하는 계층입니다.

</details>

### Q3. DNS가 무엇인가요?

<details>
<summary>Answer</summary>

</details>
 
### Q4. 도메인 이름으로 실제 IP를 어떻게 찾을 수 있는지 흐름을 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q5. TCP와 UDP의 차이에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q6. TCP 헤더에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q7. MTU가 무엇인가요?

<details>
<summary>Answer</summary>

</details>

### Q8. 3-way hand shake, 4-way hand shake 흐름에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

</details>

### Q9. HTTP 프로토콜에 대해서 아는대로 말해주세요.

<details>
<summary>Answer</summary>

</details>

### Q10. HTTP와 HTTPS 의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

</details>

### Q11. HTTPS가 동작하는 방식에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q12. HTTP 1.0과 1.1의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

</details>

### Q13. HTTP2와 그 특징에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q14. HTTP 헤더의 구조에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q15. keep-alive 헤더에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q16. HTTP GET과 POST의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

</details>

### Q17. 쿠키와 세션에 대해서 설명해 주세요

<details>
<summary>Answer</summary>

</details>
