<div align="center">

# 안녕하세요, 문제를 '성과로' 바꾸는 PM 김제현입니다 👋

**Product Manager** · 사용자의 숨겨진 니즈를 찾아 데이터로 검증하고, 제품 성장으로 연결합니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://j-hyunn.github.io/portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jehyunn)
[![Email](https://img.shields.io/badge/lab.jehyun@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lab.jehyun@gmail.com)

</div>

---

## 🧭 About Me

- 🔍 사용자 **행동 데이터와 인터뷰**로 문제를 정의하고, 제품 구조로 바꿔 성과를 만듭니다.
- 📊 전환율 · 처리시간 · 오류율 · 응답률처럼 **측정 가능한 지표**로 문제를 재정의합니다.
- 🛠️ 기획 – 정책 – 협업 – 출시 – 개선까지 **End-to-End 오너십**으로 실행합니다.
- 🤖 요즘은 **AI 에이전트 설계와 바이브 코딩**으로 직접 서비스를 만들고 운영하고 있습니다.

---

## 💼 Career

| 기간 | 회사 | 도메인 | 직무 |
|---|---|---|---|
| 2023.11 – 2025.09 | **Paprika Data Lab** | B2B SaaS (Form Builder) | Product Manager |
| 2022.01 – 2023.10 | **Newlink** | B2C Fintech (가상자산 거래소) | 서비스 기획 · Product Designer |
| 2020.07 – 2021.08 | **BravePeople** | B2C Commerce | BX Designer |

---

## 🎓 Education

### 🏆 [KT Cloud] Tech Up — Product Management 1기 `2025.09 – 2026.04`

> 과정 통합 프로젝트 **대상** 🥇 · 프로덕트 매니지먼트 과정 **최우수 수료생** 선정

<br/>

### ⚾ [Playball](https://j-hyunn.github.io/portfolio/projects/playball) — KBO 티켓팅 플랫폼 `2026.01 – 2026.04`

> "문제는 수요 부족이 아니라 **수요 분배의 비효율**이다."
> 모두가 같은 좌석을 동시에 클릭하며 발생하는 핫스팟 경합을, 선호 기반 **블록 추천 + 연석 자동배정**으로 해소한 과정 통합 프로젝트. (14인 팀 / Product Manager)

- **Role** — 기획 · 추천 / 대기열 / VQA 정책 설계 · KPI 정의 · 부하테스트 리드
- **분산 추천 알고리즘 설계** — 온보딩에서 수집한 선호 구역을 후보로 두고, 연석 확보 가능 수 · 선호 점수 · 블록 혼잡도로 랭킹. 노출 회전·쿨다운으로 추천발 2차 핫스팟까지 차단
- **동시성 제어** — 좌석 단위가 아닌 **블록 단위 분산 락 + Watch Dog 연장**, HOLD 5분 후 Cleanup Scheduler 자동 해제
- **AI 봇 방어** — 마우스 궤적 기반 위험 등급(T0~T3) + VQA(위치·타이밍 동시 충족) 관문. 직접 AI 공격 에이전트를 만들어 방어 체계를 역검증
- **측정 구조를 먼저 설계** — 추천 ON/OFF 태그로 분산 효과를 부하테스트에서 수치로 증명

| 지표 (추천 OFF → ON) | 결과 |
|---|---|
| 인기 좌석 경합 | 2,472건 → **0건** |
| 좌석 확보 성공률 | 60.4% → **100%** |
| 가상 유저당 HOLD 시도 | 6.24회 → **1회** |

📄 [PRD · BRD · 기능 명세 · 운영 정책 문서 보기](https://j-hyunn.github.io/portfolio/projects/playball)

<br/>

**그 외 과정 프로젝트**

- 🍽️ **캐치테이블 문화·예술 카테고리 확장** — 다이닝을 앵커로 반경 3km POI를 연결해 앱 이탈을 줄이는 카테고리 확장 기획 (POI 클릭 전환 50% / 예매 버튼 전환 60%)
- 🛡️ **뱅크샐러드 AI 보험 코치** — 마이데이터 기반 보장 공백 리포트와 멀티 에이전트 '선분석–후상담' 흐름 설계

---

## 🚀 Personal Projects

### 🎤 [Replai](https://replai-interview.vercel.app) — AI 모의면접 서비스 `2026.03 ~ 운영 중`

> "내 서류를 읽은 AI가 면접관이 되면 안 되나?"라는 질문에서 시작한 서비스.
> JD와 이력서를 교차 분석한 AI 면접관과 모의면접을 진행하고, 답변별 평가 리포트를 받습니다.

- **기획부터 출시·운영까지 1인 진행** — 서비스 기획 · 멀티 에이전트 설계 · 바이브 코딩 · 배포
- **멀티 에이전트 구조** — 분석 / 면접관 / 평가 에이전트를 역할별로 분리하고, 대화 세션이 필요한 면접관 에이전트에만 ADK Runner 적용
- **3종 면접관 페르소나** (탐색형 · 압박형 · 기술검증형) 와 온디맨드 힌트 · AI 자율 판단 꼬리질문 로직 설계
- 출시 후 스트리밍 응답, 프롬프트 분리, API 키 AES-256-GCM 암호화 등 **지속 개선 이터레이션 운영 중**

`Next.js` `Google ADK` `Gemini` `Supabase` `Vercel`

📄 [PRD · TRD · 멀티 에이전트 아키텍처 문서 보기](https://j-hyunn.github.io/portfolio/projects/replai)

<br/>

### 🗂️ [Portfolio](https://j-hyunn.github.io/portfolio) — PM 포트폴리오 사이트 `2026 ~`

> 프로젝트 산출물(PRD/BRD/정책 문서)을 그대로 열람할 수 있는 문서 중심 포트폴리오 사이트.
> 기획 · 디자인 · 구현 · 배포를 직접 진행했습니다.

`React` `TypeScript` `Vite` `Tailwind CSS` `GitHub Pages`

---

## 🧰 Skills

**Product**
`PRD & 기능 명세` `제품 로드맵 · 백로그` `GTM 전략` `퍼널 · 행동 데이터 분석` `A/B · 베타 테스트 설계`

**Design & UX**
`프로덕트 디자인` `UX 플로우 설계` `디자인 시스템` `사용성 개선`

**Tools**
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![GA4](https://img.shields.io/badge/GA4-E37400?style=flat-square&logo=googleanalytics&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

<div align="center">

**사용자의 선택을 돕는 경험을 설계하고, 데이터와 실행으로 검증합니다.**

</div>
