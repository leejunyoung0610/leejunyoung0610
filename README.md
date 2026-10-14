### 안녕하세요, 이준영입니다 👋

**데이터로 먼저 확인하고, 결과를 보기 전에 판단 기준을 정하는 백엔드·데이터 개발자**를 지향합니다.
세종대학교 컴퓨터공학과 졸업 예정

---

#### 대표 프로젝트

**🏪 가게내비 — 상가 자리 이력 서비스** · 개인 · 개발 중 (저장소 공개 준비 중)
- 서울 식품 인허가 공공데이터 **704,116건**을 건물·층 단위 이력으로 정리하고, 같은 조건 자리의 폐업률을 보여줍니다.
- 통계 판정 기준을 **결과보다 먼저 커밋(사전 등록)** 하고, 재현 테스트로 원 분석 스크립트의 누락 버그(1,000㎡ 이상 점포 880건)를 찾았습니다.
- 주소 검색 일치율 **95.85%**(무작위 2,000건, 95% CI 94.88~96.64%), 외부 API 키가 로그·테스트 파일에 남지 않는 구조.
- FastAPI · PostgreSQL/PostGIS · SQLAlchemy(async) · Next.js · GitHub Actions

**🐾 [GANADI](https://github.com/leejunyoung0610/capstone_petcare) — 반려동물 안구질환 AI 스크리닝** · 캡스톤 4인 팀 팀장
- 모델이 질환 대신 촬영 기기 특징으로 판별하는 **지름길 학습**을 찾아내고, 판별 헤드를 바꾼 실험에서 Top-1 **27.25% → 53.77%**, Top-3 **51.65% → 84.35%** (검증 데이터 기준 오프라인 평가).
- ONNX 변환으로 CPU 추론 **443ms → 38ms(11.6배)**, INT8 양자화로 모델 **214MB → 18MB**.
- EfficientNet-B3 · FastAPI · React · MySQL · AWS

**🌍 [Living World Engine](https://github.com/leejunyoung0610/living-world-engine) — LLM 출력 검증·비용 통제 백엔드 (AI 대화형 RPG)** · 1인 풀스택
- "LLM은 상태를 제안하고, 시스템이 검증한다": LLM이 제안한 상태 변경은 검증기(변화량 상한·변경 사유 필수)를 통과한 것만 반영합니다.
- 턴별 토큰·비용 기록, 일일 비용 경보, 동시 요청에도 원자적으로 차감되는 턴 할당량, API 호출 제한, Sentry · LLM을 목(mock)으로 대체한 테스트 382개.
- FastAPI · PostgreSQL · Docker · React/TypeScript · Claude Tool Use

**🎓 [ABEEK 자동 판정 시스템](https://github.com/leejunyoung0610/sejonghackathon) — 공학인증 졸업요건** · 세종대 해커톤 5인 팀
- 11개 학과(트랙 포함 13개)의 2021~2026 교과과정과 인증 규칙을 SQL 시드 데이터로 만들고, 과목 매칭·설계이수 순서·학과별 대체 규칙을 판정하는 엔진을 구현.
- Spring Boot 3 · JPA · MySQL 8 · Docker Compose

---

#### 일하는 방식
- **만들기 전에 데이터로 판단합니다.** 가게내비는 코드를 쓰기 전에 공공데이터로 "이 서비스가 의미 있는 숫자를 줄 수 있는가"부터 확인했습니다.
- **틀린 값보다 빈 값.** 모르는 값은 추측해서 채우지 않고, 사용자에게 보이는 부정적 표시는 근거가 강한 것만 냅니다.
- **AI 에이전트와 일해도 판단은 직접.** 구현은 AI 코딩 에이전트와 나누되, 범위·판단 기준·검증·머지는 제가 맡고 모든 결정을 기록으로 남깁니다.

#### Tech
`Python` `FastAPI` `Java` `Spring Boot` `PostgreSQL/PostGIS` `MySQL` `SQLAlchemy` `pandas` `PyTorch` `ONNX` `React` `Next.js` `TypeScript` `Docker` `GitHub Actions` `AWS`
