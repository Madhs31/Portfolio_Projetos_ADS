
# 🧠 MindDoc Analyzer | API 2º Semestre — FATEC

🔗 **Repositório do Projeto (Equipe):** [Acessar GitHub](https://github.com/equipeAdalove/API-SEMESTRE2)

## 📌 Sobre o Projeto

O **MindDoc Analyzer** é uma aplicação desktop desenvolvida durante o segundo semestre de ADS, voltada à organização e à consulta de informações contidas em relatórios clínicos no contexto da saúde mental.

A solução utiliza modelos de linguagem para apoiar a identificação de sintomas, diagnósticos e informações relacionadas a tratamentos, organizando os dados extraídos para consulta e revisão. O sistema auxilia o trabalho de organização dos registros e não substitui a avaliação de profissionais de saúde.

## 🏢 Parceiro de Negócios (Cliente)

O projeto foi desenvolvido em parceria com a FATEC São José dos Campos, sob responsabilidade do professor **Giuliano Bertoti** pelo levantamento dos requisitos. O desafio envolveu a construção de uma aplicação Java integrada a banco de dados relacional e modelos de IA locais.

## 🚀 Funcionalidades e Demonstração

- 📝 **Cadastro de relatórios:** registro de documentos clínicos.
- 🧠 **Processamento com IA local:** apoio à identificação e extração de informações relevantes.
- ✏️ **Revisão:** edição e correção dos dados extraídos.
- 🔍 **Consulta e filtragem:** busca dos relatórios armazenados.
- 🗄️ **Persistência de dados:** armazenamento estruturado das informações em banco relacional.
- 📊 **Visualização:** organização das informações para apoiar sua interpretação.
- 🔐 **Autenticação e autorização:** controle de acesso aos registros.
- 🧩 **Seleção de modelo:** escolha do modelo de linguagem e visão utilizado no processamento.
- 🗂️ **Gerenciamento:** atualização e exclusão de relatórios armazenados.

### 🛠️ Arquitetura do Sistema

<a id="arq"></a>

O sistema foi organizado em componentes que separam as responsabilidades da interface, da lógica em Java, da persistência no MySQL e da comunicação com os modelos de linguagem executados por meio do Ollama.

| Componente | Responsabilidade |
|---|---|
| Interface | Cadastro, consulta, edição e apresentação dos relatórios. |
| Aplicação | Regras de negócio e organização das informações em Java. |
| Persistência | Armazenamento e recuperação dos registros em MySQL. |
| Inteligência artificial | Extração e estruturação de informações com modelos locais. |

O processamento local reduz a dependência de serviços externos, mas não garante privacidade absoluta. A segurança depende também das práticas de acesso, armazenamento e tratamento dos dados. Os resultados extraídos pela IA precisam ser revisados.

[🔗 Consultar a Wiki da equipe](https://github.com/equipeAdalove/API-SEMESTRE2/wiki)

### 🖥️ Demonstração

Confira a demonstração da versão final (Sprint IV) disponibilizada pela equipe:

https://github.com/user-attachments/assets/09271e88-c83b-4651-ac8e-a33ceca6f24e

## 💻 Tecnologias Utilizadas

Tecnologias e ferramentas utilizadas pela equipe na construção do projeto. Minha atuação individual é detalhada na seção de contribuições pessoais.

### ⚙️ Back-end e Testes

<p align="left">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img alt="Maven" src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
  <img alt="JUnit" src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" />
</p>

### 🧠 Inteligência Artificial

<p align="left">
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
</p>

### 🖥️ Interface

<p align="left">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🗄️ Banco de Dados

<p align="left">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

### 🛠️ Gestão, Metodologia e IDE

<p align="left">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img alt="IntelliJ IDEA" src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="Jira" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
  <img alt="Trello" src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white" />
</p>

## 📌 Contribuições Pessoais

Atuei como **desenvolvedora** da equipe AdaLove, contribuindo para a lógica da aplicação, a estruturação da persistência de dados e as atividades de qualidade do software.

Participei da elaboração de testes unitários com **JUnit**, verificando o comportamento esperado das funcionalidades e identificando falhas lógicas antes da integração dos componentes. Esses testes auxiliam na verificação do software, mas não garantem a exatidão clínica das informações geradas pela IA.

Também colaborei com os fluxos de interface e a estilização visual em CSS. Utilizei Git e IntelliJ IDEA durante o desenvolvimento, além de Jira e Trello no acompanhamento das atividades.

### 🎯 Principais Entregas

- Participação no desenvolvimento da lógica em Java e na estruturação da persistência;
- Elaboração de testes unitários com JUnit;
- Identificação e correção de falhas lógicas;
- Colaboração nos fluxos de interface e estilização com CSS;
- Organização das atividades e versionamento do código.

### Hard Skills

  <br>
  <table align="center">
    <tr><th>Tecnologia / Metodologia</th><th>Nota</th><th>Classificação</th></tr>
    <tr><td>Java (Lógica e POO)</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>Maven e automação de build</td><td>★★☆☆☆</td><td>Já ouvi falar</td></tr>
    <tr><td>JUnit (Testes Unitários)</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>MySQL (Modelagem e SQL)</td><td>★★★★☆</td><td>Sei fazer com ajuda</td></tr>
    <tr><td>Integração de IA (Ollama)</td><td>★★☆☆☆</td><td>Já ouvi falar</td></tr>
    <tr><td>CSS3 e Figma</td><td>★★★★★</td><td>Sei fazer com autonomia</td></tr>
    <tr><td>Git / Jira / Trello</td><td>★★★★★</td><td>Sei fazer com autonomia</td></tr>
  </table>

### Soft Skills

  <br>
  <table align="center">
    <tr><th>Habilidade</th><th>Autoavaliação</th></tr>
    <tr><td>Pensamento Analítico</td><td>★★★☆☆</td></tr>
    <tr><td>Qualidade e Atenção aos Detalhes</td><td>★★★★☆</td></tr>
    <tr><td>Trabalho em Equipe</td><td>★★★★☆</td></tr>
    <tr><td>Comunicação Assertiva</td><td>★★★☆☆</td></tr>
    <tr><td>Organização e Planejamento</td><td>★★★☆☆</td></tr>
  </table>
  
Exemplos de aplicação durante o projeto:

- **Qualidade e atenção aos detalhes:** a elaboração dos testes exigiu observar os comportamentos esperados e identificar inconsistências na lógica.
- **Trabalho em equipe:** a integração da lógica Java, persistência e interface demandou colaboração e acompanhamento das atividades.

## 📅 Metodologia e Sprints

O trabalho foi organizado com Scrum, Jira e Trello. O repositório oficial registra quatro sprints concluídas. A síntese abaixo corresponde às histórias do backlog da equipe.

| Sprint | Foco das entregas |
|---|---|
| Sprint 1 | Extração de informações dos documentos, interface de cadastro e apresentação dos resultados, controle de acesso. |
| Sprint 2 | Persistência dos dados, edição e exclusão dos registros e execução local. |
| Sprint 3 | Consulta e filtragem dos relatórios, seleção de modelos, autenticação e melhorias da interface. |
| Sprint 4 | Documentação, testes e correções para a entrega final. |

[Consultar os backlogs, registros e demonstrações das entregas](https://github.com/equipeAdalove/API-SEMESTRE2)

## 📚 Aprendizados

O MindDoc Analyzer ampliou meus conhecimentos em programação orientada a objetos, Java, persistência e testes automatizados. Aprendi a importância de verificar o comportamento dos componentes antes da integração e de separar as responsabilidades do software. O contato com IA local também reforçou a necessidade de revisar as informações extraídas e adotar cuidados com dados sensíveis.

---

[⬅️ Voltar para o Menu Principal](../README.md)
