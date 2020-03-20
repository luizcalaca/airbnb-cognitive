# airbnb-cognitive

# a. Como foi a definição da sua estratégia de modelagem?

Na visão geral inicial do dataset, é perceptível que para o problema da predição do valor há variáveis que não farão sentido algum e já podem ser eliminadas desde o início.

É verificado, os campos nulos, que, em porcentagem alta, serão "sujeiras" para o nosso modelo e, assim, podemos retirá-los, como pode ser visto no código notebook.

No quesito outilier, vou verificado a partir da variável price, valores desvio padrão alto, a partir do gráfico. Como pode ser visto no código.

Há o símbolo monetário (dólar $) que também precisou ser retirado de vários campos, a fim de que pudéssemos realizar o nosso processo de trabalho com os valores.

# b. Como foi definida a função de custo utilizada?


# c. Qual foi o critério utilizado na seleção do modelo final?

Foi escolhido o RandomForest por uma decisão matemática no contexto Ensemble na melhoria do contexto das redes neurais.


# d. Qual foi o critério utilizado para validação do modelo? Por que escolheu utilizar este método?


# e. Quais evidências você possui de que seu modelo é suficientemente bom?

