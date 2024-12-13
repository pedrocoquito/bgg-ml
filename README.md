# **Previsão de Nota em Jogos de Tabuleiro**

## **Introdução**

O objetivo deste projeto é prever a nota de jogos de tabuleiro utilizando técnicas de machine learning.  
O dataset utilizado contém informações como ano de publicação, número de jogadores, tempo de jogo e complexidade dos jogos, sendo essas variáveis as principais determinantes da nota média.

### **Descrição do Dataset**

O dataset utilizado neste projeto foi retirado do [BoardGameGeek Dataset](https://www.kaggle.com/datasets/melissamonfared/board-games). Ele inclui as seguintes colunas:

| **Coluna**                                             | **Descrição**                                                                                   | **Tipo de dado**    |
|--------------------------------------------------------|---------------------------------------------------------------------------------------------------|------------------|
| `ID`                                                   | Identificação do jogo                                                                          | Integer          |
| `Name`                                                 | Nome do jogo                                                                            | String           |
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

---

### **Estrutura do Projeto**

Este trabalho segue os seguintes passos:

1. **Carregamento e preparação dos dados**:  
   Inclui a limpeza e manipulação inicial do dataset para remover valores ausentes e selecionar as colunas mais relevantes.

2. **Análise exploratória (EDA)**:  
   Análise visual e estatística dos dados para entender distribuições e relações entre as variáveis.

3. **Treinamento inicial e avaliação de modelos**:  
   Comparação inicial entre diferentes modelos de machine learning, como Regressão Linear e Random Forest.

4. **Otimização de hiperparâmetros**:  
   Aplicação de técnicas como RandomizedSearchCV para ajustar os hiperparâmetros e melhorar o desempenho do modelo.

5. **Resultados finais e análise**:  
   Apresentação dos resultados, análise das variáveis mais importantes e comparações entre os modelos utilizados.

---

### **Acesso ao Código**

O notebook com todo o código e análises realizadas pode ser acessado no link a seguir:  
[**Google Colab Notebook**](https://colab.research.google.com/drive/1kYwNefpw3JoILxSQuXmMu6R4BxcpuafX)
