# 정진호 / Ayden

복잡한 개발 경험을 작은 인터페이스로 풀어내는 TypeScript 개발자입니다.

상태 관리, 폼 상태, 표준 지향 백엔드 프레임워크처럼 반복되는 개발 문제를 작고 예측 가능한 도구로 다루는 일에 관심이 많습니다.

> I build small tools for better developer experience — mostly around TypeScript, state management, forms, and standard-first backend architecture.

---

## Current focus

### ilokesto

[`ilokesto`](https://github.com/ilokesto)는 여러 프레임워크에서 반복되는 UI, 상태, 폼, 네트워크 문제를 작고 명확한 TypeScript 패키지로 나누어 다루는 OSS 생태계입니다.

핵심 로직은 프레임워크에 의존하지 않게 두고, 각 프레임워크 어댑터는 가능한 한 얇게 유지하는 방향으로 설계하고 있습니다.

| Area | Packages |
| --- | --- |
| State & form core | [`@ilokesto/store`](https://github.com/ilokesto/store), [`@ilokesto/state`](https://github.com/ilokesto/state), [`@ilokesto/form`](https://github.com/ilokesto/form) |
| UI primitives | [`@ilokesto/utilinent`](https://github.com/ilokesto/utilinent), [`@ilokesto/overlay`](https://github.com/ilokesto/overlay), [`@ilokesto/modal`](https://github.com/ilokesto/modal), [`@ilokesto/toast`](https://github.com/ilokesto/toast) |
| Utilities & networking | [`@ilokesto/fetcher`](https://github.com/ilokesto/fetcher) and smaller supporting packages |

이전의 `Caro-Kann`, `Sicilian`, `Grunfeld` 같은 실험은 현재의 `state`, `form`, `overlay/modal/toast` 패키지군으로 재정리하고 있습니다.

### fluo

[`fluo`](https://github.com/fluojs/fluo)는 Standard-First TypeScript Backend Framework입니다.

표준 Decorator, DI, 설정, 검증, 직렬화, OpenAPI, 인증, 런타임 어댑터를 하나의 모듈러 백엔드 프레임워크로 설계하고 있습니다. Node.js, Bun, Deno, Cloudflare Workers 같은 런타임을 염두에 두고, 프레임워크 코어와 플랫폼 어댑터를 분리하는 구조를 실험합니다.

`fluo`의 관심사는 단순한 라우터가 아니라, 백엔드 애플리케이션을 구성하는 패키지 표면 전체입니다.

- Core: DI, config, i18n, runtime
- HTTP: routing, validation, serialization, OpenAPI, GraphQL
- Auth & platform: JWT, Passport, Fastify, Express, Node.js, Bun, Deno, Cloudflare Workers
- Tooling: CLI, testing, examples, documentation

---

## What I care about

- 복잡한 개념을 이해하기 쉬운 언어로 설명하기
- 프레임워크와 런타임에 강하게 묶이지 않는 구조 설계하기
- 작고 예측 가능한 API 만들기
- 상태 관리, 폼 상태, 백엔드 프레임워크처럼 반복되는 문제를 더 단순하게 다루기
- 코드뿐 아니라 문서, 예제, 네이밍까지 포함한 개발자 경험 개선하기

---

## Writing

기술을 단순히 사용하는 것보다, 왜 그렇게 설계했는지 설명하고 공유하는 일을 중요하게 생각합니다.

블로그에서는 주로 이런 주제를 다룹니다.

- 프론트엔드 아키텍처
- 상태 관리
- 의존성 주입과 설계 패턴
- TypeScript 라이브러리 설계
- 개발자 경험과 기술 의사결정

[ayden94.com](https://ayden94.com)

---

## Core stack

```txt
Language    TypeScript, JavaScript
Frontend    React, Next.js
Backend     Node.js, Express, NestJS
Testing     Jest, Vitest
Infra       AWS, Vercel, Netlify
Tools       Git, GitHub, pnpm
```

---

## Certification

- AWS Certified Solutions Architect

---

## Links

- Blog: [ayden94.com](https://ayden94.com)
- GitHub: [github.com/ayden94](https://github.com/ayden94)
- LinkedIn: [jinho-jeong-8ab999345](https://www.linkedin.com/in/jinho-jeong-8ab999345/)

---

![ayden's GitHub stats](https://github-readme-stats.vercel.app/api?username=ayden94&theme=dark&show_icons=true)
