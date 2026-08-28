# Análise e Previsão de Demanda para Varejo

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-F7931E?logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-2.x-05A6F0?logo=xgboost&logoColor=white)
![Portfolio](https://img.shields.io/badge/Portfolio-Ready-2ea44f)

</div>

Projeto de análise e previsão de demanda em varejo com foco em comparar o comportamento de uma loja física e um canal de e-commerce. A solução simula padrões reais de vendas, sazonalidade, comportamento do cliente e gestão de estoque, usando modelos de machine learning para reduzir desperdício, evitar rupturas e apoiar decisões operacionais.

## Sobre o projeto

Este repositório demonstra uma aplicação prática de ciência de dados em negócios de varejo. A partir de dados sintéticos diários, o estudo explora correlação entre variáveis, compara modelos preditivos e analisa cenários de estoque e custo operacional.

### Objetivos principais

- prever a demanda por canal de venda;
- identificar os fatores que mais afetam as vendas;
- comparar modelos de previsão;
- otimizar compras e reposição;
- reduzir perdas por excesso e ausência de produto.

## Valor de negócio

A solução é relevante para empresas que precisam melhorar a eficiência operacional em:

- varejo físico;
- e-commerce;
- marketplaces;
- gestão de categorias e SKU;
- planejamento de promoções;
- reposição de estoque.

## Fluxo da análise

### 1. Geração de dados sintéticos
Dados diários são criados para representar clientes, pedidos, clima, sazonalidade e comportamento de compra em cenários realistas.

### 2. Análise exploratória
A matriz de correlação das variáveis numéricas é calculada e visualizada em heatmap para identificar padrões importantes.

### 3. Preparação para modelagem
Os dados são segmentados por canal e transformados para treino e validação.

### 4. Modelagem preditiva
Os modelos avaliados incluem:

- Regressão Linear
- Árvore de Decisão
- XGBoost Regressor

### 5. Avaliação de desempenho
As métricas calculadas incluem:

- RMSE
- MAE
- R²

### 6. Simulação de estoque e custo
O projeto compara cenários como:

- compra ideal;
- previsão com margem de segurança;
- estratégia baseada em média histórica.

## Stack tecnológica

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Estrutura do repositório

```text
.
├── modelos_preditivos_vilarejo.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── data/
└── notebooks/
```

## Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/analise-previsao-demanda-varejo.git
cd analise-previsao-demanda-varejo
```

### 2. Crie um ambiente virtual

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

Linux/macOS:

```bash
source .venv/bin/activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Abra o notebook

Execute as células em sequência no arquivo `modelos_preditivos_vilarejo.ipynb`.

## Dados

O projeto utiliza dados sintéticos gerados no próprio notebook, o que facilita reprodução, estudo e apresentação em portfólio.

## Resultados esperados

Com essa análise, é possível responder perguntas como:

- quais fatores mais impactam a demanda;
- qual modelo apresenta melhor desempenho;
- como a política de estoque afeta custo e disponibilidade;
- quando a previsão entrega maior valor para a operação.

## Próximos passos

Futuras evoluções úteis incluem:

- dashboard em Streamlit;
- deploy em aplicação web;
- previsão por SKU ou categoria;
- integração com dados reais;
- automação de treinamento e monitoramento.

## Licença

Este projeto foi desenvolvido para fins de estudo e apresentação em portfólio.

---

Este repositório já está em um bom estágio para publicação no GitHub como projeto técnico de análise e previsão de demanda para varejo.

