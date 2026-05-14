<!--
이 파일은 깃허브 첫 화면 명함용 Profile README 초안입니다.
사용 방법:
1. 깃허브에서 본인 사용자명과 동일한 새 저장소 "jihooooo6/jihooooo6" 생성 (Public)
2. 이 파일 내용을 그대로 README.md 로 푸시
3. 깃허브 첫 화면(github.com/jihooooo6)에 자동 노출됨

방향성: 균형형 (이력 명함 + 인격 본문)
- 헤더의 정량 카드는 명함 효과로 유지
- 본문은 결·관심·실험 중심 (채용 사이트 서류와 차별화)
- 이력 정보(기술 스택·연동·프로젝트 타임라인)는 collapsible로 접어둠
- 핀 저장소가 실제 작업 어필의 메인
-->

<div align="center">

# 조정인 · JO JUNG IN

### 공공기관 30건 이상의 자바 백엔드 6년차 — AI 협업으로 한 단계 더

</div>

---

## 한눈에 보기

<table>
  <tr>
    <td align="center"><b>30건 이상</b><br/><sub>공공 SI 프로젝트</sub></td>
    <td align="center"><b>15곳 이상</b><br/><sub>공공기관 고객사</sub></td>
    <td align="center"><b>80% 이상</b><br/><sub>단독·소규모 팀 주도</sub></td>
    <td align="center"><b>5년 2개월</b><br/><sub>실전 경력</sub></td>
  </tr>
</table>

## 일하는 원칙

- 시간 가는 줄 모르고 몰입하기 — 일 자체에서 동기와 재미를 찾기
- 추측 대신 데이터로 결정 — 힙덤프·전후 수치 비교
- 표준화의 본질은 동료의 작업 비용을 낮추는 것
- 익숙한 영역도 "이 방식이 정말 최선일까" 다시 묻기
- AI에 맡길 것과 직접 검증할 것을 분리
- 지금이 아니라 6개월 후의 사람이 읽을 수 있게

## 5년간 쌓아온 실무 노하우

- **프로젝트 유형별 분포 (총 30건 이상)**
  - 신규 구축: 약 11건
  - 유지보수·고도화: 약 17건 (신규 기능 과업 등 포함)
  - 장기 운영(2년 이상): 약 5건

- **RESTful API 설계·개발**
  - `GET` · `POST` · `PUT` · `DELETE` · `PATCH` 전체 메서드 활용
  - **60건 이상 신규 API 단독 설계**
  - 인터페이스 설계서 작성·문서화

- **외부 시스템 통합 경험**  
  ↳ **17건 이상 연동**. 통합 패턴에 익숙

  <details>
  <summary><b>외부 시스템 연동 경험</b> — 인증·결제·메시징·지도·공공 데이터 API 등 (펼쳐 보기)</summary>

  | 영역 | 연동 시스템 |
  |---|---|
  | 인증·전자서명 | GPKI 전자서명 · NICE 본인인증 · 한국모바일 인증 · SNS 로그인(페이스북 · 인스타그램 · 카카오 · 네이버) · JWT 토큰 · 비대면자격확인서비스 · 주민자격확인서비스 |
  | 결제·정산 | 토스페이먼츠 · 금융결제원 이지로(대용량 계좌이체) · 서울페이 · 구LG 페이 |
  | 메시징·알림 | 카카오톡 알림톡 · SMS 문자전송(드림라인) · GMAIL 전송 시스템 |
  | 지도·미디어·에디터 | 카카오맵 · 네이버맵 · Vimeo API · 스마트에디터 · CK에디터 |
  | 공공 데이터 API | 한국은행 · 통계청 KOSIS · 공공데이터포털 · 한국전력공사 |
  | 공공 표준 연동 | 서울시 게시판 · 직원게시판 · 서울시 배너 · 온나라 연계 · 조직도 연계 |
  | 보안·인프라 | KISA SEED 국가표준 암호화 · 유량제어 솔루션 |

  </details>

- **성능 진단·점진 개선**
  - 힙덤프 분석으로 OOM 원인 추적
  - SXSSF · MyBatis ResultHandler 커서 처리로 메모리 절약
  - 웹/WAS 분리 튜닝으로 **응답 약 3.5배 개선**

- **인프라 운영·서버 이관**
  - 공공클라우드 → 데이터센터 서버 이관
  - Apache · OpenSSL 소스컴파일 버전업
  - WEB 설치·설정 · WAS 설치·설정 · 웹/WAS 분리 구성 (mod_jk 연동)
  - DB 설치 · 메모리 최적화
  - Jenkins CI/CD · 배포 파이프라인 단독 구축

- **웹 보안·취약점 조치**
  - 다수 공공 사업에서 보안 점검 대응 및 조치
  - Apache · OpenSSL 등 서버 소프트웨어 업그레이드
  - HTTP 보안 헤더 설정 (HSTS · CSP · X-XSS-Protection 등)
  - HTTP 메서드 제한 · GET→POST 변경 등 애플리케이션 코드 보완
  - 단일 사업에서 **15개 항목 단독 조치** (서버 담당자 부재 환경)

- **모듈 표준화·자동화 도구**
  - 사내 CMS 모듈 패턴 표준화로 신규 모듈 추가 비용 절감
  - SVN 복사 · 웹취약점 점검 등 반복 작업을 사내 도구로 자동화

- **현장 대응·시스템 개편 경험**
  - 긴급 대응 (오류·트래픽·장애 상황)
  - 대규모 디자인 개편 (UI 리뉴얼)
  - 온나라 연계 (정부 통합 시스템)
  - 조직도 개편·데이터 연계

## 최근 관심·실험

- **AI 작업 흐름을 인프라처럼 운영**
  - **글로벌·프로젝트별 `CLAUDE.md` 2단 계층**  
    ↳ 모든 프로젝트 공통 규칙 + 프로젝트별 도메인 컨텍스트
  - **공통 MD 로 모듈화**  
    ↳ 자주 쓰는 패턴을 분리해 필요한 부분만 호출하도록 설계 (재사용 가능한 컴포넌트처럼)
  - **Skills 로 작업 모듈화**  
    ↳ 특수 작업은 필요 시에만 로드해 **토큰 효율** 유지
  - **문서·정리 자동화**  
    ↳ 노션 등 외부 도구를 작업 흐름에 연계
  - **작성 규칙 표준화**  
    ↳ 파일 접두사·한글 표기 등
  
  → AI 도구가 일관되게 작동하도록 흐름 자체를 다듬는 중입니다

- **Claude Code 기반 바이브코딩**
  - 설계·검증은 본인, 구현은 도구, **책임은 본인**이라는 분리 원칙으로 운영
  - 동작구청 탄소중립마일리지를 **약 2주 단독**으로 완성하며 실증

- **AI 도구 5종 비교 사용**
  - `Claude` · `Cursor` · `GitHub Copilot` · `GPT` · `Gemini` 유료 구독, 메인은 **Claude**
  - 작업 성격에 맞춰 도구를 골라 쓰는 패턴을 다듬는 중

- **운영 중 시스템 점진 개선 패턴**
  - 깨지지 않게 바꾸기 · 단계 쪼개기 · 롤백 경로 먼저
  - 한 시스템을 **5년 동안 운영**하며 다듬은 감각을 정리하는 중

- **챗봇·Agent 영역으로 한 걸음**
  - 백엔드의 연장선에서 AI 서비스 영역을 천천히 학습 중

## 핀 저장소

저장소별 README에 "문제 → 해결 → 정량 성과" 구조로 케이스 스터디를 정리 중입니다. (작성 중)

---

<details open>
<summary><b>기술 스택</b> — Java · Kotlin · Spring Boot · Vue · 전자정부 + AI 도구 등</summary>

<br>

#### 백엔드
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![전자정부 프레임워크](https://img.shields.io/badge/%EC%A0%84%EC%9E%90%EC%A0%95%EB%B6%80%20%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC-1976D2?style=flat-square)
![MyBatis](https://img.shields.io/badge/MyBatis-D9272D?style=flat-square)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0099CC?style=flat-square)

#### 프론트엔드
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![Nuxt.js](https://img.shields.io/badge/Nuxt.js-00DC82?style=flat-square&logo=nuxt.js&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

#### 데이터베이스
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Tibero](https://img.shields.io/badge/Tibero-1A237E?style=flat-square)
![MSSQL](https://img.shields.io/badge/MSSQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

#### 인프라·도구
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black)
![LENA](https://img.shields.io/badge/LENA-455A64?style=flat-square)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![SVN](https://img.shields.io/badge/SVN-809CC9?style=flat-square&logo=subversion&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

#### AI 도구 (일상 사용)
![Claude](https://img.shields.io/badge/Claude%20Code-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square)
![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-181717?style=flat-square&logo=githubcopilot&logoColor=white)
![GPT](https://img.shields.io/badge/GPT-10A37F?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)

</details>

<details>
<summary><b>외부 시스템 연동 경험</b> — 인증·결제·메시징·지도·공공 데이터 API 등 (펼쳐 보기)</summary>

<br>

| 영역 | 연동 시스템 |
|---|---|
| 인증·전자서명 | GPKI 전자서명 · NICE 본인인증 · 한국모바일 인증 · SNS 로그인(페이스북 · 인스타그램 · 카카오 · 네이버) · JWT 토큰 · 비대면자격확인서비스 · 주민자격확인서비스 |
| 결제·정산 | 토스페이먼츠 · 금융결제원 이지로(대용량 계좌이체) · 서울페이 · 구LG 페이 |
| 메시징·알림 | 카카오톡 알림톡 · SMS 문자전송(드림라인) · GMAIL 전송 시스템 |
| 지도·미디어·에디터 | 카카오맵 · 네이버맵 · Vimeo API · 스마트에디터 · CK에디터 |
| 공공 데이터 API | 한국은행 · 통계청 KOSIS · 공공데이터포털 · 한국전력공사 |
  | 공공 표준 연동 | 서울시 게시판 · 직원게시판 · 서울시 배너 · 온나라 연계 · 조직도 연계 |
| 보안·인프라 | KISA SEED 국가표준 암호화 · 유량제어 솔루션 |

</details>

<details>
<summary><b>추가로 접한 기술</b> — 중기부 프로젝트</summary>

<br>

중기부 프로젝트에서 신규 스택 도전 중 접한 기술입니다.  
꾸준한 활용보다는 해당 프로젝트에서 단발적으로 접한 기술입니다.

- **언어·프레임워크**: Kotlin · Spring Boot · JPA · QueryDSL
- **인프라·배포**: Docker · 컨테이너 · AWS (S3·Batch 등) · GitLab CI/CD
- **프론트엔드**: Pinia · Chart.js · Sass/SCSS · Axios · Yarn
- **백엔드·도구**: JHipster · Liquibase · EhCache
- **모니터링**: Prometheus · Sentry

</details>

<details>
<summary><b>프로젝트 타임라인 (30건 이상 · 2021 ~ 2026)</b> — 주요 8건 + 그 외 19건 (펼쳐 보기)</summary>

<br>

#### 주요 프로젝트 (9건 · 2021.02 ~ 2026.03)

| 발주처 | 프로젝트 | 한 줄 |
|---|---|---|
| 동작구청 | 탄소중립마일리지 | 리눅스·웹·WAS·DB·Java·Worker 환경 직접 구축<br>AI 협업 단독 · GPKI · 비대면자격확인(구민인증) · Jenkins |
| 중기부 | 관리자시스템 | Kotlin + Vue.js 신규 스택 · 90% 이상 단독 수행 |
| 구로구청 | 대표 홈페이지 | 현장 상주 단독 · 다수 클래스 점검·안정화 |
| 서울시 | 패션위크 | 단독 운영 · 공공클라우드 → 데이터센터 이관 |
| 서울시 | 장애인 버스요금<br>지원시스템 | 환급 정산 핵심 모듈 개발 · 금융결제원 직접 협의 |
| 서울시 | 대표 홈페이지 | CMS 기반 게시판 공통 모듈 설계·개발 |
| 관악구청 | 긴급재난지원금 | WEB·WAS 각 4대 환경 단독 신규 구축 |
| 금천구청 | 긴급재난지원금 | 유량제어 환경 단독 신규 구축 |
| 국립오페라단 | 홈페이지 | 5년 단독 · 웹/WAS 분리 튜닝으로 응답 약 3.5배 개선 |

#### 자치구 프로젝트 (14건 · 2021.05 ~ 2026.03)

- 동작구청 탄소중립마일리지
- 강서구청 자치회관
- 구로구청 대표 홈페이지
- 구로구청 교육통합포털
- 양천구청 틈새업무
- 양천구청 비상연락망
- 양천구청 전보관리
- 양천구청 전산장비 통합관리
- 금천구청 공모사업 관리시스템
- 금천구청 온종일 돌봄포털
- 관악구청 긴급재난지원금
- 금천구청 긴급재난지원금
- 금천구청 적응형 홈페이지
- 성북구청 온가족 행복망

#### 서울특별시 및 산하기관 (7건 · 2021.03 ~ 2026.02)

- 서울시 패션위크
- 서울시 스마트라이프위크
- 서울시 역사박물관 유물관리
- 서울시 버스요금 지원시스템
- 서울시 대표 홈페이지
- 서울시 좋은간판
- 서울시 문화원연합회

#### 공공기관 및 협회 (6건 · 2021.02 ~ 2026.02)

- 한국전자출판협동조합 아카디피아
- 중기부 중소기업 밀집지역 정보시스템
- 한국수목원정원관리원
- 한국제약바이오협회
- 한국공학대학교 허브사업단
- 국립오페라단 홈페이지

> 각 프로젝트의 상세 수행 내역은 보안상 공개 페이지에 노출하지 않습니다.  
> 필요 시 직접 연락 주세요.

</details>

---

## 연결

- 이메일: foeverqhsk@naver.com

<sub>자세한 경력기술서·자기소개서·포트폴리오는 채용 절차 중 별도로 제공해 드립니다.</sub>
