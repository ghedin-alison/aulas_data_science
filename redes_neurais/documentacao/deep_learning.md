# Deep Learning
##### Redes neurais profundas: com muitas camadas


## Arquiteturas de redes neurais profundas
 - Redes neurais convolucionais
 - Redes neurais recorrentes
 - Self organizing maps
 - Boltzmann Machines
 - Autoencoders


### Redes neurais convolucionais
 - Revolucionaram reconhecimento de imagem
 - É uma série de etapas de transformação da imagem antes da imagem entrar em uma rede neural
 - Ao invés de trabalhar com pixels, busca destacar características da imagem, criando filtros(filter maps)
 - Pooling, redução de dimensionalidades destacando caracteristicas importantes
 - Flatering, transforma em vetor para processar pela rede neural
 
### Redes neurais recorrentes
 - Auto-regressão. Relação entre os dados, ordem de dependência
 - Tem a capacidade de manter conexão entre os dados
 - Ótima pra prever dados de séries temporais
 - Outros processos que requerem sequencia, por exemplo a fala
 - Imagem que tem uma ação. Descrever a ação da imagem.
 - Performance muito boa.
 - Treinamento de reconhecimento de fala, fraudes, 
 - LSTM - long short term memory
 
### Self organizing maps
 - O mapa vai se organizando em locais onde tem maior densidade


### Boltzmann machines
 - Não tem camada de saída
 - Tudo é conectado com tudo
 - Não tem direção
 - Não espera dados, gera estados de um sistema
 - Sistema de recomendação, gerar dados para sistemas desbalanceados, ou sistemas com poucos dados de uma determinada classe
 
###  Autoencoders
 - São direcionados
 - Codifica a si mesmo
 - Saídas semelhantes a entrada
 - Rede não supervisionada ou auto-supervisionada
 - Utilizados para sistemas de recomendação bastante poderosos

 
