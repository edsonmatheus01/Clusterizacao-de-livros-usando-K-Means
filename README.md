# Clusterização de livros usando K-means
Este é um projeto que utiliza o algoritmo K-means para realizar a clusterização de livros com base em suas características, como título e sinopse.


# Como utilizar
Clone o repositório para o seu computador
Certifique-se de ter as bibliotecas Pandas, Numpy, Matplotlib, Scikit-learn e NLTK instaladas em sua máquina
Abra o arquivo cluster_livros.py em seu editor de código
Rode o arquivo para obter a clusterização dos livros


# Dados utilizados
Os dados utilizados no clustering foram gerados manualmente e estão disponíveis no arquivo livros.csv. Cada livro é composto pelos seguintes atributos:
Título
Autor
Sinopse
Resultados
Os seis livros do arquivo "livros.csv" foram classificados em quatro clusters pelo algoritmo K-means. Os grupos em que cada livro foi classificado estão indicados na


# saída do algoritmo:
Cluster 0: Clean Code, Clean Architecture
Cluster 1: Refactoring, Design Patterns
Cluster 2: The Pragmatic Programmer
Cluster 3: Code Complete
O K-means classificou os livros com base nas características dos mesmos que foram usadas como entrada para o algoritmo. No caso do exemplo, as características foram extraídas do título e da sinopse de cada livro, que foram convertidas em uma representação numérica para serem usadas pelo K-means. A partir dessas características, o K-means calcula a distância entre cada livro e agrupa aqueles que são mais similares em um mesmo cluster.
