<h1 align="center">João Victor de Moraes da Cruz</h1>

<p align="center">
  <sub>Engenharia de Software · Desk Imperial · Saquarema, RJ · Brasil</sub>
</p>

<p align="center">
  <a href="https://github.com/Victorzinn704/Desk-Imperial-Open-Source"><img alt="Desk Imperial Open Source" src="https://img.shields.io/badge/projeto%20principal-Desk%20Imperial-0A66C2?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://app.deskimperial.online"><img alt="Aplicação em produção" src="https://img.shields.io/badge/app-app.deskimperial.online-111827?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://api.deskimperial.online"><img alt="API em produção" src="https://img.shields.io/badge/api-api.deskimperial.online-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=Victorzinn704&style=flat-square&color=0A66C2">
  <img alt="GitHub followers" src="https://img.shields.io/github/followers/Victorzinn704?style=flat-square&color=111827">
  <img alt="GitHub stars" src="https://img.shields.io/github/stars/Victorzinn704?style=flat-square&color=F5A623">
</p>

---

## Leitura rápida

Sou estudante de Engenharia de Software e uso este GitHub como um registro público de construção técnica. O centro do meu trabalho hoje é o **Desk Imperial**, uma plataforma full-stack open source para gestão comercial, mas o perfil não fica limitado a ele: mantenho projetos de tempo real, C/C++, frontend, automação operacional e documentação técnica.

Minha organização aqui segue uma ideia simples: cada repositório precisa mostrar **problema**, **decisão técnica**, **código**, **testes**, **documentação**, **evidência de uso** e **limites conhecidos**. Quando isso não está claro, trato como backlog de engenharia, não como detalhe estético.

---

## Mapa dos projetos

| Frente | Repositório | Papel no portfólio | Estado atual |
| --- | --- | --- | --- |
| Produto principal | [Desk Imperial](https://github.com/Victorzinn704/Desk-Imperial-Open-Source) | Plataforma full-stack com backend, frontend, tempo real, testes, observabilidade e documentação extensa. | Base principal, CI ativo, app e API publicados. |
| Tempo real e runtime | [TX - Tradutor em REALTIME](https://github.com/Victorzinn704/TX-Tradutor-em-REALTIME) | Pipeline local de áudio com Python, Rust, GPU, captura WASAPI, VAD, ASR e fallback de tradução. | CI ativo, testes Python e Rust documentados. |
| C, C++ e redes | [Aprendendo em C e C++](https://github.com/Victorzinn704/Aprendendo-em-C-e-C-) | Repositório de estudo aplicado com estruturas de dados, simulação de rede, terminal interativo e página demonstrativa. | Pages e workflow de qualidade ativos. |
| Frontend aplicado | [Gerenciador de Tarefas](https://github.com/Victorzinn704/Gerenciador-de-Tarefas-) | Interface React para fluxo de tarefas, tema claro/escuro, testes e documentação de uso. | Pages e workflow de qualidade ativos. |
| Operação local | [Project Sentinel](https://github.com/Victorzinn704/project-sentinel) | Gateway local para uso autorizado de modelos compatíveis com OpenAI, com auditoria, políticas e SQLite. | CI ativo com testes Go, build e guard de publicação. |
| SaaS em estabilização | [RH Insights](https://github.com/Victorzinn704/RH-Insights) | Plataforma multi-tenant para RH com Firebase, regras de isolamento, Gemini e módulos administrativos. | CI restaurado, audit zerado e documentação forte; segue em estabilização de produto. |

---

## Como os projetos conversam

O objetivo não é acumular repositórios desconectados. Cada projeto ocupa uma camada diferente da minha formação.

**Desk Imperial** é o produto mais completo: regra de negócio, banco de dados, API, frontend, operação em tempo real, testes, observabilidade e documentação. Ele mostra como eu organizo um sistema grande e como registro decisões para manter o projeto evoluindo sem depender de memória.

**TX - Tradutor em REALTIME** aprofunda runtime e processamento local. O projeto trabalha com captura de áudio, decisão de quando usar GPU, redução de ruído operacional, fallback e testes em Python/Rust. Ele complementa o Desk Imperial porque exige pensar em latência, fluxo contínuo e falha parcial.

**Aprendendo em C e C++** cobre base técnica: memória, estruturas de dados, simulação no terminal, redes e leitura de comportamento passo a passo. A ideia é mostrar fundamentos de forma executável, não apenas teoria solta. A demonstração web existe para apresentar o fluxo, mas o código C/C++ fica versionado como referência principal.

**Gerenciador de Tarefas** funciona como campo de frontend aplicado. Ele reforça estado de interface, persistência local, tema claro/escuro, responsividade, acessibilidade básica e testes de comportamento.

**Project Sentinel** entra na camada de operação e controle local. O foco é executar tarefas autorizadas com registro, política e previsibilidade, evitando que automação vire caixa-preta.

**RH Insights** fica como projeto de produto em estabilização. Ele tem uma boa base documental, problema de negócio claro e CI restaurado; o próximo passo é amadurecer a experiência do produto e reduzir warnings técnicos restantes.

---

## Projeto principal: Desk Imperial

Plataforma open source para pequenos e médios comerciantes brasileiros. O objetivo é substituir planilhas soltas por uma operação integrada: venda, comanda, estoque, financeiro, folha, calendário, carteira de clientes, mobile e administração.

**O que o projeto cobre hoje**

- PDV, comandas e fluxo de venda com atualização em tempo real.
- Financeiro por período, carteira, movimentações e leitura de caixa.
- Folha de pagamento automatizada, cargos e regras de comissão.
- Produtos, combos, portfólio comercial e operação mobile.
- LGPD, admin PIN, auditoria e isolamento por tenant.
- Backend NestJS, frontend Next.js, PostgreSQL, Prisma, Redis e Socket.IO.

**Evidências públicas**

- Repositório: [Desk-Imperial-Open-Source](https://github.com/Victorzinn704/Desk-Imperial-Open-Source)
- App: [app.deskimperial.online](https://app.deskimperial.online)
- API: [api.deskimperial.online](https://api.deskimperial.online)
- Documentação técnica, testes, arquitetura, setup, operação e planos de evolução no próprio repositório.

---

## Repositórios em destaque

<table>
<tr>
<td width="50%" valign="top">

### TX - Tradutor em REALTIME

Tradutor local de áudio para Windows 11, com pipeline híbrido em Python e Rust.

**Pontos técnicos**

- Captura de microfone e áudio do sistema via WASAPI.
- VAD em camadas para reduzir processamento desnecessário.
- Transcrição com faster-whisper/CTranslate2.
- Tradução com fallback local e contextual.
- Testes Python e Rust documentados.

**Links**

- [Repositório](https://github.com/Victorzinn704/TX-Tradutor-em-REALTIME)
- [Índice técnico](https://github.com/Victorzinn704/TX-Tradutor-em-REALTIME/blob/main/docs/INDEX.md)
- [Matriz de testes](https://github.com/Victorzinn704/TX-Tradutor-em-REALTIME/blob/main/docs/MATRIZ-DE-TESTES-E-EVIDENCIAS.md)

</td>
<td width="50%" valign="top">

### Aprendendo em C e C++

Repositório de fundamentos com foco em C, C++, estruturas de dados e redes.

**Pontos técnicos**

- Simulador de rede no terminal com fluxo demonstrativo.
- Cadastro de ambiente, dispositivos, pacotes e rotas.
- Documentação para usuário técnico e não técnico.
- Evidências de execução, testes e limites conhecidos.
- Demonstração web para GitHub Pages.

**Links**

- [Repositório](https://github.com/Victorzinn704/Aprendendo-em-C-e-C-)
- [Demonstração no GitHub Pages](https://victorzinn704.github.io/Aprendendo-em-C-e-C-/)
- [Matriz de testes e casos de uso](https://github.com/Victorzinn704/Aprendendo-em-C-e-C-/blob/main/docs/testing/use-case-test-matrix.md)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Gerenciador de Tarefas

Aplicação React para organização de tarefas, com foco em fluxo simples, tema claro/escuro e documentação verificável.

**Pontos técnicos**

- Interface responsiva com estados claros.
- Tema claro e escuro.
- Testes de comportamento.
- Documentação de casos de uso e evidências.
- Publicação via GitHub Pages.

**Links**

- [Repositório](https://github.com/Victorzinn704/Gerenciador-de-Tarefas-)
- [Demonstração no GitHub Pages](https://victorzinn704.github.io/Gerenciador-de-Tarefas-/)
- [Matriz de testes e evidências](https://github.com/Victorzinn704/Gerenciador-de-Tarefas-/blob/main/docs/MATRIZ-DE-TESTES-E-EVIDENCIAS.md)

</td>
<td width="50%" valign="top">

### Project Sentinel

Gateway local para operação autorizada com modelos compatíveis com OpenAI.

**Pontos técnicos**

- Servidor local em Go.
- Políticas de permissão e auditoria.
- Persistência local com SQLite.
- Guia de operação e treinamento.
- Documentação de segurança e validação.

**Links**

- [Repositório](https://github.com/Victorzinn704/project-sentinel)
- [Documentação](https://github.com/Victorzinn704/project-sentinel/tree/main/docs)
- [Matriz de testes](https://github.com/Victorzinn704/project-sentinel/blob/main/docs/testing/use-case-test-matrix.md)

</td>
</tr>
</table>

---

## Stack por uso real

<table>
<tr>
<td width="33%" valign="top">

### Produto web

Next.js · React · TypeScript · Vite · Tailwind CSS · PWA · Framer Motion · Zod

</td>
<td width="33%" valign="top">

### Backend e dados

NestJS · Node.js · PostgreSQL · Prisma · Redis · Socket.IO · Firebase · Firestore

</td>
<td width="33%" valign="top">

### Sistemas e runtime

C · C++ · Python · Rust · Go · PowerShell · SQLite · WASAPI · CUDA · CTranslate2

</td>
</tr>
<tr>
<td width="33%" valign="top">

### Qualidade

GitHub Actions · Jest · Vitest · Playwright · pytest · cargo test · ESLint · TypeScript check

</td>
<td width="33%" valign="top">

### Observabilidade

SonarQube · Grafana · Prometheus · k6 · logs estruturados · health checks

</td>
<td width="33%" valign="top">

### Operação

Docker · Linux · Oracle Cloud · Railway · Vercel · GitHub Pages · Cloudflare

</td>
</tr>
</table>

---

## Padrão de documentação que estou consolidando

Estou organizando meus repositórios para seguirem o mesmo raciocínio de engenharia. A meta não é deixar tudo bonito por fora; é permitir que outra pessoa entenda o projeto sem depender de explicação informal.

Em cada projeto, busco manter:

- **README de entrada** explicando objetivo, contexto, stack, status e como executar.
- **Casos de uso** mostrando onde a funcionalidade aparece na prática.
- **Matriz de testes e evidências** conectando fluxo, comando, resultado esperado e comprovação.
- **Guia de ambiente** para preparação local, dependências e comandos.
- **Arquitetura** com decisões, trade-offs, limites e próximos passos.
- **Capturas de tela ou logs não sensíveis** para comprovar funcionamento.
- **CI quando o projeto permite** para reduzir regressão e validar mudanças antes do merge.

Essa estrutura já está mais madura no Desk Imperial, TX, Aprendendo em C/C++, Gerenciador de Tarefas, Project Sentinel e RH Insights. O próximo ajuste é manter essa régua em todos os repositórios menores.

---

## Como eu trabalho

- Escrevo documentação junto com o código, principalmente quando existe regra de negócio ou decisão técnica que pode ser esquecida depois.
- Prefiro fluxo rastreável: requisito, implementação, teste, evidência e limite conhecido.
- Trato teste como ferramenta de manutenção, não como formalidade para passar em pipeline.
- Quando uma entrega ainda não está confiável, marco como estabilização em vez de vender como pronta.
- Tento manter o projeto apresentável para pessoas técnicas e também explicável para quem só quer entender o uso.

---

## Ciclo atual de melhoria

O foco atual do perfil é deixar os repositórios conversando entre si:

- reduzir warnings técnicos restantes no RH Insights;
- manter o workflow do Project Sentinel como porta mínima de qualidade para mudanças futuras;
- manter os READMEs alinhados com guias de uso, testes e evidências;
- melhorar tópicos, descrições e links de demonstração nos repositórios;
- publicar demonstrações no GitHub Pages quando fizer sentido;
- separar claramente estudo, produto, runtime, frontend e operação.

---

## English summary

Software Engineering student from Brazil, focused on building public, documented and testable software. My main project is **Desk Imperial**, an open source full-stack commercial management platform with production app, API, real-time flows, tests and technical documentation.

I also maintain projects in real-time audio translation, C/C++ fundamentals, React interfaces and local operation tooling. This profile is organized as a technical portfolio: each repository should show the problem, architecture, implementation, tests, evidence and known limits.
