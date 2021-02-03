# 운영체제(OS)

## 목차

1. [운영체제가 무엇인지 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q1-%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EC%A7%80-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
2. [프로세스에 대하여 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q2-%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%EC%97%90-%EB%8C%80%ED%95%98%EC%97%AC-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
3. [스레드에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q3-%EC%8A%A4%EB%A0%88%EB%93%9C%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
4. [프로세스와 스레드의 주요 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q4-%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%EC%99%80-%EC%8A%A4%EB%A0%88%EB%93%9C%EC%9D%98-%EC%A3%BC%EC%9A%94-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
5. [멀티 스레딩의 장, 단점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q5-%EB%A9%80%ED%8B%B0-%EC%8A%A4%EB%A0%88%EB%94%A9%EC%9D%98-%EC%9E%A5-%EB%8B%A8%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
6. [멀티 프로세스 대신 멀티 스레딩을 사용하는 이유는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q6-%EB%A9%80%ED%8B%B0-%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4-%EB%8C%80%EC%8B%A0-%EB%A9%80%ED%8B%B0-%EC%8A%A4%EB%A0%88%EB%94%A9%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EC%9D%B4%EC%9C%A0%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
7. [멀티 프로세싱과 멀티 프로그래밍의 차이에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q7-%EB%A9%80%ED%8B%B0-%ED%94%84%EB%A1%9C%EC%84%B8%EC%8B%B1%EA%B3%BC-%EB%A9%80%ED%8B%B0-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
8. [소켓이란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q8-%EC%86%8C%EC%BC%93%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
9. [커널이란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q9-%EC%BB%A4%EB%84%90%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
10. [힙영역과 스택영역의 차이점을 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q10-%ED%9E%99%EC%98%81%EC%97%AD%EA%B3%BC-%EC%8A%A4%ED%83%9D%EC%98%81%EC%97%AD%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%84-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
11. [교착상태에 대해서 설명해주세요. (필요조건, 해결방법)](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q11-%EA%B5%90%EC%B0%A9%EC%83%81%ED%83%9C%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94-%ED%95%84%EC%9A%94%EC%A1%B0%EA%B1%B4-%ED%95%B4%EA%B2%B0%EB%B0%A9%EB%B2%95)
12. [은행원 알고리즘의 정의와 장단점에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q12-%EC%9D%80%ED%96%89%EC%9B%90-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EC%9D%98-%EC%A0%95%EC%9D%98%EC%99%80-%EC%9E%A5%EB%8B%A8%EC%A0%90%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
13. [스풀링이란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q13-%EC%8A%A4%ED%92%80%EB%A7%81%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
14. [RAID란 무엇이고 종류에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q14-raid%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B4%EA%B3%A0-%EC%A2%85%EB%A5%98%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
15. [뮤텍스와 세마포어의 차이는 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q15-%EB%AE%A4%ED%85%8D%EC%8A%A4%EC%99%80-%EC%84%B8%EB%A7%88%ED%8F%AC%EC%96%B4%EC%9D%98-%EC%B0%A8%EC%9D%B4%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
16. [운영체제에서 기아(Starvation)에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q16-%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C%EC%97%90%EC%84%9C-%EA%B8%B0%EC%95%84starvation%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
17. [교착상태와 기아상태의 차이점은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q17-%EA%B5%90%EC%B0%A9%EC%83%81%ED%83%9C%EC%99%80-%EA%B8%B0%EC%95%84%EC%83%81%ED%83%9C%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
18. [운영체제에서 에이징은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q18-%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C%EC%97%90%EC%84%9C-%EC%97%90%EC%9D%B4%EC%A7%95%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
19. [운영체제에서 페이징은 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q19-%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C%EC%97%90%EC%84%9C-%ED%8E%98%EC%9D%B4%EC%A7%95%EC%9D%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
20. [운영체제에서 세그멘테이션이란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q20-%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C%EC%97%90%EC%84%9C-%EC%84%B8%EA%B7%B8%EB%A9%98%ED%85%8C%EC%9D%B4%EC%85%98%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
21. [스케줄링(Process Scheduling)이란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q21-%EC%8A%A4%EC%BC%80%EC%A4%84%EB%A7%81process-scheduling%EC%9D%B4%EB%9E%80)
22. [CPU Scheduling에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q22-cpu-scheduling%EC%9D%B4%EB%9E%80)
23. [선점 스케줄링과 비선점 스케줄링의 차이점에 대해서 설명해주세요.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q23-%EC%84%A0%EC%A0%90-%EC%8A%A4%EC%BC%80%EC%A4%84%EB%A7%81%EA%B3%BC-%EB%B9%84%EC%84%A0%EC%A0%90-%EC%8A%A4%EC%BC%80%EC%A4%84%EB%A7%81%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%97%90-%EB%8C%80%ED%95%B4%EC%84%9C-%EC%84%A4%EB%AA%85%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94)
24. [CPU 스케줄링의 종류를 설명하시오.](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q24-cpu-%EC%8A%A4%EC%BC%80%EC%A4%84%EB%A7%81%EC%9D%98-%EC%A2%85%EB%A5%98%EB%A5%BC-%EC%84%A4%EB%AA%85%ED%95%98%EC%8B%9C%EC%98%A4)
25. [메모리 단편화란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q25-%EB%A9%94%EB%AA%A8%EB%A6%AC-%EB%8B%A8%ED%8E%B8%ED%99%94%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
26. [내부 단편화와 외부 단편화란 무엇인가요?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q26-%EB%82%B4%EB%B6%80-%EB%8B%A8%ED%8E%B8%ED%99%94%EC%99%80-%EC%99%B8%EB%B6%80-%EB%8B%A8%ED%8E%B8%ED%99%94%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
27. [메모리 단편화 해결방법은?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q27-%EB%A9%94%EB%AA%A8%EB%A6%AC-%EB%8B%A8%ED%8E%B8%ED%99%94-%ED%95%B4%EA%B2%B0%EB%B0%A9%EB%B2%95%EC%9D%80)
28. [사용자 수준 스레드와 커널 수준 스레드의 각각 장단점은?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q28-%EC%82%AC%EC%9A%A9%EC%9E%90-%EC%88%98%EC%A4%80-%EC%8A%A4%EB%A0%88%EB%93%9C%EC%99%80-%EC%BB%A4%EB%84%90-%EC%88%98%EC%A4%80-%EC%8A%A4%EB%A0%88%EB%93%9C%EC%9D%98-%EA%B0%81%EA%B0%81-%EC%9E%A5%EB%8B%A8%EC%A0%90%EC%9D%80)
29. [사용자 수준 스레드와 커널 수준 스레드 차이는?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q29-%EC%82%AC%EC%9A%A9%EC%9E%90-%EC%88%98%EC%A4%80-%EC%8A%A4%EB%A0%88%EB%93%9C%EC%99%80-%EC%BB%A4%EB%84%90-%EC%88%98%EC%A4%80-%EC%8A%A4%EB%A0%88%EB%93%9C-%EC%B0%A8%EC%9D%B4%EB%8A%94)
30. [모드 스위치와 프로세스 스위치간의 차이점은?](https://github.com/zhsks528/Front-End-Interview-Questions/tree/master/OS#q30-%EB%AA%A8%EB%93%9C-%EC%8A%A4%EC%9C%84%EC%B9%98%EC%99%80-%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4-%EC%8A%A4%EC%9C%84%EC%B9%98%EA%B0%84%EC%9D%98-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80)

## 질문과 답변

### Q1. 운영체제가 무엇인지 설명해주세요.

<details>
<summary>Answer</summary>

운영체제는 컴퓨터 하드웨어가 컴퓨터 소프트웨어와 통신하고 작동하도록하는 소프트웨어 프로그램입니다.

목적은 아래와 같습니다.

1. 사용자에게 프로그램을 쉽고 효율적으로 실행할 수 있도록 환경을 제공합니다.
2. 하드웨어 및 소프트웨어 자원을 효율적으로 할당, 관리, 보호합니다.

</details>

### Q2. 프로세스에 대하여 설명해주세요.

<details>
<summary>Answer</summary>

프로세스는 **운영체제로부터 자원을 할당받아 실행중인 프로그램**입니다.

특징은 아래와 같습니다.

1. 각각 독립된 메모리 영역(코드, 데이터, 힙, 스택)이 존재합니다.
2. 기본적으로 최소 1개의 스레드(메인 스레드)를 가지고 있습니다.
3. 별도의 주소 공간에서 실행되며, 한 프로세스는 다른 프로세스의 변수나 자료구조에 접근할 수 없습니다.
4. 다른 프로세스의 자원에 접근하려면 프로세스 간의 통신(IPC)을 사용해야 합니다. (파이프,파일, 소켓 등)

</details>

### Q3. 스레드에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

스레드는 **프로세스로부터 자원을 할당받아 실행되는 프로그램 흐름단위**입니다.

특징은 아래와 같습니다.

1. 프로세스 내에서 각각 스택만 따로 할당받고 나머지 자원(코드, 데이터, 힙)을 공유합니다.
2. 같은 프로세스 안에 있는 여러 스레드들은 같은 힙 공간을 공유합니다.
3. 한 스레드가 프로세스의 자원을 변경하면, 다른 이웃 스레드도 변경 결과를 즉시 볼 수 있습니다.

장점은 아래와 같습니다.

1. 프로세스들 간의 **통신이 향상**됩니다.
2. 실행 환경을 공유하다보니 **메모리가 절약**됩니다.
3. 하나의 프로세스안에 여러 개의 스레드를 생성하여 **병행성을 증진**시킵니다.

</details>

### Q4. 프로세스와 스레드의 주요 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

주요 차이점은 **자원을 할당받는곳**, **자원 공유**, **통신 비용**입니다.

프로세스는 **운영체제로부터 자원을 할당받아 실행되는 프로그램**입니다.
특성상 독립적인 메모리 영역을 가지며 프로세스 간 통신이 쓰레드에 비해 어렵습니다.

스레드는 **프로세스로부터 자원을 할당받아 실행되는 프로그램 흐름단위**입니다.
특성상 스택을 제외한 나머지 영역을 공유하기 때문에 프로세스간 통신에 비해 비용이 적습니다.

</details>

### Q5. 멀티 스레딩의 장, 단점은 무엇인가요?

<details>
<summary>Answer</summary>

멀티 스레딩이란 하나의 프로세스 안에 여러 개의 스레드를 만들어 실행하는 방법입니다.

장점은 아래와 같습니다.

1. 문맥교환의 오버헤드가 적습니다.
2. 스택을 제외한 나머지 자원을 공유하기 때문에 메모리 효율적으로 활용할 수 있습니다.

단점은 아래와 같습니다.

스레드는 프로세스의 자원을 변경하면 다른 스레드도 영향을 받기 때문에...

1. 동기화에 주의해야합니다.
2. 교착상태를 발생시킬 수 있습니다.

</details>

### Q6. 멀티 프로세스 대신 멀티 스레딩을 사용하는 이유는 무엇인가요?

<details>
<summary>Answer</summary>

1. 프로세스 간의 통신(IPC)보다 스레드 간의 통신의 비용이 더 적으므로 통신 부담이 줄어듭니다.
2. 문맥 교환시 스레드는 스택 영역만 처리하기 때문에 전환 속도가 빠릅니다.
3. 프로세스를 생성하여 자원을 할당하는 시스템 콜이 줄어들어 자원을 효율적으로 관리할 수 있습니다.

</details>

### Q7. 멀티 프로세싱과 멀티 프로그래밍의 차이에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

멀티 프로세싱은 여러 개의 처리장치(CPU)를 장착하여 동시에 여러 작업을 병렬로 실행하는 방법입니다.

멀티 프로그래밍은 프로세스가 입출력 작업의 응답을 대기할 동안 다른 프로그램(프로세스)를 수행시킬 수 있도록하는 방법입니다.

</details>

### Q8. 소켓이란 무엇인가요?

<details>
<summary>Answer</summary>

네트워크 상에서 돌아가는 두 개의 프로그램을 연결하는 사용되는 것입니다.

</details>

### Q9. 커널이란 무엇인가요?

<details>
<summary>Answer</summary>

커널은 운영체제의 핵심적인 부분으로 운영체제의 모든 부분에 대한 기본 서비스를 제공합니다.

</details>

### Q10. 힙영역과 스택영역의 차이점을 설명해주세요.

<details>
<summary>Answer</summary>

힙영역은 아래와 같습니다.

1. 사용자가 직접 관리할 수 있는 메모리 영역입니다.
2. 사용자에 의해 메모리의 공간이 동적으로 할당 및 해제됩니다.
3. 런타임때 유용하게 사용되는 공간입니다.

스택영역은 아래와 같습니다.

1. 함수의 호출과 관계되는 지역변수와 매개변수가 저장되는 영역입니다.
2. 함수의 호출과 함께 할당되며, 호출이 완료되면 소멸합니다.
3. 컴파일 때 크기가 결정됩니다.

</details>

### Q11. 교착상태에 대해서 설명해주세요. (필요조건, 해결방법)

<details>
<summary>Answer</summary>

교착상태는 두 개 이상의 프로세스나 스레드가 서로 자원을 무한히 기다리게 되는 상태입니다.

필요조건으로는 4가지가 있습니다.

#### 1. 상호 배제

- 자원은 한 번에 한 프로세스만이 사용할 수 있어야 합니다.

#### 2. 점유 및 대기

- 최소한 하나의 자원을 점유하고 있으면서 다른 프로세스에 할당되어 사용하고 있는 자원을 추가로 점유하기 위해 대기하는 프로세스가 있어야합니다.

#### 3. 비선점

- 다른 프로세스에 할당된 자원은 사용이 끝날때 까지 강제로 빼앗을 수 없어야합니다.

#### 4. 환형대기

- 각 프로세스가 다음 프로세스가 요구하는 자원을 가지고 있습니다.
- ex) A -> B, B -> C, C -> D

해결방법으로는 4가지가 있습니다.

#### 1. 예방기법

- 교착상태가 발생하지 않도록 필요조건 중 한가지를 제거하는 방법입니다.

#### 2. 회피기법

- 교착상태를 피하기 위해 은행가 알고리즘을 이용하는 방법입니다.

#### 3. 발견기법

- 교착상태를 발생했는지 점검하고 복구하는 방법입니다.

#### 4. 회복기법

- 교착상태를 발생시킨 프로세스를 종료하거나, 할당된 자원을 해제함으로써 회복하는 방법입니다.

</details>

### Q12. 은행원 알고리즘의 정의와 장단점에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

은행원 알고리즘은 프로세스가 자원을 요구할 때 시스템은 자원을 할당한 이후에도 안정상태로 남아있는지 사전에 검사하여 교착상태를 회피하는 기법입니다.

단점은 아래와 같습니다.

1. 프로세스가 요구하는 최대 자원 요구량을 알아야합니다.
2. 항상 안정상태로 남아있으려고 하다보니 자원 이용도가 낮습니다.
3. 프로세스들은 유효한 시간내에 자원을 반납해야합니다.

</details>

### Q13. 스풀링이란 무엇인가요?

<details>
<summary>Answer</summary>

스풀링은 장치, 프로그램 또는 시스템에서 데이터를 사용하고 실행하기 위해 일시적으로 데이터를 수집하는 프로세스입니다.

예시로는 프린터가 있는데, 다른 응용프로그램이 동시에 출력을 프린터로 보내면 스풀링은 이러한 모든 작업으 ㄹ디스크 파일에 보관하고 프린터에 따라 대기열에 넣습니다.

</details>

### Q14. RAID란 무엇이고 종류에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

여러개의 디스크를 배열하여 속도, 안정성, 효율성, 가용성을 증가하는데 쓰이는 기술입니다.

장점은 3가지입니다.

1. 운용가능성, 데이터 안정성 증대
2. 디스크 I/O 향상
3. 메모리 증설 용이성

종류는 아래와 같습니다

1. RAID 0 : 내 결함성이 없는 스트림 디스크 어레이
2. RAID 1 : 미러링 및 이중화
3. RAID 2 : 오류 수정 코드(Hamming Code) 사용
4. RAID 3 : 바이트 단위로 나누어 디스크에 동등하게 분산 기록
5. RAID 4 : 블록 단위로 나누어 디스크에 기록
6. RAID 5 : 패리티 정보를 스트립으로 구성된 디스크 내에서 처리
7. RAID 6 : 디스크에 두 개의 패리티를 기록

</details>

### Q15. 뮤텍스와 세마포어의 차이는 무엇인가요?

<details>
<summary>Answer</summary>

뮤텍스와 세마포어는 병행처리를 위한 동기화 기법입니다.

가장 큰 차이점은 **동기화의 갯수**입니다.

- 뮤텍스는 **오직 1개의** 프로세스만이 접근 가능합니다.
- 세마포어는 **세마포어의 변수만큼** 프로세스가 접근 가능합니다.

</details>

### Q16. 운영체제에서 기아(Starvation)에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

특정 프로세스의 우선순위가 낮아 자원을 할당받지 못하고 있는 상태입니다.

해결 방안은 아래와 같습니다.

1. **에이징 기법**을 이용합니다.
2. 요청 순서대로 처리하는 **요청 큐** 사용합니다.
3. 프로세스 우선순위를 수시로 변경하여 높은 우선순위를 가지도록 기회를 부여합니다.

</details>

### Q17. 교착상태와 기아상태의 차이점은 무엇인가요?

<details>
<summary>Answer</summary>

가장 큰 차이점은 발생 조건에 있습니다.

교착상태는 여러 개의 프로세스가 공유자원을 점유하기 위해 요청할 때 발생합니다.

기아상태는 여러 개의 프로세스가 부족한 자원을 점유하기 위해 경쟁할 때 발생합니다.

</details>

### Q18. 운영체제에서 에이징은 무엇인가요?

<details>
<summary>Answer</summary>

에이징은 자원 스케줄링 시스템에서 기아상태를 방지하는 기법입니다.

특정 프로세스가 우선순위가 낮아 자원을 점유하지 못하고 기다리게 되는 경우, 다른 프로세스가 한번 양보하거나 기다린 시간에 비례하여 일정 시간이 지나면 우선순위를 한 단계씩 높여 가까운 시간 안에 자원을 할당 받도록 하는 기법입니다.

</details>

### Q19. 운영체제에서 페이징은 무엇인가요?

<details>
<summary>Answer</summary>

세그멘테이션과 가상메모리를 일정한 크기로 나누어 메모리를 관리하는 기술입니다.

장점으로는 메모리를 페이지 단위로 가져와서, 프로세스의 효율적인 운영이 가능합니다.

단점으로는 페이지 부재 현상이 발생할 수 있습니다.

</details>

### Q20. 운영체제에서 세그멘테이션이란 무엇인가요?

<details>
<summary>Answer</summary>

메모리를 서로 다른 논리적인 블록 단위인 세그먼트로 나누고 메모리를 할당하여 물리 주소를 논리 주소로 변환하는 것을 말합니다.

내부 단편화는 없지만 외부 단편화가 생길 수 있습니다.

</details>

### Q21. 스케줄링(Process Scheduling)이란?

<details>
<summary>Answer</summary>

여러 프로세스가 있고, 이 프로세스들이 자원(CPU 등)을 동시에 요구하는데 자원이 제한되어 있다. 그러면 제한된 자원들을 어떻게(순서를 할당하는 등) 나눠줄 것인지에 대한 정책을 말한다.

</details>

### Q22. CPU Scheduling이란?

<details>
<summary>Answer</summary>

매 시점 어떠한 프로세스에 CPU를 할당해 작업을 처리할 것인지 결정하는 역할을 합니다.

발생시기는 아래와 같다.

1. 실행상태에서 대기상태로 전환될 때 (예, 입출력 요청) - Non preemptive(비선점)
2. 실행상태에서 준비상태로 전환될 때 (예, 인터럽트 발생) - preemptive(선점)
3. 대기상태에서 준비상태로 전환될 때(예, 입출력이 종료될 때)
4. 종료될 때(Terminated)

</details>

### Q23. 선점 스케줄링과 비선점 스케줄링의 차이점에 대해서 설명해주세요.

<details>
<summary>Answer</summary>

선점 스케줄링: CPU를 할당받아 실행 중인 프로세스로부터 CPU를 선점(빼앗는 것)하여 다른 프로세스를 할당 할 수 있는 방식입니다

- ex) RR, SRT, MLQ, MFQ

비선점 스케줄링: CPU를 할당받은 프로세스는 스스로 CPU를 반납할 때까지 CPU를 독점하여 사용하는 방식입니다.

- ex) FCFS, SJR, HRN

</details>

### Q24. CPU 스케줄링의 종류를 설명하시오.

<details>
<summary>Answer</summary>

비선점 스케줄링 (Nonpreemptive)

#### 1. FCFS (First Come First Served)

- 큐에 도착한 순서대로 CPU 할당한다.
- 실행 시간이 짧은 게 뒤로 가면 평균 대기 시간이 길어진다.

#### 2. SJF (Shortest Job First)

- 수행시간이 가장 짧다고 판단되는 작업을 먼저 수행한다.
- FCFS 보다 평균 대기 시간 감소, 짧은 작업에 유리하다.

#### 3. HRN (Highest Response ration next)

- 긴 작업과 짧은 작업 간의 지나친 불평등을 어느 정도 보완한 기법이다.
- 짧은 작업이나 대기시간이 긴 작업은 우선순위가 높아진다.

선점 스케줄링 (Preemptive)

#### 1. 우선순위 (Priority Scheduling)

- 정적/동적으로 우선순위를 부여하여 우선순위가 높은 순서대로 처리
- 우선 순위가 낮은 프로세스가 무한정 기다리는 Starvation 이 생길 수 있음
- Aging 방법으로 Starvation 문제 해결 가능

#### 2. 라운드 로빈 (Round Robin)

- FCFS에 의해 프로세스들이 보내지면 각 프로세스는 동일한 시간의 만큼 CPU를 할당 받음
  - Time Quantum or Time Slice : 실행의 최소 단위 시간
- 할당 시간(Time Quantum)이 크면 FCFS와 같게 되고, 작으면 문맥 교환 (Context Switching) 잦아져서 오버헤드 증가
- 시분할 방식에 효과적이다.

#### 3. SRT (short remaining time)

- 가장 짧은 시간이 소요된다고 판단되는 프로세스를 먼저 수행한다.
- 남은 처리 시간이 더 짧다고 판단되는 프로세스가 준비 큐에 생기면 언제라도 실행중인 프로세스가 선점됨다.

#### 4. 다단계 큐 (Multilevel Queue)

- 작업들을 여러 종류의 그룹으로 나누어 여러 개의 큐를 이용하는 기법

#### 5. 다단계 피드백 큐 (Multilevel Feedback Queue)

- 입출력 위주와 CPU 위주인 프로세스의 특성에 따라 서로 다른 CPU의 타임 슬라이스를 부여
- 짧은 작업에 유리, 입출력 위주의 작업에 우선권을 줌
</details>

### Q25. 메모리 단편화란 무엇인가요?

<details>
<summary>Answer</summary>

메모리를 할당 및 해제를 함으로써 생기는 메모리의 빈공간을 말합니다.

그 빈공간의 크기보다 작거나 큰 프로그램들이 들어오게 되면 메모리의 공간이 남거나 사용할 수 없습니다. 하나둘씩 메모리의 빈공간이 쌓이게 되면 메모리의 용량이 남아도 사용할 수 없게 됩니다.

</details>

### Q26. 내부 단편화와 외부 단편화란 무엇인가요?

<details>
<summary>Answer</summary>

내부단편화는 분할된 영역이 할당될 프로그램의 크기보다 커서 사용되지 않고 남아있는 빈공간을 말합니다.

- 페이징에서 발생됩니다.

외부단편화는 분할된 영역이 할당될 프로그램의 크기보다 작아서 모두 빈 공간으로 남아있는 전체 영역을 말합니다.

- 세그멘테이션에서 발생됩니다.

</details>

### Q27. 메모리 단편화 해결방법은?

<details>
<summary>Answer</summary>

방법은 2가지가 있습니다.

1. 메모리를 압축합니다. (디스크 조각모음)
2. 메모리의 빈공간을 통합합니다.

</details>

### Q28. 사용자 수준 스레드와 커널 수준 스레드의 각각 장단점은?

<details>
<summary>Answer</summary>

**커널 수준 스레드**

- 장점: 커널이 직접 제공해주기 떄문에 안정성과 다양한 기능이 제공됩니다.
- 단점: 사용자 모드에서 커널 모드로의 전환이 빈번하게 이뤄져 성능 저하가 발생합니다.

**사용자 수준 스레드**

- 장점 : 커널은 쓰레드의 존재조차 모르기 때문에 모드 간의 전환이 없고 성능 이득이 발생한다.
- 단점 : 하나의 스레드가 커널에 의해 블로킹되면 프로세스 전체가 블로킹되고, 이를 해결하려면 프로그래밍이 어려워지고 커널 레벨 쓰레드에 비해 결과 예측이 어려워진다.

</details>

### Q29. 사용자 수준 스레드와 커널 수준 스레드 차이는?

<details>
<summary>Answer</summary>

가장 큰 차이점은 **생성 주체가 누구인가**입니다.

커널이 쓰레드 모델을 지원하지 않거나 제공하는 쓰레드 모델이 마음에 들지 않을 경우, 커널에 의존적이지 않은 형태로 스레드의 기능을 제공하는 라이브러리를 활용할 수 있는데 이러한 방식으로 제공되는 스레드가 **사용자 수준 스레드**입니다.

프로그래머 요청에 따라 스레드를 생성하고 스케줄링하는 주체가 커널이면 **커널 수준 스레드**라고 한다.

</details>

### Q30. 모드 스위치와 프로세스 스위치간의 차이점은?

<details>
<summary>Answer</summary>

모드 스위치는 사용자 모드에서 커널모드로 변경할 때 발생하며 완전문맥교환이 필요하지 않고 시스템 스택을 사용합니다.

프로세스 스위치는 보통 문맥교환이라고 부르는 것이며 실행중인 프로세스를 멈추고 새 프로세스를 실행하는 것입니다.

</details>
