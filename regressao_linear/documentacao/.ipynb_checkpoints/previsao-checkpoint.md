# Previsão

## Como prever?
- Previsão = Intersecção(x=0) + (inclinação * valor a prever)
- Equação da reta
`f(x) = mx + a`


## No Jupyter:
#### Cálculo manual
`velocidade = modelo.intercept_ + modelo.coef_ * 22`

22 é um valor aleatório de um exemplo

#### ou 

##### Previsão utilizando a função do sklearn

`modelo.predict([[22]])`
