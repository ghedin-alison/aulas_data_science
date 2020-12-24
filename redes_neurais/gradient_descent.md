# Gradient Descent

 - Loss Function / Cost Function: diferença entre a previsão e o valor real
  - Root Mean Square Error(independete de escala)
   - O desvio padrão da amostra da diferença entre o previsto e o teste
   - Isso ajuda na avaliação e correção dos pesos
   
   
## Ajustando os pesos
 - Learning Rate:  taxa de aprendizado
 - Como ajustar os pesos? Aumentar, diminuir? Em quanto?
 - Lembrando que podemos ter muitos pesos para ajustar.
 - O melhor valor para um peso é chamado de ótimo global.
 
## Gradient Descent
 - É uma técnica de otimização na busca dos melhores pesos.
 - Analisa o ângulo da nossa função de custo e através disso calcula os melhores pesos
 - Melhor utilizado em funcões de custo que tem formato convexo.
 
## Stochastic(inclui elementos de aleatoriedade - estocasticos) Gradient Descent
 - Os pesos são utilizados após cada linha, ganhando em perfromance no treinamento da rede neural
 - permite de forma otimizada bucasr configurações melhores para sua rede neural
 
 