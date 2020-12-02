# Correlação (R)

 - Mostra a força e a direção da relação entre variáveis
 - Pode ser um valor entre -1 e 1
 - A correlação de A ~ B é a mesma que B ~ A
 
`Quanto mais próximo das extremidade(1, -1(perfeita se igual)), mais forte é a correlação. Quanto mais proximo de zero, mais fraca(se igual, inexistente) `

### Gráfico com dados concentrados, indica correlação forte
### Gráfico com dados dispersos, indica correlação fraca


`Correlação se assemelha a coeficiente angular de uma reta.`

## Coeficiente de Determinação($R^2$)
 - Mostra o quanto o modelo consegue explicar os valores
 - Quanto maior, mais explicativo ele é
 - O restante da variabilidade está em variáveis não incluídas no modelo
 - Varia entre 0 e 1(sempre positivo)
 - Calcula-se com o quadrado do coeficiente de relação
 
 # Cálculo da correlação entre x e y no jupyter
   correlacao = np.corrcoef(x, y)
