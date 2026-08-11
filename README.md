<h1 align="center">Olá, mundo!! 💻🌻</h1>

## 📚 Sobre mim

Meu nome é Mellyssa Mendes, sou desenvolvedora backend formada em Sistemas de Informação pelo IFES e atualmente curso Pós-Graduação em Engenharia de Software na USP/Esalq. Gosto de resolver problemas reais com código limpo e arquitetura bem pensada. Atuei como desenvolvedora Backend nas empresas Americanas e Will bank, atuando principalmente com TypeScript e Java. Gosto de estudar e aprender coisas novas — hoje estou me aprofundando em Kubernetes, Cloud e em aplicações com IA generativa (integração de LLMs). 

## 🛠️ Tecnologias

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,java,typescript,go,spring,nestjs,nodejs,postgresql,mongodb,docker,kubernetes,git,github" />
</a>

## 💼 Projetos em destaque

### 💰 [Extrato Popular](https://github.com/mellyssamnds/extrato-popular)
API REST de gestão financeira pessoal para as classes C e D — sem burocracia, sem custo e sem exigência de conta bancária premium. Desenvolvida durante o **Hackathon Ada Tech 2026** em parceria com a Artemisia.

🛠️ Java 21 | Spring Boot 3.3 | Spring Security + JWT | PostgreSQL | Spring AI (RAG) | OpenAI API | Swagger | JUnit/Mockito/JaCoCo

- Transforma extratos bancários (CSV/OFX) em um painel financeiro completo: categorização automática de gastos, orçamentos por categoria e alertas de limite.
- Otimização financeira com **3 algoritmos via Strategy Pattern** (Knapsack, Gulosa e ROI).
- Inclui um **pipeline de IA com RAG**: chat financeiro e relatórios personalizados gerados por LLM (gpt-4o-mini).
- Isolamento multi-tenant garantido por testes de integração dedicados.
- **297 testes automatizados**, 95% de cobertura de linhas (JaCoCo) — Clean Architecture com separação clara entre domínio, aplicação, infraestrutura e interfaces.

### 📦 [Go Pedidos API](https://github.com/mellyssamnds/go-pedidos-api)
API REST desenvolvida em **Go** (projeto de estudo, já que estou aprendendo a linguagem) para gerenciamento de clientes, produtos e pedidos, com criação de pedidos 100% transacional.

🛠️ Go 1.26 | net/http | PostgreSQL 18 | pgx/v5 | golang-migrate | testify | Docker Compose

- Arquitetura em camadas (Controllers → Services → Repositories → Database).
- Interface `Querier` permite reaproveitar a mesma implementação de repositório em operações comuns e transacionais.
- Criação de pedidos dentro de uma única transação: valida estoque, atualiza quantidades e persiste itens — com rollback automático em caso de falha.
- Testes unitários (mocks) e testes de integração contra PostgreSQL real, com relatório de cobertura via `go tool cover`.

### 🏅 [Esportes dELAS](https://github.com/mellyssamnds/esportes-delas)
Sistema para incentivar e empoderar meninas através da prática esportiva, oferecendo um ambiente seguro e inclusivo. Projeto Final da Imersão JavaScript da **{reprograma}**.

🛠️ TypeScript | NestJS | Node.js | MongoDB (Mongoose) | Swagger | Render

- CRUD completo de atletas e treinos, com documentação de API via Swagger e deploy em nuvem.
- Projeto com propósito social: combate estereótipos de gênero no esporte e promove autoconfiança entre meninas e jovens.

