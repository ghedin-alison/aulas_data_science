# Agrupamentos

- Tarefas não supervisionadas
- Não existem classes
- Objetivo é criar grupos a partir de atributos(características) das instâncias

## Tipos:

### Agrupamento Completo
Cada elemento é adicionado em um único grupo

### Agrupamento Parcial
Cada instância pode pertencer a mais de um grupo

### Modelo Difuso
Cada elemento pertence a um grupo segundo uma probabilidade

### Modelo Hierárquico
Permite que o grupo tenha subgrupos


#### Agrupadores podem agrupar todos os elementos ou podem deixar elementos sem agrupar(gerar ruído).

## K-means e K-medoid
São os agrupadores mais simples e bastante utilizados
 - Simples
 - Baseado em protótipo
 - Encontra um número de grupos definido pelo usuário
 - Agrupa todos os objetos(não gera ruídos)
 - Definir os centróides é uma etapa fundamental
 - Distância Euclidiana

### K-means
 - Protótipo é um centróide: média de grupo de pontos. Quase nunca é um ponto real de dados.

### K-medoid
 - Protótipo baseado em medoid: ponto mais representativo. É um ponto real de dados.


### Problemas de K-means e K-medoid
 - Dificuldade para detectar grupos naturais, não esféricas, de tamanho ou densidades muito diferentes.
 - Restrito a dados que exista uma noção de centro
 - Pode ser melhorado escolhendo os centros(uso de seeds)
 
 
## DBSCAN
 - Baseado em densidade
 - Menos afetado por ruído
 - Número de grupos definido automaticamente
 - Pontos de baixa densidade são definidos com ruído e não agrupados
 - A densidade é baseada no raio especificado. Um ponto pode estar no interior, no limite, ou sem classificação(ruído)
 - Não é bom para grupos cuja densidade varia muito.
 
## Hierárquico

### Aglomerativa
 - Começa com pontos em grupos individuais e cada etapa funde os pares mais próximos. Requer uma noção de proximidade. Mais comuns.
 
### Divisiva
 - Começa incluindo todos, e a cada etapa divide até que reste apenas grupos únicos.

#### Dendograma é a representação gráfica do cluster hierárquico
 