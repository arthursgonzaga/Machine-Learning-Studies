# Machine Learning Studies

Estudos acerca de Machine Learning na trilha de aprendizado da Alura.

## Organização do Repositório

### Classificadores e SKLearn

Introdução ao Machine Learning, colocando os parâmetros principais de Support Vector Machine (modelos lineares) para predição. Visto também os impactos da seleção correta dos arquivos de teste e treino.

#### Tópicos Principais: SVM e LinearSVM

### Classificação Por Trás dos Panos

Utilizando os conceitos apresentados anteriormente para estudo dos algoritmos Bayesianos (Naive Bayes). Mostrado o algoritmo de baseline e também a utilização de variáveis categóricas para ML. Por fim, realizando uma comparação com o algoritmo de AdaBoost.

#### Tópicos Principais: Naive Bayes e AdaBoost

### Lidando com Altas Dimensões

Pré-tratamento analítico utilizando matriz de correlação, desvios padrões e valores nulos. Utilizado também modelos de seleção de features como o RFE e o KBest. Feita a redução do número de features para dataviz, utilizando o RFECV e o PCA.

#### Tópicos Principais: RFE e KBest

### K-Means, DBSCAN e MeanShift

Avaliação de um dataset de vinhos, foi possível separar os dados em grupos, ou seja, clusterizar os dados. Os dados foram testados nos métodos de K-Means, DBSCAN e MeanShift. No final, foi validado o melhor método a ser aplicado a partir do coeficiente de silhueta. 
Nota: tive que rodar este notebook no Colab, pois a biblioteca Biokit não foi instalada no Jupyter nativamente.

#### Tópicos Principais: K-Means, DBSCAN e MeanShift

### Clusterização: Extraindo Padrões de Dados

Iniciando a aula com um dataset relacionado a cartões de créditos. O objetivo é separar clientes em grupos semelhantes. Realizado o pré-tratamento de dados faltantes e visualizado os primeiros parâmetros de silhoutte. Feita a análise de agrupamento e semelhança com os métodos de Davies-Bouldin e Calinski-Harabasz. Segregado por variância as melhores features e trabalhado para separar os grupos desta forma.

#### Tópicos Principais: Métodos de Comparação, Silhouette, Davies-Bouldin e Calinski-Harabasz

### Validação de Modelos

Abordagem de métodos para estratificação, validação cruzada e o efeito da aleatoriedade no desenvolvimento de um modelo.

#### Tópicos Principais: K-Fold, Árvore de Decisão e Validação Cruzada

### Otimização de Modelos

Iniciada a otimização de modelos utilizado ferramentos como o GridSearch. Foi realizada a exploração manual dos melhores hiperparâmetros através da correlação e também a exploração automatizada utilizando o GridSearchCV. Visto que o GridSearch consome muito poder computacional, validamos a busca dos hiperparametros pelo RandomizedSearchCV. Analisado sem validação cruzada o processo de retirada de mais uma amostra (agora chamado de validação), para concretização do modelo.

#### Tópicos Principais: Hiperparâmetros, GridSearch, Correlação, RandomizedSearch

### Deep Learning: Introdução ao Keras

Com as bibliotecas TensorFlow e Keras, foi realizada a criação de uma rede neural para classificação de tipos de roupas (camisetas, camisas, bolsas, botas, etc). No conteúdo, aborda-se a normalização e os conceitos de overfitting e underfitting. Épocas, validação e número de camadas foram alguns parâmetros testados no modelo para melhoria da acurácia e minimização das perdas. Por fim, realizada a exportação do modelo, que pode ser encontrado neste [link](https://github.com/arthursgonzaga/Machine-Learning-Studies/tree/main/Modelos).

#### Tópicos Principais: Keras, Redes Neurais, Camadas, TensorFlow