# scikit-learn

## Explicação
1. Importação das bibliotecas necessárias: O código começa importando as bibliotecas necessárias. pandas é usado para manipulação de dados, train_test_split da sklearn.model_selection é usado para dividir os dados em conjuntos de treinamento e teste, LinearRegression da sklearn.linear_model é usado para criar o modelo de regressão linear e metrics da sklearn é usado para calcular o erro quadrático médio.
2. Leitura dos dados: O código lê um arquivo CSV contendo os dados e armazena-os em um DataFrame pandas chamado df.
3. Divisão dos dados: Os dados são divididos em conjuntos de treinamento e teste usando a função train_test_split. 80% dos dados são usados para treinamento e 20% para teste.
4. Criação do modelo de regressão linear: Um objeto de regressão linear é criado usando a classe LinearRegression.
5. Treinamento do modelo: O modelo é treinado usando o conjunto de treinamento. Isso é feito com a função fit, que recebe os dados de treinamento como argumentos.
6. Previsão: O modelo treinado é usado para fazer previsões no conjunto de teste. Isso é feito com a função predict, que recebe os dados de teste como argumento.
7. Cálculo do erro quadrático médio: O erro quadrático médio das previsões é calculado usando a função mean_squared_error da sklearn.metrics. Isso fornece uma medida de quão bem o modelo se ajusta aos dados.
