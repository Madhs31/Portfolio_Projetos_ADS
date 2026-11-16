
# 🧠 Synapse | API 6º Semestre — FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/Titus-System/synapse)

## 📌 Sobre o Projeto

O **Synapse** é uma aplicação web desenvolvida com base na metodologia **API (Aprendizagem por Projetos Integrados)** durante o 6º semestre do curso de Análise e Desenvolvimento de Sistemas da **FATEC São José dos Campos — Prof. Jessen Vidal**, pela equipe **Titus System**.

O principal objetivo da solução é **estruturar, documentar e simular regras de negócio relacionadas ao comissionamento de vendas**, utilizando inteligência artificial para auxiliar na interpretação das informações fornecidas pelos usuários e na avaliação de seus impactos financeiros.

A plataforma permite transformar descrições de regras de negócio em estruturas processáveis, executar simulações utilizando dados históricos e comparar os resultados com um cenário de referência, denominado **baseline**.

A proposta busca facilitar a definição de regras, a análise de cenários e a tomada de decisões empresariais, considerando os impactos financeiros antes da aplicação das regras em um ambiente operacional.

## 🏢 Parceiro de Negócios (Cliente)

O projeto foi desenvolvido a partir de um desafio proposto pela **Dom Rock**, representada por **Luiz Otavio e Andre Almeida**.

O desafio está relacionado à dificuldade de registrar, organizar e manter regras de negócio corporativas que sofrem alterações frequentes, especialmente aquelas associadas ao comissionamento de vendas, às campanhas de incentivo e às políticas comerciais.

A ausência de mecanismos adequados para estruturar essas informações pode ocasionar inconsistências, dificuldades de auditoria e perda de conhecimento organizacional.

Diante desse cenário, a solução busca centralizar a definição das regras, apoiar sua interpretação por meio de inteligência artificial e disponibilizar recursos de simulação e análise dos resultados.

## 🚀 Funcionalidades e Demonstração

- 📝 **Entrada de Regras por Texto:** definição de regras de comissionamento por meio de descrições textuais e parâmetros estruturados.
- 🎙️ **Captura e Transcrição de Voz:** conversão das informações fornecidas por áudio em texto para processamento.
- 🤖 **Extração e Geração de Código com IA:** interpretação das regras de negócio e geração de código para execução das simulações.
- 📊 **Simulação de Comissionamento:** aplicação das regras sobre dados históricos de vendas.
- 📈 **Comparação com Baseline:** comparação dos resultados simulados com um cenário de referência.
- 💰 **Avaliação Orçamentária:** análise dos resultados considerando o orçamento informado.
- 🔄 **Sugestões de Adaptação:** apoio à revisão das regras e metas de acordo com os parâmetros estabelecidos.
- 🗂️ **Histórico de Regras:** consulta e gerenciamento das regras salvas e arquivadas.
- 🔎 **Detalhamento dos Resultados:** apresentação das comissões por colaborador, com filtros e paginação.
- 🔐 **Autenticação e Controle de Acesso:** gerenciamento das sessões e proteção dos recursos da aplicação.
- 📋 **Auditoria e Explicabilidade:** recursos relacionados à rastreabilidade e à compreensão dos processamentos, previstos no escopo da terceira sprint.

> As funcionalidades apresentadas correspondem ao escopo geral do projeto. As entregas visuais parciais e as funcionalidades previstas para etapas posteriores são diferenciadas das integrações já realizadas.

### 🛠️ Arquitetura do Sistema

<a id="arq"></a>

A arquitetura do **Synapse** separa a interface web, a API principal, os serviços de inteligência artificial e os componentes responsáveis pela execução das simulações.

Essa organização permite distribuir as responsabilidades entre os serviços e utilizar mecanismos de comunicação assíncrona durante o processamento das regras.

| Componente | Responsabilidade | Tecnologias principais |
| --- | --- | --- |
| Front-end | Entrada das regras, formulários, histórico e visualização dos resultados | Vue.js, TypeScript, Vite e Tailwind CSS |
| API Principal | Gerenciamento dos fluxos, autenticação, persistência e integração com a interface | Java e Spring Boot |
| Serviço de Geração de Código | Extração, validação e transformação das regras com apoio de IA | Python, FastAPI e LangGraph |
| Worker de Execução | Execução isolada do código gerado e realização das simulações | Python e Docker |
| Mensageria | Comunicação assíncrona entre os serviços | RabbitMQ |
| Banco de Dados | Armazenamento das regras, execuções e resultados | PostgreSQL |
| Autenticação | Gerenciamento de identidades, sessões e controle de acesso | Keycloak e JWT |
| Processamento de Voz | Transcrição das informações fornecidas por áudio | Deepgram |

O **RabbitMQ** é utilizado para organizar a comunicação assíncrona entre os serviços responsáveis pela geração de código e pela execução das simulações.

A interface acompanha os estados do processamento por meio de **Server-Sent Events (SSE)**, permitindo atualizar as informações apresentadas ao usuário durante a execução das atividades.

O código gerado pela inteligência artificial é executado em contêineres isolados, com restrições de rede e recursos computacionais, buscando reduzir os riscos associados à execução de código produzido automaticamente.

[🔗 Consultar a documentação da arquitetura](https://github.com/Titus-System/synapse/blob/main/docs/ARCHITECTURE.md)

### 🖥️ Demonstração

Confira a demonstração da **Sprint 2**, disponibilizada no repositório da equipe:

https://github.com/user-attachments/assets/5c50876b-64d8-44c6-9050-4d9dfb758745

## 💻 Tecnologias Utilizadas

As tecnologias abaixo correspondem ao conjunto de ferramentas utilizadas pela equipe no desenvolvimento do projeto. Minha atuação individual é detalhada na seção de contribuições pessoais.

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
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🗄️ Banco de Dados e Mensageria

<p align="left">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
  <img alt="SSE" src="https://img.shields.io/badge/Server_Sent_Events-333333?style=for-the-badge" />
</p>

### 🔐 Autenticação e Infraestrutura

<p align="left">
  <img alt="Keycloak" src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white" />
  <img alt="JWT" src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

### 🛠️ Desenvolvimento, Qualidade e Design

<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" />
  <img alt="Pytest" src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Atuo como **desenvolvedora full-stack** no Dev Team da equipe **Titus System**, participando da construção das interfaces, da integração com os serviços do back-end, da autenticação e das funcionalidades relacionadas à inteligência artificial.

Na camada de apresentação, participei da estruturação inicial da aplicação utilizando **Vue.js, TypeScript, Vite e Tailwind CSS**, incluindo a organização das rotas, dos componentes, do gerenciamento de estado e da integração com o ambiente Docker.

Entre minhas principais contribuições, destaca-se o desenvolvimento do **formulário de regras de comissionamento**, contemplando a validação dos parâmetros, da competência e do orçamento, além da integração com os serviços responsáveis pela criação e consulta dos processamentos.

Também desenvolvi funcionalidades relacionadas ao **histórico de regras salvas e arquivadas**, incluindo paginação, contadores e componentes compartilhados de navegação.

Na apresentação dos resultados, implementei o **detalhamento das comissões por colaborador**, com filtros por matrícula, loja e competência, paginação local e tratamento dos estados de carregamento, erro e ausência de dados.

No contexto da autenticação, participei da integração com o **Keycloak**, contribuindo para a proteção da API utilizando JWT, o gerenciamento da sessão do usuário, a proteção das rotas e o envio dos tokens nas requisições realizadas ao back-end.

Minha atuação também contemplou a estruturação inicial da API desenvolvida em **Java e Spring Boot** e do serviço de geração de código em **Python e FastAPI**.

Contribuí para a extração das regras de negócio a partir das transcrições e para a integração da validação de domínio ao fluxo de geração de código, buscando identificar conflitos e impedir que regras inconsistentes avancem para as etapas posteriores.

Na funcionalidade de voz, implementei o cliente de integração com o serviço de transcrição **Deepgram Nova-3**, incluindo validação dos formatos de áudio, tratamento de falhas, limitação das tentativas de processamento e controle de concorrência.

Também participei do fluxo de recebimento e aceitação de metas sugeridas, de ajustes de persistência e da validação dos contratos utilizados pelos serviços.

Complementarmente, desenvolvi as interfaces visuais destinadas à entrada de regras por texto e voz e ao chatbot de correção, registradas como **entregas visuais parciais**, com integração funcional prevista para etapas posteriores.

Durante o desenvolvimento, participei das atividades relacionadas a testes automatizados, padronização das verificações de qualidade, versionamento e integração das alterações utilizando Git e GitHub.

### 🎯 Principais Entregas

- Estruturação inicial da aplicação front-end utilizando Vue.js, TypeScript, Vite e Tailwind CSS;
- Organização das rotas, componentes, gerenciamento de estado e integração com o ambiente Docker;
- Desenvolvimento do formulário de regras de comissionamento, com validação de parâmetros, competência e orçamento;
- Integração com os serviços de criação e consulta dos processamentos;
- Implementação do histórico de regras salvas e arquivadas, com paginação e contadores;
- Desenvolvimento da interface de detalhamento das comissões por colaborador;
- Implementação de filtros por matrícula, loja e competência;
- Tratamento dos estados de carregamento, erro e ausência de dados;
- Integração dos mecanismos de autenticação utilizando Keycloak e JWT;
- Implementação da proteção de rotas e do gerenciamento de sessões;
- Participação na estruturação inicial da API e do serviço de geração de código;
- Desenvolvimento do cliente de integração com o Deepgram Nova-3;
- Implementação de validações de áudio, tratamento de falhas, controle de concorrência e limitação de tentativas;
- Contribuição para a extração de regras de negócio a partir das transcrições;
- Integração da validação de domínio ao fluxo de geração de código;
- Participação no fluxo de recebimento e aceitação de metas sugeridas;
- Desenvolvimento das interfaces de entrada por texto e voz e do chatbot de correção, como entregas visuais parciais;
- Participação em ajustes de persistência, testes automatizados e validação de contratos;
- Versionamento, integração das alterações e colaboração utilizando Git e GitHub.

### Hard Skills

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
      <td>Vue.js, TypeScript e Vite</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Tailwind CSS e Componentização de Interfaces</td>
      <td>★★★★★</td>
      <td>Sei fazer com autonomia</td>
    </tr>
    <tr>
      <td>Java e Spring Boot</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Python, FastAPI e Integração de IA</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Keycloak e Autenticação JWT</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>PostgreSQL e Migrações de Banco de Dados</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>RabbitMQ e Processamento Assíncrono</td>
      <td>★★★★☆</td>
      <td>Sei fazer com ajuda</td>
    </tr>
    <tr>
      <td>Testes Automatizados e Validação de Contratos</td>
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

### Soft Skills

<details>
  <summary><b>Clique para ver a lista de soft skills</b></summary>

  <br>

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
      <td>Adaptabilidade e Aprendizagem Contínua</td>
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
      <td>Raciocínio Lógico e Resolução de Problemas</td>
      <td>★★★★★</td>
    </tr>
  </table>
</details>

<br>

As atividades realizadas permitem destacar as seguintes habilidades comportamentais relacionadas à minha participação:

- **Adaptabilidade e aprendizagem contínua:** a atuação em diferentes componentes da arquitetura exigiu ampliar meus conhecimentos para além da interface, envolvendo autenticação, serviços em Java e Python, inteligência artificial e processamento de áudio.

- **Raciocínio lógico e resolução de problemas:** a construção dos fluxos de processamento exigiu compreender os contratos de dados, identificar inconsistências, tratar falhas e implementar mecanismos de validação.

- **Trabalho em equipe:** o desenvolvimento de funcionalidades distribuídas entre diferentes componentes demandou colaboração, integração das alterações e acompanhamento das dependências entre as entregas.

- **Comunicação técnica:** a integração entre a interface, a API principal e os serviços de inteligência artificial exigiu alinhamento sobre os formatos de dados, as responsabilidades e os fluxos de processamento.

- **Orientação ao cliente:** a construção dos formulários e das visualizações exigiu compreender as necessidades relacionadas à definição das regras de comissionamento e à análise dos resultados financeiros.

## 📅 Metodologia e Sprints

O desenvolvimento seguiu o framework **Scrum**, com planejamento das atividades, acompanhamento do Product Backlog, critérios de aceitação e realização de entregas incrementais.

A equipe utilizou critérios de **Definition of Ready (DoR)** e **Definition of Done (DoD)** para organizar o início das atividades e estabelecer as condições necessárias para considerar uma funcionalidade concluída.

O projeto foi estruturado em três sprints, conforme o cronograma oficial da equipe.

| Etapa | Data registrada | Escopo documentado |
| --- | --- | --- |
| Kick-off | 26/08/2026 | Início do projeto e apresentação do desafio |
| Sprint 1 | 27/09/2026 | Entrada por texto, simulação de regras, comparação com baseline e histórico |
| Sprint 2 | 25/10/2026 | Captura e transcrição de voz e sugestões de adaptação |
| Sprint 3 | 22/11/2026 | Auditoria, explicabilidade e validação dos parâmetros extraídos por voz |

O cronograma oficial registra a Feira de Soluções para **03/12/2026**.

Considerando o recorte de **16/11/2026**, as duas primeiras sprints foram realizadas, enquanto a terceira sprint permanece em desenvolvimento e a apresentação final está prevista.

[Consultar os registros oficiais das entregas](https://github.com/Titus-System/synapse)

## 📚 Aprendizados

O desenvolvimento do Synapse possibilitou ampliar meus conhecimentos em desenvolvimento full-stack, integração de serviços e construção de aplicações distribuídas.

A estruturação das interfaces e dos formulários contribuiu para aprofundar meus conhecimentos em Vue.js, TypeScript, Tailwind CSS, gerenciamento de estado e organização de componentes reutilizáveis.

A participação na autenticação e na integração dos serviços desenvolvidos em Java e Python permitiu compreender melhor os contratos de comunicação, o gerenciamento de sessões e as responsabilidades dos diferentes componentes da arquitetura.

A integração com o Deepgram e os mecanismos de validação das regras também reforçou a importância do tratamento de falhas, da consistência dos dados e da rastreabilidade das informações.

Além dos conhecimentos técnicos, o projeto contribuiu para o aprimoramento da minha capacidade de trabalhar em equipe, adaptar-me a novas tecnologias, compreender sistemas complexos e solucionar problemas de integração.

Essa experiência representa uma etapa de consolidação da minha formação acadêmica, unindo conhecimentos de desenvolvimento de interfaces, back-end, autenticação, inteligência artificial e integração de serviços.

---

[⬅️ Voltar para o Menu Principal](../README.md)
