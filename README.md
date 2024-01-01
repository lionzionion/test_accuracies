# test_accuracies

# README - Análise de Árvore de Decisão
* Este repositório contém código Python para treinar, ajustar e avaliar modelos de árvore de decisão usando a biblioteca scikit-learn. O código é projetado para análise de dados relacionados a atividades humanas, como reconhecimento de padrões de movimento.

## Conteúdo do Repositório
### Dados:

* Os dados utilizados estão armazenados nos arquivos X_train.txt, y_train.txt, subject_train.txt, X_test.txt, y_test.txt e subject_test.txt.
### Pré-processamento:

* O código realiza o carregamento e pré-processamento dos dados, incluindo a criação de um índice duplo e ajuste dos nomes das colunas.
### Treinamento de Árvore de Decisão:

* Uma árvore de decisão é treinada com um número mínimo de observações por folha igual a 20, utilizando as três primeiras variáveis dos dados.
### Análise de Desempenho por ccp_alpha:

* Diferentes valores de ccp_alpha são explorados para treinar múltiplas árvores de decisão.
* A acurácia é calculada para cada árvore nos conjuntos de treinamento e validação.
* Um gráfico visualiza a relação entre ccp_alpha e a acurácia.
### Avaliação na Base de Teste:

* Os dados de teste são carregados e pré-processados.
* A acurácia da melhor árvore é calculada na base de teste.
### Resultados e Insights:

* O resultado final inclui a impressão da melhor árvore, melhor ccp_alpha e melhor acurácia na base de teste.
* Insights e sugestões são fornecidos para aprimorar a análise.
### Execução do Código
* Certifique-se de ter um ambiente Python configurado.
* Instale as bibliotecas necessárias executando pip install -r requirements.txt.
* Execute o notebook Decision_Tree_Analysis.ipynb.
### Observações Adicionais
O código foi projetado para análise de dados específicos. Adapte-o conforme necessário para diferentes conjuntos de dados.
Experimente ajustar outros parâmetros e explorar mais valores de ccp_alpha para otimizar o desempenho do modelo.
Sinta-se à vontade para contribuir, relatar problemas ou fornecer sugestões para aprimorar este projeto!
### Obs.:
Os arquivos x_test.txt e x_train.txt são muito grandes para o github o download se encontra nos links abaixo:

Sua primeira atividade é carregar a base.

Ela está disponível neste link: 
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

dados 
https://archive.ics.uci.edu/ml/machine-learning-databases/00240/

dataset.names 
https://archive.ics.uci.edu/ml/machine-learning-databases/00240/UCI%20HAR%20Dataset.names

UCI HAR Dataset.zip 
https://archive.ics.uci.edu/ml/machine-learning-databases/00240/UCI%20HAR%20Dataset.zip




