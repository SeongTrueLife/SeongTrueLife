## 👤 Profile
**성창훈 (Sung Changhoon) · @SeongTrueLife**
 
화학공학·물리학 전공의 기술 기반, 지식재산권 법리 지식, AI 개발 경험을 바탕으로
기술과 권리, 산업 현장을 연결하는 일을 해왔습니다.
 
- 인하대학교 화학공학 전공 / 물리학 부전공
- Microsoft AI School 8기 수료, 산업 AI 기업 인턴 경험

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
* **Email:** sch629000@gmail.com
