# ML--transferLearning

O algoritmo de Transfer Learning é uma técnica que consiste em utilizar uma rede neural pré-treinada em um conjunto de dados de alta qualidade e aplicar essa rede em outro conjunto de dados semelhante. Isso permite que a rede pré-treinada transfira o conhecimento aprendido em um conjunto de dados para outro, acelerando significativamente o processo de treinamento e melhorando a precisão da rede final.

A rede neural utilizada neste projeto é a MobileNet V2, que é uma rede pré-treinada projetada para dispositivos móveis e de baixa potência. Essa rede é capaz de classificar imagens em milhares de categorias diferentes com alta precisão, e tem sido utilizada em diversos projetos de visão computacional.

No projeto de Transfer Learning com o Dataset de Gatos e Cachorros, a rede MobileNet V2 é adaptada para classificar imagens em apenas duas categorias: gatos e cachorros. Para isso, a camada de saída da rede é removida e substituída por uma nova camada de classificação com duas unidades, uma para cada categoria. Em seguida, a rede é treinada novamente utilizando o conjunto de dados de gatos e cachorros, utilizando a técnica de Transfer Learning.

Ao utilizar o Transfer Learning, a rede é capaz de aprender a classificar imagens de gatos e cachorros com alta precisão em um tempo muito menor do que seria necessário para treinar a rede a partir do zero. Isso torna a técnica de Transfer Learning uma ferramenta poderosa para diversos problemas de classificação de imagens em visão computacional.




## Execução

O código pode ser executado em um ambiente Python como o COLAB. Para executar o projeto, siga os seguintes passos:

1. Abra o ambiente COLAB em seu navegador.
2. Crie um novo notebook ou abra um existente.
3. Copie o código do arquivo "transfer_learning_gatos_cachorros.py".
4. Cole o código no notebook do COLAB.
5. Execute o código.

## Dataset

O dataset utilizado neste projeto contém imagens de gatos e cachorros. O dataset pode ser baixado por meio do seguinte link:

https://www.microsoft.com/en-us/download/details.aspx?id=54765

## Resultados

O modelo treinado com Transfer Learning foi capaz de atingir uma acurácia de 92% no dataset de validação.

## Referências

O código deste projeto foi baseado no seguinte notebook:

https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb

## Autora

Paula Flávia

## Licença

Este  projeto é distribuído sob a licença MIT.
