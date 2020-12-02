# Resíduos

#### Valores acima da linha de regressão possuem residuo positivo

#### Valores abaixo da linha de regressão possuem residuo negativo

#### Valores ajustados, são pontos imaginários traçados na linha de regressão

#### Residuos é a diferença entre o valor no ponto e o valor ajustado na linha

### Cálculo e gráfico de residuos no Jupyter
 - import da biblioteca: `from yellowbrick.regressor import ResidualsPlot`

**visualizador = ResidualsPlot(modelo)**

**visualizador.fit(x, y)**

**visualizador.poof()**