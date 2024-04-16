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

컴퓨터와 컴퓨터도서로 이해 할 수 있는 언어, 공용된 언어를 사용해야 한다.  


*** 

port : 

논리적인 접속 장소를 뜻한다

*컴퓨터 관련 분야에서 운영체제 통신에서 종단점을 뜻한다*

TCP/IP를 사용할 떄 클라이언트 프로그램이 네트워크 상의 특정 서버 프로그램을 지정하는 방법으로 사용

-포트 번호:

컴퓨터에서 실행되고 있는 서버를 구분 짓기 위한 번호이다.

IP내에서 프로세스 구분을 하기 위해서 포트 번호를 사용한다.


OSI 7 계층
----------

컴퓨터 통신 분야에서 다양한 표준에 대한 국제적인 표준 정의를 위한 기본 골격을 의미하낟.

네트워크에서 필요로 하는 기능을 7개의 계층을 이용하여 정리한 것이다.

7. 응용 계층: 파일 전송, 접근 및 관리 및 문서, 메세지 교환
   + 사용자에게 데이터를 입력하거나 보여주는 역할
     
6. 표현 계층: 전송 형식 협상, 데이커의 표현방식 변환등
   +데이터를 서로 이해할수 있도록 도와주는 표현 역할

5. 세션 계층: 응용 개체들간의 대화, 동기화 제어, 연결세션 관리 등
   +통신을 하는데 필요한 일들을 담당하는 역할
   
4. 전송 계층: 종단 간의 메세지 전송(연결 관리, 에러제어, 데이터 분리. 흐름 제어등)
+ 데이터 전송 제어와 오류 제어를 담당

3. 네트워크 계층: 경로 배정, 주소, 호 설정 및 해지 등
+ 네트워크 계층의 역할은 데이터를 발신지부터 목적지까지 전송

2. 데이터 링크 계층: 데이터 링크의 제어(프레임화,데이터 투명성, 오류제어 등)
+데이터의 단위: Frame(프레임), 장비: Bridge(브리지)와 Swith(스위치)가 있다

1. 물리계층: 기계적 , 물리적, 전기적인 통신망 접면의 정의
+물리 계층에 속하는 계층에는 허브, 리피터, 케이블이 있다.
