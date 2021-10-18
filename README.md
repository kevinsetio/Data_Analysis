## Análise de Dados com Python

Este repositório contém mini-projetos de análise de dados extraídos via API ou de datasets públicos realizados com Python.

* [Dados Covid API](https://github.com/kevinsetio/Data_Analysis/blob/master/Dados_covid.ipynb)

Projeto que visa a geração de um gráfico para acompanhamento dos diagnósticos de casos de covid-19 e dos casos de recuperação. Os dados são recuperados do repositório criado pela Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE).

A escolha pela geração do gráfico e do Qr Code foi através da API do quickchart para exploração das possibilidades de análise e visualização diferentes das usualmente utilizadas em Python.

* [Análise Exploratória, através de Matplotlib-Seaborn, no dataset de carros usados à venda na Alemanha](https://github.com/kevinsetio/Data_Analysis/blob/master/Analise_exploratoria_Seaborn.ipynb)

Processo de análise gráfica dos dados do dataset a fim de verificar como as variáveis se relacionam entre si e quais insights podem ser tiraradas ao observar os resultados.

* [Análise preditiva do Dataset Titanic (Kaggle)](https://github.com/kevinsetio/Data_Analysis/blob/master/Kaggle_Titanic/Titanic.ipynb)

Projeto de criação de um modelo de machine learning com o intuito de prever se os passageiros do Titanic sobreviveram ou não.

Passamos pelo processo de obtenção dos dados, limpeza e data wrangling, além de uma rápida análise exploratória antes da criação do modelo.

O algoritmo inicial escolhido para o modelo foi o Random Forest e criado o modelo, foi realizado o tuning dos hiperparâmetros para otimização do modelo. Adicionalmente, aplica-se uma feature selection (com e sem tuning) para comparação da robustez do modelo de acordo com a quantidade de variáveis escolhidas.

Por fim, comparamos o resultado ao utilizar outro tipo de algoritmo Support Vector Machine (SVM).
