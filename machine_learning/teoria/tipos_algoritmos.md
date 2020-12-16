# Tipos de Algoritmos

## Árvores de Decisão
 - Nodo raiz
 - Nodos Internos
 - Nodos Terminais(classes aparecem aqui!)
 - Algoritmo de Partição: grau de pureza


## Regras
 - São semelhantes as arvores de decisão, porém são estruturas do tipo 'IF'.
 - Podem ter vários tipos de ínicio
 - Podem fazer várias avaliações ao mesmo tempo.
 
## Naive Bayes
 - Baseado na teoria das probabilidades e que supõe que os atributos vão influenciar a classe de forma independente

## Redes Bayesianas
- Uma rede Bayesiana pode mostrar eventual dependência entre os atributos através da probabilidade condicional

## Redes Neurais Artificiais e aprendizado profundo
 - Terá uma seção interia a respeito dess item
 
## Máquina de Vetor e suporte
 - Cria vetores de suportte otimizados que são utilizados pra criar uma divisão na classificação dos dados

## Métodos de Grupos
 - Constroem grupos de classificadores
 - Treina vários classificadores com parametros diferentes
 - Utiliza o que tem melhor performance
 - Exemplos: Florestas aleatórias(induzem vários classificadores de árvore de decisão) e Boosting
 

## Aprendizado baseado em Instância
 - Classificador de vizinho mais próximo(Nearest-neighbor)
 - Não cria um modelo baseado em informações anteriores.
 - Busca semelhança entre dados historicos e aquele que se quer classificar, em tempo real.
 - Utiliza a distância Euclidiana para fazer a classificação.
 - Tem um custo maior no processo de classificação, pq precisa carregar os dados. Mas não tem etapa prévia de geração de modelo.
 
 
## Seleção de atributos
 - Avaliar com quantos atributos temos um modelo com maior taxa de acerto.
 - Nem sempre mais atributos significam maior taxa de acerto. E também podemos ter piora na performance.
 - Podemos utilizar algoritmos que nos ajudam a escolher quais são os atributos mais importantes e nos trazem modelo com melhor performance.
 
### Maldição da dimensionalidade
 - A inclusão de muitos atributos em um modelo, degradam sua performance.
 - Se existem muitos atributos, como saber quais são mais relevantes para o modelo?
 - A seleção de atributos pode ser feita manualmente ou através de algoritmos.
 


