# 안녕하세요, 김준호입니다 👋

**프론트엔드 엔지니어 · AI 에이전트로 개발하는 사람**

복잡한 운영 도메인을 빠르고 직관적인 화면으로 풀어내고, 그 기반이 되는 플랫폼과 디자인 시스템을 만듭니다.
그리고 요즘은 **AI에게 일을 "시키는" 단계를 넘어, 안전하게 "맡기는" 개발 환경**을 설계하는 데 가장 많은 시간을 씁니다.

## AI로 일하는 방식

| 한 일 | 결과 |
|---|---|
| **LLM 코드리뷰 자동화** — PR 생성 시 품질·보안·성능을 자동 검토 | 리뷰 대기 시간 **70% 이상 단축** |
| **보안 감사 자동화** — 취약점 감지 → 이슈 생성 → 수정 PR까지 | 취약점 대응 **2일 → 4시간** |
| **AI 에이전트 실행 하네스** — 그래프 엔지니어링 기반으로 여러 단계의 개발 워크플로를 하나의 오케스트레이션 흐름으로 관리 | 이슈 분석 → 코드 → PR이 한 흐름으로 |
| **루프 엔지니어링** — E2E 테스트까지 자동 검증·재시도하도록 파이프라인에 포함 | 사람 개입 없이 검증 반복 |
| **배포 순회 스킬 + 탐색적 테스트 AI 자동화** — 배포 환경을 돌며 AI가 탐색적 테스트 수행 | 사람이 놓치는 경로를 자동으로 점검 |
| **멀티 에이전트 병렬 개발** — Git Worktree로 에이전트 여러 개를 동시에 운용 (최대 18개 워크트리) | 독립 기능을 동시에 진행 |
| **Claude Code 커스텀 스킬 9종 + MCP(GitHub·Jira·Figma)** | 팀 워크플로 표준화 |
| **매뉴얼 → 지식 자동화 파이프라인** — 문서화 → 사내 챗봇 학습 → 봇 QA까지 자동화 | 72개 문항 전 항목 정답 검증 |

> 핵심 원칙: **에이전트가 어기면 안 되는 규칙은 말이 아니라 저장소에 코드로 남긴다.**
> 그 규칙의 실물은 아래 대표 프로젝트의 [`CLAUDE.md`](https://github.com/CescJuno/frontend-monorepo-showcase/blob/main/CLAUDE.md)와 슬래시 커맨드에서 볼 수 있습니다.

## 대표 프로젝트

**[frontend-monorepo-showcase](https://github.com/CescJuno/frontend-monorepo-showcase)**
pnpm + Turborepo 모노레포. 공유 UI 패키지와 Claude API 기반 면접 준비 앱.

- LLM Provider 추상화(Anthropic·Gemini), 일부 작업만 로컬 LLM으로 우회
- **LLM에 보내기 전 개인정보 마스킹** — 이메일·전화·주민번호·카드·계좌·주소·여권
- 에이전트 작업 원칙(`CLAUDE.md`)과 슬래시 커맨드를 저장소에 포함

## 프론트엔드 전문 영역

- **대규모 어드민/SaaS** — 대용량 테이블 가상화, 지도·차트 시각화, 서버 상태 관리 설계
- **모노레포 플랫폼 · 디자인 시스템** — 공유 패키지 설계, 레거시를 점진 전환하는 Strangler 패턴, 스키마 기반 UI

## 기술 스택

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?logo=anthropic&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?logo=turborepo&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?logo=pnpm&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
