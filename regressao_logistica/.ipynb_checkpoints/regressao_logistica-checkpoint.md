# Regressão Logística

### Candidatura x Gastos
 - _Quanto mais o postulante a um cargo legislativo arrecada, maior a chande de ele conseguir o que quer_
      Fonte: "O Estadão"
 - Nesse caso nossa variável dependente é uma boolena(eleito ou não)   
 - Graficamente o que liga esses dois estados(sim ou não) é uma sigmóide
 - Semelhante a regressão linear, porém a variável de resposta é binária: sucesso ou fracasso
 - O sucesso ou fracasso é representado através da probabilidade
 - Também pode ser simples ou múltipla
 
#### Regressão linear 
 $ y = b0 + b1 * x$
#### Probabilidade 
 $ p = 1 / (1 + e^(-y)) $
#### Regressão logistica 
 $ ln |p / 1- p| = b0 + b1*x $ 
 
##### No Jupiter:  
```python 
    def model(x):
        return 1 / (1 + np.exp(-x))
```


### Valores abaixo de 0,5 são classificados como fracesso, acima, sucesso
 