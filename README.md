# IMDb Movie Analytics

## Sobre o Projeto

Projeto de Análise Exploratória de Dados (EDA) desenvolvido em Python para investigar fatores relacionados ao sucesso comercial e ao reconhecimento crítico de filmes.
A análise utiliza dados históricos do IMDb para explorar relações entre orçamento, faturamento, avaliações do público, duração, gêneros, diretores e premiações do Oscar.
O objetivo é identificar padrões que ajudem a responder perguntas como:
- Filmes com maior orçamento recebem mais Oscars?
- Filmes mais bem avaliados ganham mais premiações?
- Quais gêneros dominam a indústria cinematográfica?
- Existe relação entre duração e avaliação dos filmes?
- Quais diretores apresentam melhor desempenho financeiro?

---

## Objetivos

- Analisar a evolução histórica da indústria cinematográfica.
- Investigar fatores relacionados ao faturamento dos filmes.
- Avaliar possíveis relações entre orçamento, notas e premiações.
- Comparar o desempenho dos principais gêneros cinematográficos.
- Identificar diretores com maior sucesso financeiro e reconhecimento crítico.

---

## Dataset

O conjunto de dados contém informações históricas sobre filmes, incluindo:
- Ano de lançamento
- Gênero
- Diretor
- Roteirista
- Duração
- Orçamento
- Faturamento
- Nota IMDb
- Quantidade de votos
- Premiações no Oscar

Fonte:
- [world_imdb_movies_top_movies_per_year](https://bit.ly/49AOfcj)
  
---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Fluxo do Projeto

```mermaid
flowchart LR

A[Dataset IMDb] --> B[Limpeza dos Dados]
B --> C[Tratamento de Nulos]
C --> D[Padronização de Campos]
D --> E[Análise Exploratória]
E --> F[Visualizações]
F --> G[Insights]
```

---

## Tratamento dos Dados

Durante a preparação dos dados foram realizadas atividades como:
- Tratamento de valores nulos.
- Conversão de tipos de dados.
- Padronização de colunas.
- Transformação de campos multivalorados (gêneros, diretores e roteiristas).
- Criação de variáveis derivadas para análise por década.
- Conversão de duração para minutos.

---

## Análises Realizadas

### Evolução das Notas ao Longo das Décadas

Avaliação da média das notas IMDb por década para identificar mudanças na percepção do público ao longo do tempo.

### Quantidade de Filmes por Década

Análise do crescimento da produção cinematográfica ao longo dos anos.

### Distribuição por Gênero

Identificação dos gêneros mais populares da indústria.

### Evolução da Duração dos Filmes

Comparação da duração média dos filmes em diferentes períodos.

### Evolução dos Orçamentos

Análise histórica do crescimento dos investimentos em produções cinematográficas.

### Oscar vs Orçamento

Investigação da relação entre investimento financeiro e premiações.

### Oscar vs Avaliação IMDb

Verificação da influência das avaliações do público nas premiações.

### Duração vs Nota IMDb

Análise da relação entre tempo de duração e recepção dos filmes.

### Desempenho dos Gêneros

- Duração média
- Distribuição das notas
- Quantidade de premiações
- Popularidade ao longo das décadas

### Análise Financeira

- Faturamento médio por gênero
- Diretores com maior faturamento médio
- Diretores mais premiados

---

## Principais Insights

### Premiações não dependem apenas do orçamento

A correlação encontrada entre orçamento e número de Oscars foi muito baixa, indicando que altos investimentos não garantem reconhecimento da Academia.

### Avaliações do público não explicam totalmente as premiações

Filmes com notas elevadas no IMDb não necessariamente recebem mais Oscars.

### Drama domina a indústria

O gênero Drama aparece consistentemente entre os mais produzidos ao longo das décadas.

### Duração não influencia significativamente as avaliações

Não foi observada relação relevante entre o tempo de duração do filme e sua nota no IMDb.

### Diretores de animação apresentam forte desempenho financeiro

Os maiores faturamentos médios foram observados em produções ligadas ao segmento de animação.

---

## Estrutura do Projeto

```text
IMDB-Movie-Analytics/
│
├── IMDB_estudo.ipynb
├── data/
│   └── imdb_dataset.csv
│
├── images/
│   ├── rating_decadas.png
│   ├── oscar_vs_budget.png
│   └── faturamento_diretores.png
│
└── README.md
```

---

## Como Executar

```bash
git clone https://github.com/seu-usuario/imdb-movie-analytics.git

cd imdb-movie-analytics

pip install pandas numpy matplotlib seaborn

jupyter notebook
```

---

## Competências Demonstradas

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Storytelling com Dados
- Estatística Descritiva
- Análise de Correlação
- Python para Análise de Dados

---

## Conteúdo deste repositório
- Arquivo .ipynb 


