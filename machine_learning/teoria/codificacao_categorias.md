# Codificação de Categorias(categorical encoding)
 - Algoritmos entendem números
 - Categorical encoding é o processo de transformar categorias em números
 - Duas formas:
  - Label encoding
   - cada categoria recebe um número;
   - problema é que o algoritmo pode interpretar dados como uma ordem de grandeza 
  - One-hot encoding
   - **Cada categoria é transformada em outro atributo**: dummy variable
   - Um valor binário informa a ocorrência

### Dummy variable trap
 - O valor dos atributos se torna altamente previsivel
 - Resultado, correlação entre as variáveis independentes: multicolinearidade
 - Solução: Excluir um dos atributos. Normalmente a primeira colunca do one-hot encoding
 
### Qual usar?

| Label encoding | One-hot encoding |
| -------------- | ---------------- |
| Há ordem(prog. Junior, pleno, senior) | Não há ordem |
| Grande número de categorias, não dá pra usar one-hot encoding | Número de categorias é pequeno |

