
# 📦 AdaTech | API 4º Semestre — FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/equipeAdalove/API-SEMESTRE4)

> 🎓 **Projeto de destaque do meu Trabalho de Graduação II (TG2).**

## 📌 Sobre o Projeto

O **AdaTech** é uma aplicação web desenvolvida durante o quarto semestre de ADS para apoiar a automação da elaboração da instrução de registro aduaneiro.

O sistema permite enviar pedidos de compra em PDF, extrair Part-Numbers e utilizar inteligência artificial para sugerir códigos da Nomenclatura Comum do Mercosul (NCM) e descrições de produtos. Os resultados são disponibilizados para conferência e correção antes da geração de uma planilha Excel.

O objetivo é reduzir o esforço manual na organização das informações aduaneiras. As sugestões da IA não substituem a revisão humana nem garantem, por si só, conformidade fiscal.

## 🏢 Parceiro de Negócios (Cliente)

O desafio foi proposto pela **TecSys**, representada por **Creonice Honório**, empresa que atua com soluções de gestão logística e processos aduaneiros.

A demanda envolveu facilitar a identificação e organização de dados como Part-Number, NCM, descrição, fabricante, origem e endereço do fabricante, incorporando automação e inteligência artificial ao fluxo de trabalho.

## 🚀 Funcionalidades e Demonstração

- 📄 **Upload de documentos:** envio de pedidos de compra em PDF.
- 🔎 **Extração de Part-Numbers:** identificação dos códigos presentes nos documentos.
- 🤖 **Sugestões com IA:** apoio à identificação de NCMs e elaboração de descrições de produtos.
- 🌐 **Enriquecimento de informações:** recuperação de contexto complementar para o processamento.
- ✏️ **Revisão e correção:** conferência e edição dos dados pelo usuário.
- 📊 **Exportação para Excel:** geração das planilhas com os resultados.
- 🔐 **Autenticação:** acesso à aplicação mediante identificação do usuário.
- 🗂️ **Histórico:** consulta aos documentos anteriormente processados.

### 🛠️ Arquitetura do Sistema

<a id="arq"></a>

O AdaTech separa a interface web, os serviços de processamento, a persistência e a integração com inteligência artificial.

| Componente | Responsabilidade | Tecnologias |
|---|---|---|
| Front-end | Autenticação, envio de documentos, apresentação e revisão das informações. | React, TypeScript, Vite |
| Back-end | Processamento dos documentos, regras de negócio e disponibilização dos serviços. | Python, FastAPI |
| Inteligência artificial | Apoio à extração e geração de sugestões. | Ollama, RAG |
| Recuperação de contexto | Complementação das informações utilizadas no processamento. | DuckDuckGo |
| Persistência | Armazenamento dos registros e histórico. | PostgreSQL |

O fluxo de trabalho pode ser resumido em: envio do PDF → extração de Part-Numbers → recuperação de informações e geração de sugestões → revisão humana → exportação para Excel.

A abordagem de recuperação de informações e geração assistida (RAG, *Retrieval-Augmented Generation*) permite complementar o contexto dos modelos. A interface apresenta os resultados para conferência; a classificação sugerida não equivale a uma aprovação fiscal.

[🔗 Consultar a Wiki da equipe](https://github.com/equipeAdalove/API-SEMESTRE4/wiki)

### 🖥️ Demonstração

Confira a demonstração da versão final (Sprint III):

https://github.com/user-attachments/assets/382b0799-d370-4754-acb5-068a4deda1cc

## 💻 Tecnologias Utilizadas

Tecnologias e ferramentas utilizadas pela equipe na construção do projeto. Minha atuação individual é detalhada na seção de contribuições pessoais.

### ⚙️ Back-end e IA

<p align="left">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img alt="DuckDuckGo" src="https://img.shields.io/badge/DuckDuckGo-DE5833?style=for-the-badge&logo=duckduckgo&logoColor=white" />
  <img alt="RAG" src="https://img.shields.io/badge/RAG-7C3AED?style=for-the-badge" />
</p>

### 🖥️ Front-end e Build

<p align="left">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🗄️ Banco de Dados

<p align="left">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

### 🛠️ Gestão, Comunicação e Design

<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
  <img alt="Slack" src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Atuei como **desenvolvedora front-end**, com foco na estruturação, componentização e responsividade da interface web. Minha atuação concentrou-se na construção das interfaces e na integração dos dados retornados pela API com o fluxo de processamento de documentos aduaneiros.

Desenvolvi componentes com React e TypeScript, formulários de entrada e interfaces destinadas à apresentação dos resultados produzidos pelos serviços de inteligência artificial. Utilizei os contratos disponibilizados pela API FastAPI para organizar as informações consumidas pela interface e tratar os diferentes estados do processamento.

A tipagem estática auxiliou na identificação de incompatibilidades durante o desenvolvimento, enquanto HTML, CSS e os protótipos do Figma contribuíram para a organização visual e a responsividade. A comunicação com os desenvolvedores do back-end foi importante para o alinhamento dos dados e das funcionalidades.

### 🎯 Principais Entregas

- Estruturação de componentes React com TypeScript;
- Construção de formulários de entrada de informações;
- Desenvolvimento das interfaces de apresentação dos resultados de processamento;
- Organização visual das informações relacionadas aos produtos;
- Integração com a API FastAPI e utilização dos contratos de dados;
- Ajustes de responsividade e consistência visual;
- Alinhamento de integração com o back-end, acompanhamento no Jira e comunicação pelo Slack;
- Versionamento das alterações com Git e GitHub.

### Hard Skills

<details>
  <summary><b>Clique para ver a lista de hard skills</b></summary>

  <br>
  <table align="center">
    <tr><th>Tecnologia / Metodologia</th><th>Nota</th><th>Classificação</th></tr>
    <tr><td>Python e FastAPI</td><td>★★★★★</td><td>Sei fazer com autonomia</td></tr>
    <tr><td>Integração de IA e busca (Ollama / DuckDuckGo)</td><td>★★★☆☆</td><td>Entendi</td></tr>
    <tr><td>React, TypeScript e Vite</td><td>★★★★★</td><td>Sei fazer com autonomia</td></tr>
    <tr><td>Modelagem relacional (PostgreSQL)</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>Ecossistema Node.js</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>HTML5 / CSS3 / Figma</td><td>★★★★★</td><td>Sei fazer com autonomia</td></tr>
    <tr><td>Git / Jira / Slack</td><td>★★★★★</td><td>Sei fazer com autonomia</td></tr>
  </table>
</details>

### Soft Skills

<details>
  <summary><b>Clique para ver a lista de soft skills</b></summary>

  <br>
  <table align="center">
    <tr><th>Habilidade</th><th>Autoavaliação</th></tr>
    <tr><td>Orientação ao Cliente (TecSys)</td><td>★★★★★</td></tr>
    <tr><td>Visão Arquitetural e Raciocínio Lógico</td><td>★★★★★</td></tr>
    <tr><td>Trabalho em Equipe</td><td>★★★★★</td></tr>
    <tr><td>Comunicação Assertiva</td><td>★★★★★</td></tr>
    <tr><td>Resolução de Problemas</td><td>★★★★★</td></tr>
  </table>
</details>

Exemplos de aplicação durante o projeto:

- **Orientação ao cliente:** organizei interfaces e formulários considerando o fluxo de conferência das informações aduaneiras.
- **Visão arquitetural e raciocínio lógico:** a integração com a API exigiu compreender os formatos de dados e os estados do processamento.
- **Comunicação técnica:** o alinhamento dos contratos com os responsáveis pelo back-end foi necessário para integrar as funcionalidades.

## 📅 Metodologia e Sprints

O desenvolvimento seguiu Scrum, com acompanhamento no Jira e comunicação pelo Slack. O repositório oficial registra **três sprints concluídas**:

| Sprint | Período | Principais entregas | Status |
|---|---|---|---|
| Sprint 1 | 08/09 a 28/09/2025 | Upload de PDF, extração de Part-Numbers, sugestões de NCM e descrições e exportação Excel. | ✅ Concluída |
| Sprint 2 | 06/10 a 26/10/2025 | Formulários de revisão das informações e autenticação. | ✅ Concluída |
| Sprint 3 | 03/11 a 23/11/2025 | Histórico de documentos e documentação de instalação e utilização. | ✅ Concluída |

[Consultar o cronograma e os relatórios oficiais](https://github.com/equipeAdalove/API-SEMESTRE4)

## 📚 Aprendizados

O AdaTech aprofundou meus conhecimentos em React, TypeScript, organização de componentes e integração de APIs. O desafio de transformar informações aduaneiras em interfaces compreensíveis ampliou minha compreensão sobre regras de negócio e experiência do usuário. Também aprendi que sistemas com IA devem considerar as limitações das sugestões geradas e a necessidade de conferência humana.

---

[⬅️ Voltar para o Menu Principal](../README.md)
