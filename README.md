# RedeProfundaParaMnist
Rede Neural Profunda utilizando o tensorflow para classificar o dataset Mnist

A partir do tutorial fornecido pelo tensorflow foi possível implementar uma rede neural profunda (neste exemplo apenas duas camadas e uma totalmente conectada) para realizar o aprendizado nos dados do Mnist e medir a acurácia obtida pela rede no final do treinamento e teste.
O primeiro resultado mostrado abaixo refere-se a rede modificada, com os parâmetros alterados conforme o exercício e executada sem a camada totalmente conectada. A segunda Parte refere-se aos resultados da rede completa apresentada no tutorial, assim pode ser notado e comparar a acurácia de ambas as redes e tirar algumas conclusões.

Conforme pode ser apreciado nos resultados abaixo a rede completa apresentou uma acurácia de 99%, o que era esperado conforme o tutorial informa, após a alteração dos parâmetros e deixando a rede mais simples obteve-se uma acurácia de 98%. Uma observação importante foi que
a rede sem a camada totalmente conectada obteve um melhor tempo de execução por ter menos pesos a serem atualizados, em contra partida para alguns passos no treino obteve uma acurácia parcial relativamente baixa, levando alguns steps a mais até consegui manter uma média apropriada. 

A rede completa a partir da segunda amostra de step obteve um valor de 90% e alguns passo seguintes melhorou seu aprendizado obtendo o valor da média e o mantendo durante todo o treino, mostrando uma certa estabilidade.

O resultados podem ser visto no arquivo Resultados.
