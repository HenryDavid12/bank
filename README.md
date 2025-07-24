#  Bank Marketing Analysis – Otimizando Conversão com Dados

##  Visão Geral

Este projeto tem como objetivo analisar dados de campanhas de marketing telefônico de um banco europeu para promover o produto **Depósito a Prazo**. Através de análises exploratórias, modelagem preditiva e segmentação de clientes, foram identificados os principais fatores que influenciam a conversão e como otimizar os esforços da campanha para **aumentar o ROI e reduzir a inadimplência**.

---

##  Objetivo de Negócio

> **Como aumentar a taxa de aquisição de clientes para o produto bancário "Depósito a Prazo", utilizando dados para segmentar, priorizar e personalizar as campanhas de marketing?**

---

##  Principais Insights

-  **Conversão Geral:** Apenas 11% dos clientes contatados adquiriram o produto.
-  **Canal de contato é decisivo:** 82% das conversões ocorreram via **celular**.
-  **Duração da ligação** tem correlação positiva (+0.37) com a conversão.
-  **Muitas tentativas de contato** (variável `campaign`) reduzem as chances de aquisição.
-  **Clusters de clientes** revelaram grupos com maior propensão à conversão.
    - Cluster 2 apresenta maior frequência de aquisição.
    - Cluster 1 e 0 contém uma frequência menor, entretanto, possui um número menor de clientes, indicando boa conversão.
-  Clientes com **maior saldo bancário** convertem mais e apresentam menor inadimplência.
-  Nível de educação "secondary" concentra maior inadimplência.

---

## 🔎 Metodologia

### 🔹 Etapas:
1. **Pré-processamento dos dados**
   - Limpeza, tratamento de nulos e encoding de variáveis categóricas
2. **Análise Exploratória (EDA)**
   - Visualizações com Seaborn e Matplotlib
   - Análise de correlação (Pearson + Cramér’s V)
3. **Segmentação com KMeans**
   - Clustering de perfis com base em dados financeiros e demográficos
4. **Modelagem preditiva**
   - Random Forest e XGBoost para prever conversão
5. **Criação de dashboard em Power BI**
   - KPIs, gráficos interativos e painéis segmentados

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.11**
  - `pandas`, `numpy`, `seaborn`, `matplotlib`
  - `scikit-learn`, `xgboost`
- **Power BI**
  - Dashboard com KPIs, gráficos e filtros interativos
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📈 Resultados Esperados

- Otimização de campanhas com foco em canais mais eficientes (ex: celular)
- Redução de custos ao evitar perfis com baixa propensão e alta inadimplência
- Segmentação inteligente com base em clusters de alto potencial
- Apoio à decisão com visualizações claras e insights orientados a dados

---

## 🖥️ Dashboard (Power BI)

https://app.powerbi.com/links/kE9XEFF20Y?ctid=43425ceb-4e5b-4236-91ee-8996016132fd&pbi_source=linkShare

> KPIs principais: Conversão Geral, Conversão por tipo de contato, conversão por cargo, Aquisições, perfomance dos clusters.

---

## 👨‍ Sobre o Autor

**Henry David**  
Analista de Dados | Python • Power BI • SQL •
Excel

henryalvdavid@gmail.com

 LinkedIn:https://www.linkedin.com/in/henryalvdavid  
 Medium: https://medium.com/@henryprojetos12

---

## 📂 Estrutura do Projeto

```bash
bank-marketing-project/
│
├── data/                   bank-full.csv
├── notebooks/              bank.csv
├── dashboards/             https://l1nq.comJfaiS 


