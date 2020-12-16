# Dimensionamento de características

- Processo de transformação de dados numéricos
- Variáveis em escalas diferentes 
 - Contribuem de forma desbalanceada para o modelo
 - Exemplo: Salário e Altura
- Gradient Descent converge mais rapidamente para o mínimo local 
 
 
## Principais técnicas de dimensionamento de características
 - Padronização(Z-Score)
 - Normalização(Min-Max)
 
### Padronização(Z-Score)
 - Dados aproximados da média(zero) e desvio padrão 1
 - Podem ser negativos
 - Não afeta outliers
 - Deve ser usado na maioria dos casos
 
 $Xp = (X - m) / o $ 
 
 
 ##### Ver aula de distribuição normal padrão
 
 
### Normalização(Min-Max)
 - Transforma para escala comum entre zero e um
 - Usado em processamento de imagens e RNA
 - Quando não sabemos a distribuição dos dados
 - Quando precisam ser positivos
 - Algoritmos não requerem dados normais
 - Remove outliers pois impõe limites
 
 $Xn = (X - Xmin)/(Xmax - Xmin)   $
 
 
 
#### Observações sobre dimensionamento de características
- Não vai necessariamente melhorar seu modelo
- Árvores de decisão não precisam de nenhum tipo
- Não se aplica a atributos categóricos transformados