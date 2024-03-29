## 용어 정리

- 정보 보호 기술 AAA 기술
  - 인증(Authentication) : 시스템을 접근하기 전에 접근 시도하는 사용자의 신원을 검증
  - 인가(Authorization) : 검증된 사용자에게 어떤 수준의 권한과 서비스를 허용
  - 계정(Accounting) : 사용자의 자원(시간, 정보, 위치 등)에 대한 사용 정보를 수집

- ARP 스푸핑(ARP Spoofing)

  - 근거리 통신망 하에서 ARP 메시지를 이용하여 상대방의 데이터 패ㅣㅋㅅ을 중간에서 가로채는 중간자 공격 기법

- 결합도(Coupling) 내공외제스자 (약하게 할 수록 좋음) 강 :arrow_double_down: 약 순

  - 내용 결합도
    - 하나의 모듈이 다른 모듈의 **내용**을 직접 참.
    - 다른 모듈 내부에 있는 변수나 기능을 사용하는 경우의 결합도
  -  공통 결합도
    - 두 모듈이 동일한 **전역 변수를 공유**.

  - 외부 결합도
    - **외부**의 다른 모듈에서 참조
  - 제어 결합도
    - **제어 신호** 를 이용하여 통신하는 경우
  - 스탬프 결합도
    - **자료 구조** 형태로 전달되어 이용
  - 자료 결합도
    - **매개변수**를 통해서만 상호작용

- OSI 7계층 (아파서 티내다 피나다)

  - 응용 계층 (Application Layer, 7 계층) : 사용자와 네트워트 간 응용서비스 연결, 데이터 생성
    - HTTP, FTP, TALNET 등
  - 표현 계층(Presentation Layer, 6 계층) : 데이터 형식 설정, 부호교환, 데이터 압축, 문맥 관리 기능
    - JPEG : 이미지를 위한 표준 규격
    - MPEG : 멀티미디어를 위한 표준 규격
  - 세션 계층(Session Layer, 5 계층) : 연결 접속, 동기 제어, 송수신 간의 논리적인 연결
    - SSH, SSL/TLS, RPC
  - 전송 계층(Transport Layer, 4계층) : 신뢰성있는 통신 보당, 흐름 제어, 오류 제어
    - TCP, UDP, RTCP, SNMP, RTP
  - 네트워크 계층(Network Layer, 3 계층) : 데이터를 목적지까지 가장 안전하고 빠르게 전달
    - IP, ICMP, IGMP, ARP, RARP, 라우팅 프로토콜

  - 데이터 링크 계층(Data Link Layer, 2 계층) : 물리계층을 통해 송수신되는 정보의 오류와 흐름을 관리
    - HDLC, PPP, ATM

  - 물리 계층(Physical Layer, 1 계층) : 실제 접속 등
    - RS-232C

- 테스트 케이스의 구성요소
  - 테스트 조건, 테스트 데이터, 예상 결과
  - 테스트 시나리오 :구체적인 절차를 명세
  - 테스트 스크립트 : 실행 절차에 대한 명세
  - 목 오브젝트 

- 원인-결과 그래프
  - 관계와 출력에 영향을 미치는 상황을 체계적으로 분석, 효용성이 높은 테스트 케이스를 선정 테스트

- 개인키 암호화 방식
  - DES : 56비트 미국 NBS 64 비트 대칭키 암호
  - AES : 미국 표준, 128비트, DES를 대체
  - SEED : 한국인터넷진흥원에서 개발한 블록 암호화 알고리즘
  - ARIA : 국가정보원과 개발 한국 표준

- TKIP (Temporal key Integrity Protocol) : 임시 키 무결성 프로토콜
- 삭제 이상 : 한 튜플을 삭제할 때 의도와는 상관없는 값들도 함께 연쇄 삭제
- 정보보호 관리체계 ISMS(Information Security Management System)

- 키
  - 후보키 : 유일성과 최소성을 만족
  - 슈퍼키 : 유일성은 만족시키지만 최소성은 만족시키지 못한다.

- 관계 대수
  - 관계형 데이터베이스에서 원하는 정보를 어떻게(How) 유도하는가를 기술하는 절차적인 언어
- 관계 해석
  - 원하는 정보가 무엇이라는 것만 정의하는 비절차적인 언어

- 대칭키 알고리즘
  - IDEA : Xuejia Lai 64비트 블록, 128비트 key
  - SKIPJACK : NSA에서 개발, 전화기와 같은 음성을 암호화

- 객체지향 설계 원칙 SOLID
  - SRP(단일 책임 원칙) : 객체는 단 하나의 책임만 가져야 한다.
  - OCP (개방-폐쇄 원칙): 확장에 대해 열려 있어야 하고, 수정에 대해서는 닫혀 있어야 한다.
  - LSP (리스코프 치환 원칙): 상속받은 하위 클래스는 언제나 상위클래스로 교체 가능
  - ISP(인터페이스 분리원칙) : 클라이언트는 미사용 메서드와 의존관계를 맺으면 안된다.
  - DIP(의존역전 원칙) : 의존 관계를 맺을 때, 변화하기 어려운 것에 의존

- 회귀 테스트 : 소프트웨어의 변경 또는 수정된 코드에 새로운 결함이 없을음 확인
- IGP : 내부 라우팅 프로토콜
- EP : 외부 라우팅 프로토콜
- OSPF : SPF 알고리즘 기반으로 하는 링크상태 라우팅 프로토콜
- BGP : 서로 다른 조직의 네트워크를 연결 할 때 사용하는 라우팅 프로토콜

- 관계대수
  - 셀렉트(알파) : 조건에 만족하는 튜플 반환
  - 프로젝트(파이) : 속성들의 값으로만 구성된 튜플 반환
  - 조인 (▷◁) : 두 릴레이션의 공통 속성을 이용 하나로 합쳐서 새로운 릴레이션을 만듬
  - 디비전 (나누기) : 조건에 맞는 것들만 릴레이션 A에서 튜플을 꺼내 프로젝션
  - 합집합(U)  
  - 교집합(∩)
  - 차집합(-)
  - 카디션 프로덕트(X)

- 디자인 패턴
  - 생성패턴
    - 추상 팩토리 패턴 : 연관된 객체들을 그룹으로 생성
    - 빌더 패턴 : 객체를 조립하여 생성, 생성

- 사회공학 : 사람들간의 기본적인 신뢰를 기반으로 사람을 속여 비밀 정보를 획득하는 기법
- 다크데이터 : 죽은 데이터, 저장공간만 차지
- SEIM : 머신러닝 기술을 이용하여 IT 시스템에서 발생하는 대량의 로그를 통합관리 및 분석. 사전 위협에 대응하는 보안 솔루션(Security Information and Event Management)

- Trustzone : 프로세서 안에 독립적인 보안 구역을 따로 두어 중요한 정보를 보호하는 ARM사에서 개발한 하드웨어 기반의 보안 기술
- typosquatting : 사용자들이 사이트에 접속할 때 주소를 잘못 입력하거나 철자를 빠뜨리는 실수를 이용하기 위해 유사한 유명 도메인을 미리 등록하는 일 URL 하이재킹이라고도 한다.
- SSO(Single Sign On)
  - 한 번의 로그인을 통해 다른 시스템에도 재인증 절차 없이 접근하여 이용하는 방법

- 프로세스 스케줄링 기법
  - 선점 우선순위가 높은 다른 프로세스가 CPU를 강제로 빼앗아 선점 할 수 있는 기법
    - RR (Round Robin)
    - SRT (Shortest Remaining time) : 실행시간이 가장 작은 프로세스를 먼저 실행
    - MFQ (Multilevel Feedback Queue) : 짧은 작업, 입출력 위주의 프로세스
  - 비선점 : 강제로 빼앗아 선점할 수 없는
    - FCFS (First Come First Served) : 먼저 들어온 프로세스 먼저 처
    - SJF (Shortest Job First) : 처리시간이 짧은 프로세스부터 처리
    - HRN : 짧은 작업시간이라면 대기시간이 긴 프로세스부터 처리

- UML
  - 객체지향 모델링 언어
  - 구성요소 : 사물, 관계, 다이어그램
