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

### [ilokesto](https://github.com/ilokesto/ilokesto)

**조합할 수 있는 작은 도구, 프레임워크에 묶이지 않는 코어.**

ilokesto는 에스페란토로 ‘도구 상자’를 뜻합니다. 애플리케이션 전체를 책임지는 하나의 라이브러리보다, 프론트엔드에서 반복되는 문제를 각자의 역할이 명확한 TypeScript 라이브러리로 풀어내고자 합니다.

설계의 출발점은 순수 TypeScript 코어와 필요한 만큼의 얇은 프레임워크 바인딩입니다. 패키지는 각자의 책임과 버전을 유지하고, 공통 추상화를 늘리기 전에 일관된 규칙을 먼저 공유합니다. 상태, 폼, UI 동작을 각각 이해하기 쉽게 만들고 여러 프로젝트에서 재사용하는 것이 목표입니다.

패키지는 `@ilokesto/` 스코프로 배포합니다.

| 패키지 | 역할 |
| :--- | :--- |
| [store](https://github.com/ilokesto/ilokesto/tree/main/packages/store) | 프레임워크와 독립적인 상태 저장, 갱신, 구독. |
| [state](https://github.com/ilokesto/ilokesto/tree/main/packages/state) | 상태 조합과 여러 프레임워크를 위한 얇은 바인딩. |
| [form](https://github.com/ilokesto/ilokesto/tree/main/packages/form) | 폼 상태, 필드 메타데이터, Standard Schema 검증. |
| [utilinent](https://github.com/ilokesto/ilokesto/tree/main/packages/utilinent) | 반복되는 렌더링 패턴을 위한 작은 선언적 React 컴포넌트. |
| [overlay](https://github.com/ilokesto/ilokesto/tree/main/packages/overlay) | 오버레이 상태와 생명주기 관리. |
| [modal](https://github.com/ilokesto/ilokesto/tree/main/packages/modal) | 모달 상호작용. |
| [toast](https://github.com/ilokesto/ilokesto/tree/main/packages/toast) | 토스트 알림. |
| [fetcher](https://github.com/ilokesto/ilokesto/tree/main/packages/fetcher) | fetch 기반 네트워크 유틸리티. |

### [fluo](https://github.com/fluojs/fluo)

**표준 우선, 명시적 의존성, 분명한 경계.**

fluo는 TC39 표준 데코레이터와 명시적인 의존성 주입을 바탕으로 만드는 TypeScript 백엔드 프레임워크입니다. 어떤 모듈이 기능을 소유하고, 무엇에 의존하며, 어디까지 책임지는지 코드에서 드러나는 구조를 지향합니다.

레거시 데코레이터 메타데이터에 기대기보다 의존성을 직접 선언하고, 필요한 기능을 패키지 단위로 조합합니다. 프레임워크 코어와 호스트 어댑터를 분리하며, 런타임 지원 범위도 패키지별로 명확히 정의합니다. 편리한 API만큼 예측 가능한 동작 계약, 테스트 가능한 구조, 문서화된 한계를 중요하게 생각합니다.

패키지 이름은 `@fluojs/` 스코프를 사용합니다.

| 영역 | 패키지 |
| :--- | :--- |
| 코어 | [core](https://github.com/fluojs/fluo/tree/main/packages/core), [di](https://github.com/fluojs/fluo/tree/main/packages/di), [runtime](https://github.com/fluojs/fluo/tree/main/packages/runtime), [config](https://github.com/fluojs/fluo/tree/main/packages/config), [i18n](https://github.com/fluojs/fluo/tree/main/packages/i18n) |
| HTTP·API | [http](https://github.com/fluojs/fluo/tree/main/packages/http), [validation](https://github.com/fluojs/fluo/tree/main/packages/validation), [serialization](https://github.com/fluojs/fluo/tree/main/packages/serialization), [openapi](https://github.com/fluojs/fluo/tree/main/packages/openapi), [graphql](https://github.com/fluojs/fluo/tree/main/packages/graphql) |
| 인증 | [jwt](https://github.com/fluojs/fluo/tree/main/packages/jwt), [passport](https://github.com/fluojs/fluo/tree/main/packages/passport) |
| 데이터 | [prisma](https://github.com/fluojs/fluo/tree/main/packages/prisma), [drizzle](https://github.com/fluojs/fluo/tree/main/packages/drizzle), [mongoose](https://github.com/fluojs/fluo/tree/main/packages/mongoose), [redis](https://github.com/fluojs/fluo/tree/main/packages/redis), [cache-manager](https://github.com/fluojs/fluo/tree/main/packages/cache-manager) |
| 메시징 | [microservices](https://github.com/fluojs/fluo/tree/main/packages/microservices), [cqrs](https://github.com/fluojs/fluo/tree/main/packages/cqrs), [event-bus](https://github.com/fluojs/fluo/tree/main/packages/event-bus), [queue](https://github.com/fluojs/fluo/tree/main/packages/queue), [cron](https://github.com/fluojs/fluo/tree/main/packages/cron) |
| 실시간 | [websockets](https://github.com/fluojs/fluo/tree/main/packages/websockets), [socket.io](https://github.com/fluojs/fluo/tree/main/packages/socket.io), [notifications](https://github.com/fluojs/fluo/tree/main/packages/notifications), [email](https://github.com/fluojs/fluo/tree/main/packages/email), [slack](https://github.com/fluojs/fluo/tree/main/packages/slack), [discord](https://github.com/fluojs/fluo/tree/main/packages/discord) |
| 운영 | [terminus](https://github.com/fluojs/fluo/tree/main/packages/terminus), [metrics](https://github.com/fluojs/fluo/tree/main/packages/metrics), [throttler](https://github.com/fluojs/fluo/tree/main/packages/throttler) |
| 어댑터 | [Fastify](https://github.com/fluojs/fluo/tree/main/packages/platform-fastify), [Express](https://github.com/fluojs/fluo/tree/main/packages/platform-express), [Node.js](https://github.com/fluojs/fluo/tree/main/packages/platform-nodejs), [Next.js](https://github.com/fluojs/fluo/tree/main/packages/platform-nextjs), [Bun](https://github.com/fluojs/fluo/tree/main/packages/platform-bun), [Deno](https://github.com/fluojs/fluo/tree/main/packages/platform-deno), [Workers](https://github.com/fluojs/fluo/tree/main/packages/platform-cloudflare-workers) |
| 도구 | [react](https://github.com/fluojs/fluo/tree/main/packages/react), [cli](https://github.com/fluojs/fluo/tree/main/packages/cli), [testing](https://github.com/fluojs/fluo/tree/main/packages/testing), [vite](https://github.com/fluojs/fluo/tree/main/packages/vite), [studio](https://github.com/fluojs/fluo/tree/main/packages/studio) |

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
