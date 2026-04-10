# João Victor de Moraes da Cruz

Saquarema, RJ, Brasil  
Estudante de Engenharia de Software | Fundador do Desk Imperial

[![Open Source](https://img.shields.io/badge/Open%20Source-Desk%20Imperial-blue?style=for-the-badge&logo=github)](https://github.com/Victorzinn704/Desk-Imperial-Open-Source)
[![Website](https://img.shields.io/badge/App-app.deskimperial.online-black?style=for-the-badge&logo=vercel)](https://app.deskimperial.online)
[![API](https://img.shields.io/badge/API-api.deskimperial.online-0A66C2?style=for-the-badge&logo=fastapi)](https://api.deskimperial.online)

## Sobre mim

Sou estudante de Engenharia de Software e construo software orientado a problema real.

Hoje, meu principal projeto é o **Desk Imperial**, uma plataforma open source de gestão comercial feita para pequenos e médios comerciantes brasileiros. Nele, eu atuo de ponta a ponta: produto, arquitetura, backend, frontend, tempo real, testes, observabilidade, deploy e documentação.

Não tento parecer especialista em tudo. Prefiro me apresentar por evidências: produto em produção, monorepo full-stack, operação em tempo real, auditoria com SonarQube e um volume de código que já exige disciplina de engenharia de verdade.

## Projeto principal — Desk Imperial

O Desk Imperial nasceu para tirar o comerciante brasileiro da planilha e concentrar operação e gestão no mesmo sistema.

Hoje, o projeto reúne, no mesmo produto:

- PDV e comandas em tempo real
- financeiro por período
- folha de pagamento
- portfólio de produtos e combos
- calendário comercial
- operação mobile para dono e equipe
- observabilidade OSS e trilha de qualidade contínua

**Links principais**

- App: https://app.deskimperial.online
- API: https://api.deskimperial.online
- Open source: https://github.com/Victorzinn704/Desk-Imperial-Open-Source

## Evidências de execução

Esses são os sinais que melhor representam como eu trabalho hoje:

- monorepo full-stack com `apps/api`, `apps/web`, `packages` compartilhados e documentação técnica organizada
- cerca de **50 mil linhas de código analisadas no SonarQube**, com trilha de backlog técnico e gate de qualidade
- mais de **700 testes no backend** e **130 testes no frontend**, com validação de lint, typecheck, test e build
- **16 módulos de domínio na API** e **70+ arquivos de documentação** cobrindo arquitetura, produto, segurança e operação
- fluxo em **tempo real com Socket.IO + Redis**, mantendo equipe e operação sincronizadas
- app web com foco em **PWA**, uso mobile e experiência operacional para dono e funcionário

## Como eu construo o projeto

### Frontend

No frontend, eu foco em experiência, fluidez e operação real. O objetivo não é só deixar a interface bonita, mas criar telas que ajudem o usuário a vender, acompanhar a operação e tomar decisão com clareza.

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)](https://www.framer.com/motion)
[![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)](https://zod.dev)
[![Lucide](https://img.shields.io/badge/Lucide-111111?style=for-the-badge&logo=lucide&logoColor=white)](https://lucide.dev)
[![Hello Pangea DnD](https://img.shields.io/badge/Hello%20Pangea%20DnD-61DAFB?style=for-the-badge&logo=react&logoColor=000000)](https://github.com/hello-pangea/dnd)
[![React Big Calendar](https://img.shields.io/badge/React_Big_Calendar-0F172A?style=for-the-badge&logo=googlecalendar&logoColor=white)](https://github.com/jquense/react-big-calendar)
[![Canvas Confetti](https://img.shields.io/badge/Canvas_Confetti-FF6A00?style=for-the-badge&logo=javascript&logoColor=white)](https://www.npmjs.com/package/canvas-confetti)
[![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)

### Backend

No backend, eu trabalho na regra de negócio, consistência da operação e estabilidade dos fluxos mais sensíveis do sistema. É a camada em que concentro autenticação, comandas, pedidos, produtos, consentimento e integração entre os módulos.

[![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)](https://nestjs.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)](https://socket.io)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
### Infra

Na infraestrutura, eu penso em como o sistema sobe, roda, evolui e pode ser operado com mais autonomia. Isso envolve monorepo, ambientes, containers, cloud e a transição para uma base mais madura de runtime e observabilidade.

[![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white)](https://turbo.build/repo)
[![npm Workspaces](https://img.shields.io/badge/npm_Workspaces-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://docs.npmjs.com/cli/v10/using-npm/workspaces)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://kernel.org)
[![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://railway.com)
[![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/cloud/)
[![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com)
[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com)

### Banco de dados

Na camada de dados, eu trabalho com modelagem, persistência, acesso estruturado e apoio à performance do sistema. Aqui entram o banco transacional, a camada ORM, o runtime gerenciado e o cache que sustenta partes críticas da operação.

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)](https://www.prisma.io)
[![Neon](https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=00110A)](https://neon.com)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io)

### Observabilidade

Na observabilidade, eu uso métricas, dashboards, análise estática e trilhas de auditoria para entender o comportamento real do sistema. O foco aqui é reduzir ruído, medir gargalos e tornar a evolução mais segura.

[![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)](https://grafana.com)
[![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)](https://prometheus.io)
[![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)](https://www.sonarsource.com/products/sonarqube/)
[![OSS Observability](https://img.shields.io/badge/OSS-Observability-111827?style=for-the-badge)](https://grafana.com/oss/)
[![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)](https://k6.io)

### Segurança

Na segurança, eu procuro proteger autenticação, mutações críticas e isolamento dos dados. Isso envolve controles de sessão, validações, escopo por workspace e barreiras contra abuso operacional.

[![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io)
[![CSRF Protection](https://img.shields.io/badge/CSRF-Protection-7C3AED?style=for-the-badge)](https://owasp.org/www-community/attacks/csrf)
[![Multi-tenant](https://img.shields.io/badge/Multi--tenant-Isolation-1D4ED8?style=for-the-badge)](https://en.wikipedia.org/wiki/Multitenancy)
[![Admin PIN](https://img.shields.io/badge/Admin%20PIN-Rate%20Limited-D97706?style=for-the-badge)](https://redis.io)
[![Cache Invalidation](https://img.shields.io/badge/Cache-Invalidation-059669?style=for-the-badge)](https://redis.io)

### Testes e qualidade de código

Em testes e qualidade, eu trabalho para garantir que o sistema continue evoluindo sem perder previsibilidade. É aqui que entram cobertura, validação automatizada, análise estática e revisão constante da base de código.

[![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)](https://jestjs.io)
[![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)](https://vitest.dev)
[![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)](https://playwright.dev)
[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://eslint.org)

## Skills

<details>
<summary><strong>Skills úteis no projeto</strong></summary>

- **Arquitetura full-stack orientada a produto** — organizar backend, frontend, contratos compartilhados e documentação pensando no uso real do sistema.
- **Sistemas em tempo real** — projetar fluxos com `Socket.IO`, cache e invalidação para manter a operação sincronizada entre web e mobile.
- **Modelagem de domínio** — transformar problema de negócio em regras de caixa, comanda, pedidos, combos, consentimento e portfólio.
- **Qualidade contínua** — usar lint, typecheck, testes, build e SonarQube como parte do fluxo normal de desenvolvimento.
- **Investigação e correção de regressões** — localizar gargalos, ruídos e bugs silenciosos sem tratar sintoma como solução definitiva.
- **Documentação técnica** — registrar decisões, riscos, arquitetura e planos de evolução para manter o projeto sustentável.
- **Observabilidade OSS** — estruturar métricas, alertas, dashboards e trilhas de análise para entender o comportamento real do sistema.

</details>

<details>
<summary><strong>Minhas skills e base técnica</strong></summary>

- **Aprendizado rápido com execução real** — aprendo melhor construindo, validando e iterando em cima de produto vivo.
- **Ownership técnico** — gosto de entender o sistema por inteiro e assumir responsabilidade por estabilidade, clareza e evolução.
- **Pensamento de produto** — não penso só em tecnologia; penso em quem usa, por que usa e no que realmente gera valor.
- **Capacidade de aprofundamento** — quando um tema exige mais, eu entro fundo em debugging, qualidade, arquitetura e operação.
- **Disciplina para melhorar código existente** — tenho paciência para reduzir ruído, organizar backlog técnico e amadurecer base já grande.
- **Comunicação técnica escrita** — consigo transformar decisões e aprendizados em documentação útil, não só em código.
- **Base técnica complementar** — além do que uso hoje no projeto, também mantenho repertório em fundamentos de desenvolvimento web e construção de software além da stack principal do Desk Imperial.
- **Construção progressiva sem arrogância** — prefiro consistência, evidência e evolução contínua a pose de senioridade vazia.

</details>

## O que eu busco agora

Quero crescer em ambientes em que engenharia, produto e aprendizado caminhem juntos.

Tenho interesse especial por oportunidades de **Desenvolvimento** em times que valorizem:

- engenharia full-stack com responsabilidade real
- qualidade contínua e redução de regressão
- produto com problema concreto para resolver
- arquitetura, observabilidade e evolução sustentável

## Resumo rápido

Se eu precisasse resumir meu momento atual em uma frase, seria esta:

> Sou estudante de Engenharia de Software, mas já construo e mantenho um produto full-stack real, com foco em operação, qualidade e aprendizado acelerado.

## English summary

I am a Software Engineering student from Brazil and the founder of Desk Imperial, an open-source full-stack platform built for small and medium Brazilian merchants.

My work today is focused on real product execution: backend architecture, frontend experience, real-time operations, testing, observability and continuous quality. I am still early in my career, but I already build with production responsibility and strong learning velocity.
