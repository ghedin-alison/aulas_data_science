# Distribuição T de Student
   - utilizada para amostras pequenas n <= 30;
   - Quando não se conhece o desvio padrão
   - Tendencia de encontrat valores nas caudas
   - Se n>= 30, assemelha-se a distribuição normal
   - Grau de liberdade corresponde ao tamanho da a amostra menos 1(n - 1)
   
Pode ser usada para:
    - Calcular probabilidades
    - Calcular intervalos de confiança
    - Executar testes de hipotese
    
    
Como usar:
 - Calcula o valor de t.(n -1)
 - Consultamos a tabela de distribuição T.
 
 
 
   
## Teste de T de student
    - Teste de hipotese
    - Compara duas médias
    - Pré-requisistos:
        - Duas populações são independentes
        - Variável normalmente distribuida
        - Variância entre as duas variáveis é aproximada
    - H0: Não há diferença significativa
    
    
[Tabela T de student](http://www.ttable.org/)
##### Utilizar a tabela quando não tiver acesso ao python, a coluna da esquerda são os graus de liberdade. E com base no calculo de t,
##### verifica onde o valor de T se encaixa no cruzamento com graus de liberdade


`from scipy.stats import t
 t.cdf(1.5, 8)`
##### O valor 1.5 vem do calculo t = (X - x)/(S/sqrt(n), onde X = 80, x = 75, S = 10 e n = 9)
##### O valor 8 vem dos graus de liberdade que é (n - 1)           
 