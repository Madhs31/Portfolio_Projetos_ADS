# 📦 AdaTech | API 4º Semestre - FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/equipeAdalove/API-SEMESTRE4)

## 📌 Sobre o Projeto

O **AdaTech** é uma aplicação corporativa desenvolvida com base na metodologia **API (Aprendizagem por Projetos Integrados)** durante o 4º semestre do curso de Análise e Desenvolvimento de Sistemas da **FATEC São José dos Campos - Prof. Jessen Vidal**.

O principal objetivo do software é **automatizar e auditar a criação da instrução de registro aduaneiro**, garantindo que todo o processo logístico seja executado de maneira ágil, segura e estritamente alinhada à legislação alfandegária vigente. Integrando Inteligência Artificial e enriquecimento de dados automatizado, o sistema simplifica fluxos de trabalho complexos, valida códigos fiscais (NCM) previamente e gera instruções precisas para mitigar erros documentais que causam multas severas no despacho aduaneiro.

## 🏢 Parceiro de Negócios (Cliente)

O projeto foi desenvolvido para atender a um desafio real proposto pela **TecSys**, parceira acadêmica deste semestre especializada em soluções de gestão logística e processos aduaneiros. A solução foi desenhada para otimizar a esteira operacional da empresa, incorporando automação inteligente para reduzir a sobrecarga manual na classificação de produtos e garantir conformidade fiscal nas operações de comércio exterior.

## 🚀 Funcionalidades e Demonstração

* 📄 **Geração Automatizada de Instruções:** Emissão padronizada de guias e instruções para o despacho alfandegário com base no escopo da carga.
* 🤖 **Validação por IA & Web Search:** Uso de LLMs locais (Ollama) integrados à busca (DuckDuckGo) para validação semântica e auditoria de NCMs.
* ⚖️ **Motor Fiscal:** Checagem contínua de regras tributárias e exigências alfandegárias para mitigar falhas humanas.
* 🔄 **Gestão de Fluxo (Workflow):** Acompanhamento de status das instruções logísticas, desde a entrada da carga até a aprovação final.

### 🛠️ Arquitetura do Sistema 
<a id="arq"></a>
<div>
A arquitetura do <b>AdaTech</b> foi projetada para suportar alta concorrência e integrações complexas. O sistema adota um padrão de microsserviços desacoplados, onde a API de alta performance em <b>FastAPI</b> orquestra a lógica fiscal e o processamento de IA, enquanto serviços secundários em <b>Node.js</b> suportam o ecossistema, persistindo dados relacionais criticamente estruturados no <b>PostgreSQL</b>.

[🔗 Leia mais sobre a arquitetura do software na Wiki!](https://github.com/equipeAdalove/API-SEMESTRE4/wiki) 
</div>

Confira a demonstração completa das funcionalidades entregues na versão final (Sprint IV):

* 🖥️ **Demonstração:**

<div align="center">
  <video src="https://github.com/user-attachments/assets/382b0799-d370-4754-acb5-068a4deda1cc" width="650" controls>
  </video>
</div>

## 💻 Tecnologias Utilizadas

A plataforma integra tecnologias modernas de desenvolvimento web, automação e inteligência artificial:

### ⚙️ Back-end & IA
<p align="left">
  <img alt="Python" src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" />
  <img alt="Node.js" src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
  <img alt="Ollama" src="https://img.shields.io/badge/-Ollama-0D1117?style=for-the-badge&logo=ollama&logoColor=white" />
  <img alt="DuckDuckGo" src="https://img.shields.io/badge/duckduckgo-de5833?style=for-the-badge&logo=duckduckgo&logoColor=white" />
</p>

### 🖥️ Front-end & Build
<p align="left">
  <img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🗄️ Banco de Dados
<p align="left">
  <img alt="Postgres" src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

### 🛠️ Gestão, Comunicação & Design
<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="Jira" src="https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white" />
  <img alt="Slack" src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Atuei como desenvolvedora Front-end na equipe Adalove, assumindo a responsabilidade direta pela estruturação, componentização e responsividade da interface corporativa da aplicação.

Minha atuação foi centralizada na construção de painéis robustos para o gerenciamento da esteira logística utilizando **React** e **TypeScript**. A tipagem estática do TypeScript foi fundamental para mapear com segurança os contratos de dados complexos retornados pela API (desenvolvida em Python/FastAPI), garantindo que a interface manipulasse as regras aduaneiras e os status das cargas sem erros em tempo de execução.

Implementei fluxos visuais limpos e intuitivos com HTML5 e **CSS3** (baseados nos protótipos do **Figma**), focando na usabilidade dos operadores da TecSys. Desenvolvi os formulários de entrada de dados e as telas que exibem os resultados da validação semântica gerada pela Inteligência Artificial local (Ollama/DuckDuckGo), permitindo que o usuário visualize de forma clara as inconsistências fiscais ou a aprovação das descrições de NCMs. A agilidade no ciclo de desenvolvimento e recarga da interface foi impulsionada pelo uso do empacotador **Vite**.

No escopo operacional e de equipe, realizei o versionamento contínuo dos componentes visuais via **Git**, utilizando o **Slack** para alinhar os contratos de integração diretamente com os desenvolvedores do Back-end e o **Jira** para o acompanhamento ágil das entregas sob a metodologia Scrum.

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
      <td>Python & FastAPI (APIs de Alta Performance)</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Integração de IA & Search (Ollama / DuckDuckGo)</td>
      <td>★★★☆☆</td>
      <td>Entendi</td>
    </tr>
    <tr>
      <td>React, TypeScript & Vite</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Modelagem Transacional (PostgreSQL)</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Ecossistema Node.js</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>HTML5 / CSS3 / Figma</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Git / Jira / Slack (Orquestração Corporativa)</td>
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
      <td>Orientação ao Cliente (TecSys)</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Visão Arquitetural & Raciocínio Lógico</td>
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
      <td>Resolução de Problemas Complexos</td>
      <td>★★★★★</td>
    </tr>
  </table>
</details>
<br>

As duas habilidades comportamentais (Soft Skills) mais significativas para mim durante este projeto foram:

* **Orientação ao Cliente (TecSys):** Por se tratar de um desafio real de mercado proposto pela TecSys, essa habilidade foi a chave para o desenvolvimento das interfaces. Foi necessário entender a fundo as necessidades dos operadores aduaneiros e estruturar fluxos visuais limpos e intuitivos, garantindo que os resultados gerados pelas auditorias de IA fossem exibidos de forma clara para mitigar erros em tempo real.
* **Visão Arquitetural & Raciocínio Lógico:** Essencial para atuar com maestria no Front-end de um ecossistema baseado em microsserviços. Precisei aplicar um forte raciocínio lógico para traduzir os contratos complexos e múltiplos status retornados pela API em FastAPI, integrando esses dados de ponta a ponta no ecossistema de componentes em React e TypeScript com total segurança em tempo de execução.

<br>

## 📅 Metodologia e Sprints

O desenvolvimento baseou-se no framework **Scrum**, orquestrado via Jira e Slack, dividindo a complexidade do projeto corporativo em 4 Sprints focadas na agregação de valor contínua para a TecSys:

* **Sprint 1:** Imersão no domínio de regras aduaneiras da TecSys, levantamento de requisitos, elaboração do Product Backlog e design das telas logísticas no Figma.
* **Sprint 2:** Modelagem relacional no PostgreSQL, setup do ambiente de microsserviços (FastAPI/Node.js) e criação do módulo de entrada de dados das cargas.
* **Sprint 3:** Integração da esteira de validação por IA (Ollama + DuckDuckGo) com os formulários do Front-end em React/TypeScript.
* **Sprint 4:** Geração automatizada da instrução de registro aduaneiro, testes rigorosos de consistência no fluxo de status, gravação das demonstrações e homologação final com a TecSys.

---
[⬅️ Voltar para o Menu Principal](https://github.com/Madhs31/Portfolio_Projetos_ADS)
