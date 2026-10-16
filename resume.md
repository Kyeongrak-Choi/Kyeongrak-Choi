# 최경락 | 이력서 · 경력기술서

> 10년 4개월 동안 모바일·백엔드 서비스를 개발하고 운영해 왔으며, 현재는 AI Agent와 LLM 애플리케이션 개발로 전문 영역을 확장하고 있습니다.

- Email: [kyungrac12@gmail.com](mailto:kyungrac12@gmail.com)
- GitHub: [github.com/Kyeongrak-Choi](https://github.com/Kyeongrak-Choi)
- 지원 분야: AI Engineer / AI Agent Engineer

## 요약

Android, Flutter, Spring 기반 앱과 서버를 개발해 왔습니다. 결제·주문·ERP 연동, 생산·재고 관리처럼 현업 데이터와 연결되는 시스템에서 기능 개발, 배포, 운영 이슈 대응을 경험했습니다.

현재 엔코아 AI Orchestration Engineer 과정에서 Python, FastAPI, LLM, LangGraph를 학습하고 있습니다. PlanEat에서는 대화형 식단 추천 서비스의 백엔드와 Agent Orchestrator를 맡았고, SubSync에서는 영상 문맥 기반 AI Tutor 백엔드와 LLM Provider fallback을 구현했습니다.

## 기술

| 구분 | 기술 |
| --- | --- |
| 실무 개발 | Android, Java, Flutter, Dart, Spring Framework, MyBatis, JSP, REST API |
| 데이터·연동 | Oracle, MySQL, SQL, ERP 연동, Firebase |
| 운영·협업 | Google Play Console, Firebase Crashlytics, Firebase Performance, GitHub, Git, SVN |
| AI 프로젝트·교육 | Python, FastAPI, LangGraph, LLM API, RAG, MCP, ChromaDB, OpenAI API, NeMo Guardrails |

## AI 프로젝트

### PlanEat | 대화형 AI 식단 추천 서비스

- Repository: [Kyeongrak-Choi/PlanEat](https://github.com/Kyeongrak-Choi/PlanEat)
- 형태: 엔코아 AIO 2기 Team 2 프로젝트
- 역할: BE · Agent Orchestrator

**담당 내용**

- FastAPI와 LangGraph로 `재료 입력 → 재료 확인 → 조건 입력 → 추천 완료`의 다단계 대화 흐름 구현
- 세션별 후보·확정 재료·식단 조건을 관리하고, 조건이 충족될 때만 Tool Hub를 호출하도록 구성
- Jev 판정과 Guardrails를 적용하고, 판정의 confidence 미달 또는 timeout에는 규칙 기반 흐름으로 전환
- 사용자 피드백을 기존 식단 조건에 누적해 재추천 흐름에 반영
- 배포 환경에서 PDF 생성 중 메모리 사용량이 커지는 문제를 확인하고, 검증된 CSV 단일 참조 경로를 사용하도록 조정

### SubSync | YouTube 기반 영어 학습 서비스

- Repository: [Kyeongrak-Choi/Subsync](https://github.com/Kyeongrak-Choi/Subsync)
- 형태: 엔코아 AIO 2기 Team 4 프로젝트
- 역할: AI Tutor 백엔드 · LLM Provider fallback

**담당 내용**

- 현재 재생 중인 영상의 자막과 문맥을 바탕으로 답변하는 AI Tutor 구현
- 이전 질문·답변을 잇는 후속 질문, 선제 질문, 답변 피드백 흐름 구성
- Gemini 기본 모델에 장애·사용량 제한을 대비한 Groq → stub 폴백 구조 설계·구현
- 자막과 사용자 질문을 시스템 지시와 분리해 프롬프트 인젝션 위험을 줄이도록 설계

### 지름막 | 충동구매 방지 소비 습관 앱

- Google Play: [지름막](https://play.google.com/store/apps/details?id=com.pause72.jireummak&hl=ko)
- Flutter 기반 개인 프로젝트로, 앱 콘셉트 기획, UI/UX 설계, 개발, 배포·운영을 1인으로 수행

## 경력

### 보나캠프㈜ | IT본부 · 책임연구원 / 팀원

**2022.06 - 2024.02 · 1년 9개월**

- 주류 결제 단말기: 결제, 주문, 프린터, RFID 기능을 통합한 Android 앱 및 Spring·Oracle 서버 개발·유지보수
- 주류 유통 ERP 연동 앱: 판매·경영·재고·결제·주문 관리 기능을 위한 Android 앱 및 서버 개발·유지보수
- 도매사별 주문 앱: 도매사 요구사항에 맞춘 Android 주문 앱 개발·유지보수
- 경영관리 앱 리뉴얼과 사내 서버 상태 관리 앱: Flutter 기반으로 기획부터 개발까지 수행
- Google Play, Firebase, GitHub를 활용한 운영·배포 관리 및 Crashlytics·Performance 기반 이슈 대응

### ㈜진코퍼레이션 | IT서비스부문 · 대리 / 팀원

**2018.07 - 2021.12 · 3년 6개월**

- 파리바게뜨 국내·해외 매장용 모바일 POS 앱과 서버 개발·유지보수
  - 기술: Miaps, Spring, MyBatis, Oracle, SVN
- 중국 사업부 생산관리 Android 태블릿 앱 개발·유지보수
  - 기술: Android, SVN

### ㈜새한산업 | 전산팀 · 사원 / 팀원

**2014.02 - 2018.04 · 4년 3개월**

- 생산 현황 조회와 비가동 Push 알림 기능을 제공하는 Android 앱·알림 프로그램 개발·유지보수
- 자재 재고 조회, 중국 수출 파렛트 선적용 QR 코드 Android 앱과 모바일 서버 개발·유지보수
- 금형관리, 중국법인 ERP, 회계원가 시스템 개발 및 ERP·CKD·SCM 운영 시스템 유지보수

### ㈜네오포인트 | 기술연구소 · 주임 / 팀원

**2012.12 - 2013.09 · 10개월**

- LG전자 옵티머스 X3·옵티머스 3D OS 업그레이드 모델팀 업무 수행
- 소방방재청 모바일 재난정보 포털 앱 RFP 작성
- 삼성카드 m포켓 고도화 프로젝트의 QA·기획 및 서버 개발 업무 수행

## 학력 · 교육

### 한국공학대학교 | 컴퓨터공학 학사

- 4년제 졸업
- 작품: NFC를 이용한 자동주문 시스템(Android 앱)

### 엔코아 AI Orchestration Engineer 과정 | 2026.08 - 2027.02 · 수강 중

- Python 백엔드, DB·세션 관리, Function Calling, 지식 저장소·장기 기억, 상태 머신 기반 흐름 제어, 멀티 에이전트 협업 설계를 학습
- 과정 소개: [멀티 에이전트 AI 오케스트레이션 캠프](https://encorecampus.ai/orchestration)
