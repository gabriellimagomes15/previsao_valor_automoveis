# Previsão de valores de automóveis
Projeto de coleta de dados (web scraping) de site de vendas de automóveis e treinamento de modelo de previsão de valores de automóveis.

Este projeto foi desenvolvido no **workshop disponível em: https://www.youtube.com/watch?v=pZT9pq6lMh4**

**Etapas do Projeto**
* Coleta via "raspagem de dados" e estruturamento dos dados em arquivos CSV;
* Preparação dos dados;
* Análise exploratória da base;
* Treinamento e validação de modelos de regressão;
* Scprit executável em *notebook* e *.py* para fazer previsões;

Todo o projeto foi desenvolvido utilizando jupyter notebook no colab.

# Pastas e Códigos
### dados_olx/
Pasta para armazenar dados coletados no processo de web scraping.

### modelos/
Pasta para armazenar modelos treinados.

### 01_web_scraping.ipynb
Código que realiza a coleta de dados no site https://olx.com.br/autos-e-pecas/carros-vans-e-utilitarios?o=1

### 02_coleta_preparacao.ipynb
Código para realizar toda a preparação dos dados
* transformações
* normalizações
* criação de novas variáveis
* dentre outras.

### 03_analise_exploratoria.ipynb
Realiza toda análise necessária para desenvolver o algoritmo de ML.
- distribuição
- outlier
- frequências
- relações/correlações

### 04_modelagem.ipynb
Treinamento de algoritmos para regressão, validação das métricas dos algoritmos e modelo final salvo em **joblib**.

### 05_executar_modelo.ipynb
Código para executar as previsões de acordo com os dados de entrada.

### 05.1_funcoes_executar_modelo.ipynb
Funções utilizadas na execução da aplicação.

# Execução da aplicação
Você pode executar aplicação no **google colab** ou na sua *máquina local* utilizando **Anaconda** ou similare.
Para isso, faça o **download do repositório** e coloca no seu diretório. Você pode usar o modelo já treinado, para isso base abrir e rodar o código **05_executar_modelo.ipynb**. 
Mas você pode rodar todo o processo desde o início, coletando novos dados e treinando um novo modelo, assim, executando os código na sequência indicada acima.

