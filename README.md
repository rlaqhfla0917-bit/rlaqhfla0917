# 김보림 | AI 서비스 개발 · AI 신뢰성 검증

해양 조사 현장의 업무 문제를 웹 시스템으로 개선한 경험을 계기로 Python·AI·데이터 기반 서비스 개발을 공부했습니다. KT AIVLE School DX 컨설턴트 과정에서 AI Agent, 지식그래프, API 및 클라우드 프로젝트를 진행했습니다.

**관심 분야:** AI Agent · RAG · API · 테스트 자동화 · 예외 처리 · 신뢰성

## 대표 프로젝트

| 프로젝트 | 직접 확인할 수 있는 구현 | 기술 / 공개 시연 |
| --- | --- | --- |
| **[AI 업무비서](https://github.com/rlaqhfla0917-bit/ai-office-assistant)** | 자연어 의도 분기, SQL·문서 검색, 업무별 권한 검사, 메일·업무 변경 전 `interrupt()` 승인 | Python · LangGraph · SQLite · ChromaDB(설정에 따라 키워드 폴백). **공개 Streamlit 데모는 모의 데이터·읽기 중심이며 메일 전송은 비활성화** |
| **[AERON 항공정비 AI](https://github.com/rlaqhfla0917-bit/AERON)** | Neo4j 관계 검색, Node.js 백엔드, 정비 근거 기반 RAG/LLM 응답, 실패 시 규칙 기반 폴백 | Node.js · Neo4j · Cypher · RAG · LLM. [정적 웹 시연](https://rlaqhfla0917-bit.github.io/AERON/) — **실제 DB·LLM 미연결** |
| **[SkyCare 항공 지연·결항 API](https://github.com/rlaqhfla0917-bit/skycare-disruption-api)** | 대체편 DB 조회 및 모의 데이터 폴백, 예약 요청 Redis Queue 등록, Queue·DLQ 길이 조회, 예약 목록 API | Python · FastAPI · PostgreSQL · Redis. [정적 웹 시연](https://rlaqhfla0917-bit.github.io/skycare-disruption-api/) — **실제 항공사 시스템 미연결** |

> **코드/데모 구분:** 공개 정적 화면은 사용 흐름을 설명하기 위한 시연입니다. 구현 범위와 로컬 실행 조건은 각 저장소 README에 명시했습니다. 실제 테스트 결과가 없는 기능을 검증 완료라고 표시하지 않습니다.

## 개발·검증 근거

- **[AI 업무비서 안전성 테스트](https://github.com/rlaqhfla0917-bit/ai-office-assistant/tree/main/tests)** — 역할별 접근, 승인 거절 시 쓰기 금지, 승인 후 처리, 메일 발송 차단 등 회귀 테스트와 자동 실행 설정
- **[수산물 동적 가격 API](https://github.com/rlaqhfla0917-bit/seafood-dynamic-pricing-api)** — 6가지 신선도·어획량·재고 조건, 합산식 가격 엔진, FastAPI 응답·재고 부족 409 테스트. KT AIVLE School 발표자료 기반 **포트폴리오 재구현**
- **[예산 맞춤형 식단 추천](https://github.com/rlaqhfla0917-bit/budget-meal-planner)** — 공공 데이터 품질 관리, SciPy MILP 기반 조건 최적화, 회귀 테스트. **현재 배포 준비 단계**
- **[TRACE 시료 인수인계](https://github.com/rlaqhfla0917-bit/trace-sample-handover)** — 현장 실무 문제에서 출발한 FastAPI·SQLite 웹 MVP. **실근무 당시 원본이 아니라 가상 데이터로 재구현한 프로토타입**
- **[CloudOps 장애 분석 MVP](https://github.com/rlaqhfla0917-bit/cloudops-ai-assistant)** — 규칙 기반 장애 분류 및 FastAPI·pytest, [GitHub Actions 실행 이력](https://github.com/rlaqhfla0917-bit/cloudops-ai-assistant/actions)

그 외: [금융사기 신고 서버리스 API](https://github.com/rlaqhfla0917-bit/fraud) · [영양 교육 웹 게임](https://github.com/rlaqhfla0917-bit/nutri)

## 기술 스택

**개발** Python · FastAPI · SQL · SQLite · PostgreSQL · Node.js · JavaScript · TypeScript  
**AI/Data** LangGraph · RAG · Neo4j/Cypher · ChromaDB · pandas · scikit-learn  
**인프라/검증** Docker · Redis · AWS EC2/RDS/Lambda/API Gateway · pytest · unittest · GitHub Actions  
**UI** Streamlit · React

기술별 구현 범위는 각 프로젝트의 소스와 README에서 확인할 수 있습니다.

## 경험

- KT AIVLE School DX Consultant 9기 수료
- 7인 팀 AERON 빅프로젝트 PM · 우수상
- KT AIVLE School 우수 기자단
- 해양 분야 약 3년: 현장조사, 제안서·발주처 자료, 일정 협의, 시료 인수인계 업무 개선

**GitHub:** https://github.com/rlaqhfla0917-bit
