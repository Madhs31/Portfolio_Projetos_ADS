# 💬 SyncDesk | API 5º Semestre — FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/Titus-System/SyncDesk)

## 📌 Sobre o Projeto

O **SyncDesk** é um sistema de atendimento desenvolvido com base na metodologia **API (Aprendizagem por Projetos Integrados)** durante o 5º semestre do curso de Análise e Desenvolvimento de Sistemas da **FATEC São José dos Campos — Prof. Jessen Vidal**, pela equipe **Titus Systems**.

O principal objetivo da solução é **centralizar o atendimento ao cliente por meio de um chat estruturado**, com triagem automatizada, registro do histórico das interações e acompanhamento do ciclo de vida dos chamados.

A plataforma reúne uma **aplicação mobile para solicitantes** e uma **interface web para atendentes e administradores**, permitindo organizar a abertura, o encaminhamento e o encerramento das demandas, além de acompanhar indicadores da operação.

## 🏢 Parceiro de Negócios (Cliente)

O projeto foi desenvolvido a partir de um desafio proposto pela **Pro4Tech**, representada por **Larissa Souza e Rafael Monteiro**.

A proposta busca melhorar a organização do suporte, a experiência dos solicitantes e o acompanhamento gerencial dos atendimentos, reunindo informações e ferramentas em um ambiente integrado.

## 🚀 Funcionalidades e Demonstração

- 💬 **Chat em tempo real:** troca de mensagens entre solicitantes e atendentes.
- 🤖 **Triagem automatizada:** perguntas iniciais para identificar a necessidade do solicitante e orientar o atendimento.
- 🎫 **Gestão de chamados:** abertura, atribuição, encaminhamento, atualização de status e encerramento das solicitações.
- 🔎 **Histórico e pesquisa:** registro das conversas e busca de mensagens anteriores.
- 👥 **Gestão de usuários:** funcionalidades administrativas e controle de acesso por perfil.
- 🔔 **Notificações visuais:** alertas de novas mensagens e atualizações na interface.
- 📊 **Dashboards e auditoria:** visualização de indicadores para acompanhamento da operação.
- ⭐ **Avaliação do atendimento:** registro da satisfação do solicitante após o encerramento.

### 🛠️ Arquitetura do Sistema

<a id="arq"></a>

A arquitetura do **SyncDesk** separa a API, as interfaces web e mobile e a biblioteca compartilhada de integração. Essa organização permite desenvolver os componentes de forma independente e padronizar a comunicação entre as aplicações.

| Componente | Responsabilidade | Tecnologias principais |
| --- | --- | --- |
| [SyncDesk API](https://github.com/Titus-System/syncdesk-api) | Lógica de negócio, autenticação, triagem, chamados e persistência | Python, FastAPI, SQLAlchemy e JWT |
| [SyncDesk Web](https://github.com/Titus-System/syncdesk-web) | Interface dos atendentes e administradores | React, JavaScript, Vite, Tailwind CSS e React Query |
| [SyncDesk Mobile](https://github.com/Titus-System/syncdesk-mobile) | Aplicativo dos solicitantes | React Native, Expo e TypeScript |
| [SyncDesk Library](https://github.com/Titus-System/syncdesk-library) | Padronização da comunicação das interfaces com a API | TypeScript, Axios e WebSocket |

O **PostgreSQL** armazena dados estruturados, como usuários, chamados e permissões, enquanto o **MongoDB** é utilizado para mensagens e interações.

A comunicação em tempo real utiliza **WebSocket**, e a biblioteca compartilhada centraliza configurações e chamadas à API, reduzindo a duplicação da lógica de integração entre as interfaces.

<div align="center">
  <img
    src="https://raw.githubusercontent.com/Titus-System/SyncDesk/main/docs/diagramas/arquitetura.png"
    alt="Arquitetura do SyncDesk"
    width="850"
  />
</div>

### 🖥️ Demonstração

Confira a demonstração da **Sprint 1**, disponibilizada no repositório da equipe:

[▶️ Assistir à demonstração do SyncDesk](https://youtu.be/ucNTISGGgis)

## 💻 Tecnologias Utilizadas

### ⚙️ Back-end e Integração

<p align="left">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img alt="SQLAlchemy" src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
  <img alt="Axios" src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" />
  <img alt="WebSocket" src="https://img.shields.io/badge/WebSocket-333333?style=for-the-badge" />
</p>

### 🖥️ Front-end Web

<p align="left">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img alt="React Query" src="https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
</p>

### 📱 Mobile e Biblioteca Compartilhada

<p align="left">
  <img alt="React Native" src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="Expo" src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
</p>

### 🗄️ Banco de Dados

<p align="left">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
</p>

### 🛠️ Desenvolvimento, Qualidade e Design

<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="Pytest" src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img alt="ESLint" src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Atuei como **desenvolvedora front-end** no Dev Team da equipe **Titus Systems**, com foco no **SyncDesk Web**, aplicação destinada aos atendentes e administradores da plataforma. Minha participação abrangeu a estruturação inicial do projeto, o desenvolvimento das interfaces e a integração com os serviços do back-end.

Configurei o ambiente de desenvolvimento com **React, Vite, Tailwind CSS e ESLint** e participei da construção das telas de login, cadastro, chat e gerenciamento de chamados. Ao longo das entregas, aprimorei a organização dos componentes, das rotas e dos layouts, buscando manter a consistência visual e facilitar a manutenção da aplicação.

Na integração com o back-end, utilizei os **hooks da biblioteca SyncDesk**, configurei o token de acesso e adaptei os fluxos de usuários e chamados aos serviços disponíveis. Também contribuí para a implementação das operações de **criação, consulta, edição e exclusão de notas nos chamados**, além de aprimorar a interface de edição dos atendimentos.

Atuei na reestruturação das telas de edição de usuários e dos perfis de acesso, bem como na integração dos níveis de atendimento. Desenvolvi a estrutura da **página de relatórios**, ajustei seus filtros e participei da padronização dos componentes visuais do **design system**. Complementarmente, contribuí para a integração de notificações e para a inclusão de um modal de documentação com acesso ao GitHub.

Durante todo o desenvolvimento, utilizei **Git e GitHub** para versionar as alterações, integrar entregas entre branches e resolver conflitos, colaborando para a evolução conjunta da aplicação.

<h3>Hard Skills</h3>
<details>
  <summary><b>Clique para ver a lista de hard skills</b></summary>
  <br>
  <table align="center">
    <tr>
      <th width="300px">Tecnologia / Metodologia</th>
      <th width="100px">Nota</th>
      <th width="200px">Classificação</th>
    </tr>
    <tr>
      <td>React, JavaScript & Vite</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Tailwind CSS & Componentização de Interfaces</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Integração com APIs & React Query</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Autenticação & Gerenciamento de Tokens</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>WebSocket & Notificações em Tempo Real</td>
      <td>★★★☆☆</td>
      <td>Entendi</td>
    </tr>
    <tr>
      <td>HTML5 / CSS3 / Figma</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Git / GitHub / Scrum</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
  </table>
</details>

<h3>Soft Skills</h3>
<details>
  <summary><b>Clique para ver a lista de soft skills</b></summary>
  <br>
  <table align="center">
    <tr>
      <th width="300px">Habilidade</th>
      <th width="200px">Classificação</th>
    </tr>
    <tr>
      <td>Orientação ao Cliente (Pro4Tech)</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Adaptabilidade & Raciocínio Lógico</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Trabalho em Equipe</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Comunicação Assertiva</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Resolução de Problemas</td>
      <td>★★★★★</td>
    </tr>
  </table>
</details>
<br>

As atividades realizadas permitem destacar duas habilidades comportamentais relacionadas à minha participação:

- **Trabalho em equipe:** a integração da interface com a biblioteca compartilhada e os serviços exigiu atenção às alterações produzidas pelos demais integrantes. A resolução de conflitos e a manutenção dos fluxos de usuários e chamados fizeram parte desse trabalho conjunto.

- **Resolução de problemas:** os ajustes nos hooks, nos filtros de relatórios, nos níveis de atendimento e nos componentes visuais exigiram analisar o comportamento da aplicação e adequar as interfaces às necessidades do sistema.

## 📅 Metodologia e Sprints

O desenvolvimento seguiu o framework **Scrum**, com reuniões diárias, revisões e retrospectivas. O repositório registra **três sprints**, com as histórias de usuário marcadas como concluídas no backlog.

| Etapa | Data registrada | Escopo documentado |
| --- | --- | --- |
| Kick-off | 03/03/2026 | Início do projeto |
| Sprint 1 | 05/04/2026 | Chat entre solicitantes e atendentes, triagem inicial e gestão do ciclo de vida dos chamados |
| Sprint 2 | 03/05/2026 | Recursos administrativos, gestão de usuários, monitoramento e pesquisa no histórico de conversas |
| Sprint 3 | 31/05/2026 | Alertas visuais, dashboards, gráficos de auditoria e avaliação do atendimento |

O cronograma também registra a Feira de Soluções para **25/06/2026**. A realização dessa etapa não é confirmada pelo status apresentado no README da equipe.

---

[⬅️ Voltar para o Menu Principal](https://github.com/Madhs31/Portfolio_Projetos_ADS)
