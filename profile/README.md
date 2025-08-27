<div align="center">
<img width="1200" height="500" alt="KakaoTalk_Photo_2025-08-26-22-09-10" src="https://github.com/user-attachments/assets/98bab01e-b7e6-429a-95e9-54a8a13d0f72" />

### 한국오라클 기업프로젝트 *Old Young*
[young-old.com](young-old.com)
</div>

## 🚕 소개

올영(OldYoung)은 공공데이터를 바탕으로 고령화 대비 공공 서비스 개선을 위한 시니어 동행 복지 플랫폼 서비스입니다.

기본 정보를 입력해 본인의 수급 분위와 위치를 확인하고, 이를 통한 맞춤형 혜택을 제공받을 수 있습니다.

노인 친화형 대화를 위한 맞춤 프롬프트를 토대로 실시간으로 Q&A 또한 가능합니다.

## 🖥 서비스 화면 (사진 업데이트 예정)

<img width="384" height="761" alt="스크린샷 2025-08-27 오후 2 36 40" src="https://github.com/user-attachments/assets/1bd4937d-8901-4c95-8a29-339431a4e39a" />
<img width="390" height="762" alt="스크린샷 2025-08-27 오후 2 36 59" src="https://github.com/user-attachments/assets/5ffe6ccf-a895-4dd9-8b9f-2f14594f1a7e" />

## 🛠 Tech Stacks

### 🎨 Frontend Tech Stack

- **TypeScript**: 정적 타입으로 안정적인 개발 환경 제공  
- **pnpm / Vite**: 빠르고 효율적인 패키지 설치 및 프론트엔드 빌드 환경  
- **Tailwind CSS**: 유틸리티 기반 CSS 프레임워크  
- **@tailwindcss/vite**: Vite에서 Tailwind CSS를 쉽게 사용할 수 있도록 지원하는 플러그인  
- **React**: 컴포넌트 기반 UI 개발을 위한 JavaScript 라이브러리  
- **react-router-dom**: SPA 라우팅 처리 라이브러리  
- **Axios**: REST API와 통신하기 위한 HTTP 클라이언트  
- **@tanstack/react-query**: 서버 상태(fetching, caching 등)를 효율적으로 관리하는 라이브러리  
- **@tanstack/react-query-devtools**: React Query 상태를 시각적으로 디버깅할 수 있는 개발 도구  
- **react-hook-form**: 선언적이고 간결한 폼 상태 관리 라이브러리  
- **@hookform/resolvers / Zod**: react-hook-form과 함께 사용하는 유효성 검사 및 스키마 검증 도구  
- **react-intersection-observer**: 뷰포트 진입 여부를 감지하는 Intersection Observer 구현 라이브러리  
- **react-mobile-picker-scroll**: 모바일 환경에서 사용할 수 있는 스크롤형 선택 피커 UI  
- **clsx**: 조건부 className 조합을 간편하게 할 수 있는 유틸 함수  
- **vite-plugin-svgr**: SVG 파일을 React 컴포넌트로 변환해 사용할 수 있도록 하는 Vite 플러그인  
- **vite-plugin-pwa**: PWA(Progressive Web App) 지원을 위한 Vite 플러그인  
- **Kakao Maps JavaScript SDK**: 장소 검색 및 좌표(x, y) 추출, 행정구역(구/동) 파싱 지원  
- **Harumi Chatbot UI**: 입력/리스트 컴포넌트 기반 대화형 인터페이스, React Query로 대화 이력 관리 및 낙관적 업데이트  


---

### ⚙️ Backend

- **Spring Boot**: Java 기반 웹 애플리케이션 프레임워크
- **Java 17**: 최신 LTS 버전의 Java
- **Spring Security + JWT**: 인증 및 권한 처리
- **JPA (Hibernate)**: ORM 프레임워크
- **WebSocket (STOMP)**: 실시간 채팅 기능 구현
- **Spring AI (OpenAI)**: OpenAI(GPT-4o-mini) 모델을 활용하여 AI 채팅 기능을 구현했습니다.
- **Flask API 연동**: 소득분위 분석과 같은 AI 관련 추가 기능은 외부 Flask 서버와 통신하여 처리합니다.
- **PostgreSQL** : AI Flask 서버와의 빠른 통신을 위한 READ 속도가 빠른 SQL

---

### 🤖 AI
- **Python 3.11**: 모델 서버 및 API 개발 언어
- **LangChain**: RAG(Retrieval-Augmented Generation) 파이프라인 구축
- **OpenAI GPT-3.5-turbo**: 소득 분위 추론 및 자연어 응답 생성
- **FAISS VectorDB**: 벡터 기반 유사도 검색으로 정책·문서 검색 최적화
- **Flask-RESTX**: API 서버 및 Swagger 문서화
- **PostgreSQL**: 입력 데이터 및 질의 로그 관리

---

### ☁️ Infrastructure (아키텍처 사진))

- **AWS EC2**: 애플리케이션 서버 호스팅
- **AWS RDS (MySQL)**: 관리형 데이터베이스
- **Nginx**: 리버스 프록시 및 SSL 인증 처리
- **Docker**: 컨테이너 기반 환경 구성

---

### 🔁 CI/CD & DevOps

- **Jenkins**: CI/CD 파이프라인 구축 및 자동 배포
- **Discord Webhook**: 배포 및 장애 알림 전송
- **Docker Compose**: 분산 컨테이너 관리 

---

### 💬 Communication & Collaboration

- **GitHub Projects / Issues**: 이슈 및 프로젝트 관리
- **Notion**: 문서 협업 및 일정 관리
- **Figma**: UI/UX 디자인 협업
- **Discord**: 팀 커뮤니케이션



## 👥 Members

| PM / Backend | Backend | AI | FE |
|:------------:|:-------:|:--:|:--:|
| <img src="https://avatars.githubusercontent.com/u/150355097?v=4&s=120" width="140"/><br>[박규민](https://github.com/FrontHeadlock) | <img src="https://avatars.githubusercontent.com/u/162654709?v=4&s=140" width="140"/><br>[최민수](https://github.com/CMIN-SU) | <img src="https://avatars.githubusercontent.com/u/97944596?v=4&s=120" width="140"/><br>[한준희](https://github.com/paplap) | <img src="https://avatars.githubusercontent.com/u/97932282?v=4&s=120" width="120"/><br>[고민균](https://github.com/miinnne) |



