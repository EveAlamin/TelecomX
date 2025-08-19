# 📊 Análise de Evasão de Clientes - Telecom X

Este projeto tem como objetivo analisar a **evasão de clientes** da empresa fictícia **Telecom X**, identificando padrões, perfis e fatores contratuais que mais influenciam o cancelamento de serviços.  
A partir disso, busca-se apoiar a criação de **estratégias de retenção** mais inteligentes e proativas.

---

## 🚀 Tecnologias Utilizadas
- Python 3.x  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 🔧 Etapas do Projeto

### 1. Extração  
- Dados coletados via **API** no formato JSON.  

### 2. Transformação  
- **Normalização** do JSON para DataFrame.  
- **Limpeza de colunas** e simplificação dos nomes.  
- **Tratamento de dados ausentes** (ex.: valores nulos em `Fatura_Total`).  
- **Padronização de categorias** (ex.: "No internet service" → "No").  
- **Conversão para numérico** de variáveis binárias (Yes/No → 1/0).  
- **Tradução** das colunas para português.  

### 3. Carga e Análise  
- Análise Exploratória de Dados (EDA) com gráficos e estatísticas.  
- Principais achados:  
  - Clientes **mês a mês** apresentam a maior taxa de churn.  
  - Existe uma correlação inversa entre **tempo de contrato** e evasão.  
  - **Primeiros meses** são críticos para retenção.  

### 4. Relatório Final  
- Taxa geral de churn: **26,5%**.  
- Perfis de clientes mais propensos a cancelar.  
- Recomendações de estratégias para reduzir evasão.  

---

## 📊 Resultados Esperados
- Melhor compreensão do comportamento dos clientes.  
- Identificação de fatores de risco para evasão.  
- Apoio à tomada de decisão em estratégias de retenção.  

