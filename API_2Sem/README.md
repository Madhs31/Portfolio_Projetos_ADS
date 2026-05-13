# 🧠 MindDoc Analyzer | API 2º Semestre - FATEC

## 📌 Sobre o Projeto

O **MindDoc Analyzer** é um software desenvolvido como entrega da disciplina de **API (Aprendizagem por Projetos Integrados)** durante o 2º semestre do curso de Análise e Desenvolvimento de Sistemas da **FATEC São José dos Campos - Prof. Jessen Vidal**.

O projeto atua no contexto da saúde mental, especificamente focado na otimização de rotinas em hospitais psiquiátricos e clínicas de psicologia. O objetivo do software é facilitar o acesso, a organização e a análise inteligente de dados extraídos de relatórios clínicos. Integrando Inteligência Artificial para processamento de linguagem natural, o sistema analisa textos médicos longos e extrai automaticamente informações cruciais — como sintomas, diagnósticos e respostas a tratamentos —, estruturando prontuários para apoiar uma tomada de decisão médica mais ágil e fundamentada.

## 🏢 Parceiro de Negócios (Cliente)

O projeto foi desenvolvido em parceria com a FATEC São José dos Campos, tendo como responsável pelos requisitos o professor Giuliano Bertoti. A proposta foi conduzida em ambiente acadêmico, simulando um cenário real de mercado com foco na construção de uma aplicação estruturada em Java, conectada a um banco de dados relacional e integrada a modelos de IA locais para análise semântica de documentos.

## 🚀 Funcionalidades e Demonstração

* 📝 **Cadastro de Relatórios:** Inserção e digitalização de relatórios clínicos e históricos de pacientes.
* 🧠 **Processamento com IA Local:** Utilização de LLMs executados localmente para ler prontuários e identificar entidades médicas (sintomas e diagnósticos).
* 📊 **Análise de Evolução:** Interface focada na clareza das informações para apoiar a tomada de decisão médica e psicológica.
* 🗄️ **Armazenamento Seguro:** Centralização dos relatórios processados em um banco de dados relacional estruturado.

### 🛠️ Arquitetura do Sistema 
<a id="arq"></a>
<div>
A arquitetura do <b>MindDoc Analyzer</b> precisou equilibrar requisitos funcionais e não funcionais críticos, como privacidade absoluta de dados sensíveis de saúde (evitando o envio de prontuários para nuvens públicas), desempenho de processamento e manutenibilidade. <br>
O sistema foi desenhado de forma modular, separando a camada de persistência, as regras de negócio em Java e a comunicação com o serviço de IA.

[🔗 Leia mais sobre a arquitetura do software na Wiki!](https://github.com/equipeAdalove/API-SEMESTRE2/wiki/3.-Arquitetura-do-Sistema) 
</div>

### 🎨 Protótipo Figma
<a id="prototipo"></a>
<div align="center">
  <table>
    <tr>
      <th><img src="" alt="Início"></th>
      <th><img src="" alt="Home"></th>
      <th><img src="" alt="Cadastrar"></th>
    </tr>
    <tr>
      <td><img src="" alt="Passo 1"></td>
      <td><img src="" alt="Passo 2"></td>
      <td><img src="" alt="Editar"></td>
    </tr>
    <tr>
      <td><img src="" alt="Home Pós Cadastro"></td>
      <td><img src="" alt="Consultar"></td>
      <td><img src="" alt="Excluir"></td>
    </tr>
  </table>
</div>

Confira os vídeos de demonstração da versão final (Sprint IV):
* 🖥️ **Demonstração:** [Clique para visualizar](https://github.com/user-attachments/assets/09271e88-c83b-4651-ac8e-a33ceca6f24e)


## 💻 Tecnologias Utilizadas

A aplicação foi construída integrando ecossistemas de desenvolvimento corporativo e inteligência artificial local:

### ⚙️ Back-end & Testes
<p align="left">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img alt="Maven" src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
  <img alt="JUnit" src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white" />
</p>

### 🧠 Inteligência Artificial
<p align="left">
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-FFFFFF?style=for-the-badge&logo=ollama&logoColor=black" />
</p>

### 🖥️ Interface
<p align="left">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🗄️ Banco de Dados
<p align="left">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

### 🛠️ Gestão, Metodologia & IDE
<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="IntelliJ IDEA" src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
  <img alt="Trello" src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Atuei como desenvolvedora da equipe Adalove focada na construção da lógica de software, estruturação da persistência de dados e garantia de qualidade.

Para assegurar a robustez do código e a exatidão no tratamento das informações dos pacientes, participei da elaboração de testes automatizados unitários utilizando a biblioteca **JUnit**, identificando e corrigindo falhas lógicas antes da integração das funcionalidades. Também colaborei com os fluxos de interface e estilização visual com **CSS**.

No escopo de organização e versionamento, utilizei ativamente o **Git** integrado à IDE **IntelliJ IDEA** para o desenvolvimento diário, mantendo o rastreamento das tarefas e o planejamento das entregas perfeitamente sincronizados através das ferramentas ágeis **Jira** e **Trello**.

<h3>Hard Skills</h3>
<details>
  <summary><b>Clique para ver a lista de hard skills</b></summary>
  <br>
  <table align="center">
    <tr>
      <th width="300px">Tecnologia / Metodologia</th>
      <th width="200px">Classificação</th>
    </tr>
    <tr>
      <td>Java (Lógica e OOP)</td>
      <td>★★★☆☆</td>
    </tr>
    <tr>
      <td>Maven & Automação de Build</td>
      <td>★★☆☆☆</td>
    </tr>
    <tr>
      <td>JUnit (Testes Unitários)</td>
      <td>★★☆☆☆</td>
    </tr>
    <tr>
      <td>MySQL (Modelagem e SQL)</td>
      <td>★★★☆☆</td>
    </tr>
    <tr>
      <td>Integração de IA (Ollama)</td>
      <td>★★★☆☆</td>
    </tr>
    <tr>
      <td>CSS3 & Figma</td>
      <td>★★★★★</td>
    </tr>
    <tr>
      <td>Git / Jira / Trello</td>
      <td>★★★★★</td>
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
      <td>Pensamento Analítico</td>
      <td>★★★★☆</td>
    </tr>
    <tr>
      <td>Qualidade e Atenção aos Detalhes</td>
      <td>★★★★☆</td>
    </tr>
    <tr>
      <td>Trabalho em Equipe</td>
      <td>★★★★☆</td>
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

## 📅 Metodologia e Sprints

O desenvolvimento seguiu os pilares da metodologia ágil (**Scrum**), gerenciado através do Jira e Trello, dividindo o escopo do **MVP (Minimum Viable Product)** em 4 Sprints incrementais:

* **Sprint 1:** Levantamento de requisitos, configuração do ambiente Java/Maven no IntelliJ, criação de wireframes no Figma e estruturação do repositório.
* **Sprint 2:** Modelagem do banco de dados MySQL para os relatórios clínicos e implementação das primeiras entidades e serviços em Java.
* **Sprint 3:** Conexão com o serviço do Ollama para processamento dos textos, implementação da interface visual e criação dos primeiros testes com JUnit.
* **Sprint 4:** Cobertura final de testes unitários, refatoração de código, validação da extração inteligente de diagnósticos e entrega da versão final do software.
