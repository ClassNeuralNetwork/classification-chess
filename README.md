# ♚ Classificação Binária de Vantagem Posicional No Xadrez ♔

Este projeto apresenta um modelo de **perceptron multicamadas** voltado a **classificação binária** de vantagem posicional dada uma determinada posição do tabuleiro de xadrez. Determinando assim se quem está com mais vantagem são as peças brancas ou as pretas.

## 📊 Dataset
O dataset escolhido está disponível em: [dataset chess evaluations](https://www.kaggle.com/datasets/ronakbadhe/chess-evaluations), sendo escolhido da plataforma do [kaggle](https://www.kaggle.com/).


Assim, ele possui:

* Duas colunas, sendo elas:
    1. FEN. Uma string que representa uma posição exata do tabuleiro de xadrez
    2. Evaluation. Representando a avaliação do tabuleiro, podendo ser positiva(+), negativa(+) ou neutra(#), onde positivo indica vantagem das brancas e negativo das pretas


* Cerca de 16 milhões de posições do xadrez

## 🛠️ Tecnologias Utilizadas

* **Linguagem**: Python 

* **Bibliotecas**: 
    * [Chess](https://pypi.org/project/chess/): Utilizada para pré-processamento dos dados, com base nos valores do tabuleiro.

    * [TensorFlow](https://www.tensorflow.org/?hl=pt-br): Necessária para as manipulações do modelo de IA

    * [MatPlotLib](https://matplotlib.org/): Utilizada para plotagem de gráficos.

    * [Pandas](https://pandas.pydata.org/): Utilizada para organização dos dados vindos do dataset.

    * [ScikitLearn](https://scikit-learn.org/stable/): Usada para cálculo de métricas, além de manipulação de dados e realizar parte do treinamento.
