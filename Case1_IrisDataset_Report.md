# Case 1 - Iris Dataset
[Notebook de analise - Em breve](x)

## Base de Dados
A base de dados Iris possui cinco variáveis (colunas) sobre flores do gênero Iris e contém 150 observações (linhas). Quanto às variáveis, são elas: 
uma categórica, identificando a variedade ou espécie da flor e quatro numéricas, informando a largura e o comprimento da sépala e da pétala.
A imagem abaixo indica a diferença entre os termos, caso você não soubesse — como 85% das pessoas.

![Sepal_Petal](https://www.sakurai.dev.br/assets/images/posts/2018-10-17-classificacao-iris-03.png = 512x)

## Métricas
As variáveis numéricas apresentam os valores mínimos e máximos e as métricas de média, mediana e moda como a seguir:
| variety    |   sepal.length |   sepal.width |   petal.length |   petal.width |
|:-----------|---------------:|--------------:|---------------:|--------------:|
| Setosa     |           5.01 |          3.43 |           1.46 |          0.25 |
| Versicolor |           5.94 |          2.77 |           4.26 |          1.33 |
| Virginica  |           6.59 |          2.97 |           5.55 |          2.03 |

	
Já agrupando a variável categórica, verificamos que a distribuição de linha está balanceada entre espécies, isto é, todas possuem a mesma quantidade de observações.
| variety | Frequência Absoluta | Frequência Percentual (%) |
| :--- | :---: | :---: |
| **Setosa** | 50 | 33.33% |
| **Versicolor** | 50 | 33.33% |
| **Virginica** | 50 | 33.33% |

	
## Gráfico de Radar
Avançando para os gráficos, o de radar nos permite comparar características entre as espécies. Inicialmente comparamos a média de comprimento e largura entre elas.
![Fig 1](https://drive.google.com/file/d/1tF8-mF95WLroam2LRaaXfiWuFlPz_Pl9/view?usp=sharing)
