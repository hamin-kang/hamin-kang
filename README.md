# 강화민 | 백엔드 개발자

> AI가 작성한 코드든 직접 작성한 코드든, 왜 동작하는지 이해하고 사용합니다.

Java와 Spring을 주로 다루는 백엔드 개발자입니다.
요즘은 Claude Code 같은 AI 에이전트를 적극적으로 활용하면서, 백엔드 외에 RAG나 프론트엔드까지 직접 만들어보고 있습니다.

![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

## 기술 스택

- **Backend:** Java, Spring Boot, Spring Data JPA, Spring Security(JWT), Gradle
- **Database:** PostgreSQL, MySQL, pgvector
- **AI / Data:** Python, FastAPI, LangChain, LangGraph, RAG
- **Frontend:** React, Next.js, TypeScript
- **Tools:** Docker, GCP, GitHub Actions, Git, Claude Code


## 프로젝트

### KCpilot — KC 인증 사전진단 AI (개인)
제품 정보를 입력하면 어떤 KC 인증이 필요한지 법령 근거와 함께 알려주는 서비스입니다.
Spring Boot 백엔드를 중심으로 Next.js 프론트, FastAPI(LangGraph) AI 서비스를 붙인 구조를 만들었습니다.

만들면서 가장 고민한 건 AI가 법령에 없는 내용을 그럴듯하게 지어내는 문제였습니다.
그래서 검색된 법령 텍스트 안에 있는 내용만 근거로 답하게 하고, 판단이 애매할 땐 점수를 지어내는 대신 인증별로 HIGH/MEDIUM/LOW만 표시하도록 했습니다.

GCP Compute Engine에 배포해 GitHub Actions CD로 자동 배포되는 구조로 운영 중입니다.

**→ 서비스: http://34.22.88.255:3000**

`LangGraph` `Python` `FastAPI` `Spring Boot` `Java` `PostgreSQL` `pgvector` `Next.js` `TypeScript` `GCP` `Docker` `GitHub Actions`

https://github.com/hamin-kang/kcpilot

### PickCar — 공유차량 예약·운영 플랫폼 (팀 5명, PM·백엔드)
서울 6개 거점 공유차량의 예약 서비스와 운영 관리 시스템을 만든 팀 프로젝트입니다.
PM을 맡아 일정과 이슈를 관리하면서, 백엔드로 예약·결제와 차량 사고 접수 기능을 구현했습니다.

`Spring Boot` `Java` `JPA` `MySQL`

https://github.com/kosaTeam3/PickCar

### PoseFit — AI 운동 자세 분석 (팀 5명, 백엔드·프론트)
웹캠으로 운동하면 포즈 추정 모델(ViTPose-Base)이 관절 키포인트를 실시간 추출하고,
정답 영상과 비교해 점수와 언어 피드백을 제공하는 서비스입니다.

백엔드(FastAPI + SQLAlchemy async) 전반과 Next.js 프론트엔드를 담당했고,
LangGraph 기반 포즈 분석 파이프라인 일부를 구현했습니다.

**→ 서비스(구글 로그인 O): https://scholarship-compression-peoples-photo.trycloudflare.com**

**→ 서비스: http://116.125.141.65:13000/**

**→ 관리자 페이지: http://116.125.141.65:13001/**

`LangGraph` `Python` `FastAPI` `ViTPose` `ChromaDB` `Next.js` `TypeScript` `MySQL`

https://github.com/Korea-AI-Organization-Developer/posefit

## 연락
- Email: kyden5386@gmail.com
- GitHub: github.com/hamin-kang
