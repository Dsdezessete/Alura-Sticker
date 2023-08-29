# 👾 AluraStickers

#### Este é um programa em Java que busca os dados de séries de TV populares do site IMDB e exibe informações relevantes para o usuário, como título, classificação e poster da série.

## 👨🏻‍💻 Funcionamento do programa:

- O programa faz uma requisição HTTP para a URL "https://raw.githubusercontent.com/alura-cursos/imersao-java-2-api/main/MostPopularTVs.json" e obtém uma resposta no formato JSON contendo informações sobre as séries mais populares do momento. Em seguida, o programa extrai os dados relevantes do JSON (título, poster e classificação) e os exibe na tela para o usuário. Além disso, o programa também converte a classificação da série em um número de estrelas e exibe as estrelas correspondentes na tela.

- Como executar o programa:
    Para executar o programa, é necessário ter o Java instalado em sua máquina. Em seguida, basta compilar o arquivo AluraStickers.java e executar o arquivo resultante.

- Dependências:
    O programa utiliza a biblioteca java.net.http para fazer a requisição HTTP e a biblioteca com.google.gson para fazer o parsing do JSON. É necessário ter essas bibliotecas instaladas em sua máquina para compilar e executar o programa.