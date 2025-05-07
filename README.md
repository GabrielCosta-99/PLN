# Análise de Sentimentos com Processamento de Linguagem Natural (PLN)

Este projeto aplica técnicas fundamentais de Processamento de Linguagem Natural (PLN) em Python para realizar a análise de sentimentos de textos em inglês. Utilizamos bibliotecas como `nltk` e `TextBlob` para pré-processar os dados e extrair informações de polaridade e subjetividade.

## Tecnologias utilizadas

- Python 3.x
- NLTK
- TextBlob

## Funcionalidades

- Limpeza e normalização de texto
- Tokenização em palavras
- Remoção de stopwords
- Análise de sentimento (polaridade e subjetividade)

## Como executar

1. Instale as dependências:

```bash
pip install nltk textblob
python -m textblob.download_corpora 
````
## Conclusão

Neste projeto, foram aplicadas técnicas essenciais de PLN: limpeza do texto, tokenização, remoção de stopwords e análise de sentimentos. A limpeza textual assegurou que apenas informações relevantes fossem mantidas, enquanto a tokenização permitiu o tratamento das palavras individualmente. A remoção de stopwords eliminou ruídos que poderiam comprometer os resultados.

Por fim, a análise de sentimentos com a biblioteca TextBlob demonstrou ser uma solução eficaz para identificar emoções em textos, fornecendo métricas de polaridade (positivo/negativo) e subjetividade (fato/opinião). Essas etapas são fundamentais em sistemas que interpretam linguagem humana, com aplicações práticas em diversas áreas como marketing, atendimento ao cliente, redes sociais, entre outras.
