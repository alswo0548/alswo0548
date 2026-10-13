<!--
  GitHub 프로필 README
  - 올리는 곳: alswo0548/alswo0548 저장소(사용자 이름과 같은 이름의 Public 저장소)의 README.md
  - 이미지·링크: alswo0548/portfolio 저장소를 가리킵니다. (portfolio 저장소를 먼저 올려야 이미지가 보입니다)
  - 수정 방법: portfolio 저장소의 docs/APPLY_GUIDE.md 참고
-->

# 이민재

**AI 서비스 · Python 백엔드 개발자**

**데이터를 안전하게 저장하고 판단하는 서버**를 만들고, **LLM·AI 기능을 실제 서비스 흐름에 연결**합니다.<br>
K-Digital Training AI·데이터 분석 과정에서 팀 프로젝트 2개를 진행했고, 최종 프로젝트 **OCTV**는 팀장으로 개발하고 있습니다.

- **관심 직무** &nbsp; AI 서비스·LLM 개발 · 머신러닝/딥러닝 개발 · 데이터 분석 · Python 백엔드
- **주요 기술** &nbsp; Python · FastAPI · PostgreSQL · SQLAlchemy · psycopg · LangGraph · OpenAI API · Celery · Redis · Docker
- **포트폴리오** &nbsp; 프로젝트를 누르면 시연 화면 → 기술 상세 문서 순서로 볼 수 있습니다. &nbsp;[전체 목록 보기](https://github.com/alswo0548/portfolio)

<br>

## 대표 프로젝트

<a href="https://github.com/alswo0548/portfolio/blob/main/projects/01-octv/README.md"><img align="right" width="46%" src="https://raw.githubusercontent.com/alswo0548/portfolio/main/assets/01-octv/thumbnail.png" alt="OCTV 썸네일 — 통합관제 WEB 목업 화면"></a>

### 01 · OCTV

**AI 재난 CCTV 대응 지원 시스템**<br>
`최종 프로젝트` `2인 팀 · 팀장` `개발 중`

CCTV로 탐지한 재난 사건의 위험도와 대응 우선순위를 판단하고, 대응 기관·접근 경로 결정을 돕는 관제 플랫폼

**기술** &nbsp;FastAPI · PostgreSQL · psycopg · Celery · Redis · FastMCP<br>
**담당** &nbsp;DB 설계 · 사건 저장·조회 API · 기관별 조회 권한 · AI 판단 작업 큐 · 외부 API·MCP 연동

[**프로젝트 보기 →**](https://github.com/alswo0548/portfolio/blob/main/projects/01-octv/README.md) &nbsp;·&nbsp; [기술 상세](https://github.com/alswo0548/portfolio/blob/main/projects/01-octv/TECHNICAL.md)

<br clear="right">

<a href="https://github.com/alswo0548/portfolio/blob/main/projects/02-gooddeedquest/README.md"><img align="right" width="46%" src="https://raw.githubusercontent.com/alswo0548/portfolio/main/assets/02-gooddeedquest/thumbnail.png" alt="GoodDeedQuest 썸네일 — 커뮤니티 피드와 AI 친구 추천 화면"></a>

### 02 · GoodDeedQuest

**AI 기반 선행 퀘스트 플랫폼**<br>
`중간 프로젝트` `5인 팀` `완료`

선행을 게임 퀘스트처럼 수행하는 모바일 앱. 개인화 커뮤니티 피드와 LLM 기반 팀원 추천을 구현

**기술** &nbsp;FastAPI · SQLAlchemy · LangGraph · GPT-4o<br>
**담당** &nbsp;커뮤니티 추천 알고리즘 · 팀 챌린지 · AI 팀원 추천 · 관리자

[**프로젝트 보기 →**](https://github.com/alswo0548/portfolio/blob/main/projects/02-gooddeedquest/README.md) &nbsp;·&nbsp; [기술 상세](https://github.com/alswo0548/portfolio/blob/main/projects/02-gooddeedquest/TECHNICAL.md) &nbsp;·&nbsp; [소스코드](https://github.com/QuestismTeam/GoodDeedQuest)

<br clear="right">

<a href="https://github.com/alswo0548/portfolio/blob/main/projects/03-climbing-web/README.md"><img align="right" width="46%" src="https://raw.githubusercontent.com/alswo0548/portfolio/main/assets/03-climbing-web/thumbnail.png" alt="Climbing Web 썸네일 — 메인 화면과 클라이밍장 지도 화면"></a>

### 03 · Climbing Web

**클라이밍장 · 선수 정보 웹사이트**<br>
`개인 프로젝트` `1인` `완료`

클라이밍 종목 소개, 지도 기반 클라이밍장 찾기와 성향 설문 추천, 선수 기록 차트를 담은 5페이지 웹사이트

**기술** &nbsp;JavaScript · Kakao Maps API · OpenWeather API · Chart.js<br>
**구현** &nbsp;화면 설계 · 지도 검색 · 로드뷰 · 날씨 · 설문 추천 TOP 3 · 선수 검색·필터 · 차트

[**프로젝트 보기 →**](https://github.com/alswo0548/portfolio/blob/main/projects/03-climbing-web/README.md) &nbsp;·&nbsp; [기술 상세](https://github.com/alswo0548/portfolio/blob/main/projects/03-climbing-web/TECHNICAL.md)

<br clear="right">

<br>

## 이렇게 일합니다

- **데이터 규칙은 DB에서 먼저 보장합니다.** 중복 사건 방지는 부분 UNIQUE 인덱스로, 기관별 조회 범위는 SQL 조건으로 강제합니다.
- **LLM 출력은 그대로 믿지 않습니다.** Schema 검증 · 후보 대조 · 규칙 기반 대체 문구로 LLM이 실패해도 기능이 멈추지 않게 합니다.
- **위험한 경로를 테스트로 남깁니다.** 권한 우회 · 중복 저장 · 마이그레이션 실패 경로를 단위 테스트와 CI로 확인합니다.

<!--
## Contact
연락처를 공개하려면 이 주석을 풀고 이메일을 적으세요.
- Email: your-email@example.com
-->
