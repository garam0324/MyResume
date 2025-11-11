# 안녕하세요, [김가람](https://github.com/garam0324)입니다.
> 2004.03.17 | 단국대학교 사이버보안학과(2023.03 ~ 재학 중)<br>
> 010-2048-6646 | rlb040317@gmail.com | [🔗GitHub](https://github.com/garam0324)

<img src="./프로필.png" width="150" alt="프로필 사진" align="right">

<h3 align="center"> 코드 속 취약점을 발견하고, 개발자의 시선으로 보안을 설계합니다.</h3>
<p align="center">
사이버보안을 전공하며 <b>취약점은 코드가 작성되는 그 순간부터 시작</b>된다는 것을 배웠습니다.<br>
개발자의 의도를 이해해야만 그 안의 허점도 제대로 찾을 수 있기 때문입니다.<br>
현재는 모의해킹과 취약점 분석을 진행하며 개발 과정에서의 보안 취약점을 탐색하고,<br>
웹·네트워크·모바일 보안부터 악성코드 분석까지 실전 경험을 쌓아가고 있습니다.<br>
이런 경험을 통해 개발자의 관점에서 시스템을 분석하고 안전한 코드 설계를 이해함으로써,<br>
<b>기능과 보안이 공존하는 균형 잡힌 시스템을 설계하는 보안 전문가</b>로 성장하고자 합니다.
</p>

---

## SKILL
### Language
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![JAVA](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

### OS
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)

### Tool
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burp-suite&logoColor=white)

### Database
![MYSQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

### Framework & Library
![FUSE](https://img.shields.io/badge/FUSE-2C2D72?style=for-the-badge&logo=linux&logoColor=white)
![Volatility](https://img.shields.io/badge/Volatility-0A66C2?style=for-the-badge&logo=gnome-terminal&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

## PROJECT
> 배지를 클릭하면 프로젝트 상세 페이지로 이동합니다.
- **랜섬웨어 대응 FUSE 파일시스템 개발 (2025.10 ~ 진행 중)** [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/garam0324/RansomWAR_BLUE01) [![Notion](https://img.shields.io/badge/Notion-F2F2F2?style=flat-square&logo=notion&logoColor=000000)](https://www.notion.so/RansomWAR-BLUE01-RansomShiled-1a346e976de948d886bc60b37a2f7689)
  * C, FUSE
  * 역할
    + 파일 헤더 기반 시그니처 검사
    + 엔트로피 기반 이상징후 탐지
    + 대량 파일 삭제 요청 차단
    + 미허가된 파일 읽기 요청 시 FAKE_DATA 반환
    + 스냅샷 기능 구현
    + 로깅 기능 구현
  * 성과
    + 확장자 위조 및 암호화 시도를 실시간으로 식별·차단
    + 스냅샷 기능을 통한 데이터 복구 가능성 확보
    + 민감 데이터 노출 방지
    + 멀티스레드 로그 관리 모듈 구현으로 실시간 이벤트 처리 성능 향상

- **LD_PRELOAD 기반 MBR 보호 PoC 구현 (2025.11)** [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/garam0324/MBRlocker_LDPRELOAD)
  * C
  * 역할
    + MBR locker 어셈블리 코드 분석
    + LD_PRELOAD 기반 `fopen`, `fwrite`, `system` 훅 구현
    + 공격 페이로드 추출 및 분석
  * 성과
    + MBR/블록디바이스(dev/sd*) 대상의 쓰기·재부팅 시도 차단·우회하여 데이터 손상 방지
    + 정적·동적 분석을 통해 행위 시그니처 도출
   
- **텔레그램 봇 기반 후방 감지 시스템 (2025.06)** [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/garam0324/Rear_Detection_System)
  * Python, Raspberry Pi
  * 역할
    + 하드웨어 및 회로 설계
    + `/start`, `/backward`, `/stop` 명령어를 통한 명령 처리 로직 설계
    + 실시간 후방 감지 시스템 구현 (거리 측정, LED 경고, 카메라 실시간 촬영 + 사진 전송)
  * 성과
    + Telegram 명령어를 통한 원격 후방 감지 및 실시간 시각 피드백 
    + LED 점멸 속도, 카메라 촬영, 경고 메시지 전송 등 기능을 비동기로 통합해 실시간성 확보
    + 후속 개선 방향으로 실시간 영상 스트리밍, 거리 기반 경고 주기 조절, 명령어 자동 복구 기능 제안
   
- **Pandas 기반 공공 Wi-Fi 설치와 효율성 분석 (2024.12)** [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/garam0324/DataScience_Wifi)
  * Python
  * 역할
    + 서울시 공공데이터 4종(공공 Wi-Fi 사용량·설치 위치·인터넷 이용시간·인구 밀도) 수집
    + `pandas` 기반 데이터 병합 및 이상치 제거
    + 상관분석으로 변수 간 관계 규명
    + 정규성·등분산성·집단 간 차이 검정 수행 및 절사평균 계산
    + 선형·막대·상자·산점도 그래프 및 트리맵, 버블 차트 구현
    + 서울시 공공 Wi-Fi 설치 위치와 사용량을 지도 시각화
  * 성과
    + 데이터 기반 도시 통신 인프라 효율성 진단
    + 고효율 지역(양천구) vs 저효율 지역(강서구) 비교를 통해 설치 정책 개선 방향 제시

- **간단한 랜섬웨어 구현 (2024.11)** [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/garam0324/Ransomware)
  * C
  * 역할
    + 멀티스레드 파일 처리 구조 설계
    + `./target` 디렉토리 하위 파일을 순회하여 확장자 기반 필터링으로 대상 파일 선별
    + 헤더 기반 마스크(XOR) + AES로 마스크 암호화하는 경량 암복호화 루틴 구현
    + 암/복호화 모듈 분리 및 재사용성 확보
  * 성과
    + 병렬 처리로 파일 타입별 동시 작업 가능 -> 전체 처리 시간 단축
    + 키 재사용 없이 각 파일마다 서로 다른 랜덤 마스크를 사용해 단순한 패턴 공격 난이도 상승
    + 로그 출력으로 암호화/복호화 결과 확인 가능
   
- **간단한 셸 구현 (2024.11)** [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/garam0324/Mysh)
  * C
  * 역할
    + 내부/외부 명령 구분 및 실행 제어
    + 백그라운드(`&`) 실행
    + 리다이렉션(`>`, `>>`) 기능
    + 파이프(`|`) 지원
  * 성과
    + 유닉스 기본 셸 기능 제공
    + `fork`, `exec`, `pipe`, `dup2` 등 프로세스·파일 디스크립터 제어 흐름을 직접 구현하여 시스템 호출 이해도 향상
    + 토큰화와 따옴표 처리를 통해 공백 포함 인수(예: `"Hello world"`) 정상 처리 가능
   
- **몬스터 잡기 게임 (2023.12)** [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/garam0324/Monster/tree/main)
  * JAVA
  * 역할
    + 멀티스레드 환경을 통해 각 몬스터가 독립적으로 이동 및 공격 로직을 수행하도록 설계
    + 플레이어 체력 관리, 데미지 적용, 게임 오버 처리 로직 구현
    + 공격 몬스터 사망 시 전체 공격력 감소 로직 추가로 게임 난이도 조절 기능 구현
  * 성과
    + Java 스윙 기반 플레이어-몬스터 인터랙션 GUI 게임 구현
    + 멀티스레드 구조를 통해 프레임 지연 없는 동시 동작 처리
    + 객체지향적 코드 구조로 유지보수성 향상

---

## Activity
| 기간 | 활동명 | 활동 내용 |
| :---: | :---: | :--- |
| 2025.07 ~ 2025.08 | **여름방학 대학생 교육기부 「쏙쏙캠프」** <br>(한국과학창의재단) | - 기획·운영 준비 : 수업안·유인물 제작, 물품·식사·명찰 준비, 현장 동선·시간표 조율 등<br>- 중학생 대상 파이썬 강의(기초문법, 제어구조, 응용 프로젝트)<br>- 현장 운영·피드백 및 학생 이해도에 따른 보충 차시 운영<br>- 예산 관리 및 최종 결과보고서 작성 |
| 2023.03 ~ 현재 | **중앙동아리 Aegis** <br>(단국대학교) | - C 언어 스터디 참여 (2023.03 ~ 2023.06)<br>- 각종 세미나 참여 |
| 2023.03 ~ 2024.02 | **사이버보안학과 학생회** <br> **기획운영부 부원** <br>(단국대학교) | - 학과 행사 기획 : 축제, 간식행사 등<br>- 협업 및 행사 진행 보조 : 부스 운영, 질서 유지, 참여 안내 등 |

---

## Experience
| 기간 | 기관명 | 업무 및 성과 |
| :---: | :---: | :--- |
| 2025.07 ~ 현재 | **빽다방** | • 주문·결제 및 음료 제조, 베이커리·디저트류 관리<br>• 매장 청결 및 위생 관리 담당(테이블·아이스크림 기계 등)<br><br>• 다품목 메뉴 환경에서의 멀티태스킹 능력 향상<br>• 공차에서 익힌 운영 경험을 기반으로 매장 흐름을 효율화하고 동료 보조<br>• 주문량이 많은 환경에서 효율적으로 대응하며 빠른 적응력과 우선순위 판단 능력을 기름 |
| 2023.07 ~ 2025.07 | **공차** | • 고객 응대 및 주문·결제, 음료 제조, 포장 및 매장 정리<br>• 위생 점검 및 품질 관리(보관 온도, 유통기한, 청결 기준 등 준수)<br><br>• 다양한 고객층을 응대하면서 상황에 맞는 커뮤니케이션 방식 습득<br>• 장기 근무자로서 매장 내 커뮤니케이션 중심 역할 수행, 긍정적 근무 분위기 조성<br>• 꾸준한 근속과 성실한 태도로 매장 내 핵심 인력으로 인정받음 |
