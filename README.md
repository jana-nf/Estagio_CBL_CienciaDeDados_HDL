# Estagio_CBL_CiênciaDeDados_HDL
Protótipo de pipeline de dados (ETL/ELT) desenvolvido com Python, Pandas, SQL e GIT, seguindo a metodologia Challenge-Based Learning (CBL) para estágio em Ciência de Dados.

# 🚀 Fase 1: Engajamento (Big Idea & Essential Question)
Definir o escopo do desafio de aprendizado, alinhando-o com os objetivos da vaga.

## Ideia Central (Big Idea):

O Valor dos Dados: Como os Dados Brutos são Transformados em Insights Acionáveis e Conhecimento Estratégico para a Empresa.

## Pergunta Essencial (Essential Question):

Como posso desenvolver um fluxo de trabalho de ponta a ponta em Python, utilizando práticas de engenharia de software (Git), para transformar dados heterogêneos em um dataset limpo e pronto para análise, gerando um insight estratégico que promova uma melhoria processual na área de atuação?

## O Desafio (Challenge):

Construir um mini-pipeline de ETL (Extração, Transformação e Carga) para processar dados de vendas (simulados: CSV, JSON, consulta SQL) e gerar um painel de indicadores (dashboard) simples em Python, que revele a principal 'dor' ou oportunidade de otimização de processo na operação de uma empresa hipotética (ex: logística, marketing).


# 🔬 Fase 2: Investigação (Learning Resources & Activities) 
Esta é a fase de aquisição de conhecimento e desenvolvimento das habilidades necessárias para superar o Desafio.

## Tópico (Habilidade):
- Python Intermediário (Scripts e Automação) 

- Processamento de Múltiplas Fontes (ETL)

- GIT para Controle de Versão

- Organização e Documentação

- Extração de Insights e Relatórios


## Atividades de Estudo Recomendadas:
- Estruturas de Dados Avançadas: Foco em Dicionários, List Comprehensions, e itertools.

- Pandas: Dominar read_csv, read_json, merge, groupby, apply, e tratamento de valores ausentes (NaN).

- Funções e Classes: Praticar a escrita de scripts modulares e reutilizáveis (automação de tarefas).

- Extração de APIs: Praticar requisições HTTP (biblioteca requests) para obter dados em formato JSON.

- SQL Básico: Foco em SELECT, FROM, WHERE, JOIN (consultas simples). Usar um banco de dados local (ex: SQLite).

- Leitura/Escrita de Arquivos: Praticar a manipulação de caminhos e formatos (os, pathlib).

- Comandos Essenciais: Dominar init, clone, add, commit, push, pull, branch, e merge.

- Fluxo de Trabalho: Praticar o trabalho com branches (desenvolvimento em feature branches e merge para main).

- Boas Práticas: Aprender a usar docstrings (documentação de funções), comentários claros e type hinting.

- Estrutura de Projeto: Organizar o código em pastas lógicas (src, data, notebooks).

- Visualização Básica: Utilizar matplotlib e seaborn (ou Plotly) para criar gráficos que contem uma história sobre os dados.

- Estatística Descritiva: Calcular médias, medianas, desvios e identificar outliers.


## Recursos de Aprendizagem Sugeridos:
- Cursos online (DataCamp, Coursera) com foco em Pandas.

- Prática no Kaggle (limpeza de dados).

- Livros/Documentação do Python sobre estruturas e bibliotecas padrões.

- Tutoriais sobre a biblioteca requests e json no Python.

- Exercícios práticos de SQL online (SQL Zoo, HackerRank).

- Projetos que simulem a leitura de dados de CSV, JSON e DB ao mesmo tempo.

- Curso básico de Git e GitHub (ex: FreeCodeCamp, Alura).

- Utilizar Git em todos os projetos de Python desenvolvidos na Fase 2.

- Guias de estilo de código (ex: PEP 8).

- Leitura sobre melhores práticas de documentação de código em Python.

- Tutoriais de visualização de dados em Python (foco em comunicação clara).

- Análise de datasets de exemplo (ex: dados de vendas) para encontrar tendências.


# ✨ Fase 3: Ação (Solution Development & Reflection)
Aplicação prática do conhecimento adquirido, culminando na solução do Desafio e reflexão sobre o aprendizado.

## Etapa 1: Desenvolver a Solução do Desafio

### Ação: 

Construção do Mini-Pipeline de ETL


### Extração (E):

Criar três fontes de dados simuladas: um CSV de pedidos, um JSON de informações do cliente (extraído via simulação de API), e um pequeno banco de dados SQLite com dados de estoque (consulta SQL básica).


### Transformação (T):

Escrever um script Python (usando Pandas) que leia, integre (merge), limpe (trate NaNs e formate tipos) e transforme os dados das três fontes em um dataset único e coerente.


### Automação: 

Garantir que este processo seja executado por um único script modular.


### Carga e Análise (L & Insights):

Carregar o dataset limpo em um arquivo final (ex: clean_data.csv).

Desenvolver o segundo script de análise para extrair um insight claro (ex: "Qual a categoria de produto com maior margem, mas com o maior tempo médio de entrega?") e gerar um gráfico de visualização (relatório simples).


### Controle de Versão:

Usar o Git desde o início, para criar branches para a extração, transformação e análise, e fazer commits regulares e detalhados.


## Etapa 2: Compartilhamento e Documentação

### Documentação: 

Escrever um README.md claro no repositório Git, explicando o propósito do projeto, como executar o script (instruções), e o insight final encontrado.

### Organização: 

Organizar o repositório seguindo a Estrutura de Projeto (ex: /src para scripts, /data para dados brutos e limpos).


## Etapa 3: Reflexão (Otimização e Melhoria)

### Responder às seguintes perguntas para consolidar o aprendizado:

O que aprendi sobre lidar com tipos de dados conflitantes de múltiplas fontes? (Relacionado ao Processamento de Dados)

Onde o uso do Git me salvou de um problema? (Relacionado ao Controle de Versão)

Como meu script de automação poderia ser melhorado para ser mais rápido ou robusto (ex: tratamento de erros)? (Relacionado à Otimização de Processos)

O insight gerado pode realmente levar a uma melhoria processual na empresa hipotética? (Relacionado à Extração de Insights e Alinhamento Estratégico)

Este plano de estudo transforma as atividades e habilidades da vaga em um projeto prático e tangível apresentado no processo seletivo.
