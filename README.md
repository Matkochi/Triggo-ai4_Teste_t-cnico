# Triggo-ai4_Teste_técnico


---

## 🧱 01 – Preparação dos Dados (`01_preparacao_dados.ipynb`)

### Objetivo:
Transformar os arquivos brutos em um único dataset consolidado e limpo.

### Etapas:
- Importação de múltiplos arquivos `.csv` (clientes, pedidos, pagamentos, produtos, avaliações, etc.)
- Conversão de colunas de data (`datetime`)
- Tratamento de nulos e duplicatas
- Junções entre tabelas relacionais (merge)
- Normalização de colunas (como categorias e tipos)
- Exportação do `dataset_olist_preparado.csv` para uso posterior

---

## 📊 02 – Análise Exploratória de Dados (`02_analise_exploratoria.ipynb`)

### Objetivo:
Explorar padrões, tendências e relações úteis para o negócio.

### Perguntas respondidas:
- 📈 **Volume de pedidos por mês** → Análise de sazonalidade
- ⏱️ **Distribuição do tempo de entrega** → Desempenho logístico
- 🚚 **Correlação entre valor do frete e distância** → Custo de entrega
- 🛒 **Categorias de produtos mais lucrativas**
- 🌎 **Estados com maior ticket médio**

### Exemplos de gráficos:
- Série temporal de pedidos mensais
- Histograma do tempo de entrega
- Gráfico de dispersão (frete vs distância)
- Gráfico de barras (faturamento por categoria)
- Mapa de calor (ticket médio por estado)

---

##  03 – Modelagem Preditiva (`03_modelagem.ipynb`)

### Objetivo:
Aplicar machine learning para solucionar problemas de negócio.

####  Predição de Atrasos
- Criação de feature `pedido_atrasado` (bool)
- Modelos usados:
  - Regressão Logística
  - Random Forest Classifier
- Avaliação:
  - Acurácia, matriz de confusão, F1-score
  - Importância de variáveis

#### 👥 Segmentação de Clientes
- Clusterização com KMeans
- Variáveis: ticket médio, frequência de pedidos, total gasto
- Resultado: grupos distintos com comportamentos de compra diferentes

---

##  04 – Análise de Satisfação do Cliente (`04_satisfacao_cliente.ipynb`)

### Objetivo:
Entender o que afeta a nota dos clientes (`review_score`)

### Fatores analisados:
- Tempo de entrega
- Categoria do produto
- Preço do pedido
- Se houve atraso
- Forma de pagamento

### Técnicas:
- Boxplots, violin plots
- Correlação com tempo de entrega
- Comparações entre avaliações altas e baixas

---

## 📊 05 – Dashboard Interativo (`05_dashboard.py`)

### Objetivo:
Visualizar insights de maneira executiva e interativa.

### Construído com:
- Dash + Plotly
- Pandas para manipulação de dados

### Visualizações:
-  **Evolução de vendas ao longo do tempo** (com filtros por estado e categoria)
-  **Mapa de calor de vendas por estado**
-  **Relação entre tempo de entrega e avaliação**
-  **Ranking de vendedores** (vendas, avaliação, eficiência logística)

### Exemplo de Interface:

![dashboard vendas](
---

## 🧱 01 – Preparação dos Dados (`01_preparacao_dados.ipynb`)

### Objetivo:
Transformar os arquivos brutos em um único dataset consolidado e limpo.

### Etapas:
- Importação de múltiplos arquivos `.csv` (clientes, pedidos, pagamentos, produtos, avaliações, etc.)
- Conversão de colunas de data (`datetime`)
- Tratamento de nulos e duplicatas
- Junções entre tabelas relacionais (merge)
- Normalização de colunas (como categorias e tipos)
- Exportação do `dataset_olist_preparado.csv` para uso posterior

---

## 📊 02 – Análise Exploratória de Dados (`02_analise_exploratoria.ipynb`)

### Objetivo:
Explorar padrões, tendências e relações úteis para o negócio.

### Perguntas respondidas:
- 📈 **Volume de pedidos por mês** → Análise de sazonalidade
- ⏱️ **Distribuição do tempo de entrega** → Desempenho logístico
- 🚚 **Correlação entre valor do frete e distância** → Custo de entrega
- 🛒 **Categorias de produtos mais lucrativas**
- 🌎 **Estados com maior ticket médio**

### Exemplos de gráficos:
- Série temporal de pedidos mensais
- Histograma do tempo de entrega
- Gráfico de dispersão (frete vs distância)
- Gráfico de barras (faturamento por categoria)
- Mapa de calor (ticket médio por estado)

---

## 🧠 03 – Modelagem Preditiva (`03_modelagem.ipynb`)

### Objetivo:
Aplicar machine learning para solucionar problemas de negócio.

#### 🔍 Predição de Atrasos
- Criação de feature `pedido_atrasado` (bool)
- Modelos usados:
  - Regressão Logística
  - Random Forest Classifier
- Avaliação:
  - Acurácia, matriz de confusão, F1-score
  - Importância de variáveis

#### 👥 Segmentação de Clientes
- Clusterização com KMeans
- Variáveis: ticket médio, frequência de pedidos, total gasto
- Resultado: grupos distintos com comportamentos de compra diferentes

---

## 😊 04 – Análise de Satisfação do Cliente (`04_satisfacao_cliente.ipynb`)

### Objetivo:
Entender o que afeta a nota dos clientes (`review_score`)

### Fatores analisados:
- Tempo de entrega
- Categoria do produto
- Preço do pedido
- Se houve atraso
- Forma de pagamento

### Técnicas:
- Boxplots, violin plots
- Correlação com tempo de entrega
- Comparações entre avaliações altas e baixas

---

## 📊 05 – Dashboard Interativo (`05_dashboard.py`)

### Objetivo:
Visualizar insights de maneira executiva e interativa.

### Construído com:
- Dash + Plotly
- Pandas para manipulação de dados

### Visualizações:
- 📈 **Evolução de vendas ao longo do tempo** (com filtros por estado e categoria)
- 🌎 **Mapa de calor de vendas por estado**
- 🕒 **Relação entre tempo de entrega e avaliação**
- 🧑‍💼 **Ranking de vendedores** (vendas, avaliação, eficiência logística)

### Exemplo de Interface:

![Evolução_vendas_mensal](https://github.com/user-attachments/assets/cbfdfe94-f120-48c6-81d1-26d90e34a207)


## ⚙️ Instalação e Execução

### 🔧 Pré-requisitos
- Python 3.10+
- Jupyter Notebook
- VS Code (opcional)
- pip ou conda

### 📦 Instalar dependências
```bash
pip install -r requirements.txt
)

>  (Substitua a URL acima por um screenshot salvo localmente ou hospedado no GitHub)

---

##  Instalação e Execução

###  Pré-requisitos
- Python 3.10+
- Jupyter Notebook
- VS Code (opcional)
- pip ou conda

###  Instalar dependências
```bash
pip install -r requirements.txt
