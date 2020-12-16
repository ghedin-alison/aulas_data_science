# Classificação

- Queremos descobrir ou descrever a classe de um fato
- Normalmente a classe em uma relação está representada em um atributo especial, posicionado como último atributo da relação



## Aprendizado de Máquina


### Algoritmo I: calcular o aproveitamento do papel para uma gráfica
### Algoritmo II: prever se a pessoa será boa ou má pagadora de um empréstimo

| Gráfica | Crédito |
| ------- | ------- |
| Baseado em entrada: Dados atuais | Baseado em dados Históricos |
| Algoritmo puro | Algoritmo + Modelo |
| 100% performance | Não se espera 100% |
| Performance constante | Performance varia |
| Atende qualquer negócio | Adequa-se ao negócio |
| Não precisa aprender | Precisa aprender e reaprender |


## Modelo
 - Treinamento: fornecer condições para que aprenda as caracteristicas de negócio
  - Teste: testa se aprendeu
  
#### Método Hold out: 70% treinamento, 30% teste  

#### Método Validação Cruzada(Cross Validation): treinos em partições de 10%, 10% teste. Alternando a partição usada para testar o modelo.Verifica qual o melhor modelo, e o coloca em produção.