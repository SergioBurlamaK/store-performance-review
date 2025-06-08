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

### Insights
#### ✅ Loja 1 - Líder de Faturamento
Fatura R$ 1,534,509.12 (4.55% acima da média)
Vantagem sobre a Loja 2: R$ 46,050.06
Vantagem sobre a Loja 4: R$ 150,011.54

#### 📈 Loja 2 - Segunda Colocada
Fatura R$ 1,488,459.06 (1.40% acima da média)
Próxima da liderança, com potencial para crescer

#### 📉 Loja 3 - Estável, mas abaixo da média
Fatura R$ 1,464,025.03 (0.26% abaixo da média)
Próxima da média, mas sem grande destaque

#### ⚠️ Loja 4 - Menor Faturamento
Fatura R$ 1,384,497.58 (5.68% abaixo da média)
Diferença significativa para líder (R$ 150K)

### 2. Vendas por Categoria
![grafico2](https://github.com/user-attachments/assets/fe4ea369-e53b-409d-a02d-5c9cea954c4f)

### Insights
Padrão consistente: Todas as lojas têm móveis como categoria mais vendida e instrumentos musicais ou utilidades domésticas como menos vendidas.

Performance relativa (baseado no gráfico radar):
- Loja 3 se destaca com o melhor desempenho geral
- Loja 4 mostra um perfil equilibrado
- Lojas 1 e 2 têm perfis similares, com a Loja 1 ligeiramente à frente

### 3. Média de Avaliação das Lojas
![grafico3](https://github.com/user-attachments/assets/15eb3bc7-a01a-47ef-8956-95430b3d8dc7)

### Insights
Variação pequena: Todas as lojas estão na faixa de 3.98 a 4.05, indicando consistência no atendimento.
Média geral: 4.02 (linha vermelha tracejada no gráfico).

Distribuição (baseado no boxplot):
- Loja 3 tem a menor variação (mais consistente)
- Loja 1 apresenta maior dispersão nas avaliações

Esta análise sugere que, embora todas as lojas mantenham padrões relativamente altos de satisfação, há espaço para melhorias, particularmente na Loja 1, que está ligeiramente abaixo das demais.

### 4. Produtos Mais e Menos Vendidos
![grafico4](https://github.com/user-attachments/assets/8d568bc2-ba23-40c4-aee4-73d815d77e5f)

### Insights
#### Médias Gerais:
- Média dos mais vendidos: 61 unidades (linha verde tracejada)
- Média dos menos vendidos: 33 unidades (linha vermelha tracejada)

#### Padrões Observados:
- Todas as lojas têm diferença significativa entre top e bottom (mínimo 22 unidades)
- Produtos de mobília/eletrodomésticos dominam os mais vendidos
- Itens de nicho (instrumentos, acessórios) aparecem como menos vendidos

#### Performance Relativa:
- Loja 2 tem o produto mais vendido com maior volume (65 unidades)
- Loja 3 mostra a menor diferença entre extremos (22 unidades)
- Lojas 1 e 4 têm padrões similares de diferença (~27-29 unidades)

Esta análise revela oportunidades tanto para capitalizar nos sucessos atuais quanto para melhorar o desempenho dos produtos subutilizados, com estratégias específicas por loja.

### 5. Frete Médio por Loja
![grafico5](https://github.com/user-attachments/assets/3b4a1575-79bd-4830-9a1c-9116dd5bd997)

### Insights
Média Geral: R$ 33,17
Variação: Diferença de R$ 3,41 entre a loja mais cara (1) e mais econômica (4)

Distribuição:
- Loja 1 responde por 26,1% do total de fretes
- Loja 4 por apenas 23,6%, apesar de ter volume similar de vendas

O gráfico de pizza mostra:
- Proporção relativa de cada loja no total de fretes
- Destaque visual para a Loja 1 (mais cara)
- Distribuição equilibrada entre as demais

Esta análise revela oportunidades para otimização de custos logísticos, especialmente na Loja 1, enquanto a Loja 4 serve como benchmark de eficiência. A diferença significativa sugere que há espaço para padronização ou adaptação estratégica das políticas de frete.

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
