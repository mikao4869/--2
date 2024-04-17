컴퓨팅 클라우드 과제 -2
========================
네트워크란?
------------
네트워크의 정의: 

그물을 뜻하는 net과 work의 합성어로, 그물처럼 서로 긴밀하게 연결되어 있는 것을 의미한다

*(자원을 공유하기 위해서 서로 연결하는 것이다.)*

즉 두 대 이상의 컴퓨터들을 연결하고 서로 통신할 수 있는 것을 의미 한다.

*** 

Protocol 과 Port란?
--------------------

Protocol : 

정보기기 사이(컴퓨터 간, 컴퓨터와 단말기 간 등에서) 정보교환이 필요한 경우 이를 원활하게 하기 위해 정한 통신 규약이다.

컴퓨터와 컴퓨터도 서로 이해 할 수 있는 언어, 공용된 언어를 사용해야 한다.  

자주 쓰이는 프로토콜 정리! 

1. IP:

   데이터 세그먼트를 패킷으로 만들어 전송하는 역할을 수행한다.


2. ICMP:

   메세지에 댜한 오류 보고와 이에 대한 피드백을 원해 호스트에 보고하는 역할을 수행한다.


3.ARP:

   목적지 호스트의 하드웨어 주소를 찾는 역할을 한다
다.

   

*** 

port : 

논리적인 접속 장소를 뜻한다

TCP/IP를 사용할 떄 클라이언트 프로그램이 네트워크 상의 특정 서버 프로그램을 지정하는 방법으로 사용한다


-포트 번호:

   전송 계층의 TCP나 UDP에서 어플리케이션이 상호 구분을 위하여 사용하는 번호, 각 프로토콜의 데이터가 통하는 논리적 통로
   
  컴퓨터 내의 프로세스를 구별하는 수단이 된다

  *자주 쓰이는 포트 번호*
      


| 번호 | 프로토콜 |  설명 | 
|---|:---:|---:|
| 80 | `HTTP` | 웹 서버 접속 |
| 443 |  `HTTPS` | 웹 서버 접속(SSL) |
| 110 | `POP3` | 메일 읽기 |
| 25 | `SMTP` | 메일 서버간 메일 전송 |
| 22 | `SSH` | 컴퓨터 원격 로그인 |
| 53 | `DNS` | DNS 질의 |
| 22 | `SSH` | 컴퓨터 원격 로그인 |



OSI 7 계층
----------

컴퓨터 통신 분야에서 다양한 표준에 대한 국제적인 표준 정의를 위한 기본 골격을 의미한다

네트워크에서 필요로 하는 기능을 7개의 계층을 이용하여 정리한 것이다.

1. 물리계층: 기계적 , 물리적, 전기적인 통신망 접면의 정의

   + 물리 계층에 속하는 계층에는 허브, 리피터, 케이블이 있다.

3. 데이터 링크 계층: 데이터 링크의 제어(프레임화,데이터 투명성, 오류제어 등)

   + 데이터의 단위: Frame(프레임), 장비: Bridge(브리지)와 Swith(스위치)가 있다

4. 네트워크 계층: 경로 배정, 주소, 호 설정 및 해지 등

   + 네트워크 계층의 역할은 데이터를 발신지부터 목적지까지 전송

4. 전송 계층: 종단 간의 메세지 전송(연결 관리, 에러제어, 데이터 분리. 흐름 제어등)

   + 데이터 전송 제어와 오류 제어를 담당

5. 세션 계층: 응용 개체들간의 대화, 동기화 제어, 연결세션 관리 등

   + 통신을 하는데 필요한 일들을 담당하는 역할
   
6. 표현 계층: 전송 형식 협상, 데이터의 표현방식 변환등
   + 데이터를 서로 이해할수 있도록 도와주는 표현 역할

7. 응용 계층: 파일 전송, 접근 및 관리 및 문서, 메세지 교환
   + 사용자에게 데이터를 입력하거나 보여주는 역할
     


