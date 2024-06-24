# Trabalho Final de Modelagem Estatística

Este repositório reúne os dados, scripts e análises realizadas para o trabalho final da disciplina de Modelagem Estatística, lecionada pelo [Professor Luiz Max Fagundes de Carvalho](https://emap.fgv.br/professores/luiz-max-fagundes-de-carvalho) ([@maxbiostat](https://github.com/maxbiostat)). O objetivo era aplicar técnicas de modelagem, inferência e predição, aprendidas no decorrer desse curso e da disciplina de Inferência Estatística, a dados reais.

Para o trabalho, escolhi analisar os efeitos de condições sociais na saúde física e mental de indivíduos. Para isso, utilizei o conjunto de dados `earnings.csv`, que contém informações sobre diversos aspectos da vida diária de indivíduos no contexto norte americano, como obrigações econômicas, saúde e bem-estar, trabalho e emprego, atividades domésticas e familiares, e informações demográficas. Inicialmente, pretendo explorar modelos como modelos lineares generalizados e diferentes
métricas de avaliação da capacidade explicativa e estimativa dos modelos.

## Requisitos

Para instalar os pacotes necessários para rodar os scripts, execute o seguinte comando:

```bash
pip install -r requirements.txt
```

## Estrutura do repositório

```
STATISTICAL_MODELING
|   .gitignore
|   A2_ME_report.pdf
|   README.md
|   requirements.txt
└─── data/
|    └─── earnings/
|    | earnings.csv 
└─── images/
|    └─── eda/
|        |- ...
|    └─── models/
|        |- ...
└─── src/
|    └─── data_processing/
|        | eda.ipynb
|    └─── models/
|        | modeling.ipynb
```
