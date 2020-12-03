# Cálculos

**Correlação >> Inclinação >> Interceptação >> Previsão**

### Covariância
 - Grau de dependência, ou relação matemática, entre duas variáveis numéricas 
 - Utilizamos a Correlação de Pearson
 
     $r = cov(X, Y) / sqrt(var(x)*var(y))$  
      onde cov: covariação e var: variância

#### No Jupyter:
`correlacao = np.corrcoef(x, y)`
     
### Inclinação
 - $ m = r(Sy/Sx) $ , onde S: desvio padrão e r:correlação

#### No Jupyter:
 `modelo.coef_`

 
### Interceptação
- ponto onde a reta toca o eixo Y 
- $ b = y - mx $, onde y: média de y, x: média de x, m: inclinação

#### No Jupyter:
 `modelo.intercept_`

### Previsão 
- $ P = b + mv $ , onde b: interceptação , m: inclinação, v: variavel independente

#### No Jupyter:
`previsoes = modelo.predict(x)`
`modelo.predict([[22]])`


# Correlação não é Causa!!!!
 