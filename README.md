# Random Forest Regression para Prever Preços de Casa
O objetivo deste projeto foi criar um modelo de regressão utilizando o algoritmo Random Forest para prever os preços das casas em um conjunto de dados disponibilizado no seguinte link: http://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.data


Para isso, foram utilizadas as bibliotecas Pandas, Scikit-Learn, Seaborn, Matplotlib e SHAP. Primeiramente, o conjunto de dados foi carregado em um dataframe do Pandas, onde as colunas foram nomeadas de acordo com a descrição fornecida no link acima. Em seguida, foi plotada uma matriz de correlação utilizando a biblioteca Seaborn, para verificar as relações entre as variáveis.


Após isso, as variáveis foram separadas em conjuntos de treino e teste e um modelo de regressão linear foi treinado utilizando o conjunto de treinamento. Esse modelo foi avaliado no conjunto de teste e o erro médio quadrático e o coeficiente de determinação foram calculados. Em seguida, foi utilizado o algoritmo Random Forest para criar outro modelo de regressão, com os mesmos conjuntos de treinamento e teste. Novamente, o modelo foi avaliado e os mesmos valores de erro e coeficiente de determinação foram calculados.


Por fim, foi plotado um gráfico comparando os valores reais do conjunto de teste com os valores previstos pelos modelos de regressão, utilizando a biblioteca Matplotlib. Além disso, foi utilizada a biblioteca SHAP para criar um gráfico de resumo do SHAP (SHapley Additive exPlanations) para a feature de "num_quartos", que fornece uma explicação sobre como cada feature contribuiu para a previsão do modelo.
