💡 프로토콜이란?

서로 다른 기기 간의 통신을 하기 위한 규약입니다. 프로토콜을 통해 전달된 데이터의 오류나 누락 여부를 검출할 수 있습니다.

💡 패킷이란?

전송된 데이터를 자를 때 잘려진 형식화된 데이터 덩어리들을 부르는 단위입니다.

💡 OSI 7 Layer와 각 계층에 대한 설명을 해주세요.

1계층인 물리계층은 비트 단위로 통신하며 전기적 신호를 이용해 통신합니다.

2계층은 프레임 단위로 데이터를 전송하고 MAC 주소를 이용해 네트워크 내부에서 움직입니다.

3계층은 네트워크 사이에서 Datagram이라는 형태로 이동하고 기록된 IP 주소를 보고 가장 효율적인 경로를 찾는 라우팅을 수행합니다.

4계층은 통신의 전반적인 조율을 담당합니다. 그리고 세그먼트 헤더에 등록된 포트번호를 따라 각각의 서비스에 맞는 데이터를 전송해줍니다.

5계층, 세션 계층은 응용프로그램 간의 연결을 담당합니다.

6계층, 표현 계층은 데이터의 압축, 암호화 등을 수행합니다.

7계층은 사용자 인터페이스를 제공하는 계층입니다. HTTP 등의 프로토콜이 7계층에서 작동합니다.

💡 TCP/IP Layer와 각 계층에 대한 설명을 해주세요.

💡 OSI 7 Layer 또는 TCP/IP Layer에서 계층화하는 이유가 무엇인가요?

계층화를 통해 각각 독립적인 역할을 수행하는 단위로 나눌 수 있고 오류 발생 시 탐색이 효율적으로 이루어집니다.

💡 Encapsulation과 Decapsulation을 서로 비교하며 설명해주세요

각각의 데이터가 계층을 따라 이동할 때 원본 데이터를 분리한 단위에 헤더가 붙습니다. 각 계층에 따라 헤더는 포트번호, IP주소 MAC 주소 등을 포함하게 되는데 이것을 캡슐화라고 합니다.

역캡슐화는 반대로 수신 측에서 계층을 올라가면서 헤더를 떼어내는 과정입니다.

💡 IP란?

네트워크 계층에서 사용되는 프로토콜입니다. 패킷을 효율적으로 전송하는 라우팅을 수행합니다. IP는 데이터 전송의 성공 여부를 확인해주지 않기 때문에 상위 계층에서 신뢰성을 제공해야합니다.

💡 IP 주소란?

네트워크에 등록된 기기들을 식별하는 번호입니다.

💡 IPV4 vs IPV6 을 설명해주세요.

💡 IPv4의 주소 부족현상을 해결하기 위해 현재 어떤 방법을 사용하고 있나요?
