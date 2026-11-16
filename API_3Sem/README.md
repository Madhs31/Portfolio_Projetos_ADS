
# 📈 AdaTrade | API 3º Semestre — FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/equipeAdalove/API-SEMESTRE3)

## 📌 Sobre o Projeto

O **AdaTrade** é uma plataforma web desenvolvida durante o terceiro semestre de ADS para organizar e apresentar dados de importação e exportação dos estados brasileiros.

A solução transforma bases de comércio exterior em indicadores, filtros, gráficos e visualizações geográficas, permitindo explorar informações econômicas por região e período.

## 🏢 Parceiro de Negócios (Cliente)

O projeto foi desenvolvido em parceria com a FATEC São José dos Campos, tendo como cliente o professor **Marcus Nascimento**, do curso de Logística da FATEC. O desafio consistiu em organizar grandes volumes de dados de comércio exterior e apresentá-los de forma acessível em uma aplicação web.

## 🚀 Funcionalidades e Demonstração

- 📊 **Dashboards:** apresentação dos dados de importação e exportação.
- 🔍 **Filtros:** consulta das informações por unidade federativa, período (2014–2024), setor econômico e classificação NCM.
- 📈 **Balança comercial:** comparação de resultados de importação e exportação.
- 🗺️ **Mapa interativo:** seleção dos estados brasileiros e visualização dos dados associados.
- 📦 **Indicadores:** exploração de informações como valor financeiro e peso líquido.
- 🚚 **Modais de transporte:** visualização das exportações por meio de transporte.
- 📥 **Exportação de dados:** disponibilização de informações para análises externas.

### 🛠️ Arquitetura do Sistema

<a id="arq"></a>

A aplicação foi estruturada como uma Single Page Application (SPA) com front-end React e TypeScript, separado da API REST desenvolvida com Node.js e NestJS. O Prisma ORM auxilia no acesso aos dados do PostgreSQL, enquanto Python é utilizado no tratamento das bases de comércio exterior.

| Camada | Responsabilidade |
|---|---|
| Preparação de dados | Tratamento e organização das bases em Python. |
| Persistência | Armazenamento em PostgreSQL. |
| API REST | Consultas e disponibilização de dados com NestJS e Prisma. |
| Front-end | Indicadores, gráficos, filtros e mapa interativo com React. |

[🔗 Consultar documentação técnica e manual do usuário](https://github.com/equipeAdalove/API-SEMESTRE3/tree/Sprint-3/Documenta%C3%A7%C3%A3o)

### 🖥️ Demonstração

Confira a demonstração da versão final (Sprint III):

https://github.com/user-attachments/assets/5b22543a-625d-454c-a67b-ff6f0971a1fb

## 💻 Tecnologias Utilizadas

Tecnologias e ferramentas utilizadas pela equipe na construção do projeto. Minha atuação individual é detalhada na seção de contribuições pessoais.

### ⚙️ Back-end e ORM

<p align="left">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
</p>

### 🔬 Ciência de Dados e Processamento

<p align="left">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="Google Colab" src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
</p>

### 🖥️ Front-end e Build

<p align="left">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🗄️ Banco de Dados

<p align="left">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

### 🛠️ Metodologia, Design e IDE

<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img alt="VS Code" src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Atuei como **desenvolvedora full-stack**, sendo a principal responsável pela camada de visualização geográfica e pela integração dos componentes relacionados ao mapa interativo.

Minha principal contribuição foi a concepção e implementação do **mapa interativo dos estados brasileiros** com React e TypeScript. A funcionalidade permite selecionar uma unidade federativa e consultar os dados de comércio exterior associados à região.

Para isso, trabalhei na associação das informações econômicas aos elementos geográficos, na organização do estado da interface e na atualização dos dados conforme a interação dos usuários. Também colaborei com a organização das rotas NestJS que alimentavam o mapa e com os contratos de dados consumidos pelo front-end.

### 🎯 Principais Entregas

- Construção dos componentes de visualização geográfica;
- Implementação da seleção dos estados e atualização dos dados;
- Integração do mapa com os serviços da API;
- Colaboração na organização das rotas em NestJS;
- Tipagem dos dados e organização dos componentes em React;
- Estilização e responsividade da interface;
- Versionamento das alterações e acompanhamento das entregas no Jira.

### Hard Skills

<details>
  <summary><b>Clique para ver a lista de hard skills</b></summary>

  <br>
  <table align="center">
    <tr><th>Tecnologia / Metodologia</th><th>Nota</th><th>Classificação</th></tr>
    <tr><td>Node.js e NestJS (API REST)</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>Modelagem ORM</td><td>★★★☆☆</td><td>Entendi</td></tr>
    <tr><td>Python e preparação de dados</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>React e Vite</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>TypeScript</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>HTML5 / CSS3</td><td>★★★★★</td><td>Sei fazer com autonomia</td></tr>
    <tr><td>UI Design e Prototipação</td><td>★★★★★</td><td>Sei fazer com autonomia</td></tr>
    <tr><td>Git / Metodologia Ágil</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
  </table>
</details>

### Soft Skills

<details>
  <summary><b>Clique para ver a lista de soft skills</b></summary>

  <br>
  <table align="center">
    <tr><th>Habilidade</th><th>Autoavaliação</th></tr>
    <tr><td>Visão Sistêmica</td><td>★★★★☆</td></tr>
    <tr><td>Adaptabilidade</td><td>★★★★★</td></tr>
    <tr><td>Trabalho em Equipe</td><td>★★★★★</td></tr>
    <tr><td>Comunicação Assertiva</td><td>★★★★☆</td></tr>
    <tr><td>Organização e Planejamento</td><td>★★★★☆</td></tr>
  </table>
</details>

Exemplos de aplicação durante o projeto:

- **Visão sistêmica:** para implementar o mapa, precisei compreender o fluxo de informações entre a API e os componentes da interface.
- **Adaptabilidade:** a utilização de React, TypeScript e NestJS exigiu aprender novos conceitos de componentização e integração.
- **Comunicação técnica:** a integração do mapa demandou alinhamento dos contratos da API e a apresentação no PyDay permitiu exercitar a exposição dos resultados.

## 📅 Metodologia e Sprints

O desenvolvimento seguiu Scrum, com três sprints concluídas, conforme o backlog oficial da equipe.

| Sprint | Foco das entregas |
|---|---|
| Sprint 1 | Limpeza e normalização das bases no Google Colab, documentação dos dados, persistência e integração inicial entre front-end e back-end. |
| Sprint 2 | Consultas por estado, estruturação da API, pesquisa por NCM e painel de modais de transporte. |
| Sprint 3 | Filtros históricos, exportação de dados, mapa interativo e disponibilização da aplicação em nuvem. |

[Consultar documentação, backlogs e demonstrações da equipe](https://github.com/equipeAdalove/API-SEMESTRE3)

## 📚 Aprendizados

O AdaTrade possibilitou aprofundar meus conhecimentos em visualização geográfica, React, TypeScript e integração de APIs. A implementação do mapa mostrou a importância da consistência dos dados, do gerenciamento de estado e da compreensão do fluxo completo da aplicação. Também desenvolvi minha visão sistêmica e comunicação técnica, especialmente com a apresentação no PyDay.

---

[⬅️ Voltar para o Menu Principal](../README.md)
