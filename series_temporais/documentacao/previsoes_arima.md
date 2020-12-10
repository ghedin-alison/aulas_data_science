# Previsões com Arima

 - **Robusto**: Pode ser usado praticamente em qualquer tipo de ST
 - **Requer dados estacionários(flutuam numa mesma média/variância)**: pode ser transformado usando diferenciação(remove tendências)
 
 
## O ARIMA é composto por 3 elementos:
 - **AR**: Autoregressivo, avalia a relação entre os períodos(lags), autocorrelação
 - **I**: Integrated, aplica a diferenciação se necessário
 - **MA**: Moving Average, avalia erros entre períodos e extrai erros
 
 
 
### **AR** **I** **MA** 
**AR** -> p: ordem da parte autoregressiva
**I** -> d: grau de diferenciação(d = 0 série estacionária)
**MA** -> p: ordem da média móvel


### ARIMA sazonal
 - Inclui, além(p, q, d), os elementos(P,Q,D)
 
### Como saber qual o melhor modelo?

Existem algumas métricas:
 - AIC/AICc(Akaike Information Criteria)
 - BIC(Baysian Information Criteria)
 
Objetivo é minimizar valores 
 
 

### Como definir o parâmetros para p,q,d?

 - Pode ser extremamente difícil, mesmo para experientes
 - Não é um processo linear
 - Nem sempre o modelo intuído é o melhor
 
#### Como fazer?
 - Buscar minimizar AICc e/ou BIC
 - Testar todas as combinações prováveis?

##### Uma opção é utilizar o método auto.arima()
 - Testa diferentes combinações de p, d e r;
 - Extremamente flexível
 - Mesmo intuindo um modelo, você pode usá-lo para confirmar sua parametrização
 