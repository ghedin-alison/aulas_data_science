# Classificação II

## Matriz de confusão
 - Cruzar diferenças entre acertos e erros do modelo.
 - Falsos positivos, Falsos negativos
 
## Generalização versus Super ajuste versus sub ajuste
 - O objetivo de todo classificador é criar modelos genéricos
 - O modelo super ajustado funciona bem com dados de treino. Mas desempenho pobre em dados de teste ou de produção
 - O modelo sub ajustado não consegue boas taxas de previsão. Ele não foi capaz de capturar as características do negócio para o modelo.


### Causas do super ou sub ajuste
 - Dados não representativos
 - Dados não significativos(poucos)
 - Forma de treinamento
 - Classe rara
 - Modelo incorreto


#### Problema da classe rara
 - Transaçoes de fraude: a fraude é uma classe rara
 - O modelo pode ter dificuldade de aprender uma classe rara
 - Solução: estratiificação
 
 
### Como melhorar um modelo?
 - Testando diferentes algoritmos
 - Parametrizando algoritmos(hiper parametros)
 - Selecionando e tratando dados
 - Seleção/Engenharia de atributos
 
 ![metricas](./metricas.png)
 
##### Onde:
 - VP(verdadeiros positivos)
 - VN(verdadeiros negativos)
 - FP(Falsos positivos)
 - FN(Falsos negativos)
 
 
 
 
 
 