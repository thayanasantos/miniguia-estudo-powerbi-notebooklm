# 💡 Miniguia de Estudos: Power BI do Zero com NotebookLM

Este repositório contém a estrutura e os materiais utilizados para criar um ambiente de aprendizado inteligente sobre **Power BI**, utilizando o **Google NotebookLM**. A proposta é transformar fontes densas de conteúdo em um tutor personalizado que facilita a jornada do iniciante, além disso, servindo como desafio de projeto da **DIO**.

---

## 📖 Descrição do Projeto
>*"Este projeto nasceu da necessidade de organizar o mar de informações sobre Power BI (DAX, ETL, Visualização) em um fluxo lógico de aprendizado, utilizando a IA do NotebookLM para sintetizar documentos oficiais e tutoriais."*
>O projeto está dividido em partes para melhor aproveiamento de estudo, entre elas encontramos o glossário com os principais termos utilizados, prompts reutilizaveis, Mapa mental com o direcionamento que o aluno iniciante deve seguir, instruções de como utilizar esse guia e as tecnologias utilizadas. 

---

## 📑Glossário de Termos-Chave
|Termo| Definição|
|:--- | :---|
|**DAX**| Data Analysis Expressions; linguagem de fórmulas usada para criar cálculos e medidas personalizadas no Power BI.|
| **Medidas** | Cálculos dinâmicos onde os resultados mudam conforme o contexto. |
| **Modelagem** | O processo de conectar diferentes fontes de dados via relacionamentos. |
|**Power Query**| Ferramenta de conexão e transformação de dados (ETL) que permite limpar e preparar bases antes da modelagem.|
|**Star Schema**| Modelo de dados que organiza as informações em uma tabela fato central conectada a múltiplas tabelas dimensão.|
|**Tabela Fato**| Tabela que armazena as métricas quantitativas de um processo de negócio (ex: valores de transações, datas de ocorrência).|
|**Tabela Dimensão**| Tabela que contém atributos descritivos e contextuais sobre as entidades do negócio (ex: nome do cliente, categoria do produto).|
|**RLS**| Row-Level Security; funcionalidade que restringe o acesso aos dados para usuários específicos com base em filtros de linha.|
|**KPI**| Key Performance Indicator; métrica visual usada para avaliar o sucesso de uma organização ou atividade em relação a metas.|
|**Microsoft Fabric**| Plataforma unificada de análise de dados que integra engenharia, ciência e inteligência de dados em tempo real.|
|**Bravo for Power BI**| Ferramenta externa de produtividade para gerenciar datas, formatar DAX e otimizar o tamanho do modelo de dados.|
|**Segmentador (Slicer)**| Tipo de filtro visual interativo que permite ao usuário filtrar os dados de todo o relatório com um clique.|
|**Calculated Column**| Coluna criada no modelo de dados através de DAX que calcula valores linha a linha, aumentando o tamanho do arquivo.|
|**Measure (Medida)**| Cálculo DAX executado no momento da visualização, baseado no contexto de filtro, sendo mais eficiente que colunas calculadas.|
|**VPAX**| Formato de arquivo usado para exportar metadados e analisar a estrutura e o consumo de memória de um modelo de dados.|
|**Pareto (80/20)**| Princípio que afirma que 80% dos efeitos provêm de 20% das causas; usado para priorizar ações em análises de vendas e estoque.|

---

## 🛠️ Prompts Reutilizáveis (NotebookLM)
*Copie e cole estes prompts no chat do seu NotebookLM para extrair o melhor dos seus documentos:*

### 1. Nível Iniciante: Visão Geral
```text
Com base nos documentos carregados, crie um roteiro de estudo para as primeiras 2 semanas, focando em quem nunca abriu o Power BI. O que devo aprender primeiro?
```

### 2. Desmistificando Cálculos (DAX)
```text
Explique a diferença entre uma Coluna Calculada e uma Medida utilizando uma analogia simples. Liste 5 funções DAX essenciais para iniciantes presentes no material.
```

### 3. Guia de Resolução de Problemas
```text
Estou tentando relacionar a Tabela [A] com a Tabela [B], mas recebo um erro de 'muitos para muitos'. Com base no guia de boas práticas do notebook, como devo proceder?
```

### 4. Simulado de Conhecimento
```text
Gere 5 perguntas de múltipla escolha sobre o processo de ETL (Power Query) com base nos capítulos X e Y, e forneça o gabarito apenas quando eu responder.
```

---

## 🗺️ Mapa Mental

Esse miniguia, além de apresentar os termos mais utilizados no aprendizado do Power Bi, disponibiliza um mapa mental com as principais direções que o estudante iniciante pode seguir como exemplo abaixo: 

<img width="3761" height="1637" alt="NotebookLM Mind Map - Aprendizagem Power BI" src="https://github.com/user-attachments/assets/06824be4-9e73-4a88-8f31-db87e71a4cde" />

Em um cenário de abundância de informações e infinitas possibilidades de aprendizado, o Mapa Mental atua como uma bússola estratégica. O acesso à internet democratizou o conteúdo, mas sem um direcionamento claro, é fácil perder tempo com materiais desconexos. O mapa organiza essa jornada, transformando o excesso de dados em um caminho estruturado e eficiente. 


## 🚀 Como utilizar este guia
1. Suba os PDFs ou links da documentação oficial da Microsoft para o seu **NotebookLM**.
2. Utilize o **Glossário** acima para se familiarizar com os termos.
3. Aplique os **Prompts** na sequência sugerida para construir sua base de conhecimento.
4. Documente sua evolução na pasta `/anotacoes`.

---

## 🛠️ Tecnologias Utilizadas
* **Google NotebookLM** (IA de Contexto)
* **Power BI Desktop**
* **Markdown** (Documentação)

---
## 🔗 Link NotebookLM - Miniguia de Estudo Power BI.

[ [NotebookLM-miniguia-estudo-powerbi](https://notebooklm.google.com/notebook/4e2cce4b-19ff-4573-b54f-15a085cf386e)]

---
*Criado por [Thayana Santos] - Conecte-se comigo no [[Link do LinkedIn](https://www.linkedin.com/in/thayana-santos-abb34650/)]*
