# 강화민

## 백엔드 개발자 · Java / Spring

Java · Spring 기반 백엔드 개발자입니다.
요즘은 Claude Code 같은 AI 에이전트를 적극 활용해, 백엔드 외에 **RAG · 프론트엔드까지 직접** 만들어보고 있습니다.

> **"AI가 작성한 코드든 직접 작성한 코드든, 왜 동작하는지 이해하고 사용합니다."**

---

## 🛠 기술 스택

| 분류 | 기술 |
|------|------|
| **Backend** | ![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?logo=springsecurity&logoColor=white) ![JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?logo=spring&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?logo=postgresql&logoColor=white) |
| **AI / Data** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langgraph&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-FF6F00) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) |
| **DevOps / Tools** | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?logo=anthropic&logoColor=white) |

---

## 🚀 프로젝트

### KCpilot — KC 인증 사전진단 AI
**`개인 프로젝트` · `풀스택(Backend·Frontend·AI)`**

제품 정보를 입력하면 어떤 KC 인증이 필요한지 **법령 근거와 함께** 알려주는 서비스입니다.
Spring Boot 백엔드를 중심으로 Next.js 프론트, FastAPI(LangGraph) AI 서비스를 붙인 구조를 설계·구현했습니다.

- **할루시네이션 방지**: AI가 법령에 없는 내용을 지어내지 않도록, **검색된 법령 텍스트 안의 근거만으로** 답변하게 제한
- **신뢰도 표현 설계**: 판단이 애매할 땐 점수를 지어내는 대신 인증별 **HIGH / MEDIUM / LOW**로 표시
- **자동 배포**: GCP Compute Engine에 **GitHub Actions CD**로 자동 배포되는 구조로 운영 중

`LangGraph` `Python` `FastAPI` `Spring Boot` `Java` `PostgreSQL` `pgvector` `Next.js` `TypeScript` `GCP` `Docker` `GitHub Actions`

[![Live Service](https://img.shields.io/badge/🌐_서비스_바로가기-2ea44f?style=for-the-badge)](http://34.22.88.255:3000)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hamin-kang/kcpilot)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://app.notion.com/p/KCpilot-387e5485f3b48018b755f630610bac4c?source=copy_link)

<br>

### PoseFit — AI 운동 자세 분석
**`팀 프로젝트 (5명)` · `Backend · Frontend · RAG`**

웹캠으로 운동하면 포즈 추정 모델(MediaPipe)이 관절 키포인트를 실시간 추출하고,
정답 영상과 비교해 **점수와 언어 피드백**을 제공하는 서비스입니다.

- **백엔드 전반 담당**: FastAPI + SQLAlchemy(async) 기반 API 설계·구현
- **프론트엔드 담당**: Next.js 기반 사용자/관리자 화면 구현
- **AI 파이프라인 참여**: LangGraph 기반 포즈 분석 파이프라인 일부 구현

`LangGraph` `Python` `FastAPI` `MediaPipe` `ChromaDB` `Next.js` `TypeScript` `MySQL`

[![Live Service](https://img.shields.io/badge/🌐_posefit.org-2ea44f?style=for-the-badge)](https://posefit.org/)
[![Admin](https://img.shields.io/badge/🔐_admin.posefit.org-555555?style=for-the-badge)](https://admin.posefit.org/login)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Korea-AI-Organization-Developer/posefit)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://app.notion.com/p/PoseFit-387e5485f3b480e4a932e7ab28abb768?source=copy_link)

<br>

### PickCar — 공유차량 예약·운영 플랫폼
**`팀 프로젝트 (5명)` · `PM · Backend`**

서울 6개 거점 공유차량의 **예약 서비스와 운영 관리 시스템**을 만든 팀 프로젝트입니다.

- **PM 역할**: 일정·이슈 관리로 팀 협업 주도
- **백엔드 구현**: 예약·결제, 차량 사고 접수 기능 개발

`Spring Boot` `Java` `JPA` `MySQL`

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kosaTeam3/PickCar)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://app.notion.com/p/PickCar-30ce5485f3b48059aa05eb8361f29805?source=copy_link)

---

## 📫 연락처

- **Email**: kyden5386@gmail.com
- **GitHub**: https://github.com/hamin-kang
