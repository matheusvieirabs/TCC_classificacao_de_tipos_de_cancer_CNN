# TCC_classificacao_de_tipos_de_cancer_CNN

Repositório com os códigos de implementação dos modelos VGG16, Xception e MCTC (este proposto por mim) para trabalho de conclusão de curso para graduação no curso de Engenharia Eletrônica da UFPE. Neste trabalho, foi feito um estudo de caso da aplicação de redes neurais convolucionais na classificação de tipos de câncer de pele.

As lesões selecionadas para classificação foram: Carcinoma Basocelular, Queratose Seborreica, Nevo Benigno e Melanoma.
As imagens foram obtidas a partir do repositório ISIC.

O modelo proposto por mim, o MCTC, é um modelo que faz uso da técnica de Transfer Learning para extração de características das imagens. A base de extração de características utilizada foi a base do modelo InceptionV3, tendo seus pesos obtidos a partir da base ImageNet.

O modelo que apresentou melhor performance entre todos os modelos foi o MCTC, alcançando 85% de acurácia e erro de 0,47. O modelo VGG16 alcançou como melhor resultado a acurácia de 84% e erro de 0,48, enquanto que o melhor resultado para o modelo Xception foi de 84% e erro de 0,59.
