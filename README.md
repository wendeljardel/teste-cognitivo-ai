# teste-cognitivo-ai
Teste Cognitivo.AI

a. Como foi a definição da sua estratégia de modelagem?
  Ao analisar o problema e os dados foi constatado que não havia variáveis categóricas. Sendo cada feature um número podemos 
  tratar esse problema com modelo de Regressão.
b. Como foi definida a função de custo utilizada?

c. Qual foi o critério utilizado na seleção do modelo final?

d. Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar
este método?
Para a avaliação do modelo foi usado o método da Raiz do erro quadrático médio (RMSE). Tal método mede a divergência entre o 
modelo de regressão linear e um conjunto de dados.

e. Quais evidências você possui de que seu modelo é suficientemente bom?
Para um bom modelo as Raizes do erro quadrático médio dos conjuntos de treinamento e teste devem ser muito proximos. 
Se a raiz do conjunto de testes for muito superior ao do conjunto de treinamento, é provável que tenhamos um sobreajuste (overfit) nos dados.
Sobreajuste é usado descrever quando um modelo estatístico se ajusta muito bem ao conjunto de dados anteriormente observado, mas se mostra ineficaz para prever novos resultados.
Observando os valores de RMSE de treino e teste podemos concluir que os valores são proximos. Logo temos um bom modelo de predição.
