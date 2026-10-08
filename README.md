<h1 align="center">Kauan Kelvin</h1>

<p align="center">
  <strong>Estudante de Engenharia de Software · Back-end · Automação</strong>
</p>

<p align="center">
  Java & Spring Boot · Python · TypeScript · Arquitetura e qualidade de software
</p>

<p align="center">
  <a href="https://kauankelvindev.vercel.app/"><img alt="Portfólio" src="https://img.shields.io/badge/Portf%C3%B3lio-18181B?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/kauan-kelvin"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/kauankelvin7?tab=repositories"><img alt="Repositórios" src="https://img.shields.io/badge/Reposit%C3%B3rios-30363D?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## Sobre

Sou estudante de **Engenharia de Software**, no Brasil, e desenvolvo aplicações web, APIs e automações voltadas a problemas concretos. Minha experiência com processos administrativos e suporte de TI influencia a forma como trabalho: procuro compreender o fluxo real antes de modelar os dados e implementar a solução.

Tenho direcionado meus estudos para **Java, Spring Boot, persistência de dados e desenvolvimento back-end**. Também construo produtos com React e TypeScript e utilizo Python para automatizar tarefas operacionais.

**Busco oportunidades de estágio ou desenvolvimento júnior**, especialmente em back-end e engenharia de software.

## Projetos em destaque

Selecionei projetos que representam desafios técnicos diferentes: confiabilidade de dados, integração com APIs, isolamento de informações, automação de processos e testes.

### [Leve](https://github.com/kauankelvin7/Leve) · Agenda com sincronização e suporte offline

[![Aplicação](https://img.shields.io/badge/Abrir_aplica%C3%A7%C3%A3o-18181B?style=flat-square&logo=vercel&logoColor=white)](https://leve-agenda.vercel.app)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

O Leve é uma agenda pessoal em que **confiabilidade dos dados** é uma preocupação central. O projeto lida explicitamente com edições concorrentes, falhas de rede e sincronização, em vez de sobrescrever alterações sem aviso.

- **Arquitetura:** React, TypeScript, Firebase Auth/Firestore e API Express como caminho de escrita.
- **Decisões:** contratos de domínio com Zod, controle otimista de revisões, comandos idempotentes, fila offline e tratamento de conflitos.
- **Qualidade:** testes, fluxos de integração, verificação de PWA e documentação operacional.

### [RepoLens](https://github.com/kauankelvin7/RepoLens) · Diagnóstico de repositórios GitHub

[![Aplicação](https://img.shields.io/badge/Experimentar-18181B?style=flat-square&logo=vercel&logoColor=white)](https://repolens-zeta.vercel.app)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![GitHub App](https://img.shields.io/badge/GitHub_App-30363D?style=flat-square&logo=github&logoColor=white)

Ferramenta que avalia sinais observáveis de documentação, CI/CD, manutenção e controles de segurança de repositórios públicos. Cada diagnóstico apresenta evidências e critérios definidos, **sem usar IA para atribuir pontuações**.

- **Integração:** GitHub REST API e autenticação de GitHub App com JWT RS256.
- **Segurança e operação:** verificação HMAC SHA-256 de webhooks, invalidação de cache por repositório e separação entre escopos públicos e privados.
- **Limite explícito:** os indicadores de segurança não substituem auditoria ou análise de vulnerabilidades.

### [Omni](https://github.com/kauankelvin7/Omni) · Back-end Java para gestão de clínicas

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

Projeto de sistema de gestão para múltiplas clínicas, com agenda, pacientes, confirmações automáticas e painel administrativo.

- **Back-end:** Java 17, Spring Boot 3, PostgreSQL, autenticação JWT e renovação de sessão.
- **Modelagem:** contexto de clínica extraído do token validado e filtros de isolamento por `tenant_id`; o cabeçalho do cliente não define permissões.
- **Integrações:** interface React/TypeScript, automações em Python e ambiente com Docker Compose.

### [Automação Clínica Odontológica](https://github.com/kauankelvin7/Automacao-Clinica-Odontologica) · RPA com impacto operacional

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![RPA](https://img.shields.io/badge/RPA-Automa%C3%A7%C3%A3o-4B5563?style=flat-square)

Automação criada para um fluxo real de faturamento odontológico: preenchimento de guias em portais de operadoras, associação de documentos e registro de execução.

**Resultado documentado no estudo de caso:** tempo médio aproximado de **8 minutos para 40 segundos por guia** — redução estimada de **91,7%** no cenário descrito. Os valores vêm da documentação do projeto, não de uma medição independente.

- **Implementação:** Python, Selenium WebDriver, validações, tratamento de falhas e logs.
- **Entrega:** versão de portfólio organizada sem credenciais ou dados reais do cliente.

### [Estudos Java](https://github.com/kauankelvin7/estudos-java) · Laboratório técnico

![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)

Repositório de estudo estruturado em **14 módulos independentes**, dos algoritmos à API REST, com código executável, testes, documentação por assunto e decisões de implementação.

Inclui estruturas de dados, orientação a objetos, lambdas, Stream API, exceções, JavaFX, JDBC, MongoDB, JPA/Hibernate e Spring Boot. Na validação local de **08/10/2026**, os **28 testes automatizados passaram**. [Ver documentação e código →](https://github.com/kauankelvin7/estudos-java)

### Outros trabalhos

| Projeto | O que demonstra |
|---|---|
| [Audiobook Studio](https://github.com/kauankelvin7/audiobook-studio) | Aplicação local-first para leitura e exportação de áudio de PDFs; Rust/WASM, Web Workers e conferência explícita de OCR. |
| [Sistema Clínica](https://github.com/kauankelvin7/sistema-clinica) | Geração de documentos clínicos em DOCX/PDF, cadastro e busca de registros; FastAPI, React e PostgreSQL. |
| [Cinesia](https://github.com/kauankelvin7/Cinesia) | Plataforma de estudos com flashcards, revisão espaçada, PWA e sincronização de dados. |
| [socplug-fix](https://github.com/kauankelvin7/socplug-fix) | Diagnóstico e automação de recuperação de ambiente Java/SOCPlug no Windows. |

## Open source

Contribuo também com projetos mantidos por outras pessoas. No **[RustDesk](https://github.com/rustdesk/rustdesk)**, duas contribuições de localização e metadados Android/Fastlane foram aceitas e mescladas no repositório oficial:

- [**PR #16135** — metadados Android em português brasileiro](https://github.com/rustdesk/rustdesk/pull/16135) · mesclado em 10/09/2026.
- [**PR #16162** — metadados Android em italiano](https://github.com/rustdesk/rustdesk/pull/16162) · mesclado em 14/09/2026.

São contribuições de **localização e metadados**, não alterações no runtime. O aprendizado envolveu seguir as convenções do projeto, preparar PRs e participar do fluxo de revisão e integração upstream.

## Tecnologias aplicadas

| Área | Tecnologias utilizadas em projetos e estudos |
|---|---|
| **Back-end** | Java, Spring Boot, Spring Data JPA, Hibernate, REST, Python, FastAPI |
| **Dados** | PostgreSQL, SQL/JDBC, MongoDB, Firebase/Firestore |
| **Automação** | Python, Selenium, processamento de arquivos e logs |
| **Front-end** | React, TypeScript, Next.js, Vite |
| **Testes e entrega** | JUnit 5, Vitest, Playwright, GitHub Actions, Docker, Git |
| **Práticas** | Modelagem de domínio, validação, versionamento, tratamento de erros, documentação e integração contínua |

Minha prioridade é entender **por que uma solução foi construída de determinada forma**: regras de negócio, limites entre camadas, consistência dos dados e comportamento diante de erros. Procuro registrar essas decisões nos repositórios, ao lado do código e dos testes.

---

<div align="center">

### Contato e oportunidades

Aberto a oportunidades de **estágio e desenvolvimento júnior** em engenharia de software, back-end e automação.

[**Portfólio**](https://kauankelvindev.vercel.app/) · [**LinkedIn**](https://www.linkedin.com/in/kauan-kelvin) · [**Repositórios GitHub**](https://github.com/kauankelvin7?tab=repositories)

<sub>Projetos e contribuições acima possuem links diretos para consulta. Indicadores de estudo e de desempenho correspondem aos registros documentados na data indicada.</sub>

</div>
