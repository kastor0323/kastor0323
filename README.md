<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=JungHyun&fontSize=90" />
</div>

<div align="center">
  
# 일상을 바꾸어 더 나은 세상을 만드는, 백엔드 개발자 백정현입니다 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00FF00&center=true&vCenter=true&width=435&lines=AI+%26+ML+Enthusiast;Spring+Boot+Developer)](https://git.io/typing-svg)

</div>

## 🚀 About Me

> **백엔드 개발자**로서 **웹 개발**과 **DataBase 설계**에 특화된 개발자입니다.  
> 특히 **Spring Boot**, **MySQL** 기술을 활용한 실무 프로젝트 경험이 풍부합니다.

- 🔭 현재 **KB국민은행 IT's Your Life 7시** 수료 중
- 💬 **Spring Boot**, **운영체제**, **MySQL** 관련 같이 공부하고 토론해요
- 📫 이메일: **sanchezbeak@gmail.com**
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/kastor0323/programmers-badge/master/static/result.svg" alt="Programmers rank" />
</div>

## 🛠 주요 기술 스택

<p align="center">
  <a href="https://github.com/kastor0323">
    <img src="https://github-readme-stats-one-rouge-90.vercel.app/api/top-langs/?username=kastor0323&langs_count=10&layout=compact&theme=dark" alt="Top Langs" />
  </a>
</p>

## 🚀 주요 프로젝트

### 🎯 [Stock Management Service Project](https://github.com/sehyun00/SMS_Project)
> **AI 기반 주식 포트폴리오 리밸런싱 추천 애플리케이션**

<div align="center">
  <img src="https://img.shields.io/badge/Status-완료-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Team-우상향(4명)-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Role-부팀장%20%26%20백엔드-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Type-기업연계%20프로젝트-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/🏆%20동상%20수상-gold?style=for-the-badge"/>
</div>

**🔧 사용 기술:**
- **Frontend**: React Native, Expo, JavaScript, Data Visualization
- **Backend**: Spring Boot, Java, RESTful API Design, Redis, Flask
- **AI/ML**: GNN(Graph Neural Network), DRL(Deep Reinforcement Learning), LPPLS Model
- **External APIs**: CODEF API (계좌 정보), Kakao API (로그인)
- **Database**: MySQL, PostgreSQL

**✨ 주요 기능:**
- 🤖 AI 기반 자동화된 포트폴리오 리밸런싱 추천
- 📊 실시간 주식 정보 모니터링 및 데이터 시각화
- ⚠️ 시장 버블 감지 및 위험도 경고 시스템
- 👤 투자 성향별 맞춤형 투자 전략 제공
- 📱 크로스 플랫폼 모바일 앱 지원

**🏆 성과:**
- 🥉 **SW중심대학사업단 기업연계 프로젝트 경진대회 동상 수상**
- 포트폴리오 최적화 정확도 **85%** 달성

## 💼 기타 프로젝트

### 💹 [TradingGate Backend](https://github.com/TradingGate/TradingGate-Backend)
> **주문-매칭-정산을 하나의 흐름으로 연결한 트레이딩 코어 백엔드**

<div align="center">
  <img src="https://img.shields.io/badge/Status-완료-brightblue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Type-오픈소스%20포트폴리오-9cf?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Role-메인테이너-important?style=for-the-badge"/>
</div>

**🔧 사용 기술:**
- **Backend**: Spring Boot, Java, Kafka, PostgreSQL, Redis
- **Architecture**: Event Sourcing, Ledger-based Settlement, Projection Pattern
- **Testing**: k6 (부하 테스트), Testcontainers, 시나리오 검증
- **Deployment**: Docker, Kubernetes (로컬 데모 + EKS 운영 가정)

**✨ 핵심 설계:**
- **Ledger-first 아키텍처**: `ledger_entry`를 SSOT(Single Source of Truth)로 설정
- **Event-driven 거래 처리**: Kafka 기반 비동기 주문 처리 파이프라인
- **역할 분리**: API(주문), Worker(매칭), Risk(원장), Clearing(정산), Projection(조회용 뷰)
- **정산과 대사 분리**: Clearing(계산) vs Recon(검증)의 독립적 처리
- **성능 검증**: 대용량 75,000 ledger entries 배치 처리 완료

**🏆 성과:**
- `api -> worker -> projection -> risk -> clearing/recon` 전체 흐름 검증 완료
- Kubernetes 로컬 데모 및 EKS 운영 시나리오 문서화
- k6 부하 테스트: **206 req/s** 안정적 처리
- Clearing 배치: **75,000 ledger entries → 10,016 results** 정상 완료

**📚 주요 문서:**
- 트레이딩 코어 아키텍처
- 원장 기반 정합성 검증
- Kubernetes 배포 전략
- 부하 테스트 결과 리포트

---

### 📊 [AssayReport](https://github.com/kastor0323/AssayReport)
> **자기소개서 평가 및 분석 플랫폼 (자소서 AI 분석)**

<div align="center">
  <img src="https://img.shields.io/badge/Status-완료-brightblue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Type-개인프로젝트-yellowgreen?style=for-the-badge"/>
</div>

**🔧 사용 기술:**
- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Python, FastAPI, GPT API
- **AI/ML**: 자연어 처리(NLP), 텍스트 분석
- **Database**: PostgreSQL, Redis

**✨ 주요 기능:**
- AI 기반 자기소개서 작성 지도 및 평가
- 실시간 피드백 및 개선 방안 제시
- 자소서 강점/약점 분석 및 개선 포인트 추천
- 직무별/기업별 자소서 최적화 제안
- 작성 이력 관리 및 개선도 추적

**🏆 성과:**
- 사용자 중심 UX 설계로 직관적인 평가 인터페이스 제공
- GPT API 연동으로 고품질 AI 피드백 구현
- React + FastAPI 풀스택 개발 경험

## 🎯 목표 및 학습 계획

### 📚 2026년 학습 계획
- [ ] **국민은행 부트캠프** 수료 실무 경험 확대
- [ ] **취업 하기**
- [ ] **스크래핑과 바이브 코딩 경험 확대**

### 🏅 자격증 현황
- [x] **정보처리기사** 
- [x] **SQLD**
- [ ] **OPIC**
- [ ] **Adsp**
- [ ] **빅데이터분석기사**

## 📫 연락처 및 소셜미디어

<div align="center">

[![Email](https://img.shields.io/badge/Email-sanchezbeak@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kastor0323@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-FF5722?style=for-the-badge&logo=web&logoColor=white)](https://generated-tower-4d1.notion.site/14afed3855358059b86ac7474359c3bf)


</div>

<div align="center">

### 🌟 Thanks for visiting my profile! 🌟

<!-- 프로필 조회수 -->
<img
  src="https://komarev.com/ghpvc/?username=kastor0323&label=Profile%20views&style=flat-square&color=blueviolet"
  alt="Profile Views"
/>

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=100&section=footer"
/>

</div>
