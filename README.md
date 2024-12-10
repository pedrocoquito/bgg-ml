# Previsão de Nota em Jogos de Tabuleiro

O objetivo deste projeto é prever a nota de jogos de tabuleiro utilizando técnicas de machine learning. 
O dataset utilizado contém informações como ano de publicação, número de jogadores, tempo de jogo e complexidade dos jogos, sendo essas variáveis as principais determinantes da nota média.

O dataset utilizado se encontra no link: [BoardGameGeek Dataset](https://www.kaggle.com/datasets/melissamonfared/board-games). Este inclui as colunas:

| **Column**                                             | **Description**                                                                                   | **Data Type**    |
|--------------------------------------------------------|---------------------------------------------------------------------------------------------------|------------------|
| `ID`                                                   | Identificação do jogo                                                                          | Integer          |
| `Name`                                                 | Nome do Jogo                                                                            | String           |
| `Year Published`                                       | Ano de publicação                                                            | Integer          |
| `Min Players`                                          | Número mínimo de jogadores                                                | Integer          |
| `Max Players`                                          | Número máximo de jogadores                                                | Integer          |
| `Play Time`                                            | Duração da partida                                                                   | Integer          |
| `Min Age`                                              | Idade mínima recomendada                                                               | Integer          |
| `Users Rated`                                          | Número de jogadores que avaliaram o jogo                                                           | Integer          |
| `Rating Average`                                       | Nota média do jogo                                                                  | Float            |
| `BGG Rank`                                             | Rank no site BoardGameGeek                                                                 | Integer          |
| `Complexity Average`                                   | Complexidade do jogo                                                             | Float            |
| `Owned Users`                                          | Número de usuários que possuem o jogo                                                      | Integer          |
| `Mechanics`                                            | Mecânicas encontradas no jogo                                                            | String           |
| `Domains`                                              | Domínios e categorias do jogo                                                    | String           |


Neste trabalho, serão implementados os seguintes passos:

- Carregamento e preparação dos dados.
- Análise exploratória (EDA).
- Treinamento inicial e avaliação de modelos.
- Otimização de hiperparâmetros.
- Resultados finais e análise.

O notebook para acessar ao código e análises está no link: [notebook](https://colab.research.google.com/drive/1kYwNefpw3JoILxSQuXmMu6R4BxcpuafX#scrollTo=NUlHAOAxZ5sm)
