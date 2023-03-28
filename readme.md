# 정보보안 정리

* 이 글은 Choi Security님께서 작성한 '[시나리오 기반의 모의침투테스트 대회를 진행하며](https://blog.sunggwanchoi.com/sinario-gibanyi-moyicimtuteseuteu-daehoereul-jin/)'에 대한 내용을 포함하고 있고 TryHackMe의 강의 자료를 다수 포함하고 있습니다.

* [정보보안 기초 개념 바로잡기](https://tryhackme.com/module/introduction-to-cyber-security)

- - -

* [Offensive(공격적) Security 소개](https://tryhackme.com/module/introduction-to-offensive-security)
* [Defensive(방어적) Security 소개](https://tryhackme.com/module/introduction-to-defensive-security)

## Windows / Linux

웹 해킹을 하기 위해서는 웹 서버가 실행되는 운영 체제에 대한 지식이 필요합니다. 윈도우와 리눅스는 웹 서버가 실행되는 두 가지 주요 운영 체제입니다.  
윈도우와 리눅스를 공부하면서 운영 체제의 기본적인 구조와 작동 원리를 이해해야 합니다. 이는 파일 시스템, 프로세스 관리, 메모리 관리, 네트워크 관리 등의 개념을 포함합니다. 파일 시스템은 운영 체제가 파일을 저장하고 관리하는 방법을 정의합니다. 프로세스 관리는 운영 체제가 프로세스를 생성하고 관리하는 방법을 정의합니다. 메모리 관리는 운영 체제가 메모리를 할당하고 회수하는 방법을 정의합니다. 네트워크 관리는 운영 체제가 네트워크 연결을 설정하고 관리하는 방법을 정의합니다. 또한, 윈도우와 리눅스의 보안 기능과 취약점에 대한 지식도 필요합니다. 이는 사용자 계정 관리, 권한 관리, 패치 관리 등의 개념을 포함합니다. 사용자 계정 관리는 운영 체제가 사용자 계정을 생성하고 관리하는 방법을 정의합니다. 권한 관리는 운영 체제가 사용자에게 권한을 부여하고 제어하는 방법을 정의합니다. 패치 관리는 운영 체제가 보안 패치를 설치하고 관리하는 방법을 정의합니다.

### System 강의 / 자료

* [Wargames / 자료](#wargames)
* [권한 상승](https://tryhackme.com/module/privilege-escalation)
* [Shell 및 권한 상승](https://tryhackme.com/module/privilege-escalation-and-shells)

#### Linux

* [Linux 기초](https://tryhackme.com/module/linux-fundamentals)

#### Windows

* [Windows 기초](https://tryhackme.com/module/windows-fundamentals)
* [Windows 악용 기본](https://tryhackme.com/module/hacking-windows-1)

## Web Hacking

웹 해킹은 웹 사이트의 취약점을 공격하는 기술적 위협으로, 웹 페이지를 통하여 권한이 없는 시스템에 접근하거나 데이터 유출 및 파괴와 같은 행위를 말합니다. 웹 애플리케이션 해킹으로 가장 빈도가 많이 발생하고, 보안상 영향을 크게 줄 수 있는 것들로는 SQL 삽입, XSS, CSRF 웹 셸 업로드 등이 있습니다. 웹사이트 해킹 방법을 알고 싶다면, 컴퓨터와 다른 기술이 어떻게 작동하는지 알아야 합니다. 파이썬, PHP (서버 쪽을 망가뜨리려면 필요함) 또는 SQL과 같은 프로그래밍 언어를 배우면 컴퓨터 제어가 쉬워지고 시스템에서 취약한 점을 알아낼 수 있습니다.

### Web 강의 / 자료

* [Wargames / 자료](#wargames)
* [Web Hacking 소개](https://tryhackme.com/module/intro-to-web-hacking)
* [Web의 작동 원리](https://tryhackme.com/module/how-the-web-works)
* [Web Hacking 기초](https://tryhackme.com/module/web-hacking-1)

## Wargames

- - -

주로 사용할 페이지

* [overthewire.org(Web / System / CTF)](https://overthewire.org/wargames/)
* [tryhackme.com(Web / System / Network)](https://tryhackme.com)
* [dreamhack.io(Web / System)](https://dreamhack.io/)

필요할 때 사용하는 페이지

* [hackthebox.com](https://www.hackthebox.com/)

## Network

웹 해킹을 하기 위해서는 네트워크 지식이 필수적입니다. 네트워크의 기본적인 구조와 작동 원리를 이해하고 있어야 합니다. 이는 네트워크의 물리적 구성과 논리적 구성, IP 주소 체계, 서브넷 마스크, 라우팅 등의 개념을 포함합니다. 또한, 네트워크 프로토콜과 네트워크 보안에 대한 지식도 필요합니다. 이는 TCP/IP 프로토콜 스택, HTTP, HTTPS, FTP 등의 프로토콜과 방화벽, IDS/IPS, VPN 등의 보안 기술을 포함합니다.

### Network 강의 / 자료

* [네트워크 기본 개념 - 기초](https://tryhackme.com/room/introtonetworking)
* [네트워크 기본 개념 - 네트워킹이란?](https://tryhackme.com/room/whatisnetworking)
* [네트워크 기본 개념 - LAN](https://tryhackme.com/room/introtolan)

- - -

* [개발자를 위한 네트워킹](https://www.youtube.com/watch?v=k1gyh9BlOT8&list=PLXvgR_grOs1BFH-TuqFsfHqbh-gpMbFoy)
* [Professor Messer 급 깊은 강의](https://www.youtube.com/watch?v=Av9UFzl_wis&list=PL0d8NnikouEWcF1jJueLdjRIC4HsUlULi)

- - -

* [네트워크 보안 기본](https://tryhackme.com/module/network-security)
* [네트워크 보안 및 트래픽 분석](https://tryhackme.com/module/network-security-and-traffic-analysis)
* [네트워크 악용 기본](https://tryhackme.com/module/intro-to-networking)
* [네트워크 보안 우회 / 회피](https://tryhackme.com/module/network-security-evasion)

- - -

* [ESXi 가상 인프라 구축과 보안 솔루션을 활용한 이상징후 탐지 모니터링](https://www.inflearn.com/course/it-%EB%B3%B4%EC%95%88-%EC%9D%B8%ED%94%84%EB%9D%BC-%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81?inst=70d1c5f1#curriculum)

## Cloud

클라우드에서는 다음과 같은 개념을 배우게 됩니다.

* 데이터의 무단 노출 및 유출 방지: 클라우드 보안에서 중요한 것은 데이터의 무단 노출 및 유출을 방지하는 것입니다. 이를 위해 데이터 암호화, 백업 및 복구, 접근 제어 등의 기술이 사용됩니다.

* 취약한 액세스 제어: 클라우드 보안에서 중요한 것은 취약한 액세스 제어를 방지하는 것입니다. 이를 위해 사용자 인증, 권한 관리, 로그 관리 등의 기술이 사용됩니다.

* 공격에 대한 취약성: 클라우드 보안에서 중요한 것은 공격에 대한 취약성을 방지하는 것입니다. 이를 위해 침입 탐지 및 방지 시스템 (IDS/IPS), 방화벽, 애플리케이션 보안 등의 기술이 사용됩니다.

* 가용성 중단 방지: 클라우드 보안에서 중요한 것은 가용성 중단을 방지하는 것입니다. 이를 위해 재해 복구, 부하 분산, 네트워크 보안 등의 기술이 사용됩니다.

* 예방적 제어: 클라우드 보안에서 중요한 것은 예방적 제어를 통해 사전에 위협을 차단하는 것입니다. 이를 위해 침입 방지 시스템 (IPS), 애플리케이션 제어, 허용 목록 등의 기술이 사용됩니다.

* 감사, 모니터링 및 보고: 클라우드 보안에서 중요한 것은 감사, 모니터링 및 보고를 통해 시스템과 데이터의 변경 사항을 추적하고 무단 접근을 감지하는 것입니다. 이를 위해 로그 관리, 이벤트 관리, 감사 추적 등의 기술이 사용됩니다.

* 자동화된 제어: 클라우드 보안에서 중요한 것은 자동화된 제어를 통해 보안 업데이트를 자동으로 적용하고 위험을 수정하며 오류를 제거하는 것입니다. 이를 위해 패치 관리, 구성 관리, 자동화된 응답 등의 기술이 사용됩니다.

* 관리 제어: 클라우드 보안에서 중요한 것은 관리 제어를 통해 보안 정책, 표준, 관행 및 절차를 처리하는 것입니다. 이를 위해 정책 관리, 규정 준수 관리, 리스크 관리 등의 기술이 사용됩니다.

### Cloud 강의

* [AWS 클라우드 서비스 인프라 구축 이해와 해킹, 보안](https://www.inflearn.com/course/aws-%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C-%EB%B3%B4%EC%95%88-%EB%AA%A8%EC%9D%98%ED%95%B4%ED%82%B9#curriculum)

## 시나리오 작성

* [사이버 보안 인식](https://tryhackme.com/module/cyber-security-awareness)

### 참고 문서

* [RvaptHosting_Request_for_Proposal](./pdf/%EB%B3%B4%EA%B3%A0%EC%84%9C%20%EA%B4%80%EB%A0%A8%20%EC%98%88%EC%8B%9C%20%EC%9E%90%EB%A3%8C/RvaptHosting_Request_for_Proposal_%EC%B0%B8%EA%B3%A0%EC%9A%A9.pdf)

## 침투 테스트

* [침투 테스트 소개](https://tryhackme.com/module/introduction-to-offensive-pentesting)
* [침투 테스터를 위한 스크립팅](https://tryhackme.com/module/scripting-for-pentesters)

### 침투 테스트 보고서 예시

- - -

한국어

* [Team1 Final Report - KO](./pdf/%EB%B3%B4%EA%B3%A0%EC%84%9C%20%EA%B4%80%EB%A0%A8%20%EC%98%88%EC%8B%9C%20%EC%9E%90%EB%A3%8C/Team1_Final_Report_%ED%95%9C%EA%B5%AD%EC%96%B4.pdf)
* [Team2 Final Report - KO](./pdf/%EB%B3%B4%EA%B3%A0%EC%84%9C%20%EA%B4%80%EB%A0%A8%20%EC%98%88%EC%8B%9C%20%EC%9E%90%EB%A3%8C/Team2_RVAPTHosting_Final_Report_%ED%95%9C%EA%B5%AD%EC%96%B4.pdf)
* [Team3 Final Report - KO](./pdf/%EB%B3%B4%EA%B3%A0%EC%84%9C%20%EA%B4%80%EB%A0%A8%20%EC%98%88%EC%8B%9C%20%EC%9E%90%EB%A3%8C/Team3_Final_Report_%ED%95%9C%EA%B5%AD%EC%96%B4.pdf)

영문

* [Team1 Final Report - EN](./pdf/%EB%B3%B4%EA%B3%A0%EC%84%9C%20%EA%B4%80%EB%A0%A8%20%EC%98%88%EC%8B%9C%20%EC%9E%90%EB%A3%8C/Team1_Final_Report_%EC%98%81%EC%96%B4.pdf)
* [Team2 Final Report - EN](./pdf/%EB%B3%B4%EA%B3%A0%EC%84%9C%20%EA%B4%80%EB%A0%A8%20%EC%98%88%EC%8B%9C%20%EC%9E%90%EB%A3%8C/Team2_RVAPTHosting_Final_Report_%EC%98%81%EC%96%B4.pdf)
* [Team3 Final Report - EN](./pdf/%EB%B3%B4%EA%B3%A0%EC%84%9C%20%EA%B4%80%EB%A0%A8%20%EC%98%88%EC%8B%9C%20%EC%9E%90%EB%A3%8C/Team3_Final_Report_%EC%98%81%EC%96%B4.pdf)

## 도구

* [Nmap](https://tryhackme.com/module/nmap)
* [Metasploit](https://tryhackme.com/module/metasploit)
* [Burp-Suite](https://tryhackme.com/module/learn-burp-suite)

## 기타

* [기본적인 컴퓨터 악용(Web Hacking, Networking, 기본 침투 테스트 지식 필요)](https://tryhackme.com/module/basic-computer-exploitation)
* [위협 에뮬레이션](https://tryhackme.com/module/threat-emulation)
* [보안 모니터링](https://tryhackme.com/module/security-operations-and-monitoring)