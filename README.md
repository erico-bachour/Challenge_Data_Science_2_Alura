# Challenge Data Science 2 Alura
Challenge de Data Science promovido pela Alura Escola de Tecnologia.

A partir de uma base de dados de imóveis fornecida por uma imobiliária chamada Insight Places, o objetivo do projeto é elaborar um modelo de regressão para precificar imóveis e um recomendador de imóveis.

Todos os notebooks foram construidos usando o Google Colaboratory, ferramenta de análise de dados e machine learning do Google. No que se refere ao processamente e análise da base de dados, foi utilizado o Spark, mais especificamente a interface PySpark, que permite que utilizemos a plataforma Apache Spark a partir de comandos em linguagem de programação Python.

O Challenge foi dividdo em três etapas. Na primeira, recebemos a base de dados crua e como tarefa tratá-la de forma a filtrar dados de colunas que não interessavam, como dados de alugueis, por exemplo. Na segunda etapa continuamos a tratar nossa base de dados, expandindo colunas que estavam organizadas em listas em colunas de valores booleanos, por exemplo, e num segundo momento, finalizada a preparação, criamos modelos de regressão para auxiliar a Insight Places a precificar seus imóveis. Na etapa final, a tarefa passou a ser de agrupamento. Usando as ferramentas de Clustering, dividimos os imóveis em grupos com características similares e desenvolvemos um recomendador que, a partir do identificador de um imóvel, sugere uma lista de imóveis do mesmo cluster.
