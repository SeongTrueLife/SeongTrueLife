## 🧑‍💻 Profile
**성창훈 (@SeongTrueLife)**

화학공학·물리학 공학 베이스와 지식재산권 도메인 지식을 기반으로,
AI 프로젝트 수행 경험을 결합해
**고객 문제를 AI 솔루션으로 번역하는** 사업개발·기술영업 주니어입니다.

## 👋 About

제조·기술 현장의 복잡한 문제를 이해하고, AI로 풀 수 있는 지점을 짚어
고객·엔지니어·사업팀이 공통의 언어로 대화할 수 있도록 가교 역할을 하는 일에 관심이 있습니다.

문제를 제대로 번역하려면 기술의 원리와 한계를 직접 알아야 한다고 생각해,
아래 프로젝트들은 기획·설계·구현까지 직접 수행한 결과물입니다.
코드 자체가 최종 목적이라기보다, 고객 앞에서 솔루션의 가능성과 리스크를 
책임지고 설명할 수 있기 위한 기반으로 쌓아왔습니다.

## 🧠 Tech Stack
* **Language:** Python
* **AI / Vision:** YOLOv11, SAM (Segment Anything Model)
* **LLM / RAG:** LangChain, LangGraph, Prompt Engineering, 임베딩 모델 비교·선정
* **LLM API:** OpenAI GPT, Google Gemini, Azure OpenAI
* **Cloud:** Microsoft Azure (AZ-900 Fundamentals 인증), Azure AI Services
* **Backend:** FastAPI
* **Tools:** Git, GitHub, Docker, Power BI, Notion
* **Domain:** 화학공학(공정·반응공학·열역학), 지식재산권(특허·상표·디자인보호법)

## 🔥 Projects

### 상표권 침해 탐지·판단 AI 시스템 (TIP) — PM & Model [2026.01 ~ 2026.02]
> MS AI School 3차 프로젝트 · 6인 팀 · 최종 2위

* 현업 변리사 인터뷰로 "수동 모니터링 한계" 문제 정의, 경쟁 서비스 8개 조사 후 **"한국 상표법 특화"** 차별화 포지션 도출
* B2B 우선 진입 → B2G(지식재산처) 확장 시나리오를 30페이지 제안서로 구성, 팀 주제로 채택
* YOLOv11 + Meta SAM 조합으로 크롭 성공률 **30% → 75%** 개선
* 상표법 식별력 개념의 수학적 모델링 + LLM 판단 + 거절이유서 RAG를 LangGraph로 앙상블, **AUC 0.79 → 0.86**
* 🔗 [Repository](https://github.com/SeongTrueLife/TIP-Trademark_Project)

### 시각장애인용 알약 식별·복약 안내 서비스 (PillBuddy) — Backend·RAG·STT/TTS [2025.10]
> MS AI School 1차 프로젝트 · 6인 팀 · 최종 1위

* 시각장애인 관점의 UX 요구사항(전체 화면 터치 등) 직접 발굴·구현하여 접근성 중심 설계
* 공공 API 우선 조회 → 미존재 시 LLM 폴백 + 전문가 상담 경고 자동 삽입 구조로 의약 도메인 환각 리스크 완화 (Responsible AI)
* Azure Speech API + e약은요 공공 API + FastAPI 통합
* 🔗 [Repository](https://github.com/SeongTrueLife/PillBuddy-ms_ai_School_1st_project)

### 업무 인수인계 자동화 챗봇 (Kkuldanji) — RAG·데이터 파이프라인 [2025.12]
> MS AI School 2차 프로젝트 · 6인 팀

* 비기술 사용자가 자료 업로드만으로 RAG DB 구축 가능하도록 End-to-End 자동화
* 임베딩 모델 3종 비교(1개월 비용·한국어 성능 계산) 후 text-embedding-3-large 채택
* GPT-5.1 vs Gemini 3.0 Pro 비교 후 긴 컨텍스트 윈도우를 활용해 Gemini를 청킹 모델로 채택
* 청크 + parent_summary 동시 임베딩으로 검색 시 문맥 손실 복원
* 🔗 [Repository](https://github.com/SeongTrueLife/HoneyPot-ms_ai_school_2st_Project)

## 📖 Education
* **Microsoft AI School 8기** [2025.09 ~ 2026.02]
* **인하대학교** 화학공학 전공 / 물리학 부전공 [2009.03 ~ 2022.07]

## 🏆 Awards & Activities
* 🥇 **1위** — MS AI School 1차 프로젝트 (PillBuddy) [2025.10]
* 🥈 **2위** — MS AI School 3차 프로젝트 (TIP) [2026.02]
* 🏅 **금상** — 인하대 화학공학과 종합설계 경연대회 [2021.12]
* 🏅 **장려상** — 한국화학공학회 창의설계 경진대회 [2009]
* **출품** — Google DeepMind 'Vibe Code with Gemini 3 Pro' 해커톤 (시스템 아키텍처 설계) [2025.12]

## 📡 Links
* **GitHub:** https://github.com/SeongTrueLife
* **LinkedIn:** https://www.linkedin.com/in/chang-hun-seong-aa45b938a/
* **Email:** sch629000@gmail.com
