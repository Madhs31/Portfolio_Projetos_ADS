# 📈 AdaTrade | API 3º Semestre - FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/equipeAdalove/API-SEMESTRE3)

## 📌 Sobre o Projeto

O **AdaTrade** é uma Plataforma Web desenvolvida com base na metodologia de **API (Aprendizagem por Projetos Integrados)** durante o 3º semestre do curso de Análise e Desenvolvimento de Sistemas da **FATEC São José dos Campos - Prof. Jessen Vidal**.

O objetivo da aplicação é realizar o acompanhamento, filtragem e exibição de dados estratégicos de **importação e exportação dos estados brasileiros**. A plataforma transforma bases de dados brutas e complexas do comércio exterior em painéis visuais e relatórios dinâmicos, permitindo análises econômicas claras sobre a balança comercial, principais parceiros internacionais, rotas logísticas e categorias de produtos mais movimentadas por região.

## 🏢 Parceiro de Negócios (Cliente)

O projeto foi desenvolvido em parceria com a FATEC São José dos Campos, tendo como responsável pelos requisitos o professor Marcus Nascimento. A proposta foi conduzida em ambiente acadêmico, simulando um cenário real de mercado com foco na análise de dados massivos de comércio exterior e no desenvolvimento de uma plataforma web de alta performance para o apoio à tomada de decisão estratégica.

## 🚀 Funcionalidades e Demonstração

* 📊 **Dashboards Interativos:** Visualização gráfica do volume de importações e exportações por estado e período.
* 🔍 **Filtros Avançados:** Segmentação de dados por unidades federativas (UF), NCM (Nomenclatura Comum do Mercosul), valores financeiros e peso líquido.
* 📈 **Análise de Balança Comercial:** Comparativos automáticos para identificar superávits ou déficits comerciais regionais.
* 🗺️ **Mapeamento de Dados:** Relatórios consolidados que facilitam a extração de inteligência de mercado para tomadores de decisão.
  
### 🛠️ Arquitetura do Sistema 
<a id="arq"></a>
<div>
A arquitetura do <b>AdaTrade</b> precisou contornar o desafio de processar e exibir milhares de registros históricos alfandegários sem comprometer o tempo de carregamento da interface no navegador do usuário. <br>
O sistema foi estruturado no modelo de Single Page Application (SPA), separando completamente a camada de apresentação visual (Front-end) da camada de agregação e processamento de dados (API RESTful no Back-end).

[🔗 Leia mais sobre a arquitetura do software na Wiki!](https://github.com/equipeAdalove/API-SEMESTRE3/wiki) 
</div>

### 🎨 Protótipo Figma
<a id="prototipo"></a>
<div align="center">
  <table>
    <tr>
      <th><img src="/assets/img/Final - Dashboard (Light) (1).png" alt="Dashboard (Light)"></th>
      <th><img src="/assets/img/Final - Mapa(Light).png" alt="Mapa(Light)"></th>
      <th><img src="/assets/img/Final - NCM (Light).png" alt="NCM (Light)"></th>
    </tr>
    <tr>
      <td><img src="/assets/img/Final - Dashboard (Dark) (1).png" alt="Dashboard (Dark)"></td>
      <td><img src="/assets/img/Final - Mapa(Dark).png" alt="Mapa(Dark)"></td>
      <td><img src="/assets/img/Final - NCM (Dark).png" alt="NCM (Dark)"></td>
    </tr>
  </table>
</div>

Confira o vídeo de demonstração da versão final (Sprint IV):
* 🖥️ **Demonstração:** <div align="center">
  <video src="https://github.com/user-attachments/assets/5b22543a-625d-454c-a67b-ff6f0971a1fb" width="600" controls>
  </video>
</div>

## 💻 Tecnologias Utilizadas

Para suportar o processamento de dados e entregar uma experiência de usuário fluida, o projeto foi dividido em arquitetura moderna de microsserviços/APIs desacopladas:

### ⚙️ Back-end & ORM
<p align="left">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
</p>

### 🔬 Ciência de Dados & Processamento
<p align="left">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="Google Colab" src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
</p>

### 🖥️ Front-end & Build
<p align="left">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🗄️ Banco de Dados
<p align="left">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

### 🛠️ Metodologia, Design & IDE
<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="VS Code" src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Atuei como desenvolvedora full-stack na equipe Adalove, sendo a principal responsável pela **camada de visualização geográfica e pela integração técnica** entre os ecossistemas de Front-end e Back-end.

Minha maior contribuição foi a **concepção e implementação do mapa interativo** da plataforma. Utilizando **React** e **TypeScript**, desenvolvi a lógica de visualização espacial que permite ao usuário clicar nos estados brasileiros e visualizar, de forma instantânea, os dados de balança comercial filtrados. Para que isso fosse possível, atuei diretamente na **integração da aplicação**, mapeando os contratos de API no **NestJS** e garantindo que o estado do Front-end reagisse corretamente aos dados providos pelo **Prisma ORM**.

Além da parte geo, estruturei componentes essenciais da interface utilizando **Vite** para otimização do build, focando em uma experiência de usuário (UX) fluida e responsiva com HTML e **CSS**. No Back-end, colaborei na organização das rotas que alimentavam o mapa, assegurando que o fluxo de dados fosse tipado e seguro de ponta a ponta.

No gerenciamento do projeto, utilizei o **Git** para controle de versão e o **Jira** para garantir que as entregas de integração estivessem alinhadas com o cronograma das Sprints.

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
      <td>Node.js & NestJS (API REST)</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Modelagem ORM</td>
      <td>★★★☆☆</td>
      <td>Entendi</td>
    </tr>
    <tr>
      <td>Python & Data Prep</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>React & Vite</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>TypeScript</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>HTML5 / CSS3</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>UI Design & Prototipação</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Git / Metodologia Ágil</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
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
      <td>Visão Sistêmica</td>
      <td>★★★★☆</td>
    </tr>
    <tr>
      <td>Adaptabilidade</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Trabalho em Equipe</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Comunicação Assertiva</td>
      <td>★★★★☆</td>
    </tr>
    <tr>
      <td>Organização e Planejamento</td>
      <td>★★★★☆</td>
    </tr>
  </table>
</details>
<br>

As duas habilidades comportamentais (Soft Skills) mais significativas para mim durante este projeto foram:

* **Visão Sistêmica:** Fundamental para o meu papel de integração Full-Stack. Para fazer o mapa interativo funcionar, precisei compreender o fluxo completo da aplicação, desde como os dados eram estruturados e expostos pela API no NestJS até como o Front-end em React consumia e gerenciava o estado dessas informações para exibi-las visualmente ao usuário.
* **Adaptabilidade:** A transição para uma stack robusta baseada em TypeScript, Node.js e React exigiu um aprendizado contínuo. Tive que me adaptar rapidamente à tipagem estática e à lógica de componentização do React para garantir a entrega e a performance da visualização geográfica dentro do prazo das Sprints.

<br>

## 📅 Metodologia e Sprints

O projeto foi gerenciado e entregue seguindo o framework **Scrum**, estruturado em 4 Sprints focadas na agregação contínua de valor ao produto:

* **Sprint 1:** Tratamento inicial das bases de dados abertas de comércio exterior, prototipação das interfaces de dashboards no Figma e montagem do esqueleto da API.
* **Sprint 2:** Implementação do Front-end em TypeScript/React, criação dos componentes visuais e desenvolvimento dos endpoints de consulta no Back-end.
* **Sprint 3:** Integração completa entre Front-end e Back-end, aplicação dos filtros combinados por Estado/Produto e renderização dos gráficos de importação/exportação.
* **Sprint 4:** Otimização das consultas ao banco para grandes volumes de dados, polimento da interface, testes finais de responsividade e entrega final da solução.

---
[⬅️ Voltar para o Menu Principal](https://github.com/Madhs31/Portfolio_Projetos_ADS)
