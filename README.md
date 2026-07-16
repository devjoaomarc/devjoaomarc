# Olá, eu sou o João Marcelo 👋

Desenvolvedor migrando de front-end para back-end Java, construindo uma infraestrutura de plataforma própria (autenticação, gateway, notificações) para sustentar múltiplos sistemas.

## 🧭 Minha trajetória

- **Abril 2020 – Fevereiro 2024** — Analista de Qualidade, com automação de testes (Robot Framework, Selenium, Cypress)
- **Abril 2025 – Março 2026** — Desenvolvedor Fullstack (atuação com foco em front-end: Next.js, TypeScript, TailwindCSS) em squad com backend em Spring Boot, Keycloak, Eureka e RabbitMQ
- **Atualmente** — Cursando Análise e Desenvolvimento de Sistemas (Uniasselvi), aprofundando em **Java + Spring Boot** e construindo minha própria infraestrutura de plataforma

Essa trajetória — QA, depois front-end integrado a um backend orientado a microsserviços — é o que me trouxe até aqui: entendo tanto o que quebra em produção quanto o que a arquitetura por trás precisa entregar para o front funcionar bem.

## 🏗️ Pensando em plataforma, não só em projetos soltos

Trabalhando de perto com um backend que usava **Keycloak** (autenticação), **Eureka** (service discovery) e **RabbitMQ** (mensageria), percebi o valor de ter uma base de infraestrutura compartilhada em vez de resolver autenticação e comunicação entre serviços a cada novo sistema.

É essa a lógica por trás da **[macaoli-labs](https://github.com/macaoli-labs)**: uma organização para concentrar os serviços de infraestrutura (autenticação, gateway, notificações) que qualquer sistema meu — atual ou futuro — vai poder consumir, em vez de reconstruir do zero.

O primeiro componente é o **[macaoli-auth](https://github.com/macaoli-labs/macaoli-auth)**, autenticação via Spring Boot com sessão baseada em cookies, projetada desde o início para ser reutilizável entre múltiplos produtos (o primeiro deles: `music-booker`).

## 🧱 Stack

**Back-end (foco atual)**
`Java` · `Spring Boot`

**Front-end (experiência sólida)**
`Next.js` · `TypeScript` · `Tailwind CSS` · `PrimeReact` · `TanStack` · `React Hook Form`

**QA / Automação**
`Robot Framework`

## 📂 Repositórios da plataforma

| Repositório | Papel na arquitetura |
|---|---|
| `macaoli-auth` | Autenticação (Spring Boot + cookies) — em desenvolvimento |
| `macaoli-gateway` | Ponto único de entrada e roteamento entre serviços — planejado |
| `macaoli-notifications` | Serviço de notificações compartilhado — planejado |
| `music-booker-web` / `music-booker-server` | Primeiro produto consumindo a plataforma macaoli |

## 🌐 Onde me encontrar

- 💼 [LinkedIn](https://linkedin.com/in/devjoaom)
- 🌍 [Portfólio](https://devjoaom.macaoli.com.br)
- 🏢 [macaoli-labs](https://github.com/macaoli-labs) — organização com a infraestrutura reutilizável dos meus projetos
- ✉️ devjoaom@gmail.com

---
*Este README é atualizado conforme evoluo nos projetos e na transição para Java.*
