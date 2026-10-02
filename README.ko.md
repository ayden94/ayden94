<p align="right"><a href="./README.md">English</a> &nbsp; / &nbsp; <strong>한국어</strong></p>

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 900px)" srcset="./assets/header-mobile.svg">
  <source media="(max-width: 900px)" srcset="./assets/header-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header.svg">
  <img src="./assets/header-light.svg" alt="Ayden — 개발자이자 저자. 사려 깊은 코드와 지식의 공유." width="100%">
</picture>

# 정진호 / Ayden

**정진호 · TypeScript 개발자**<br>
『모던 리액트 디자인 패턴』 저자

복잡한 개발 문제를 작고 예측 가능한 인터페이스로 풀어냅니다. React 애플리케이션부터 상태·폼 라이브러리, 표준 지향 백엔드 아키텍처까지 다루고 있습니다.

상태를 어디에 둘지, 책임을 어떻게 나눌지, 어떤 API가 이해하기 쉬운지처럼 코드 뒤에 있는 의사결정에 관심이 많습니다. 직접 도구를 만들며 답을 찾고, 그 과정에서 배운 것을 오픈소스와 글로 공유합니다.

<p>
  <a href="https://ayden94.com/"><strong>블로그 읽기</strong></a>
  &nbsp; · &nbsp;
  <a href="https://www.linkedin.com/in/jinho-jeong-8ab999345/">LinkedIn</a>
  &nbsp; · &nbsp;
  <a href="https://wikibook.co.kr/react-design-patterns/">저서 소개</a>
</p>

<br>

## 저서

<p align="center">
  <a href="https://wikibook.co.kr/react-design-patterns/">
    <img src="https://wikibook.co.kr/images/cover/l/9791158396930.jpg" alt="정진호 지음, 모던 리액트 디자인 패턴 책 표지" width="180">
  </a>
</p>

### 모던 리액트 디자인 패턴

**리액트 애플리케이션을 위한 설계 원칙**<br>
위키북스 · 2026년 7월 출간 · 한국어 도서

리액트는 쉽게 시작할 수 있지만, 변경하기 쉬운 애플리케이션을 설계하려면 더 많은 고민이 필요합니다.

컴포넌트 구조, 상태 관리, 로직 재사용, 비동기 UI, TypeScript 패턴을 실제 코드와 함께 살펴봅니다. 패턴을 외우기보다는 어떤 문제에서 출발했는지 이해하고, 지금 만드는 애플리케이션에 맞는 선택을 할 수 있도록 돕는 책입니다.

**[도서 소개](https://wikibook.co.kr/react-design-patterns/)** &nbsp; / &nbsp; [예제 코드](https://github.com/wikibook/react-design-patterns)

<br clear="all">

## 만드는 프로젝트

| 프로젝트 | 만드는 것과 설계 방향 |
| :--- | :--- |
| **[ilokesto](https://github.com/ilokesto)** | **작은 패키지, 명확한 책임.**<br><br>상태, 폼, UI, 네트워크 문제를 다루는 TypeScript 생태계입니다. 프레임워크에 의존하지 않는 코어와 얇은 어댑터로 같은 아이디어를 다양한 환경에서 사용할 수 있도록 만듭니다.<br><br>**상태와 폼** — 예측 가능한 스토어, 상태 전이, 폼 동작.<br>**UI** — 조합 가능한 오버레이, 모달, 토스트.<br>**네트워킹** — 역할이 명확한 fetch 유틸리티.<br><br>[`store`](https://github.com/ilokesto/store) · [`state`](https://github.com/ilokesto/state) · [`form`](https://github.com/ilokesto/form) · [`overlay`](https://github.com/ilokesto/overlay) · [`fetcher`](https://github.com/ilokesto/fetcher) |
| **[fluo](https://github.com/fluojs/fluo)** | **표준을 우선하는 TypeScript 백엔드 프레임워크.**<br><br>라우팅뿐 아니라 백엔드 애플리케이션을 구성하는 전체 영역을 탐구합니다. 표준 데코레이터와 모듈 경계로 애플리케이션의 구성 요소를 연결합니다.<br><br>**기반** — DI, 설정, 재사용 가능한 모듈.<br>**HTTP와 API** — 라우팅, 검증, 직렬화, OpenAPI.<br>**런타임** — 코어와 플랫폼 어댑터를 분리하고 Node.js, Bun, Deno, Cloudflare Workers를 고려하는 설계. |

<br>

## 오픈소스

코드, 문서, 수정 제안으로 참여한 프로젝트입니다.

| 프로젝트 | 분야 |
| :--- | :--- |
| **[stableref](https://github.com/JoviDeCroock/stableref)** | React 훅 |
| **[zustand-middleware-pipe](https://github.com/zustandjs/zustand-middleware-pipe)** | 상태 관리 |
| **[senpi](https://github.com/code-yeongyu/senpi)** | 코딩<br>에이전트 |
| **[oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)** | AI<br>에이전트 |
| **[open-code-review](https://github.com/alibaba/open-code-review)** | AI<br>코드 리뷰 |

## 계속 고민하는 것들

**프론트엔드 아키텍처**<br>
컴포넌트 경계, 상태의 소유권, 애플리케이션이 커져도 이해하기 쉬운 구조.

**라이브러리 설계**<br>
작은 API, 유용한 타입 추론, 하나의 프레임워크에 묶이지 않는 코어.

**개발자 경험**<br>
다음 사람의 작업을 쉽게 만드는 도구, 문서, 예제, 네이밍.

**AI를 활용한 개발**<br>
실제 개발 흐름에 맞는 코딩 에이전트와 리뷰 도구.

## 글쓰기

도구를 사용하는 방법뿐 아니라 왜 그렇게 설계했는지, 소프트웨어의 설계 과정을 이해하기 쉬운 언어로 설명하고 싶습니다.

블로그에는 프론트엔드 아키텍처, 상태 관리, 의존성 주입, TypeScript 라이브러리 설계, 기술적 선택의 장단점을 기록합니다.

**[ayden94.com에서 읽기](https://ayden94.com/)**

## 기술과 자격증

| 분야 | 기술 |
| :--- | :--- |
| 언어 | TypeScript · JavaScript |
| UI | React · Next.js |
| 서버 | Node.js · Express · NestJS |
| 테스트 | Jest · Vitest |
| 인프라 | AWS · Vercel · Netlify |
| 도구 | Git · GitHub · pnpm |

**AWS Certified Solutions Architect**

---

<p align="center">
  <a href="https://ayden94.com/">블로그</a> &nbsp; · &nbsp;
  <a href="https://www.linkedin.com/in/jinho-jeong-8ab999345/">LinkedIn</a> &nbsp; · &nbsp;
  <a href="./README.md">Read in English</a>
</p>
