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
![Análise de Faturamento](https://raw.githubusercontent.com/SergioBurlamaK/store-performance-review/main/outputs/grafico1.png)

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
![Vendas por Categoria](https://raw.githubusercontent.com/SergioBurlamaK/store-performance-review/main/outputs/grafico2.png)

### Insights
Padrão consistente: Todas as lojas têm móveis como categoria mais vendida e instrumentos musicais ou utilidades domésticas como menos vendidas.

Performance relativa (baseado no gráfico radar):
- Loja 3 se destaca com o melhor desempenho geral
- Loja 4 mostra um perfil equilibrado
- Lojas 1 e 2 têm perfis similares, com a Loja 1 ligeiramente à frente

### 3. Média de Avaliação das Lojas
![Avaliação das Lojas](https://raw.githubusercontent.com/SergioBurlamaK/store-performance-review/main/outputs/grafico3.png)

### Insights
Variação pequena: Todas as lojas estão na faixa de 3.98 a 4.05, indicando consistência no atendimento.
Média geral: 4.02 (linha vermelha tracejada no gráfico).

Distribuição (baseado no boxplot):
- Loja 3 tem a menor variação (mais consistente)
- Loja 1 apresenta maior dispersão nas avaliações

Esta análise sugere que, embora todas as lojas mantenham padrões relativamente altos de satisfação, há espaço para melhorias, particularmente na Loja 1, que está ligeiramente abaixo das demais.

### 4. Produtos Mais e Menos Vendidos
![Produtos Extremos](https://raw.githubusercontent.com/SergioBurlamaK/store-performance-review/main/outputs/grafico4.png)

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
![Custo de Frete](https://raw.githubusercontent.com/SergioBurlamaK/store-performance-review/main/outputs/grafico5.png)

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

## 🔍 Conclusão Estratégica (Resumida)

**Recomendação Final:**  
**Vender a Loja 4** - Principais motivos:  

📉 **Faturamento:**  
- R$ 1,38M (9,8% abaixo da média das outras lojas)  
- Única loja com queda trimestral (-0.3%)  

🚚 **Custos de Frete:** 

Menor custo (R$ 31,28), mas:
- Não melhorou vendas (4ª posição)
- Não aumentou satisfação (2ª em avaliações, mas diferença mínima)  

🛒 **Mix de Produtos Problemático:**  
- Mais vendido: Cama box (logística cara) 
- Menos vendido: Guitarra (baixo giro)  

❌ **Por Que Não Outras Lojas?**

- Loja 1: Maior faturamento (compensa frete alto)
- Loja 2: Desempenho equilibrado (sem pontos fracos)
- Loja 3: Melhor avaliação (diferencial estratégico)

## 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-5B8FA8?style=for-the-badge&logo=seaborn&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)

## 📂 Estrutura dos Dados
```
store-performance-review/
├── base-de-dados/ # Pasta com dados brutos
│ ├── loja_1.csv # Dados da Loja 1
│ ├── loja_2.csv # Dados da Loja 2
│ ├── loja_3.csv # Dados da Loja 3
│ └── loja_4.csv # Dados da Loja 4
├── AluraStoreBr.ipynb # Notebook principal
├── outputs/ # Imagens dos gráficos
│ ├──  grafico1 # Gráfico da Loja 1
│ ├──  grafico2 # Gráfico da Loja 2
│ ├──  grafico3 # Gráfico da Loja 3
│ └──  grafico4 # Gráfico da Loja 4
└── README.md
```
## 🚀 Como Executar esta Análise no Google Colab

1. **Acesse o Notebook:**
   - Clique no botão abaixo para abrir diretamente no Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SEU_USUARIO/SEU_REPOSITORIO/blob/main/analise_alura.ipynb)

2. **Faça uma cópia do notebook:**
   - No menu do Colab, clique em `File` > `Save a copy in Drive`

3. **Execute a análise:**
   - Clique em `Runtime` > `Run all` (ou use Ctrl+F9)
   - Ou execute cada célula manualmente com Shift+Enter

4. **Personalização (opcional):**
   - Para alterar dados de entrada, edite a célula com os datasets
   - Modifique parâmetros de visualizações nas células de gráficos

## 💻 Execução Local (alternativa)

Se preferir executar localmente:

```bash
git clone https://github.com/SergioBurlamaK/store-performance-review.git
cd store-performance-review
jupyter notebook AluraStoreBr.ipynb
```

---

## 👨‍💻 Autor  

|  |  |
|--|--|
| ✨ **Nome** | Sergio Burlamaqui |
| 📌 **GitHub** | [![GitHub](https://img.shields.io/badge/-SergioBurlamaK-181717?style=flat&logo=github&logoColor=white)](https://github.com/SergioBurlamaK) |
| 📧 **E-mail** | [![Outlook](https://img.shields.io/badge/-sergio_o.b_junior@hotmail.com-0078D4?style=flat&logo=microsoft-outlook&logoColor=white)](mailto:sergio_o.b_junior@hotmail.com) |
| 💼 **LinkedIn** | [![LinkedIn](https://img.shields.io/badge/-Sergio_Burlamaqui-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sergioburlamaqui/) |

---
