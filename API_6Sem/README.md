# 🧠 Synapse | API 6º Semestre — FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/Titus-System/synapse)

> 🚧 Projeto em desenvolvimento, com apresentação prevista para 03/12/2026.

## 📌 Sobre o Projeto

O **Synapse** é uma aplicação web desenvolvida com base na metodologia **API (Aprendizagem por Projetos Integrados)** durante o 6º semestre do curso de Análise e Desenvolvimento de Sistemas da **FATEC São José dos Campos — Prof. Jessen Vidal**, pela equipe **Titus Systems**.

O projeto tem como objetivo **estruturar regras de negócio relacionadas ao comissionamento de vendas e avaliar seus impactos financeiros com apoio de inteligência artificial**.

A proposta permite transformar informações fornecidas pelo usuário em regras processáveis, simular seus efeitos sobre dados históricos e comparar os resultados com um cenário de referência, denominado **baseline**. O escopo contempla entrada por texto e voz, sugestões de adaptação e recursos de rastreabilidade para apoiar a análise das decisões.

## 🏢 Parceiro de Negócios (Cliente)

O desafio foi proposto pela **Dom Rock**, representada no projeto por **Luiz Otavio e Andre Almeida**.

A demanda está relacionada à dificuldade de registrar e manter regras corporativas que mudam com frequência, como campanhas de incentivo, políticas comerciais e condições de comissionamento. Quando essas informações não são estruturadas, podem ocorrer inconsistências, perda de conhecimento e dificuldades de auditoria.

O Synapse busca apoiar esse processo ao reunir definição de regras, simulação de cenários e consulta aos resultados em uma mesma aplicação.

## 🚀 Funcionalidades e Demonstração

O escopo do projeto está organizado nas seguintes funcionalidades:

- 📝 **Entrada de regras por texto:** definição dos parâmetros utilizados na simulação.
- 🎙️ **Captura e transcrição de voz:** conversão de áudio em texto para processamento das regras.
- 🤖 **Extração e geração assistidas por IA:** interpretação das informações e geração de código para representar a regra proposta.
- 📊 **Simulação de comissionamento:** aplicação da regra sobre dados históricos e comparação com o baseline.
- 💰 **Avaliação orçamentária:** análise da compatibilidade do resultado com o orçamento informado.
- 🔄 **Sugestões de adaptação:** apoio à revisão de cenários que apresentem incompatibilidade financeira.
- 🗂️ **Histórico de regras:** consulta às regras salvas e arquivadas.
- 🔎 **Detalhamento dos resultados:** visualização das comissões por colaborador, com filtros e paginação.
- 🔐 **Autenticação:** controle de acesso e gerenciamento de sessões com Keycloak.
- 📋 **Auditoria e explicabilidade:** recursos previstos para registrar fontes, versões e justificativas associadas ao processamento.

### 🛠️ Arquitetura do Sistema

<a id="arq"></a>

O **Synapse** utiliza uma arquitetura distribuída, com processamento assíncrono e comunicação orientada a eventos. A solução separa a interface, a API principal, o serviço de geração de código e o worker responsável pela execução das simulações.

| Componente | Responsabilidade | Tecnologias principais |
| --- | --- | --- |
| Front-end | Formulários, histórico, acompanhamento e visualização dos resultados | Vue.js, TypeScript, Vite e Tailwind CSS |
| API principal | Controle dos fluxos, autenticação, persistência e comunicação com a interface | Java e Spring Boot |
| Serviço de geração de código | Extração, validação e transformação das regras com apoio de IA | Python, FastAPI e LangGraph |
| Worker de execução | Execução isolada do código e processamento das simulações | Python e Docker |
| Mensageria | Comunicação assíncrona entre os serviços | RabbitMQ |
| Persistência | Armazenamento de regras, execuções e resultados | PostgreSQL |
| Autenticação | Gerenciamento de identidades e sessões | Keycloak |

O código gerado pela inteligência artificial é tratado como não confiável e executado em **contêineres isolados**, com restrições de rede e recursos computacionais. Essa separação reduz a exposição dos demais serviços durante as simulações.

A interface acompanha atualizações do processamento por meio de **Server-Sent Events (SSE)**.

[🔗 Consultar a documentação da arquitetura](https://github.com/Titus-System/synapse/blob/main/docs/ARCHITECTURE.md)

### 🖥️ Demonstração

Confira a demonstração da **Sprint 2**, disponibilizada pela equipe:

https://github.com/user-attachments/assets/5c50876b-64d8-44c6-9050-4d9dfb758745

## 💻 Tecnologias Utilizadas

### ⚙️ Back-end e Inteligência Artificial

<p align="left">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge" />
  <img alt="Deepgram" src="https://img.shields.io/badge/Deepgram-101828?style=for-the-badge" />
</p>

### 🖥️ Front-end

<p align="left">
  <img alt="Vue.js" src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

### 🗄️ Persistência, Mensageria e Segurança

<p align="left">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
  <img alt="Keycloak" src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

### 🛠️ Versionamento e Qualidade

<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" />
  <img alt="Pytest" src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Minha atuação no **Synapse** abrange o desenvolvimento de interfaces e contribuições nos serviços de back-end, autenticação e processamento de inteligência artificial, integrando diferentes etapas do fluxo de simulação.

No **front-end**, participei da estruturação inicial da aplicação com **Vue.js e TypeScript**, incluindo rotas, estado global e integração com o ambiente Docker. Implementei o formulário de regras, com validação dos parâmetros, competência e orçamento, além da integração com a API para criação e consulta dos processamentos.

Também desenvolvi o **histórico de regras salvas e arquivadas**, com paginação, contadores e componentes compartilhados de navegação. Na apresentação dos resultados, implementei o detalhamento das comissões por colaborador, com filtros por matrícula, loja e competência, paginação local e tratamento dos estados de carregamento, erro e ausência de dados.

Na frente de **autenticação**, contribuí para a integração do **Keycloak**, incluindo proteção da API com JWT, gerenciamento de sessão na interface, guarda de rotas, envio do token nas requisições e encerramento da sessão. Também realizei ajustes de responsividade e navegação.

No **back-end e no processamento de IA**, participei da estruturação inicial da API e do serviço de geração de código. Contribuí para a extração de regras a partir das transcrições e para a integração da validação de domínio ao fluxo de geração, impedindo que regras com conflitos avancem para essa etapa.

Na funcionalidade de voz, implementei o cliente de integração com o **Deepgram Nova-3** e melhorias no processamento das transcrições, incluindo validação dos formatos de áudio, tratamento de falhas, tentativas limitadas e controle de concorrência. Também contribuí para o fluxo de recebimento e aceitação de metas sugeridas.

Complementarmente, desenvolvi entregas visuais das telas de entrada por texto e voz e do chatbot de correção. Essas entregas foram registradas como parciais, com a integração funcional prevista para etapas posteriores.

As atividades foram acompanhadas pela elaboração de testes automatizados, validação de contratos, ajustes de persistência e padronização das verificações de qualidade. Utilizei **Git e GitHub** para registrar e integrar as alterações ao trabalho da equipe.

<h3>Hard Skills</h3>
<details>
  <summary><b>Clique para ver a lista de hard skills</b></summary>
  <br>
  <!-- Notas sugeridas: revisar conforme a autoavaliação pessoal. -->
  <table align="center">
    <tr>
      <th width="300px">Tecnologia / Metodologia</th>
      <th width="100px">Nota</th>
      <th width="200px">Classificação</th>
    </tr>
    <tr>
      <td>Vue.js, TypeScript & Vite</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Tailwind CSS & Componentização de Interfaces</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Java & Spring Boot</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Python, FastAPI & Integração de IA</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Keycloak & Autenticação JWT</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>PostgreSQL & Migrações de Banco de Dados</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>RabbitMQ & Processamento Assíncrono</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Testes Automatizados & Validação de Contratos</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Git / GitHub / Organização por Sprints</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
  </table>
</details>

<h3>Soft Skills</h3>
<details>
  <summary><b>Clique para ver a lista de soft skills</b></summary>
  <br>
  <!-- Notas sugeridas: revisar conforme a autoavaliação pessoal. -->
  <table align="center">
    <tr>
      <th width="300px">Habilidade</th>
      <th width="200px">Classificação</th>
    </tr>
    <tr>
      <td>Orientação ao Cliente (Dom Rock)</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Adaptabilidade & Aprendizagem Contínua</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Trabalho em Equipe</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Comunicação Técnica</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Raciocínio Lógico & Resolução de Problemas</td>
      <td>★★★★★</td>
    </tr>
  </table>
</details>

<br>

Duas habilidades comportamentais relacionadas à minha atuação neste projeto são:

- **Adaptabilidade e aprendizagem contínua:** a participação em diferentes componentes exigiu ampliar meus conhecimentos para além da interface, envolvendo autenticação, serviços Java e Python, processamento de áudio e integração com inteligência artificial.

- **Raciocínio lógico e resolução de problemas:** a construção dos fluxos exigiu compreender contratos de dados, tratar falhas e manter a consistência entre as informações processadas e os resultados apresentados. Essa habilidade esteve presente tanto nas validações das regras quanto na integração dos serviços e no detalhamento das simulações.

## 📅 Metodologia e Sprints

O desenvolvimento foi organizado em **três sprints**, com backlog, critérios de aceitação, Definition of Ready (DoR), Definition of Done (DoD) e demonstrações dos incrementos.

A tabela apresenta o foco de cada ciclo conforme a documentação específica das sprints:

| Etapa | Data | Escopo |
| --- | --- | --- |
| Kick-off | 26/08/2026 | Início do projeto |
| Sprint 1 | 27/09/2026 | Entrada por texto, simulação de regras, comparação com o baseline e histórico dos processamentos |
| Sprint 2 | 25/10/2026 | Captura e transcrição de voz e sugestões de adaptação |
| Sprint 3 — prevista | 22/11/2026 | Auditoria, explicabilidade e validação dos parâmetros extraídos por voz |
| Feira de Soluções — prevista | 03/12/2026 | Apresentação do projeto |

### 📚 Documentação das Entregas

- [Sprint 1 — Simulação e histórico](https://github.com/Titus-System/synapse/blob/main/sprints/sprint-1.md)
- [Sprint 2 — Voz e sugestões de adaptação](https://github.com/Titus-System/synapse/blob/main/sprints/sprint-2.md)
- [Sprint 3 — Auditoria e validação](https://github.com/Titus-System/synapse/blob/main/sprints/sprint-3.md)

---

[⬅️ Voltar para o Menu Principal](https://github.com/Madhs31/Portfolio_Projetos_ADS)
