<h1 align="center">Olá, eu sou o Mário Henrique 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&pause=1000&color=2EA043&center=true&vCenter=true&width=700&lines=Desenvolvedor+Back-end+.NET+Pleno;C%23+%7C+.NET+%7C+PostgreSQL+%7C+RabbitMQ+%7C+Docker;Microsservi%C3%A7os%2C+DDD+e+Clean+Architecture" alt="Desenvolvedor Back-end .NET Pleno" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/m%C3%A1rio-henrique-6a235b160/" target="_blank">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Mariohcb95/sales-green">
    <img alt="Projeto em destaque" src="https://img.shields.io/badge/Portf%C3%B3lio-SalesGreen-2EA043?style=for-the-badge&logo=dotnet&logoColor=white" />
  </a>
</p>

---

## 🚀 Sobre mim

Sou **Desenvolvedor Web Pleno** focado em **back-end com C# e .NET**, estudante de **Sistemas de Informação no IFG – Campus Goiânia**.

No dia a dia trabalho com **sistemas em produção**: evoluo e mantenho aplicações .NET (incluindo legado em Web Forms), integro plataformas, modelo e otimizo bancos **PostgreSQL** e resolvo problemas de ponta a ponta — do banco ao front-end com jQuery/AJAX.

Nas horas livres, gosto de explorar o ecossistema **.NET moderno** em projetos pessoais, praticando microsserviços, mensageria, testes automatizados e CI/CD.

- 🧩 **Gosto de:** regras de negócio complexas, integrações e domínio **fiscal/varejo** (NF-e, reforma tributária IBS/CBS)
- 📚 **Aprendendo agora:** arquitetura distribuída, observabilidade e mensageria em escala

---

## ⭐ Projeto em destaque — [SalesGreen](https://github.com/Mariohcb95/sales-green)

[![CI](https://github.com/Mariohcb95/sales-green/actions/workflows/ci.yml/badge.svg)](https://github.com/Mariohcb95/sales-green/actions/workflows/ci.yml)
![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-4169E1?logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-MassTransit-FF6600?logo=rabbitmq&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-5-1287B1?logo=apachecassandra&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white)

**Backend de varejo (mercados e hortifrútis) em microsserviços .NET 10** — catálogo com importação de planilhas, pedidos, estoque com lotes e validade, faturamento com **motor tributário preparado para IBS/CBS** e projeção analítica de risco de ruptura.

| O que o projeto demonstra | Como |
|---|---|
| 🏗️ **Arquitetura** | 5 microsserviços independentes, **DDD** + **Clean Architecture**, um banco por serviço |
| 🔁 **Consistência distribuída** | **Saga orquestrada** com compensação, **Outbox/Inbox**, consumidores idempotentes, retry e DLQ |
| 📦 **Regra de negócio real** | Reserva de estoque por **FEFO** (lote que vence primeiro), concorrência otimista, preço vigente vindo do catálogo |
| 🧾 **Domínio fiscal** | Motor tributário no domínio, pronto para a transição da reforma tributária (IBS/CBS) |
| 🛡️ **Resiliência e observabilidade** | **Polly** (timeout, retry com jitter, circuit breaker), Serilog estruturado, health checks, ProblemDetails |
| ✅ **Qualidade** | **71 testes** (xUnit, MassTransit Test Harness, **Testcontainers** com PostgreSQL e RabbitMQ reais) |
| 🚢 **Entrega** | Docker multi-stage não-root, Docker Compose, **GitHub Actions** + **SonarCloud** |
| 📝 **Decisões documentadas** | **12 ADRs** explicando o porquê de cada escolha técnica |

```bash
git clone https://github.com/Mariohcb95/sales-green.git && cd sales-green
docker compose up --build -d   # sobe tudo: 5 APIs + PostgreSQL + RabbitMQ + Cassandra
./scripts/demo.sh              # roda o fluxo completo de ponta a ponta
```

<p align="center">
  <a href="https://github.com/Mariohcb95/sales-green"><b>➡️ Ver o código, a arquitetura e os ADRs</b></a>
</p>

---

## 📂 Outros projetos

| Projeto | Descrição | Stack |
|---|---|---|
| [scraping](https://github.com/Mariohcb95/scraping) | Scraping para obter o HTML do site da Receita Federal | Python |
| [solve-simplex](https://github.com/Mariohcb95/solve-simplex) | Resolução de problemas de Pesquisa Operacional (Simplex) com PuLP | Python |
| **EconoMax** *(privado, em desenvolvimento)* | Produto voltado à economia no varejo, construído sobre a base do SalesGreen | .NET |

---

## 🛠️ Stack

**Back-end**<br/>
<img alt="C#" title="C#" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" />
<img alt=".NET" title=".NET" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dot-net/dot-net-original.svg" />
<img alt="Python" title="Python" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
<img alt="Java" title="Java" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" />

**Dados e mensageria**<br/>
<img alt="PostgreSQL" title="PostgreSQL" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" />
<img alt="Cassandra" title="Apache Cassandra" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cassandra/cassandra-original.svg" />
<img alt="RabbitMQ" title="RabbitMQ" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rabbitmq/rabbitmq-original.svg" />

**DevOps e qualidade**<br/>
<img alt="Docker" title="Docker" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" />
<img alt="GitHub Actions" title="GitHub Actions" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" />
<img alt="SonarQube" title="SonarCloud" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sonarqube/sonarqube-original.svg" />
<img alt="Git" title="Git" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" />

**Front-end**<br/>
<img alt="JavaScript" title="JavaScript" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" />
<img alt="TypeScript" title="TypeScript" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" />
<img alt="React" title="React" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" />
<img alt="jQuery" title="jQuery" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jquery/jquery-original.svg" />
<img alt="HTML" title="HTML" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" />
<img alt="CSS" title="CSS" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" />
<img alt="Bootstrap" title="Bootstrap" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" />

**Práticas:** DDD · Clean Architecture · SOLID · Microsserviços · Saga · Outbox Pattern · APIs REST · Testes automatizados · CI/CD

---

## 📊 Estatísticas

<p align="center">
  <img height="170em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Mariohcb95&theme=github_dark" alt="Estatísticas do GitHub" />
  <img height="170em" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Mariohcb95&theme=github_dark" alt="Linguagens com mais commits" />
</p>

---

## 📫 Contato

Quer trocar uma ideia sobre .NET, arquitetura ou algum dos meus projetos? Me chama no LinkedIn:

<p align="left">
  <a href="https://www.linkedin.com/in/m%C3%A1rio-henrique-6a235b160/" target="_blank">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-M%C3%A1rio%20Henrique-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
