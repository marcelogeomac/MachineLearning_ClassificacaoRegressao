Classificação e predição de cobertura de solo urbano.
Dataset contendo dados de treino e teste para uso academico de algorítimos de Machine Learning no intuito de classificar cobertura de solo urbano a partir de dados obitidos em imagem de alta resolução.

Informações espectrais em várias escalas, tamanhos, forma e textura.

Há um baixo numero de amostras de treinamento para cada classe (14 - 30) e um alto número de variáveis de classificação (148) sendo assim um ótimo conjunto de dados para testar métodos de seleção de recursos.

Objetivo
Este projeto tem como objetivo aplicar algoritmos de machine learning para classificação e predição de coberturas de solo a partir de imagem: árvores, grama, solo, concreto, asfalto, edifícios, carros, piscinas e sombras.

Especificação Técnica
Dataset: Para desenvolvimento desse projeto, será utilizado o dataset encontrado no sítio (https://archive.ics.uci.edu/) denominado Urban Land Cover Data set, disponível em: https://archive.ics.uci.edu/ml/machine-learning-databases/00295/.

Formato: A base de dados está em formato CSV, estando divivida em dois domínios (testing.csv e training.csv), colunas classe(ou categoria), dados numéricos e texto.

Métodos de Pŕe-processamento: Necessário importar dataset no AWS Glue Studio para avaliação dos dados e utilização de ferramentas de transformação quando for o caso.

Algoritmos Avaliados: Serão avaliados os algoritmos de Classificação, Regressão Logística utilizando método supervisionado.

Bibliografia
Mãos à Obra: Aprendizado de Máquina com Scikit-Learning & TensorFlow, Géron, Aurélio - Editora Alta Books Youtube Curso Deep Learning - UTFPR - português Prº Dalcimar Casanova
