# Estagio_CBL_CiênciaDeDados_HDL

🎯 Protótipo de pipeline de dados (ETL/ELT) desenvolvido com Python, Pandas, SQL e GIT, seguindo a metodologia Challenge-Based Learning (CBL) para estágio em Ciência de Dados(HDL).

# 🚀 Fase 1: Engajamento (Big Idea & Essential Question)

Definir o escopo do desafio de aprendizado, alinhando-o com os objetivos da vaga.

Este projeto foi desenhado para o processo seletivo de Estágio em Ciência de Dados na HDL, focando na construção de um sistema de informação robusto.

## Ideia Central (Big Idea):

O Valor dos Dados e a Lógica de Sistema: Como os Dados Brutos são Transformados em Insights Acionáveis e Conhecimento Estratégico para a Empresa.

Analogia HDL: Assim como uma Hardware Description Language (HDL) define a arquitetura lógica e o comportamento eficiente de um chip de computador, o pipeline de dados em Python deve definir a arquitetura lógica para transformar dados brutos em inteligência, garantindo eficiência e precisão em cada etapa do fluxo.

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

- Estruturas de Dados Avançadas, List Comprehensions, itertools, Funções e Classes, Manipulação de Arquivos e Caminhos (os, pathlib).

- Pandas: Dominar read_csv, read_json, merge, groupby, apply, e tratamento de valores ausentes (NaN).

- SQL: Praticar SELECT, FROM, WHERE, JOIN (SQLite local). APIs: Praticar requisições HTTP (requests).

- Funções e Classes: Praticar a escrita de scripts modulares e reutilizáveis (automação de tarefas).

- Extração de APIs: Praticar requisições HTTP (biblioteca requests) para obter dados em formato JSON.

- Comandos Essenciais: init, clone, add, commit, push, pull, branch, merge. Fluxo de Trabalho com feature branches.

- Boas Práticas: Aprender a usar docstrings (documentação de funções), comentários claros e type hinting.

- Estrutura de Projeto: Organizar em pastas lógicas (src, data, notebooks).

- Visualização Básica: matplotlib, seaborn ou Plotly (foco em comunicação clara).

- Estatística Descritiva: Calcular médias, desvios e identificar outliers


## Recursos de Aprendizagem Sugeridos:

- Livros/Documentação do Python sobre estruturas e bibliotecas padrões, Guias de estilo de código (PEP 8).
 
- Cursos online (DataCamp, Coursera) com foco em Pandas e ETL. Prática no Kaggle (limpeza de dados).

- Prática no Kaggle (limpeza de dados).

- Tutoriais sobre a biblioteca requests e json no Python.

- Exercícios práticos de SQL online (SQL Zoo, HackerRank).

- Projetos que simulem a leitura de dados de CSV, JSON e DB ao mesmo tempo.

- Curso básico de Git e GitHub (ex: FreeCodeCamp, Alura).
 
- Utilizar Git em todos os projetos de Python desenvolvidos na Fase 2.

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

Usar o Git desde o início, com branches (feature/extract, feature/transform, feature/analysis) e commits regulares e detalhados.

## Etapa 2: Compartilhamento e Documentação

### Documentação: 

Escrever um README.md claro no repositório Git, explicando o propósito do projeto, como executar o script (instruções), e o insight final encontrado.

### Organização: 

Organizar o repositório seguindo a Estrutura de Projeto (ex: /src para scripts, /data para dados brutos e limpos).


## ✨ Etapa 3: Reflexão (Otimização e Melhoria) - Mentalidade de Qualidade Total

Foco no Processo, Prevenção, e Orientação ao Cliente (o usuário do insight).

### Responder às seguintes perguntas para consolidar o aprendizado:

1. Foco na Qualidade e Robustez do Processo (Prevenção de Defeitos)

O que aprendi sobre lidar com tipos de dados conflitantes de múltiplas fontes?

TQM (Prevenção): Como a detecção precoce de conflitos de dados no pipeline (T) melhora a confiabilidade do dataset final, prevenindo erros de análise?

Lidar com tipos de dados como strings representando números ('10.50') em CSV e floats em JSON exigiu a definição de um padrão de tipo único logo na fase de Transformação. 
Essa padronização inicial atua como um Ponto de Controle de Qualidade (QC). Se este passo fosse ignorado, análises subsequentes (como a média de valores ou cálculos de margem) gerariam resultados incorretos ou erros de execução. O aprendizado é que a Transformação deve priorizar a consistência e a coerência dos dados antes de qualquer agregação, aplicando o princípio de que é mais barato corrigir o erro na fonte (Extração/Transformação) do que na análise final.

2. Controle de Versão como Gestão da Qualidade e Risco

Onde o uso do Git me salvou de um problema?

TQM (Rastreabilidade e Melhoria): Como o Git assegurou a rastreabilidade do meu código, facilitando auditorias e permitindo a melhoria iterativa e segura do pipeline?

O Git não apenas "salva", mas garante a integridade e auditabilidade do projeto, um pilar do TQM. 
O uso de feature branches (ex: feature/extract) impediu que o desenvolvimento da lógica de integração dos dados (muitas vezes complexa e propensa a erros) contaminasse o código principal de análise (main). 
Em um ponto, a lógica de merge estava incorreta, gerando duplicatas. 
Graças aos commits regulares, pude reverter rapidamente para a versão estável anterior (rollback), corrigindo o erro sem introduzir um novo "defeito" no produto final.
Isso demonstra a capacidade de Gerenciamento de Configuração e Qualidade no Desenvolvimento.

3. Otimização do Fluxo de Trabalho (Melhoria Contínua - Kaizen)

Como meu script de automação poderia ser melhorado para ser mais rápido ou robusto (ex: tratamento de erros)?

TQM (Eficiência e Zero Defeito): Quais otimizações podem ser aplicadas ao código para aumentar a eficiência (velocidade) e a robustez (tolerância a falhas) do pipeline, aproximando-o do "Zero Defeito"?

Para aumentar a robustez, o pipeline precisa de tratamento de exceções (try...except) para falhas de conexão (API ou SQL). 
Se a API de clientes falhar, o script deve registrar o erro e talvez carregar apenas as fontes disponíveis, em vez de travar o processo inteiro. 
Para eficiência, se o dataset crescesse, a substituição de loops em Python por operações vetorizadas do Pandas (apply) seria essencial. 
A melhoria contínua (Kaizen) aqui significa planejar a arquitetura de tal forma que ela escale (desempenho) e tolere falhas (robustez), não apenas entregue o resultado uma única vez.

4. Alinhamento Estratégico e Valor para o Cliente

O insight gerado pode realmente levar a uma melhoria processual na empresa hipotética?

TQM (Orientação ao Cliente/Stakeholder): O insight gerado é acionável e agrega valor estratégico ao "cliente" (a área de negócios que usará o painel)?

O insight encontrado ("A categoria de produto de maior margem tem o maior tempo médio de entrega") é diretamente acionável. 
Ele transforma um dado descritivo em uma oportunidade de melhoria processual. 
O "cliente" (Logística) pode agora investigar se o atraso está no picking, packing ou no transporte. 
Este resultado demonstra que o pipeline está alinhado com a estratégia de negócio, entregando um produto de alta qualidade (relevância) que resolve uma "dor" da operação, ao invés de apenas gerar gráficos bonitos.
