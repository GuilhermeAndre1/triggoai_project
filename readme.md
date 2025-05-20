# Documentação do Projeto - Dashboard de Vendas

## Introdução

Projeto criado para o teste técnico do programa treinee da triggo.ai utilizando o dataset Brazilian E-commerce Public Dataset by Olist, dataset esse que contém informações sobre mais de 100.000 pedidos de e-commerce no Brasil realizados entre 2016 e 2018.

## Ambiente
Python 3.12

# Instalação
1. Clone o repositório.

2. Crie um ambiente virtual (recomendado):

```
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
3. Instale as dependências
```
pip install -r requirements.txt
```
4. Baixe o Dataset

Baixe o dataset pelo Kaggle (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data?select=olist_customers_dataset.csv) e após extrair, adicione os arquivos .csv em uma pasta chamada dataset na pasta do repositório, exemplo: dataset\olist_customers_dataset.csv

Você é livre para alterar o nome da pasta e dos arquivos, apenas não se esqueça de atualizar no código.

# Execução
Execute o arquivo principal:

```
python app.py
```

# Observações

O Dashboard interativo feito com a biblioteca Dash, também pode ser acessado localmente no seu navegador pelo ip: **http://127.0.0.1:8050/**


