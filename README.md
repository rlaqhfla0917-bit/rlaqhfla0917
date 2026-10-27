<div align="center">
  <img src="./assets/profile-hero.svg" alt="BORIM KIM | AI Service Engineering" width="100%" />

  <br/>

  **현장에서 발견한 문제를 데이터와 소프트웨어로 해결합니다.**  
  AI Agent를 개발하며 사용자의 요청, 실행 권한, 예외 상황과 검증 방법을 함께 고민합니다.

  `AI Agent` &nbsp; `RAG / Knowledge Graph` &nbsp; `Backend API` &nbsp; `Testing`
</div>

<br/>

## Selected work

대표 프로젝트는 **직접 구현한 내용**, **공개 시연의 범위**, **검증 근거**를 구분해 정리했습니다.

<a href="https://github.com/rlaqhfla0917-bit/ai-office-assistant">
  <img src="./assets/project-agent.svg" alt="AI OFFICE ASSISTANT" width="100%" />
</a>

**[AI 업무비서 — LangGraph 기반 업무 Agent](https://github.com/rlaqhfla0917-bit/ai-office-assistant)**

Python과 LangGraph를 이용해 자연어 요청을 SQL 조회·RAG 문서 검색으로 분기하고, 사용자 권한을 확인한 뒤 메일·업무 변경 등 쓰기 작업 전에 `interrupt()` 승인을 받는 흐름을 구현했습니다.

[구현 코드 ↗](https://github.com/rlaqhfla0917-bit/ai-office-assistant) · [안전성 회귀 테스트 ↗](https://github.com/rlaqhfla0917-bit/ai-office-assistant/blob/main/tests/test_agent_safety.py) · [자동 테스트 결과 ↗](https://github.com/rlaqhfla0917-bit/ai-office-assistant/actions)

<sub>공개 Streamlit 시연은 모의 데이터·읽기 중심입니다. 실제 메일 전송은 제공하지 않습니다.</sub>

<br/><br/>

<a href="https://github.com/rlaqhfla0917-bit/AERON">
  <img src="./assets/project-aeron.svg" alt="AERON aircraft maintenance knowledge graph" width="100%" />
</a>

**[AERON — 항공정비 지식그래프 기반 AI](https://github.com/rlaqhfla0917-bit/AERON)**

현직 정비사 인터뷰를 바탕으로 정비 매뉴얼·부품·결함 관계를 Neo4j에 구조화했습니다. Node.js와 Cypher를 활용한 근거 조회, RAG 응답 및 LLM 실패 시 규칙 기반 대체 응답을 구현했습니다.

[구현 코드 ↗](https://github.com/rlaqhfla0917-bit/AERON) · [웹 시연 ↗](https://rlaqhfla0917-bit.github.io/AERON/) · [코드 검사 ↗](https://github.com/rlaqhfla0917-bit/AERON/actions)

<sub>웹 시연은 가상의 정적 화면이며 실제 Neo4j 및 LLM에 연결되지 않습니다. 검색시간 단축은 목표이며 실측 결과가 아닙니다.</sub>

<br/><br/>

<a href="https://github.com/rlaqhfla0917-bit/skycare-disruption-api">
  <img src="./assets/project-skycare.svg" alt="SkyCare disruption backend" width="100%" />
</a>

**[SkyCare — 항공 지연·결항 대응 API](https://github.com/rlaqhfla0917-bit/skycare-disruption-api)**

FastAPI에서 대체편 조회, PostgreSQL 장애 시 모의 데이터 폴백, Redis Queue 예약 요청 접수와 Queue·DLQ 길이 조회를 구현했습니다. 장애 대응 경로를 회귀 테스트로 확인합니다.

[구현 코드 ↗](https://github.com/rlaqhfla0917-bit/skycare-disruption-api) · [웹 시연 ↗](https://rlaqhfla0917-bit.github.io/skycare-disruption-api/) · [예외 테스트 ↗](https://github.com/rlaqhfla0917-bit/skycare-disruption-api/actions)

<sub>정적 웹 시연은 실제 항공사와 연결되지 않습니다. 예약 완료 Worker·실제 환불 연동은 구현 범위가 아닙니다.</sub>

<br/>

## More engineering

| Project | What I built |
| :--- | :--- |
| [**Seafood Dynamic Pricing API**](https://github.com/rlaqhfla0917-bit/seafood-dynamic-pricing-api) | 신선도·어획량·재고 6개 규칙에 따른 가격 계산, 주문·재고 처리, `409` 예외 및 API 자동 테스트. **발표자료 기반 재구현** |
| [**Budget Meal Planner**](https://github.com/rlaqhfla0917-bit/budget-meal-planner) | 공공 영양 데이터 정합성 검토, SciPy MILP 기반 예산·영양 조건 최적화 및 테스트. **Streamlit Cloud 공개 배포 완료(2026-10-15)** |
| [**TRACE**](https://github.com/rlaqhfla0917-bit/trace-sample-handover) | 해양 조사 시료 인수인계 업무를 바탕으로 만든 FastAPI·SQLite MVP. **가상 데이터로 재구현** |
| [**CloudOps Assistant**](https://github.com/rlaqhfla0917-bit/cloudops-ai-assistant) | 가상 클라우드 장애 시나리오 분류, FastAPI·pytest 및 GitHub Actions |
| [**Fraud API**](https://github.com/rlaqhfla0917-bit/fraud) | AWS Lambda·API Gateway·DynamoDB 기반 서버리스 신고 API |
| [**Nutri Deck**](https://github.com/rlaqhfla0917-bit/nutri) | 공공 영양 데이터 기반 React·TypeScript 교육용 카드·보드게임 |
| [**MarineFlow**](https://github.com/rlaqhfla0917-bit/marine-sample-ai-workflow) | 해양 시료 등록·인계·분석 검증·근거 검색·보고서 초안까지 잇는 Streamlit 기반 업무 워크플로 MVP. **현장 경험을 바탕으로 한 가상 데이터 프로토타입** |

<br/>

## Toolbox

**AI & Data** — LangGraph · RAG · Neo4j · Cypher · ChromaDB · pandas · scikit-learn

**Backend** — Python · FastAPI · SQL · PostgreSQL · SQLite · Node.js

**Infra & Validation** — Docker · Redis · AWS · pytest · unittest · GitHub Actions

**Interface** — Streamlit · React · TypeScript

<br/>

## About

- **KT AIVLE School DX Consultant 9기** 수료
- **AERON 항공정비 AI 프로젝트** 7인 팀 PM · 빅프로젝트 우수상
- **KT AIVLE School 우수 기자단**
- **해양 분야 약 3년** — 현장조사, 제안서·발주처 협의, 시료 인수인계 개선

---

<div align="center">
  <sub>Build thoughtfully. Verify carefully.</sub>
</div>
