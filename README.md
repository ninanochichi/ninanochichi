# 김우진 | Frontend Developer

> 사용자의 흐름을 읽고, 기능의 완성도를 끝까지 확인하는 프론트엔드 개발자입니다.  
> React와 TypeScript를 중심으로 인증, 상태 관리, API 연동, 마이페이지, 추천/탐색 UI를 구현해왔습니다.

[GitHub](https://github.com/ninanochichi) · [Tech Blog](https://ideas09785.tistory.com/) · [Rallit Resume](https://www.rallit.com/resumes/1608450@kedw158/%EA%B9%80%EC%9A%B0%EC%A7%84)

---

## What I Care About

- 사용자가 길을 잃지 않는 화면 흐름과 명확한 피드백을 중요하게 생각합니다.
- 기능 구현 이후에도 로딩, 빈 상태, 에러 상태, 새로고침 상황까지 확인합니다.
- API 응답과 화면 사이의 경계를 정리해 변경에 흔들리지 않는 구조를 지향합니다.
- AI 도구는 결과물을 그대로 쓰기보다 요구사항 정리, 코드 탐색, 구현 방향 비교, 검증 보조에 목적별로 활용합니다.

---

## Tech Stack

**Core**  
<kbd>React</kbd> <kbd>TypeScript</kbd> <kbd>JavaScript</kbd> <kbd>HTML5</kbd> <kbd>CSS3</kbd> <kbd>Tailwind CSS</kbd> <kbd>Vite</kbd>

**State & Data**  
<kbd>TanStack Query</kbd> <kbd>Zustand</kbd> <kbd>Axios</kbd> <kbd>React Router</kbd> <kbd>MSW</kbd>

**Workflow**  
<kbd>Git</kbd> <kbd>GitHub</kbd> <kbd>Vercel</kbd> <kbd>Figma</kbd> <kbd>Discord</kbd>

---

## Selected Projects

| Project | Role / Focus | Links |
| --- | --- | --- |
| **PGTI 게임 추천 서비스** | 취향 기반 게임 추천 서비스. 인증 흐름, 마이페이지, 매칭/추천 UI, 고객센터 챗봇 흐름 구현 및 도메인 기반 폴더 구조 정리 | [Deploy](https://oz-union-16-fe.vercel.app/) · [GitHub](https://github.com/Oz-union-16-Team-1/oz_union_16_FE) |
| **커뮤니티 서비스** | 게시글, 댓글, 좋아요, 마크다운 에디터 구현. React Query와 Zustand 기반 상태 관리, Axios 인터셉터와 MSW 흐름 구성 | [Deploy](https://oz-externship-fe-07-team1.vercel.app) · [GitHub](https://github.com/ninanochichi/oz_externship_fe_07_team1) |
| **영화 탐색 서비스** | 영화 목록, 상세, 검색, 로그인/회원가입, 마이페이지, 다크모드 UI 구현. Supabase Auth 기반 사용자 흐름 구성 | [Deploy](https://oz-16-react-mini-three.vercel.app) · [GitHub](https://github.com/ninanochichi/oz_16_react_mini) |
| **맛집 찜 서비스** | 위치 기반 정렬, 즐겨찾기, 모달 인터랙션을 포함한 맛집 탐색 경험 구현 | [Deploy](https://oz-16-react-event.vercel.app) · [GitHub](https://github.com/ninanochichi/oz_16_react_event) |

---

## Engineering Notes

**1. UI와 API 사이의 경계 정리**  
API 응답이 화면 컴포넌트에 직접 흩어지지 않도록 타입과 데이터 흐름을 분리하는 방식을 선호합니다. 화면은 사용자의 상태를 표현하는 데 집중하고, 데이터 형태의 흔들림은 어댑터나 훅 경계에서 흡수하려고 합니다.

**2. 인증과 세션 흐름 개선**  
Access Token 관리 정책을 sessionStorage와 인메모리 관리 중심으로 정리해 새로고침, 탭 이동, 인증 만료 상황에서 사용자 흐름이 끊기지 않도록 개선했습니다.

**3. 기능 단위 유지보수성**  
auth, matching, mypage처럼 도메인 기준으로 폴더를 나누고, 반복되는 UI와 비즈니스 로직을 컴포넌트와 훅 단위로 정리하는 방향을 지향합니다.

---

## AI-assisted Workflow

| Step | How I Use AI |
| --- | --- |
| Context | 요구사항, API 명세, 기존 코드 구조를 먼저 정리하고 작업 범위를 좁힙니다. |
| Build | Codex, ChatGPT, Gemini, Manus를 목적에 맞게 나눠 구현 방향 비교와 코드 탐색에 활용합니다. |
| Review | 제안된 구현은 프로젝트 구조와 사용자 흐름에 맞게 다듬고, lint/build와 브라우저 확인으로 마무리합니다. |

---

## Currently Improving

- React와 TypeScript 기반의 컴포넌트 설계
- TanStack Query를 활용한 서버 상태 관리
- 인증 흐름과 사용자 세션 안정성
- AI 에이전트를 활용한 개발 워크플로우 정리
