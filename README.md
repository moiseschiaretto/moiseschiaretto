## Olá, meu nome é Moisés Chiaretto!

QA Sênior | Test Automation Engineer (SDET) — automação end-to-end, mensageria (Kafka), contratos de API, performance e segurança, cobrindo toda a pirâmide de testes (back-end, front-end, mobile, performance, carga e segurança).

Diferencial em abordagem **QAOps & AI-First**: uso Claude Code, Claude e ChatGPT no dia a dia para acelerar geração de cenários, automação e testes exploratórios, aplicando engenharia de prompt (**Prompt Engineering**).

📍 Curitiba - PR | 🔗 [linkedin.com/in/moiseschiaretto](https://www.linkedin.com/in/moiseschiaretto)

---

## 🎓 Formação em andamento
- **UTFPR** — Especialização em Inteligência Artificial Generativa Aplicada (360h)

## 🎓 Formação concluída
- **UTFPR** — Especialista em Tecnologia Java, TI (2007 – 2009, 380h)
- **FACET** — Bacharel em Tecnologia em Processamento de Dados, TI (2002 – 2006, 2.940h)

## 📚 Cursos Complementares & Certificações
- English for Tech: Comunicação Técnica e Corporativa — Meta B2/C1 (Em andamento)
- Corporação SF: Fundamentos e Desenvolvimento no Ecossistema Salesforce - CRM (Em andamento)
- SESC da Esquina: Robótica e Eletrônica Prática (2023, 48h, Concluído)

---

## 🧰 Stack principal
* **IA Aplicada a QA (AI-First Engineering):** LLMs (Gemini, Claude), engenharia de prompt, Skills reutilizáveis, Prompt Registry (auditoria de gerações), MCP (Model Context Protocol) para integração com GitHub — geração e execução de testes assistida por IA
* **Mensageria & Cache:** Apache Kafka (KRaft), Redis — idempotência, reprocessamento, Dead Letter Queue (DLQ), consistência cache-aside
* **Back-end (API REST):** Playwright, Rest Assured (Java), Python (requests), Supertest+Jest, Robot Framework (RequestsLibrary) com BDD em Gherkin nativo (Given, When, Then) — testes de contrato em arquitetura de microsserviços (Joi, JSON Schema), múltiplos métodos HTTP, validação de status codes, Swagger, OpenAPI
* **Front-end (Web):** Playwright, Robot Framework (Browser Library) — E2E, responsivo (Desktop, Tablet, Mobile, iPhone), Page Object Model
* **Mobile:** Appium (Python, pytest), UiAutomator2, Page Object Model, Allure
* **Performance:** k6 — testes de carga e stress, com CI/CD e dashboard em tempo real; monitoramento de Core Web Vitals (LCP, CLS, INP) via Playwright
* **Segurança (DAST):** OWASP ZAP — testes de vulnerabilidades (SQL Injection, XSS, IDOR, autenticação fraca), pipeline CI/CD bloqueando merge em achados críticos
* **Linguagens:** Java, C#, Python, JavaScript, TypeScript, Node.js
* **DevOps & CI/CD:** GitHub Actions, Docker, Docker Compose, Git, GitLab
* **Gestão de Testes & Ágil:** Jira (API REST), Looker Studio (dashboards de KPIs)
* **Normas:** conhecimento de ISTQB, aderência a IEEE 29119, CMMI e ISO/IEC 25010

---

## 📌 Portfólio em destaque

Além da automação tradicional, apliquei IA generativa como arquitetura de teste, não apenas como ferramenta de produtividade.

### 🤖 IA — geração automática de suítes de testes (LLM + MCP)
- **[ai-swagger-to-playwright-generator](https://github.com/moiseschiaretto/ai-swagger-to-playwright-generator) (repositório privado — solicite acesso via moiseschiaretto@gmail.com)** — gerador de suítes de testes de contrato **Playwright** a partir da URL de qualquer especificação **Swagger/OpenAPI**, usando IA (**Gemini/Claude**) com Skills, Prompt Registry e integração **MCP**. 48/48 testes de contrato gerados automaticamente e validados contra API real.
- **ai-qa-agent-rest-tester (repositório privado — solicite acesso via moiseschiaretto@gmail.com)** — agente de QA que gera, executa e analisa causa raiz de testes de API em tempo real, via LLM (**Gemini/Claude**), com Skills, Prompt Registry e abertura automática de issues no **GitHub** via **MCP**.

### 📨 Mensageria — Sistemas Distribuídos (Kafka)
- **[java-messaging-idempotency-tests](https://github.com/moiseschiaretto/java-messaging-idempotency-tests)** — testes de integração para mensageria (**Kafka**), cache (**Redis**) e persistência (**PostgreSQL/Hibernate**) com **Spring Boot**, cobrindo idempotência, reprocessamento e Dead Letter Queue (DLQ); relatórios **Allure** e evidências de execução completas

### 🔌 Back-end — APIs
- **[cypress-playwright-api-tests](https://github.com/moiseschiaretto/cypress-playwright-api-tests)** — testes de API REST com **Cypress** e **Playwright** em **JavaScript (Node.js)**: 66 cenários cobrindo dados, schema, contrato, autenticação **JWT**, CRUD e casos negativos, com relatórios **Allure** e CI no **GitHub Actions**
- **[playwright-public-api-contract-tests](https://github.com/moiseschiaretto/playwright-public-api-contract-tests)** — testes de contrato de API REST pública com **Playwright** e **TypeScript**, validação de schema com **Joi** e pipeline CI/CD no **GitHub Actions**
- **[java-api-rest-assured-contract-tests](https://github.com/moiseschiaretto/java-api-rest-assured-contract-tests)** — testes de contrato de API REST em **Java**, **Rest Assured** + **TestNG**, validação de schema (**JSON Schema**), relatório customizado + **Allure**
- **[csharp-playwright-api-contract-tests](https://github.com/moiseschiaretto/csharp-playwright-api-contract-tests)** — testes de API REST em **C#** com **Playwright (.NET)** e **NUnit**: validação de schema e de contrato, múltiplos status HTTP (200, 201, 400, 401, 404), token automático, logs de execução, relatórios **Allure** e HTML, CI/CD
- **[robot-api-contract-tests](https://github.com/moiseschiaretto/robot-api-contract-tests)** — Framework de testes de contrato de API REST (DummyJSON) em **Robot Framework**, estendido com libraries **Python** próprias para validação de schema JSON e comparação de dados request/response. 17 cenários cobrindo múltiplos métodos e status HTTP, com relatórios **Allure** e pipeline CI/CD

### 🖥️ Front-end — E2E
- **[cypress-playwright-bdd-e2e](https://github.com/moiseschiaretto/cypress-playwright-bdd-e2e)** — testes E2E com BDD (**Cucumber/Gherkin**): os mesmos cenários executados no **Cypress** e no **Playwright**, em **JavaScript (Node.js)**, com relatórios **Allure** e CI no **GitHub Actions**
- **[playwright-frontend-e2e-tests](https://github.com/moiseschiaretto/playwright-frontend-e2e-tests)** — testes E2E responsivos (desktop, mobile, tablet, iPhone) com **Page Object Model** e **TypeScript**
- **[robot-playwright-e2e-tests](https://github.com/moiseschiaretto/robot-playwright-e2e-tests)** — testes E2E com **Robot Framework** + **Browser Library (Playwright)**, BDD em **Gherkin** nativo (Given, When, Then), site SauceDemo, relatório **Allure**, CI/CD

### 📱 Mobile
- **[mobile-python-appium-yodapp](https://github.com/moiseschiaretto/mobile-python-appium-yodapp)** — automação mobile Android com **Appium** + **Python (pytest)**, **Page Object Model** e relatórios **Allure**/HTML

### ⚡ Performance
- **[playwright-web-vitals-monitor](https://github.com/moiseschiaretto/playwright-web-vitals-monitor)** — monitoramento de Core Web Vitals (LCP, CLS, INP) e do tempo total de carregamento (Full Load) com **Playwright** e **JavaScript (Node.js)**, coleta via **PerformanceObserver**, relatório HTML próprio e execução semanal no **GitHub Actions**

### 📈 Carga
- **[k6-web-runner](https://github.com/moiseschiaretto/k6-web-runner)** — ferramenta própria de testes de carga em APIs HTTP com **k6**, desenvolvida em **JavaScript (Node.js)** + **Express**: gera o script a partir de comandos curl, transmite a execução ao vivo para o navegador via **Server-Sent Events (SSE)** e exibe dashboard web em tempo real, com smoke test no **GitHub Actions**

### 🔒 Segurança
- **[security-dast-leasing-demo](https://github.com/moiseschiaretto/security-dast-leasing-demo)** — automação de testes de segurança (DAST) com **OWASP ZAP**, app vulnerável **Node.js/Express** como alvo, interface web para diagnóstico em tempo real e pipeline CI/CD (**GitHub Actions**) que bloqueia merge em vulnerabilidades críticas

### 📊 Gestão de Testes & KPIs
- **[jira-kpi-dashboard-sync](https://github.com/moiseschiaretto/jira-kpi-dashboard-sync)** — sincronização de KPIs do **Jira** via API REST, relatório HTML e exportação CSV

Todos os repositórios têm pipeline de CI/CD via GitHub Actions.

---

## 📫 Contato
- LinkedIn: [linkedin.com/in/moiseschiaretto](https://www.linkedin.com/in/moiseschiaretto)
- E-mail: [moiseschiaretto@gmail.com](mailto:moiseschiaretto@gmail.com)
- Curitiba, PR — Disponível para novas oportunidades remotas
