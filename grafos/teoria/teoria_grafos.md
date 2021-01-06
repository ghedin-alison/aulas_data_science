# Grafos

## Aplicações:
 - Conectar pessoas e analisar suas relações
 - Combate ao terrorismo
 - Colaboração entre equipes
 - Analisar redes de comunicação
 - Achar rotas
 - Tráfego de redes
 - Prever disseminação de doenças
 - Lingustica e processamento de linguagem natural
 - Estudo de moléculas
 - Análise de redes sociais:
  - Recrutar e reter talentos
  - Monitorar a gestão de riscos corporativos
  - Monitorar e melhorar a percepção da marca
  - Monitorar e melhorar a satisfação de clientes
  - Acompanhar concorrentes
  - Buscar novas oportunidades de negócios
  - Estabelecer canais de relacinamento com clientes


## Definição
### Grafos são pontos(vértices/nodes(V)) com ligações(Arestas/edges/links(E))
 - Grafos nulos são grafos sem arestas(conexões)
 - Vértices e arestas podem possuir propriedades/características
 - Grafos podem ser direcionados e não direcionados
 - Quando as arestas tem pesos, chamamos de grafos ponderados
 - n = número de vértices, m = número de arestas
 
### Adjacência e Incidência
 - Adjacência - Vértices ligados por uma aresta É um conceito para vértices
 - Incidência - Aresta ligada por vértices. É um conceito para arestas
 
### Vizinhança
 - Vizinhança aberta - Conjunto de vértices adjacentes
 - Vizinhança fechada - Conjunto de vértices adjacentes, mais o próprio vértice


## **Grau do vértice**
 - É medido pela incidência
 - Grau zero => vértice isolado
 - Grau um => pendente
 - Grau minimo => vértice com menor incidência
 - Grau máximo => vértice com maior incidência
 - Grau do vértice direcionado varia com grau de entrada e grau de saída
 
### Laço
 - O vértice é ligado através de uma aresta a ele mesmo

### Arestas paralelas
 - Vértices são ligados através de duas arestas
 
 
## Multigrafado versus Simples
 - Simples: recebe uma única aresta
 - Multigrafado: Vértice que recebe mais de uma aresta
 
## Isomorfismo
 - É uma propriedade que mostra que existe uma equivalência na estrutura de grafos entre vértices e arestas. 
 
## Grafo Desconexo
 - Fazem parte do mesmo grafo, mas por algum motivo estão desconectados
 
## Grafo Conexo
 - Todo conjunto de vértices é ligado por uma aresta
 
## Ciclo
 - É um grafo em que todo o vértice tem grau 2

## Caminho(Path)
- Não repete nó. A não ser o primeiro.

## Tamanho de um Grafo
 - Se dá pelo número total de vértices.
 
## Grafo ponderado: Força
 - Mede a força da conexão entre vértices e arestas
 
## Acessibilidade
 - Um nó é acessível se houver um caminho até ele

## Centralidade
 - Mede a importância do nó. Quanto mais conectado, mais centralizado ele é. As vezes um ó não tão centralizado pode ser mais importante devido as ligações que ele faz.

## Coesão
 - Mede quantos nós se desligados descontectam a rede
 
## Densidade
 - é o total de conexões possiveis pelo numero de conexões existentes
 
## Grafo sem ciclos
 - Conhecido como árvore. Normalmente tem um único caminho

## Matriz de distâncias
 - Diâmetro de um grafo: distância máxima entre dois vértices.