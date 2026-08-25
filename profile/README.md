<div align="center">
  <img src="https://raw.githubusercontent.com/klaroworks/.github/main/profile/images/banner.png" alt="Klaro — AI가 노동을 대신합니다. 결과는 사람이 검증하고 승인합니다." width="100%">
</div>

<p align="center">
  <a href="https://klaroworks.ai">Website</a>
  &nbsp;·&nbsp;
  <a href="mailto:contact@klaroworks.ai">Contact</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/klaroworks/handbook">Handbook</a>
</p>

<br/>

주식회사 클라로는 공공기관과 금융기관의 문서·데이터 업무를 AI가 대신 처리하도록 만듭니다. 대신, 결과를 그대로 내보내지 않습니다. AI가 만든 초안에는 근거가 붙고, 담당자가 검토·승인한 뒤에야 업무에 반영되며, 그 판단은 기록으로 남습니다.

기관에서 AI를 쓰기 어려운 진짜 이유는 성능이 아니라 책임입니다. 자료가 시스템과 개인 폴더에 흩어져 있고, AI는 조직의 기준과 과거 판단을 모른 채 답하며, 담당자는 초안의 수치를 원문과 다시 대조해야 합니다. 우리는 AI를 도구 하나로 더 얹는 대신, 기관이 이미 가진 자료와 검토 과정을 하나의 업무 흐름으로 잇습니다.

<div align="center">
  <img src="https://raw.githubusercontent.com/klaroworks/.github/main/profile/images/trust-stack.png" alt="근거 · 승인 · 감사 — 하나의 신뢰 스택" width="92%">
</div>

## Klaro Hub — 지식노동 자동화

문서·DB·API를 권한 범위 안에서 연결하고, 질문이 오면 원문을 인용·조회해 근거를 먼저 모은 뒤 초안을 만듭니다. 검색은 키워드와 벡터를 함께 쓰고, 찾은 근거를 다시 순위 매겨 수치를 확인합니다. 근거가 모자라면 답을 지어내지 않고 안내로 넘어갑니다(교정형 RAG). 공공 문서의 사실상 표준인 한글(HWPX)로 바로 출력하고, 검토·승인 흐름은 MCP Elicitation 표준 위에 올렸습니다. 모델은 vLLM·Ollama에 LoRA를 얹어 자체 서빙하므로, 데이터를 밖으로 내보내지 않고 폐쇄망에서 단독으로 돌 수 있습니다.

<div align="center">
  <img src="https://raw.githubusercontent.com/klaroworks/.github/main/profile/images/hub-pipeline.png" alt="Klaro Hub 파이프라인: 연결 → 근거 → 초안 → 검토·승인 → 감사" width="100%">
</div>

**쓰는 곳** — 규정·회계 질의응답, 공문·보고서 작성, 기관 지식 검색·상담, 기업 심층분석과 공급망 리스크 모니터링.

**운영 중인 현장** — 서울시여성가족재단 *안심회계봇*(회계 규정 QA, 실서비스), 서울AI재단 업무매뉴얼 Q&A, 국내 시중은행 RM 기업분석 Agent.

## Klaro Forge — 개발노동 자동화

레거시 시스템 전환을 에이전트가 수행하되, 코드를 반영하기 전에 근거를 만듭니다. 컴파일과 정적 점검, SQL Diff, 기준 입출력 비교를 붙여 "컴파일만 통과"로 끝내지 않습니다. TA·AA·QA·PM의 승인 이력이 산출물과 함께 남고, 소스는 고객 환경 밖으로 나가지 않습니다. 검증 환경으로 C·ECPG 기간계 레거시 2,000본이 넘는 전환 픽스처를 직접 만들어 씁니다.

<div align="center">
  <img src="https://raw.githubusercontent.com/klaroworks/.github/main/profile/images/forge-pipeline.png" alt="Klaro Forge 파이프라인: 분석 → 전환 → Evidence → Approval → 납품" width="100%">
</div>

**현장** — 대형 카드사 EOS 대응 재구축(SI 원청 협업).

## 팀

이시헌(CEO)은 금융·공공 AI 프로젝트를 이끌고 제품을 기획합니다. 최형우(CTO)는 플랫폼·인프라·AI 엔지니어링을 맡습니다. 2026년 서울에서 시작했습니다.

우리가 일하는 방식은 [handbook](https://github.com/klaroworks/handbook)에 적어 둡니다.

<div align="center">
<sub>Seoul, Korea · 주식회사 클라로 · <a href="mailto:contact@klaroworks.ai">contact@klaroworks.ai</a></sub>
</div>
