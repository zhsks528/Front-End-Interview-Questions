# Network Interview Questions

## 목차

1. [OSI 7계층에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q1-osi-7%EA%B3%84%EC%B8%B5%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
2. [TCP/IP 4계층에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q2-tcpip-4%EA%B3%84%EC%B8%B5%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
3. [DNS가 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q3-dns%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
4. [도메인 이름으로 실제 IP를 어떻게 찾을 수 있는지 흐름을 설명해 주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q4-%EB%8F%84%EB%A9%94%EC%9D%B8-%EC%9D%B4%EB%A6%84%EC%9C%BC%EB%A1%9C-%EC%8B%A4%EC%A0%9C-ip%EB%A5%BC-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%B0%BE%EC%9D%84-%EC%88%98-%EC%9E%88%EB%8A%94%EC%A7%80-%ED%9D%90%EB%A6%84%EC%9D%84-%EC%84%A4%EB%AA%85%ED%95%B4-%EC%A3%BC%EC%84%B8%EC%9A%94)
5. [TCP와 UDP의 차이에 대해서 설명해 주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q5-tcp%EC%99%80-udp%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4-%EC%A3%BC%EC%84%B8%EC%9A%94)
6. [TCP 헤더에 대해서 설명해 주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q6-tcp-%ED%97%A4%EB%8D%94%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4-%EC%A3%BC%EC%84%B8%EC%9A%94)
7. [MTU가 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q7-mtu%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
8. [3-way hand shake, 4-way hand shake 흐름에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q8-3-way-hand-shake-4-way-hand-shake-%ED%9D%90%EB%A6%84%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
9. [HTTP와 HTTPS 의 차이는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q9-http-%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%95%84%EB%8A%94%EB%8C%80%EB%A1%9C-%EB%A7%90%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
10. [HTTPS가 동작하는 방식에 대해서 설명해 주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q10-http-%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%95%84%EB%8A%94%EB%8C%80%EB%A1%9C-%EB%A7%90%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
11. [HTTP 1.0과 1.1의 차이는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q11-http-10%EA%B3%BC-11%EC%9D%98-%EC%B0%A8%EC%9D%B4%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
12. [HTTP2와 그 특징에 대해서 설명해 주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q12-http2%EC%99%80-%EA%B7%B8-%ED%8A%B9%EC%A7%95%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4-%EC%A3%BC%EC%84%B8%EC%9A%94)
13. [HTTP 헤더의 구조에 대해서 설명해 주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q13-http-%ED%97%A4%EB%8D%94%EC%9D%98-%EA%B5%AC%EC%A1%B0%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4-%EC%A3%BC%EC%84%B8%EC%9A%94)
14. [keep-alive 헤더에 대해서 설명해 주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q14-keep-alive-%ED%97%A4%EB%8D%94%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4-%EC%A3%BC%EC%84%B8%EC%9A%94)
15. [HTTP GET과 POST의 차이는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q15-http-get%EA%B3%BC-post%EC%9D%98-%EC%B0%A8%EC%9D%B4%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
16. [쿠키와 세션에 대해서 설명해 주세요](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/Network#q16-%EC%BF%A0%ED%82%A4%EC%99%80-%EC%84%B8%EC%85%98%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4-%EC%A3%BC%EC%84%B8%EC%9A%94)
17. 로드 밸런싱(Load Balancing) 이란 무엇인가요?

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

DNS는 도메인 이름을 IP 주소로 변환하는 역할을 합니다.

웹 페이지의 로딩에는 4개의 DNS 서버가 관여를 합니다.

#### 1. DNS 리커서

클라이언트 컴퓨터로부터 쿼리를 받도록 고안된 서버입니다.

- ex. 도서관의 어딘가에 있는 책을 찾아달라고 요청받는 사서

#### 2. 루트 이름 서버

호스트 이름을 IP 주소로 변환하는 첫 단계입니다.

- ex. 도서관에서 책장 위치를 가리키는 색인

#### 3. TLD 이름 서버

특정 IP 주소 검색의 다음 단계이며, 호스트 이름의 마지막 부분을 호스팅합니다. (`example.com` 에서 TLD 서버는 `.com`)

- ex. 도서관의 특정 책장으로 생각

#### 4. 권한 있는 서버

요청한 레코드에 대한 액세스 권한이 있다면, 요청한 호스트 이름의 IP 주소를, 초기 요청을 한 DNS 리커서에 돌려보냅니다.

- ex. 책장에 있는 사전처럼 특정 이름을 정의로 변환

</details>
 
### Q4. 도메인 이름으로 실제 IP를 어떻게 찾을 수 있는지 흐름을 설명해 주세요.

<details>
<summary>Answer</summary>

1. 사용자가 웹 브라우저에 `example.com`을 입력하면, 쿼리가 인터넷으로 이동하고 DNS 재귀 확인자가 이를 수신합니다.
2. 이어서 확인자가 DNS 루트 이름 서버(.)를 쿼리합니다.
3. 루트 서버가 도메인에 대한 정보를 저장하는 최상위 도메인(TLD) DNS 서버의 주소로 확인자에 응답합니다.
4. 확인자가 .com TLD에 요청합니다.
5. TLD 서버가 도메인 이름 서버(`example.com`)의 IP주소로 응답합니다.
6. 재귀 확인자가 도메인의 이름 서버로 쿼리를 보냅니다.
7. `example.com`의 IP주소가 이름 서버에서 확인자에게 반환합니다.
8. DNS 확인자가 처음 요청한 도메인의 IP주소로 웹 브라우저에 응답합니다.
9. 브라우저가 IP주소로 HTTP 요청을 보냅니다.
10. 해당 IP의 서버가 브라우저에서 렌더링할 웹 페이지를 반환합니다.

</details>

### Q5. TCP와 UDP의 차이에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

TCP는 연결지향적이며 신뢰성을 가지고 있는 프로토콜입니다.

UDP는 비연결지향적이며 속도를 중시하는 프로토콜입니다.

</details>

### Q6. TCP 헤더에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q7. MTU가 무엇인가요?

<details>
<summary>Answer</summary>

MTU = Maximum Transmission Unit 으로 최대 전송 단위의 약자입니다.

TCP/IP 네트워크와 같이 패킷 또는 프레임 기반의 네트워크에서 전송될 수 있는 최대 크기의 패킷 또는 프레임을 가리키며, 옥텟을 단위로 사용합니다.

TCP는 어떠한 전송에서라도 각 패킷의 크기를 결정하는데 있어 MTU를 사용합니다.

MTU가 크게 설정되어 있을 때

- 커다란 크기의 패킷을 처리할 수 없는 라우터를 만났을 때 **재전송 해야하는 경우가 생길 수 있습니다**.

MTU가 작게 설정되었을 때

- 상대적으로 헤더 및 송 수신 확인에 따르는 **오버헤드가 커지게 됩니다**.

</details>

### Q8. 3-way hand shake, 4-way hand shake 흐름에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

#### 3-way hand shake (연결)

#### [STEP 1]

클라이언트가 시퀀스 넘버를 랜덤으로 생성하여 SYN 패킷에 담아 보냅니다.

#### [STEP 2]

서버는 자신만의 시퀀스 넘버를 랜덤으로 생성하여 SYN 패킷에 담고 클라이언트의 SYN 패킷에 있는 `시퀀스 번호 + 1`를 해서 ACK 패킷에 담아 같이 보냅니다.

SYN과 ACK를 받은 클라이언트는 ACK 패킷의 시퀀스 번호를 보고 자신이 보낸 시퀀스 번호와 차이가 1임을 확인합니다. 차이가 1이라면 연결되었다고 판단합니다.

#### [STEP 3]

클라이언트는 서버의 SYN 패킷에 있는 `시퀀스 번호 + 1`를 해서 ACK 패킷에 담아 보냅니다.

ACK 패킷을 받은 서버는 자신의 시퀀스 넘버와 ACK 패킷의 시퀀스 번호의 차이가 1임을 확인합니다. 차이가 1이라면 연결되었다고 판단합니다.

이후로는 본격적으로 통신할 수 있게 됩니다.

#### 4-way hand shake (해제)

#### [STEP 1]

클라이언트가 연결을 종료하겠다는 FIN 플래그를 전송합니다. 이 때 클라이언트는 `FIN-WAIT` 상태가 됩니다.

#### [STEP 2]

FIN 플래그를 받은 서버는 일단 확인 메시지 ACK를 보내고 자신의 통신이 끝날 때까지 기다리기 위해 `CLOSE-WAIT` 상태가 됩니다.

#### [STEP 3]

연결을 종료할 준비가 되면, 연결 해지를 위한 준비가 되었음을 알리기 위해 클라이언트에게 FIN 플래그를 전송합니다. 이 때 서버는 `LAST-ACK` 상태가 됩니다.

#### [STEP 4]

클라이언트는 해지준비가 되었다는 ACK를 보냅니다. 이 때 클라이언트의 상태가 `FIN-WAIT`에서 `TIME-WAIT` 으로 변경됩니다.

만약 서버에서 FIN을 전송하기 전에 전송된 패킷이 라우팅 지연이나 패킷 유실로 인한 재전송 등으로 인해 FIN 패킷보다 늦게 도착하는 상황이 발생한다면?

- 클라이언트에서 세션을 종료시킨 후 뒤늦게 도착하는 패킷이 있다면 이 패킷은 드랍되고 데이터는 유실될 것입니다.
- 클라이언트는 이러한 현상에 대비하여 서버로부터 FIN을 수신하더라도 일정시간동안 세션을 남겨놓고 잉여 패킷을 기다리는 과정을 거치게 되는데 이 과정을 `TIME-WAIT` 이라고 합니다. 일정시간이 지나면, 세션을 만료하고 연결을 종료시키며, `CLOSE` 상태로 변경됩니다.

</details>

### Q9. HTTP와 HTTPS 의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

가장 큰 차이점은 보안입니다.

HTTP는 제 3자가 전송된 데이터를 가로채면 정보를 열람할 수 있어서 보안이 취약합니다.

HTTPS는 제 3자가 전송된 데이터를 가로채더라도 암호화가 되어있기 때문에 정보를 열람할 수 없어 보안을 유지할 수 있습니다.

</details>

### Q10. HTTPS가 동작하는 방식에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q11. HTTP 1.0과 1.1의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

</details>

### Q12. HTTP2와 그 특징에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

1. 한 번의 연결에 여러 번의 송신을 할 수 있습니다.
2. 헤더 정보를 HPACK 압축 방식을 이용하여 압축해서 보냅니다.
3. 다중화를 이용하여 HOL Blocking이 발생하지 않습니다.

</details>

### Q13. HTTP 헤더의 구조에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

</details>

### Q14. keep-alive 헤더에 대해서 설명해 주세요.

<details>
<summary>Answer</summary>

TCP가 전송이 끝나면 연결이 끊어지듯이 HTTP도 서로 전송이 끝나면 끊어집니다. 그런데 매번 이렇게 똑같은 주소로 요청을 할 때마다 새로운 연결을 설정하고 끊어야 한다면 자원이 낭비됩니다.

이런 문제를 막고자 Keep-Alive가 생겼습니다.

#### 사용방법

```http
HTTP/1.1 200 OK
Connection: Keep-Alive
Content-Encoding: gzip
Content-Type: text/html; charset=utf-8
Date: Thu, 11 Aug 2016 15:23:13 GMT
Keep-Alive: timeout=5, max=1000
Last-Modified: Mon, 25 Jul 2016 04:32:39 GMT
Server: Apache
```

</details>

### Q15. HTTP GET과 POST의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

GET은 리소스를 조회할 때 쓰는 메서드로서 내용을 HEAD에 담아서 보냅니다.

POST는 리소스를 생성할 때 쓰는 메소드로서 내용을 BODY에 담아서 보냅니다.

</details>

### Q16. 쿠키와 세션에 대해서 설명해 주세요

<details>
<summary>Answer</summary>

#### 1. 쿠키

쿠키는 클라이언트 로컬에 저장되는 Key-Value쌍의 작은 데이터 파일입니다.

1. 클라이언트가 서버에 로그인 요청을 합니다
2. 서버는 클라이언트의 로그인 요청의 유효성을 확인하고(아이디와 비밀번호 검사) 응답헤더에 set-cookie: user=chrisjune 를 추가하여 응답합니다.
3. 클라이언트는 이후 서버에 요청할 때 전달받은 cookie: user=chrisjune쿠키를 자동으로 요청헤더에 추가하여 요청합니다. 헤더에 쿠키값을 자동으로 추가하여 주는데 이는 브라우저에서 처리해주는 작업입니다.

쿠키의 기한이 정해져 있지 않고 명시적으로 지우지 않는다면 반 영구적으로 쿠키가 남아있게 됩니다.

#### 2. 세션

브라우저가 종료되기 전까지 클라이언트의 요청을 유지하게 해주는 기술입니다.

1. 클라이언트가 서버에 로그인 요청을 합니다.
2. 서버는 클라이언트의 로그인 요청의 유효성을 확인하고(아이디와 비밀번호 검사) unique한 id를 sessionid라는 이름으로 저장합니다.
3. 서버가 응답할 때 응답헤더에 set-cookie: sessionid:a1x2fjz를 추가하여 응답합니다.
4. 클라이언트는 이후 서버에 요청할 때 전달받은 sessionid:a1x2fjz쿠키를 자동으로 요청헤더에 추가하여 요청합니다.
5. 서버에서는 요청헤더의 sessionid 값을 저장된 세션저장소에서 찾아보고 유효한지 확인후 요청을 처리하고 응답합니다.
   세션의 내용은 서버에 저장되기 때문에 계속하여 늘어날 경우 서버에 부하가 발생합니다.

#### 3. 쿠키와 세션의 차이점

쿠키와 세션의 차이점은 총 4가지 입니다

1. 저장위치
   쿠키는 로컬에, 세션은 로컬과 서버에 저장됩니다.

2. 보안
   쿠키는 탈취와 변조가 가능하지만, 세션은 ID값만 가지고 있고 서버에도 저장이 되어있기 때문에 상대적으로 안전합니다.

3. Lifecycle
   쿠키는 브라우저를 종료해도 파일로 남아있지만, 세션은 브라우저 종료시 세션을 삭제합니다

4. 속도
   쿠키는 파일에서 읽기 때문에 상대적으로 빠르고, 세션은 요청마다 서버에서 처리를 해야하기 때문에 비교적 느립니다.

</details>

### Q17. 로드 밸런싱(Load Balancing) 이란 무엇인가요?

<details>
<summary>Answer</summary>

부하분산 또는 로드 밸런싱은 컴퓨터 네트워크 기술의 일종으로 중앙처리장치 혹은 저장장치와 같은 컴퓨터 자원들에게 작업을 나누는 것을 의미한다.

#### 로드 밸런싱 알고리즘

#### 1. 라운드로빈

서버에 들어온 요청을 순서대로 돌아가며 배정하는 방식입니다.

- 서버와의 연결이 오래 지속되지 않는 경우 적합합니다.

#### 2. 가중 라운드로빈 방식

각 서버에 가중치를 매기고 가중치가 높은 서버에 요청을 우선적으로 배정하는 방식입니다.

- 서버의 트래픽 처리 능력이 다른 경우 사용합니다.

#### 3. 최소 연결 방식

요청이 들어온 시점에 가장 적은 연결 상태를 보이는 서버에 트래픽을 배정하는 방식입니다.

- 서버에 분배된 트래픽들이 일정하지 않은 경우에 적합합니다.

#### 4. IP 해시 방식

클라이언트의 IP주소를 특정 서버로 매핑하여 요청을 처리하는 방식입니다.

- 사용자가 항상 동일한 서버로 연결됩니다.

</details>
