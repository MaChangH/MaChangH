# 마창현 · Changhyun Ma

**AI/ML & Data Engineer**

흩어진 정보를 모아 판단을 돕고, 반복 작업을 줄이는 AI·데이터 도구를 만듭니다.
제품 비교, AI 대화 기록, 시장 데이터 연구와 콘텐츠 제작을 위한 도구를 개발합니다.
사용 흐름과 데이터 구조를 설계하고, 구현한 기능과 검증한 범위를 함께 설명합니다.

[GitHub](https://github.com/MaChangH) · [이메일](mailto:mch0729@naver.com)

## 진행 중인 프로젝트

*소개 업데이트: 2026년 10월 22일*

### OpenVentra — 근거를 남기는 제품 비교와 지식 관리

기업·제품·요금제 정보를 여러 곳에서 찾다 보면 가격을 언제 확인했는지, 판단이 왜 바뀌었는지 놓치기 쉽습니다. 자료마다 출처와 확인 시각을 연결하고, 사용자의 조건에 맞춰 같은 기준으로 비교하는 도구를 만들고 있습니다.

- **만든 기능:** 기업·제품·요금제 자료집, 원문 인용, 출처 변경·충돌 표시, 제품 비교, 실행 결과와 판단 이력, MCP 연결.
- **담당 작업:** 제품·데이터 모델 설계, PostgreSQL 기반 이력 관리, 자료 수집·비교와 AI 연결 구현.
- **현재 상태:** 로컬 고객용 파일럿 구현. 실제 고객 품질·수요 검증과 상용 운영은 별도 단계입니다.
- **기술:** Python, FastAPI, PostgreSQL, SQLAlchemy, MCP.

### PolicyTrader — 조건을 확인하며 비교하는 전략 연구 앱

전략의 결과를 비교하려면 데이터 출처, 비용, 판단 시점이 같아야 합니다. 과거 가격을 차트로 살펴보고 전략·비용·위험 조건을 바꿔 모의실행하는 로컬 앱을 개발합니다.

- **만든 기능:** Binance Vision 자료와 공식 체크섬 검사, 과거 차트, 전략 모의실행, 비용·손익 계산, 시간순 학습·평가와 정책 비교.
- **담당 작업:** 자료 검증, 전략 실행 엔진, 차트·연구 화면 구현.
- **현재 상태:** 오프라인 연구 기능 구현 및 개선 중. 실제 주문 기능이나 검증된 시장 수익성을 주장하지 않습니다.
- **기술:** Python, JavaScript, Binance Vision, Q-learning.

### Idea Wiki — AI 대화를 다음 작업으로 이어가는 도구

여러 AI 서비스에 흩어진 대화에서 이전 결정과 미해결 질문을 다시 찾는 문제를 다룹니다. 선택한 대화를 로컬 Markdown 파일로 저장하고 프로젝트별 검색·인수인계·재개로 연결합니다.

- **만든 기능:** ChatGPT·Gemini 대화 동기화, 선택한 Hermes 세션 가져오기, 프로젝트 연결, 원문 검색, 근거가 있는 요약과 재개 브리핑.
- **담당 작업:** 브라우저 확장, 로컬 수신기와 CLI, 동기화·검색·요약 검증 구현.
- **현재 상태:** 로컬 저장·검색과 GPT·DeepSeek 요약 구현. 요약할 때만 선택한 본문을 지정 모델에 전달합니다.
- **기술:** TypeScript, Node.js, WXT, Markdown.

### VideoAutomationLab — 명화에서 이야기와 영상으로

명화의 배경과 인물 이야기를 조사하고 대본·장면·영상·자막으로 만드는 제작 흐름을 개발합니다. 생성한 장면을 다시 수정할 수 있도록 소재와 편집 프로젝트를 함께 관리합니다.

- **만든 흐름:** 작품 조사 → 대본·컷 검토 → 참조 이미지와 영상 생성 → 원본 저장·파일 검사 → 자막·편집·품질 검토.
- **담당 작업:** 작품 조사와 이야기 구성, 생성 도구 연결, 파일 검증과 편집 흐름 설계.
- **현재 상태:** 실제 영상과 편집 검토본 제작. 인물·장면의 일관성을 개선하고 있으며 최종 시청·청취 검수는 별도입니다.
- **도구:** Google Flow, FilmCraft, FFmpeg, Python.

### TokenRiskLab — 토큰 위험 판단의 근거를 추적하는 연구

잔고 숫자만으로 설명하기 어려운 신규 토큰의 배분·권한·유동성·거래 흐름을 다룹니다. 원본 사건과 계산한 상태를 구분하고, 위험 근거와 모르는 부분을 함께 남깁니다.

- **만든 기능:** 합성 사건 재생, SQLite 원장, 중복 반영 방지, 확정 사건 기준 잔고 계산, 권한별 잔여량과 위험 근거 보고.
- **담당 작업:** 사건·상태 모델, 재처리와 비용 예약 규칙 구현.
- **현재 상태:** 첫 오프라인 구현. 실제 Pump.fun 수집·온체인 해석은 미연결이며, 합성 결과를 실전 탐지 정확도로 제시하지 않습니다.
- **기술:** Python, SQLite, JSONL.

### AI Daily Telegram Bot — 새 AI 소식을 모아 전달하는 자동화

매일 여러 뉴스·논문·블로그를 방문하는 반복 작업을 줄이기 위해, 새 글을 수집하고 요약해 텔레그램으로 전달하는 흐름을 만들었습니다.

- **만든 기능:** 13개 소스의 수집 설정, 새 글 선별, Gemini 요약, 텔레그램 전달, 전송 없는 시험 실행과 예약 실행.
- **담당 작업:** 수집·중복 제외·요약·전송 연결, 일시 오류 재시도와 사용량 개선.
- **현재 상태:** 파이프라인과 GitHub Actions 구성. 13개는 설정한 소스 수이며 실시간 가동률·요약 정확도는 별도 측정 대상입니다.
- **기술:** Python, Gemini API, Telegram Bot API, GitHub Actions.

## 기존 주요 사례

| 프로젝트 | 해결한 문제와 구현 | 결과를 해석할 범위 |
| --- | --- | --- |
| [NIPA-TP](https://github.com/MaChangH/NIPA-TP) | 한국어 구직 질의와 채용공고의 검색 불일치 개선. 팀장으로 데이터 처리와 임베딩 모델 개선 담당 | 272개 고정 검증 질의에서 HitRate@10 **0.72 → 0.99**, MRR@10 **0.53 → 0.97**을 측정한 팀 프로젝트 |
| [Franchise Ops Copilot](https://github.com/MaChangH/franchise-ops-copilot) | 매장 이상 징후 확인부터 근거 추적·발주 제안·사람의 승인까지 연결하는 운영 콘솔 구현 | 합성 데이터와 로컬 MCP를 사용하는 포트폴리오 데모. 40개 결정론적 평가 사례 |
| Project Finder | 로컬 Git 프로젝트를 요약·색인하고 자연어로 찾는 CLI 구현 | 로컬 Ollama 사용. 변경 없는 프로젝트는 요약·임베딩을 다시 호출하지 않음 |

코드 링크는 공개 저장소에만 연결했습니다. 연구용 모의실행, 합성 데이터 결과와 실제 서비스 운영 성과는 구분합니다.

## What I build

I build AI and data tools that bring information together, support decisions, and reduce repetitive work.
My current projects cover product research, conversation continuity, market-data experiments, and content production.

| Current project | Focus | Current boundary |
| --- | --- | --- |
| OpenVentra | Source-backed product comparisons, knowledge reuse, and judgment history through MCP | Local customer pilot; customer quality and demand remain unvalidated |
| PolicyTrader | Historical charts, strategy simulation, cost modeling, and chronological policy evaluation | Offline research; no live orders or validated market profitability |
| Idea Wiki | Selected AI conversations, local project search, source-linked summaries, and resumption | Storage/search stay local; selected text goes to the chosen summary model |
| VideoAutomationLab | Artwork research, scripts, generated footage, editable projects, and review cuts | Production experiments; continuity and final audiovisual review remain separate |
| TokenRiskLab | Event replay, finality-aware balances, and traceable token-risk evidence | Synthetic offline fixtures; no live on-chain ingestion |
| AI Daily Telegram Bot | New-item collection, Gemini summaries, and scheduled Telegram delivery | Pipeline implemented; live uptime and summary accuracy are not measured claims |

<details>
<summary>자동 갱신 활동·통계 / Automated activity and statistics</summary>

아래 영역은 기존 GitHub Actions가 갱신합니다. 위 프로젝트의 성과 지표와는 별개입니다.

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

</details>
