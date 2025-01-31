### 프로세스, 스레드, CPU

- 프로세스 : 두 가지 역할 : 로컬 환경에서는 하나의 컴퓨터에서 두 가지 역할을 모두 수행하지만, 이는 논리적으로 분리된다.
- 1. 서버 프로세스 : 서버를 실행하는 노드 프로세스가 있다. 이 프로세스는 요청을 수신하고 응답을 처리하는 역할을 한다.
  2. 클라이언트 프로세스 : 웹 브라우저 또는 HTTP 클라이언트 역할을 한다. 이 프로세스는 서버에 요청을 보내고 응답을 수신한다.

- 프로세스와 CPU

  - 프로세스 : 프로세스는 실행 중인 프로그램을 나타내며, 프로그램의 코드, 현재 상태, 메모리 공간 등을 포함한다.
  - CPU : 중앙 처리 장치는 프로세스를 실제로 실행하는 하드웨어이다.(명령 실행 / 스케줄링 / 문맥 교환)

- 프로세스와 스레드

  - 프로세스 : 하나의 프로그램이 독립적으로 실행되는 단위이다. 각 프로세스는 독립된 메모리 공간을 가지고 있어 다른 프로세스와 직접 데이터를 공유하지 않는다.
  - 스레드 : 스레드는 프로세스 내에서 실행되는 더 작은 실행 단위이다. 하나의 프로세스는 여러 스레드를 가질 수 있으며, 스레드들은 프로세스의 메모리 공간을 공유한다.

  - 정리1 : 프로세스는 CPU에서 실행되는 프로그램의 인스턴스이다.
  - 정리2 : CPU는 프로세스의 명령어를 읽고 실행하며, 여러 프로세스를 스케줄링하여 실행한다.
  - 정리3 : 프로세스는 독립적인 실행 단위로서 자체적인 메모리 공간과 샐행 상태를 가지고 있다.
