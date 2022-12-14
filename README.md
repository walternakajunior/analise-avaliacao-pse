# GRÁFICOS DE DISPERSÃO – AVALIAÇÃO PSE<p>

Na confecção dos gráficos, para reduzir a possibilidade de vieses por conta da diferença de escolares avaliados em cada escola, foram utilizadas apenas as proporções das classificações avaliadas. Todos os gráficos apresentados foram feitos através da linguagem Python, com uso das bibliotecas <i>pandas</i>, <i>matplotlib</i>, <i>seaborn</i>, <i>scikit learn</i> e <i>scipy</i>.<br>
Primeiro foi analisada a correlação entre a porcentagem das avaliações com a renda per capita, vemos que as classificações que mais se correlacionam são as classificações <b>A</b> e <b>E</b>, com um índice de 0,3, representando que, apesar de fraca, há uma correlação entre a renda per capita do bairro e escolares avaliados com a classificação <b>A</b> ou <b>E</b>.<br>

### GRÁFICO DE CORRELAÇÃO ENTRE RENDA PER CAPITA E CLASSIFICAÇÃO<p>


Quando observada a proporção dos alunos avaliados com a classificação <b>A</b>, <b>B</b> ou <b>C</b>, essa correlação pode ser observada através do gráfico de regressão linear, com a linha de tendência apontando que escolas em bairros de renda per capita maiores, tendem a ter um percentual maior de escolares avaliados com classificação entre <b>A</b> e <b>C</b>.
Mesmo considerando que as unidades escolares podem receber alunos de outros bairros, que bairros com características opostas podem fazer limite entre si e mesmo apresentar características diferentes dentro do próprio bairro, no gráfico de dispersão com a separação pelos bairros, podemos observar a tendência de escolas do mesmo bairro ou em bairros com renda per capita parecida, estarem agrupados.<br>

### GRÁFICO DE REGRESSÃO LINEAR ENTRE RENDA PER CAPITA E CLASSIFICAÇÃO %A-C<p>


### GRÁFICO DE DISPERSÃO ENTRE RENDA PER CAPITA E CLASSIFICAÇÃO %A-C<p>


Quando utilizamos o algoritmo KMeans para agrupar escolas que possuem características similares, considerando o número de apenas 2 clusters, podemos observar uma separação clara entre as escolas em bairros com a renda per capita acima e abaixo de R$800,00.<br>

### GRÁFICO DE DISPERSÃO COM CLUSTERIZAÇÃO ENTRE RENDA PER CAPITA E CLASSIFICAÇÃO %A-C (ALGORITMO KMEANS)<p>
