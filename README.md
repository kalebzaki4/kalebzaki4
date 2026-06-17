<h1 align="center">👋 Olá, eu sou Kaleb Santos</h1>

<p align="center">
  <strong>Desenvolvedor Backend Java | Spring Boot 3 | APIs Resilientes | Arquitetura Escalável</strong>
</p>

<p align="center">
  🚀 Em busca de evolução contínua e da primeira oportunidade como Estágio / Jovem Aprendiz em Tecnologia
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=kalebzaki4&color=blue&style=flat-square" alt="Views">
</p>

<div align="center">
  <a href="https://www.linkedin.com/in/kaleb-z-santos-74214434b/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/kalebzaki4">
    <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</div>

---

# 👨‍💻 Sobre Mim

Sou um desenvolvedor backend focado no ecossistema **Java e Spring Boot**, dedicado a construir sistemas seguros, limpos e de alta performance. Minha jornada na tecnologia começou em 2022 e, desde então, evoluí dos fundamentos full-stack para um mergulho profundo em arquitetura de software corporativa.

Sigo rigorosamente princípios de **Clean Code, SOLID, e separação de responsabilidades**. Busco ir além do "código que funciona", preocupando-me ativamente com a manutenibilidade a longo prazo, análise estática e prevenção de débitos técnicos.

> 🎯 **Nota de Transparência sobre meu Foco:** No meu histórico, possuo uma carga horária expressiva em tecnologias Frontend (React, TypeScript, Angular). No entanto, **o Frontend não é o meu foco**. Tomei a decisão estratégica de direcionar 100% da minha energia para a Engenharia Backend. Como estou há bastante tempo sem praticar a construção de interfaces, posso enfrentar uma curva natural de readaptação ou lentidão inicial caso precise atuar no Front. Tenho a base conceitual, mas minha real fluidez e domínio prático hoje estão nas regras de negócio, segurança e bancos de dados.

### 🎯 Meus focos atuais de estudo e aplicação:
- 🔐 **Segurança Avançada:** Autenticação Stateless com Spring Security, filtros customizados e JWT.
- 🏗️ **Arquitetura & Design:** Padrão DTO com Java Records, injeção de dependência estritamente via construtor e desacoplamento de entidades.
- 🐳 **Infraestrutura como Código & DevOps:** Containerização de ambientes com Docker/Docker Compose e automação de CI/CD.
- 🛡️ **Resiliência:** Tratamento global de exceções centralizado e controle de concorrência.

---

# 🚀 Projetos em Destaque

## 💳 [Payment Gateway API](https://github.com/kalebzaki4/payment-gateway-api)
### API Robusta para Simulação de Ecossistema Fintech

API desenvolvida para simular cenários reais do mercado financeiro e de grandes empresas de tecnologia (fintechs), focada no processamento de transações de alta criticidade, consistência de dados e resiliência.

- **Diferenciais Técnicos:** Aplicação prática de conceitos de arquitetura distribuída, gestão avançada de transações financeiras e isolamento de regras de negócio de alta complexidade.
- **Boas Práticas:** Tratamento rigoroso de payloads de entrada, blindagem contra estados inconsistentes e validação nativa.

**Tech Stack:** `Java 21` `Spring Boot 3` `Spring Data JPA` `MySQL` `Docker` `REST API`

---

## 🔗 [SyncSpace](https://github.com/kalebzaki4/room-reservation-api)
### Sistema Corporativo de Reservas com Controle de Concorrência

API corporativa de alta performance para reserva de salas, projetada para mitigar gargalos reais de concorrência e integridade transacional em sistemas escaláveis.

- **Controle de Concorrência:** Implementação de **Optimistic Locking (@Version)** para garantir a consistência dos dados em múltiplos acessos simultâneos.
- **Segurança Blindada:** Interceptação customizada de requisições via cadeia de filtros (**OncePerRequestFilter**) integrada ao Spring Security e JWT.
- **Design Limpo:** Arquitetura em camadas, injeção de dependência segura via construtor (imutabilidade com `private final`), isolamento de contratos usando **Java Records como DTOs** e tratamento global de erros com `@ControllerAdvice`.
- **Qualidade de Código:** Refatorado constantemente utilizando análise estática com **SonarQube** para eliminação de *code smells*.

**Tech Stack:** `Java 21` `Spring Boot 3.2` `Spring Security` `JWT` `MySQL` `Docker Compose` `Swagger (OpenAPI)` `JUnit` `Mockito`

---

## 📅 [Estuda+ (Plataforma FullStack)](https://github.com/kalebzaki4/Estuda-Mais)
### Ecossistema Web para Produtividade Acadêmica

Aplicação voltada para organização de tarefas e rotina de estudos, unindo uma interface moderna e intuitiva a um ecossistema backend integrado.

- **Integração Ponta a Ponta:** Autenticação segura via JWT, monitoramento de progresso do estudante em tempo real e persistência relacional.
- **Infraestrutura Local:** Ambiente totalmente containerizado e orquestrado, utilizando Nginx para servir o ecossistema frontend de forma eficiente.

**Tech Stack:** `React` `TypeScript` `Tailwind CSS` `Java` `Spring Boot` `MySQL` `Docker` `Nginx`

---

## 📦 Outros Projetos Relevantes
- **[CSV Data Importer](https://github.com/kalebzaki4/csv-data-importer):** Serviço de processamento em lote (Batch Processing) para ingestão transacional de grandes volumes de dados de vendas usando OpenCSV e Hibernate.

---

# 🛠 Tecnologias e Ferramentas

### Backend & Bancos de Dados (Foco Principal)
<img src="https://skillicons.dev/icons?i=java,spring,nodejs,mysql,postgresql,postman" alt="Backend Skills" />

### DevOps, Infraestrutura & Ferramentas
<img src="https://skillicons.dev/icons?i=docker,nginx,git,github,linux,vscode" alt="Tools Skills" />

### Frontend & Linguagens de Interface (Histórico/Conceitual)
<img src="https://skillicons.dev/icons?i=js,ts,react,html,css,tailwind" alt="Frontend Skills" />

---

# ⭐ Diferenciais que Entrego

- **Mentalidade Clean Code:** Substituição de injeção por atributo (*Field Injection*) por injeção via construtor, garantindo código altamente testável.
- **APIs Limpas (Sem try-catch espalhado):** Centralização de erros através de exceções semânticas de domínio capturadas por um Handler global.
- **Garantia de Desempenho:** Preocupação com transações e performance de banco de dados (Indexação, Batch updates com JPA).
- **Documentação Viva:** Contratos de APIs 100% documentados e testáveis via Swagger UI.

---

# 📚 Cursos & Certificações (Alura)

Com **mais de 99 cursos concluídos**, organizei abaixo as formações e especializações de maior impacto e relevância técnica para o mercado corporativo:

### 🔥 Java & Ecossistema Spring Boot (Foco Backend)
* **Trilha Java e Spring Boot 3 (32h):** Desenvolvimento de APIs REST, Spring Security (Autenticação Stateless com JWT), testes dinâmicos, documentação e deploy.
* **Trilha Java Web & Spring Data JPA (40h):** Domínio de concorrência, mapeamento relacional, consultas avançadas e uso avançado de Java Lambdas e Streams.
* **Trilha Boas Práticas em Java (30h):** Refatoração de código legado, aplicação de SOLID e automação de testes unitários.
* **Selenium com Java (8h):** Desenvolvimento de testes automatizados de aceitação ponta a ponta.

### 🐳 DevOps & Infraestrutura
* **DevOps & Containers com Docker (8h):** Construção, gerenciamento e orquestração de ambientes isolados usando Docker e Docker Compose.
* **Redes, Protocolos & Fundamentos da Web (32h):** Compreensão aprofundada de arquitetura de redes, VLANs, segurança e tráfego HTTP por baixo dos panos.

### 💾 Engenharia de Dados
* **Modelagem de Bancos de Dados (24h):** Arquitetura e design de dados relacionais (Entidades, Atributos, Relacionamentos e Modelo Lógico).

### ⚛️ Frontend (Bagagem de Fundamentos / Fora de Prática Ativa)
* **Formações React com TypeScript (~220h acumuladas):** Componentes modernos, gerenciamento de estado (Recoil/Context API), React Router, testes e performance.
* **Formações Angular & Testes Avançados (~70h):** Fundamentos do framework, CRUDs e testes de interfaces com Jasmine e Karma.
> ⚠️ *Nota técnica:* Embora possua sólida bagagem teórica nesta seção, estes estudos fazem parte da minha base fullstack inicial. Por opção de carreira, não venho exercitando o desenvolvimento visual em código recentemente, focando restritamente no backend.

---

# 📈 Roadmap 2026

- [x] APIs REST robustas com Spring Boot 3
- [x] Segurança Avançada com JWT e Filtros
- [x] Docker e Orquestração de Containers locais
- [x] Projeto Fintech Completo (`payment-gateway-api`)
- [ ] Automação de CI/CD com GitHub Actions completo nos repositórios
- [ ] Escrita de Testes de Integração abrangentes
- [ ] Arquiteturas de Microsserviços com Spring Cloud
- [ ] Deploy profissional em Provedor Cloud (AWS/GCP)

---

# 📊 Estatísticas

<p align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=kalebzaki4&theme=radical" width="400" alt="GitHub Stats">
  <img src="https://streak-stats.demolab.com?user=kalebzaki4&theme=tokyonight&hide_border=false" width="400" alt="GitHub Streak">
</p>

---

# 📬 Contato & Verification

Estou sempre aberto a feedbacks, conexões profissionais e desafios que me façam sair da zona de conforto. Vamos conversar?

* **LinkedIn:** [linkedin.com/in/kaleb-z-santos](https://www.linkedin.com/in/kaleb-z-santos-74214434b/)
* **Portfólio de Certificados Alura:** [Validar Conquistas Técnicas](https://cursos.alura.com.br/user/kalebzsantos/fullCertificate/6931f26a868ec00c34a4b1f9b7779791)

---

<p align="center">
  ⭐ <em>“Código limpo não é sobre perfeição, é sobre respeito ao próximo desenvolvedor.”</em>
</p>
