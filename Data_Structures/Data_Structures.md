# CS | Data Structures 자료구조

- **자료구조 (Data Structures)** 와 **알고리즘 (Algorithm)** 은 프로그램을 구성하는 가장 핵심적인 요소



### Data Structures 자료구조

- 비유
  - 흙이나 모래, 시멘트, 목재와 같은 자재들 → 자료구조
  - 이 자재들을 이용해서 집을 짓는 것 → 알고리즘

- 다양한 자료 구조들
  - Array (배율)
  - Stack (스택)
  - Queue (큐)
  - Deque (덱)
  - List (리스트)
  - Tree (트리)
  - Graph (그래프)
  - Hash (해시)
- 자료구조 정의
  - CS에서 효율적인 접근과 수정을 가능하게 하는 자료의 조직, 관리, 저장을 의미
  - 데이터 값의 모임, 데이터 간 관계, 데이터에 적용할 수 있는 함수나 명령을 의미한다.
- 분류
  - 선형 구조 (Linear Structure)
    - 선형 리스트 (Linear List) : 데이터 간 순서가 있는 리스트. 보통 배열로 구현
    - 연걸 리스트 (Linked List) : `노드`를 단위로 함. 노드는 `데이터` 와 다음 노드를 가리키는 `참조값` 으로 구성
    - 스택 (Stack) : 먼저 저장된 것이 꺼내 쓸 때 제일 나중에 나온다. 반대로 가장 최근에 저장된 것이 꺼낼 때 제일 먼저 나온다
    - 큐 (Queue) : 스택과 반대. 저장된 것이 제일 먼저 나온다. 가장 나중에 저장된 것이 꺼낼 때 가장 나중에 나온다
    - 덱 (Deque) : 양쪽에서 넣기/빼기가 가능한 일반화된 선형 구조
  - 비선형 구조 (Non-Linear Structure)
    - 트리 (Tree) : 뿌리와 뿌리, 혹은 다른 꼭짓점을 하나의 부모로 갖는 꼭짓점으로 이루어진 구조. 부모-자식 관계는 변(선) 으로 표현된다
    - 그래프 (Graph) : 꼭짓점과 꼭짓점을 잇는 변으로 구성

![자료구조 기초](Data_Structures.assets/R800x0)

</br></br>

#### 추상자료형 ADT(Abstract Data Type)

- 구체적인 기능의 완성을 언급하지 않고, 순수하게 기능이 무엇인지 나열한 것
- 비유
  - 전기밭솥 안에 들어가는 밥은 자료가 된다
  - 취사, 예약 취사 버튼/ 남은 시간을 표현하는 디스플레이 등에 어떤 내용이 표시되어야 하는지를 명기
  - 밥솥 **내부에서 어떤 복잡한 일이 발생하는지는 관심없고, 기능과 사용방법을 정의**한 것
- 구성
  - 데이터 선언
  - 연산 선언
- ADT를 정의할 때는 구체적인 구현은 신경쓰지 않아도 되고 실제 사용할 때 구현이 중요
- 연걸 리스트, 스택, 큐, 우선순위 큐, 이진 트리, 딕셔너리, 해시 테이블, 그래프 등