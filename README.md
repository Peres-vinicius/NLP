# LINGUAGEM DE PROCESSAMENTO NATURAL

## A ideia central do projeto é estudar sobre NLP. Buscando analisar sentimentos em textos. Desta forma, o projeto foi dividido em 3° etapas:

### 1° ETAPA:
* COLETA DOS DADOS DO TWITTER:
- Para essa etapa, foi criado um bot para extrair tweets pela API do twitter.
- Foi utilizado a biblioteca tweepy, onde cria a conexão com a API de forma simples e fácil.
- A extração dos dados é facilmente customizada, podendo alterar a query (palavra a ser buscada nos tweets) e tempo de coleta.
- Os dados coletados foram referentes à guerra que está acontecendo neste momento (02/2022).
- Após isso, é inserido em um banco de dados e retornando um DataFrame. Para mais explicações tem um repositório próprio dele.


### 2° ETAPA:
* TREINAMENTO DO MODELO:
- Nesta etapa, foi feito o treinamento do modelo (1° versão). A base de dados utilizadas para treinamento foi extraída do kaggle (https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp)
- Os dois algoritmos usados na primeira versão, foram o naive bayes e o SVM. Tendo bons resultados. Além de ser utilizado a validação cruzada.

### 3° ETAPA:
* USANDO OS DADOS COLETADOS DO TWITTER
- Aqui, após gerar um arquivo csv na 1° etapa, os dados foram tratados e submetidos ao modelo treinado. Após isso, foi adicionado o resultado ao arquivo csv e html, para melhor visualizar.


* Para a próxima versão do algoritmo, será testado novos algoritmos de machine learning e de deep learning buscando otimizar os resultados. Além de utilizar mais dados para o treinamento. Buscando uma forma de melhorar à análise de sentimentos.
