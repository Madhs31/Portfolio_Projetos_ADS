
# 📈 AdaTrade | API 3º Semestre — FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/equipeAdalove/API-SEMESTRE3)

## 📌 Sobre o Projeto

O **AdaTrade** é uma plataforma web desenvolvida durante o terceiro semestre de Análise e Desenvolvimento de Sistemas (ADS) da FATEC São José dos Campos, com o objetivo de organizar, analisar e apresentar dados de importação e exportação dos estados brasileiros.

A solução transforma bases públicas de comércio exterior em indicadores, filtros, gráficos e visualizações geográficas, permitindo explorar informações econômicas por região e período.

O projeto também proporcionou a oportunidade de aplicar conhecimentos de desenvolvimento de software, integração de sistemas e visualização de dados em um problema real, envolvendo a organização e a interpretação de informações econômicas.

## 🏢 Parceiro de Negócios (Cliente)

O projeto foi desenvolvido em parceria com a **FATEC São José dos Campos — Professor Jessen Vidal**, tendo como cliente e responsável pelo levantamento dos requisitos o professor **Marcus Nascimento, coordenador do curso de Logística da instituição**.

O desafio consistiu em organizar grandes volumes de dados de comércio exterior e apresentá-los de forma acessível em uma aplicação web, permitindo que estudantes, professores e demais interessados consultassem indicadores relacionados às operações comerciais dos estados brasileiros.

A proposta buscou integrar conhecimentos de tecnologia e logística, utilizando recursos computacionais para facilitar a análise e a interpretação dos dados.

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

A aplicação foi estruturada como uma Single Page Application (SPA), com front-end desenvolvido em React e TypeScript, separado da API REST construída com Node.js e NestJS.

O Prisma ORM auxilia no acesso aos dados armazenados no PostgreSQL, enquanto Python é utilizado no tratamento, na limpeza e na organização das bases de comércio exterior.

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

Para isso, trabalhei na associação das informações econômicas aos elementos geográficos, na organização do estado da interface e na atualização dos dados conforme a interação dos usuários.

Também colaborei com a organização das rotas NestJS que alimentavam o mapa e com os contratos de dados consumidos pelo front-end.

Essas atividades exigiram compreender o funcionamento das diferentes camadas da aplicação, garantindo que os dados processados e disponibilizados pelo back-end fossem apresentados corretamente na interface.

### 🎯 Principais Entregas

- Construção dos componentes de visualização geográfica;
- Implementação da seleção dos estados e atualização dos dados;
- Integração do mapa com os serviços da API;
- Colaboração na organização das rotas em NestJS;
- Tipagem dos dados e organização dos componentes em React;
- Estilização e responsividade da interface;
- Versionamento das alterações e acompanhamento das entregas no Jira.

### Hard Skills

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
  
### Soft Skills

  <br>
  <table align="center">
    <tr><th>Habilidade</th><th>Autoavaliação</th></tr>
    <tr><td>Visão Sistêmica</td><td>★★★★☆</td></tr>
    <tr><td>Adaptabilidade</td><td>★★★★★</td></tr>
    <tr><td>Trabalho em Equipe</td><td>★★★★★</td></tr>
    <tr><td>Comunicação Assertiva</td><td>★★★★☆</td></tr>
    <tr><td>Organização e Planejamento</td><td>★★★★☆</td></tr>
  </table>

Exemplos de aplicação durante o projeto:

- **Visão sistêmica:** para implementar o mapa, precisei compreender o fluxo de informações entre a API e os componentes da interface.
- **Adaptabilidade:** a utilização de React, TypeScript e NestJS exigiu aprender novos conceitos de componentização e integração.
- **Trabalho em equipe:** a integração do mapa com os serviços desenvolvidos pelos demais integrantes exigiu colaboração e alinhamento técnico.
- **Comunicação técnica:** a integração do mapa demandou alinhamento dos contratos da API, enquanto a apresentação do projeto no PyDay São José dos Campos permitiu exercitar a exposição dos resultados para a comunidade de tecnologia.

## 🐍 Apresentação no PyDay São José dos Campos

Além das atividades acadêmicas, tive a oportunidade de participar da **apresentação do projeto AdaTrade no PyDay São José dos Campos**, evento local da comunidade Python, voltado ao compartilhamento de conhecimentos, experiências e aplicações da tecnologia.

Durante a apresentação, o projeto foi compartilhado com a comunidade de tecnologia, demonstrando sua proposta de análise e visualização de dados de comércio exterior, bem como as funcionalidades desenvolvidas pela equipe.

A experiência possibilitou divulgar os resultados obtidos durante o terceiro semestre e demonstrar a aplicação prática dos conhecimentos adquiridos ao longo da graduação.

A participação no evento contribuiu especialmente para o desenvolvimento das seguintes competências:

- **Comunicação técnica:** apresentação das funcionalidades, dos objetivos e das tecnologias utilizadas no projeto.
- **Capacidade de apresentação:** organização das informações para explicar a solução de maneira clara.
- **Compartilhamento de conhecimentos:** divulgação dos resultados de um projeto acadêmico para pessoas da comunidade de tecnologia.
- **Desenvolvimento profissional:** ampliação das experiências relacionadas à apresentação de soluções computacionais fora do ambiente de sala de aula.

A apresentação representou uma oportunidade de conectar a formação acadêmica à comunidade de tecnologia, reforçando a importância de compartilhar conhecimentos e demonstrar os resultados do desenvolvimento de software.

## 📅 Metodologia e Sprints

O desenvolvimento seguiu a metodologia ágil Scrum, com três sprints concluídas, conforme o backlog oficial da equipe.

| Sprint | Foco das entregas |
|---|---|
| Sprint 1 | Limpeza e normalização das bases no Google Colab, documentação dos dados, persistência e integração inicial entre front-end e back-end. |
| Sprint 2 | Consultas por estado, estruturação da API, pesquisa por NCM e painel de modais de transporte. |
| Sprint 3 | Filtros históricos, exportação de dados, mapa interativo e disponibilização da aplicação em nuvem. |

[Consultar documentação, backlogs e demonstrações da equipe](https://github.com/equipeAdalove/API-SEMESTRE3)

## 📚 Aprendizados

O AdaTrade possibilitou aprofundar meus conhecimentos em visualização geográfica, React, TypeScript e integração de APIs REST.

A implementação do mapa interativo demonstrou a importância da consistência dos dados, do gerenciamento de estado e da compreensão do fluxo completo da aplicação, desde o processamento das informações até sua apresentação ao usuário.

O desenvolvimento também contribuiu para fortalecer minha visão sistêmica, minha capacidade de resolver problemas técnicos e minha adaptação a novas ferramentas e tecnologias.

Além disso, a **apresentação do AdaTrade no PyDay São José dos Campos** representou uma experiência importante para minha formação acadêmica e profissional.

A oportunidade de compartilhar os resultados do projeto com a comunidade de tecnologia permitiu desenvolver competências relacionadas à comunicação técnica, à organização de apresentações e à divulgação de soluções computacionais.

Dessa forma, o terceiro semestre contribuiu não apenas para meu aprimoramento técnico, mas também para o desenvolvimento da confiança e da capacidade de apresentar projetos, explicando suas funcionalidades, seus objetivos e os desafios enfrentados durante sua construção.

---

[⬅️ Voltar para o Menu Principal](../README.md)
