# Case 1 - Iris Dataset
[Notebook de análise - Em breve](x)

## Base de Dados
A base de dados Iris possui cinco variáveis (colunas) sobre flores do gênero Iris e contém 150 observações (linhas). Quanto às variáveis, são elas: 
uma categórica, identificando a variedade ou espécie da flor e quatro numéricas, informando a largura e o comprimento da sépala e da pétala.
A imagem abaixo indica a diferença entre os termos, caso você não soubesse — como 85% das pessoas.

<img src="https://www.sakurai.dev.br/assets/images/posts/2018-10-17-classificacao-iris-03.png" alt="Sepal_Petal" width="300"/>
<!-- ![Sepal_Petal](https://www.sakurai.dev.br/assets/images/posts/2018-10-17-classificacao-iris-03.png)] -->

## Métricas
As variáveis numéricas apresentam os valores mínimos e máximos e as métricas de média, mediana e moda como a seguir:
| variety    |   sepal.length |   sepal.width |   petal.length |   petal.width |
|:-----------|---------------:|--------------:|---------------:|--------------:|
| Setosa     |           5.01 |          3.43 |           1.46 |          0.25 |
| Versicolor |           5.94 |          2.77 |           4.26 |          1.33 |
| Virginica  |           6.59 |          2.97 |           5.55 |          2.03 |

	
Já agrupando a variável categórica, verificamos que a distribuição de linhas está balanceada entre espécies, isto é, todas possuem a mesma quantidade de observações.
| variety | Frequência Absoluta | Frequência Percentual (%) |
| :--- | :---: | :---: |
| **Setosa** | 50 | 33.33% |
| **Versicolor** | 50 | 33.33% |
| **Virginica** | 50 | 33.33% |

	
## Gráfico de Radar
A visualização nos permite avançar na descrição da base, ao destacar os pontos relevantes. O gráfico de radar nos permite comparar características entre as espécies. Inicialmente, comparamos as médias de largura (width) e de comprimento (length) entre cada uma delas.
![Fig 1](https://github.com/GeorgiaRibeiro/DataAnalysisCases/blob/main/output_iris/fig_1.png?raw=true)


## Gráfico de Dispersão
O gráfico anterior oferecia uma visão geral das características, ao agrupar por espécie e considerar a média das medidas estudadas. Já a visualização seguinte, oferece uma visão individual de cada observação entre as demais. Com isso, identificamos comportamentos fora do padrão (os chamados _"outliers"_) e possíveis correlações.

... continua.
