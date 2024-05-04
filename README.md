# Exploração do Conjunto de Dados de Exercícios
## Visão Geral

Este repositório explora o conjunto de dados "exercise" disponível na biblioteca Seaborn. O objetivo é obter insights sobre os dados e compreender a relação entre vários atributos. Seaborn é uma biblioteca de visualização em Python baseada em matplotlib, fornecendo uma interface de alto nível para desenhar gráficos estatísticos atraentes e informativos.

## Conjunto de Dados

O conjunto de dados "exercise" contém informações sobre o desempenho de indivíduos durante o exercício. Inclui os seguintes atributos:

- ID: Identificador único para cada indivíduo
- Diet: Tipo de dieta seguida pelo indivíduo
- Pulse: Frequência cardíaca durante o exercício
- Time: Tempo gasto exercitando em minutos
- Kind: Tipo de exercício realizado (3 valores)

## Estrutura do Projeto

A estrutura do projeto está organizada da seguinte forma:

```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke
```
A exploração do conjunto de dados "exercise" incluiu diversas análises estatísticas e visualizações para descobrir padrões e insights dentro dos dados. Além disso, este repositório pode servir como uma referência para utilizar a biblioteca Seaborn para tarefas de visualização e análise de dados.

## Exploração de Dados

Durante a análise do conjunto de dados "exercise", foram descobertos vários insights interessantes:

1. Distribuição de Tempo de Exercício: A distribuição do tempo gasto exercitando revelou que a maioria dos indivíduos passa entre 30 e 60 minutos exercitando-se.

2. Relação entre Dieta e Frequência Cardíaca: Observou-se uma correlação entre o tipo de dieta seguida pelo indivíduo e sua frequência cardíaca durante o exercício. Indivíduos com uma dieta específica apresentaram uma frequência cardíaca mais alta em comparação com outros grupos.

3. Tipos de Exercício Preferidos: Analisando os tipos de exercício realizados, foi possível identificar os tipos mais populares entre os participantes. Essas informações podem ser úteis para personalizar programas de exercício.

4. Variação de Frequência Cardíaca por Tipo de Exercício: Cada tipo de exercício mostrou uma distribuição diferente de frequência cardíaca. Alguns tipos de exercício parecem ser mais intensos do que outros, com uma frequência cardíaca média mais alta.

