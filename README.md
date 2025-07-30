Este projeto realiza uma análise estatística e exploratória do dataset Cleveland Heart Disease, do repositório da UCI. O objetivo é entender a relação entre fatores demográficos (idade, sexo) e a presença de doença cardíaca.
Através da criação de faixas etárias e aplicação de medidas como odds, razão de chances, logito e WOE, o projeto busca identificar padrões e grupos de risco com maior propensão à doença.

Bibliotecas e Ferramentas Utilizadas
Python 
pandas
numpy
seaborn
matplotlib
statsmodels

1. Carregamento dos Dados
Fonte: UCI Machine Learning Repository

Dataset carregado diretamente da web.

2. Criação da Variável Alvo
A variável num foi transformada em flag_doente (0 = saudável, 1 = doente).

3. Análise Cruzada por Sexo
Tabela de frequência e cálculo de:

Odds

Razão de chances (RC)

Logito

WOE (Weight of Evidence)

4. Análise por Faixa Etária
Agrupamento de idades em 5 faixas.

Cálculo de estatísticas por grupo:

Total de doentes

Odds e Odds Ratio

Logito

WOE

5. Visualizações
Gráfico de barras empilhadas (contagem de doentes por faixa etária).

Gráfico de linha (proporção de doentes por faixa etária).

Resultados e Insights
Observou-se aumento da proporção de doentes com o avanço da idade.

Homens apresentaram maior risco de desenvolver doença cardíaca no conjunto de dados.

A aplicação de WOE e logito auxilia na preparação de variáveis para modelos preditivos, como regressão logística.

