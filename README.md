# 🌟 Análise de Desempenho - Rede Alura Store

## 📌 Objetivo
Este projeto tem como objetivo ajudar o Senhor João, proprietário da rede Alura Store, a identificar qual de suas 4 lojas apresenta o menor desempenho para considerar sua venda. A análise foi realizada diretamente no Google Colab e abrange:

- Comparativo completo de faturamento entre lojas
- Desempenho por categoria de produtos
- Satisfação dos clientes (avaliações médias)
- Análise de produtos mais e menos vendidos
- Custo médio de frete por loja

## 🔍 Métricas Analisadas
| Métrica               | Descrição                          | Ferramenta de Análise         |
|-----------------------|------------------------------------|-------------------------------|
| Faturamento Total     | Soma de todas as vendas por loja   | Gráfico de Barras Horizontais |
| Vendas por Categoria  | Desempenho por tipo de produto     | Gráfico de Radar              |
| Avaliações Médias     | Satisfação dos clientes            | Gráfico Barras e Boxplot      |
| Produtos Extremos     | Itens mais/menos vendidos          | Gráfico de Barras Horizontais |
| Frete Médio           | Custo logístico por loja           | Gráfico de Pizza              |

## 📊 Principais Gráficos e Insights

### 1. Análise do faturamento
![grafico1](https://github.com/user-attachments/assets/1f6ed28c-667c-4cb8-a08c-8921577df623)
Insights:
Resultados do Faturamento:

✅ Loja 1 tem o maior faturamento, superando a média das 4 lojas em 25.3%
⚠️ Loja 4 apresenta o menor faturamento, ficando 18.7% abaixo da média

Detalhes do cálculo:
Faturamento médio das 4 lojas: R$ 47.532,50
Faturamento Loja 1: R$ 59.558,00 (+25.3% acima da média)
Faturamento Loja 4: R$ 38.654,00 (-18.7% abaixo da média)

Comparativo direto entre lojas:
A Loja 1 fatura 54.1% a mais que a Loja 4
A diferença absoluta entre elas é de R$ 20.904,00

Interpretação:
A Loja 1 tem um desempenho excepcional, ficando mais de 1/4 acima da média
A Loja 4 precisa melhorar em quase 19% para atingir a média do grupo
A disparidade entre a melhor e pior loja é de mais de 50%

### 2. Vendas por Categoria
![grafico2](https://github.com/user-attachments/assets/fe4ea369-e53b-409d-a02d-5c9cea954c4f)


### 3. Média de Avaliação das Lojas
![grafico3](https://github.com/user-attachments/assets/15eb3bc7-a01a-47ef-8956-95430b3d8dc7)


### 4. Produtos Mais e Menos Vendidos
![grafico4](https://github.com/user-attachments/assets/8d568bc2-ba23-40c4-aee4-73d815d77e5f)


### 5. Frete Médio por Loja
![grafico5](https://github.com/user-attachments/assets/3b4a1575-79bd-4830-9a1c-9116dd5bd997)



## 🛠️ Tecnologias Utilizadas]

- python
- pandas
- matplotlib
- seaborn
- numpy
- jupyter

## 📂 Estrutura dos Dados
```
store-performance-review/
├── data/ # Pasta com dados brutos
│ ├── loja_1.csv # Dados da Loja 1
│ ├── loja_2.csv # Dados da Loja 2
│ ├── loja_3.csv # Dados da Loja 3
│ └── loja_4.csv # Dados da Loja 4
├── analise_alura.ipynb # Notebook principal
├── outputs/ # Imagens dos gráficos
│ ├──  grafico1 # Gráfico da Loja 1
│ ├──  grafico2 # Gráfico da Loja 2
│ ├──  grafico3 # Gráfico da Loja 3
│ └──  grafico4 # Gráfico da Loja 4
└── README.md
```
