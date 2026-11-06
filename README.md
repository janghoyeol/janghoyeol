## 안녕하세요, AI 개발자 장호열입니다 👋

데이터를 직접 만져 보며 성장하는 AI 개발자
만든 것은 직접 배포해서 써 보고, 숫자로 확인합니다

> 🔎 **꼭 보고 가세요!** 만든 AI 에이전트를 직접 써 볼 수 있는 곳 → **[showcase.hoyeol.workers.dev](https://showcase.hoyeol.workers.dev/)**

---

### 📌 MAIN PROJECT

**[inhouse-data-agent](https://github.com/janghoyeol/inhouse-data-agent)** — 가상 회사 사내 데이터 에이전트 · [데모](https://inhouse-data-agent.onrender.com)

- 💡 면접에서 SQL 질문을 많이 받았는데, 연습할 대용량 데이터가 없음
  → AI에게 가상 데이터를 부탁했더니 회사까지 만들어 줌 → 이 회사의 사내 데이터로 직접 SQL을 써 보기로 함
- 🛠️ 묻는 사람의 권한 안에서만 답하는 AI → 권한은 프롬프트가 아니라 DB가 거름
  → 2단계: 사내 규정 문서를 찾아 원문 인용, 환불은 AI가 제안만 하고 승인은 사람이
- ✍️ 함정·권한 정답 SQL 17개는 직접 씀
- 📈 정답셋 50문항 정확도 **98%** · 다른 권역·개인정보 노출 **0건** · 환불 제안 38번 중 37번 정확

### 🧩 SUB PROJECTS

| 프로젝트 | 한 줄 | 결과 |
| --- | --- | --- |
| [korea-data-mcp](https://github.com/janghoyeol/korea-data-mcp) | 공공데이터 에이전트 4개(통계·공시·대기질·실거래가)의 도구 16개를 MCP 서버 하나로 | 원래 에이전트와 같은 답, 같은 공시 접수번호 |
| [trend-agent](https://github.com/janghoyeol/trend-agent) | 검색어가 갑자기 뜨면 왜 떴는지 → 급등은 코드가 찾고, 원인은 Claude가 기사와 함께 설명 | 원인이 알려진 급등 37건 중 78% 적중 |
| [nsmc-sentiment-classifier](https://github.com/janghoyeol/nsmc-sentiment-classifier) | 남이 학습시킨 모델 없이 토크나이저·작은 GPT를 처음부터 | 테스트 정확도 82.4% (사전학습 없으면 71.2%) |

공공데이터 에이전트: [stat-agent](https://github.com/janghoyeol/stat-agent) · [corp-agent](https://github.com/janghoyeol/corp-agent)

### 🗂️ 이전 프로젝트 (백엔드)

Realtime Board · PR Guardian · [TaskTriage](https://github.com/janghoyeol/tasktriage) · Curiosity Teacher
→ 여기서 “규칙으로 먼저 거르고, 애매한 것만 AI에게”라는 방식을 익혔고, 지금 프로젝트에도 그대로 씀

---

### 🛠️ SKILLS

| 분야 | 기술 |
| --- | --- |
| AI | Claude API(tool use), MCP, 정답셋 평가 설계, PyTorch |
| 데이터 | SQL, PostgreSQL(행 단위 보안·열 권한·전문 검색), pandas |
| 백엔드 | Python·FastAPI, Java·Spring Boot, Redis, WebSocket |
| 배포 | Docker, GitHub Actions, Render, Neon, Cloudflare Workers |

### 🎓 ETC

- 선문대학교 컴퓨터공학 졸업 (2024.08)
- 정보처리기사 (2024.12) · Microsoft AI-900 (2023.07)
- 인공지능 개발자 부트캠프 최우수상 (2024.08) · 한국디지털콘텐츠학회 하계학술대회 동상 (2024.06)

📫 jhy9732@naver.com
