# 🧠 AI Agent Study

AI Agent 공부 노트

---

## 📌 1. AI Agent란?

**AI Agent**는 LLM 기반으로 동작하며, 다양한 외부 도구 및 환경과 상호작용하면서 **스스로 계획을 수립하고, 실행하며, 피드백을 반영해 작업을 수행**할 수 있는 시스템.

기본적인 질문-응답을 넘어, 실제 애플리케이션 수준의 **지능적 자동화**를 목표.

**주요 기능**
- 목표 기반 문제 해결
- 도구 활용 (예: 웹 검색, 계산기, 데이터베이스 질의)
- 체계적인 계획 수립 및 단계별 실행
- 복잡한 워크플로우 자동화

---

### 🧩 2. 주요 구성 요소

| 구성 요소        | 설명 |
|------------------|------|
| **LLM (언어 모델)** | 에이전트의 지능을 담당하는 핵심 모델 (예: GPT-4, Claude, Gemini 등) |
| **Tool / API**    | 외부 기능을 호출하기 위한 수단 (예: Web Search, Calculator, File I/O 등) |
| **Memory**        | 과거 대화나 실행 이력을 저장하여 문맥 유지 |
| **Planner**       | 복잡한 작업을 여러 단계로 쪼개서 계획 수립 |
| **Executor**      | 계획에 따라 각 단계를 실제로 수행 |

---

### ⚙️ 3. 대표 프레임워크

| 프레임워크 | 특징 |
|------------|------|
| **LangChain** | 체인과 툴 기반 구성, AgentExecutor로 에이전트 작성 가능 |
| **AutoGen** | 여러 Agent 간 협업을 중심으로 설계된 Microsoft 오픈소스 |
| **CrewAI** | 역할 기반 다중 에이전트 구성 가능 (Planner, Researcher 등) |
| **OpenAgents** | HuggingFace 기반, 강력한 플러그인 생태계 제공 |

---

### 🚀 4. 활용 사례

- ✅ 자동화된 웹 리서치 Agent
- 📊 데이터 분석 및 시각화 Agent
- 🧾 고객 응대 챗봇 (복잡한 상담 지원)
- 💼 비즈니스 업무 자동화 (문서 요약, 일정 조율 등)
- 🔧 코드 작성 및 테스트 자동화

---

### 📚 5. 학습 자료

- LangChain 공식 문서: https://docs.langchain.com
- LangGraph : https://www.langchain.com/langgraph
- AutoGen GitHub: https://github.com/microsoft/autogen
- CrewAI 공식 문서: https://docs.crewai.io

---

![img](https://assets.weforum.org/editor/bUeTzLBRMGW-3J0robJ6gVH9ZCusP7KebufwSFGXVgA.png)
