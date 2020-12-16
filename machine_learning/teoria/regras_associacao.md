# Regras de Associação
 - Buscam a relação entre elementos.
 
## Conceitos
#### A => B
##### Suporte
 - número de transações que contém todos os itens da transação.
 - Não adianta os produtos aparecerem com frequência juntos, se raramente são comprados

##### Confiança 
 - indica a proporção de vezes que, em uma transação contendo o elemento A, também tem B.
 - Não adianta um produto ser muito comprado, se dificilmente eles aparecem juntos
 
 
##### Lift
 - O quanto aumenta a frequência de B, com a ocorrência de A.
 - Dividimos a confiança pelo suporte


- Exemplos de regras de associação: compra casada e relação de sintomas com determinada doença.
 
#### Quando se minera dados de associação, deve ser minerado através de métricas(Suporte, confiança, lift) 


## Algoritmos de associação

### Apriori e FP-Grow
 - Apriori e FP-Grow são os algoritmos mais comuns na mineração de regras de associação.
 - Apriori é baseado no princípio de que se um conjunto de itens é frequente, um subconjunto destes itens também será frequente. O princípio contrário também é valido.
 - FP-Grow induz árvores, e busca sobreposição destas árvores, onde os itens são frequentes. 