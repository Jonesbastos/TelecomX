# 📊 Desafio de Data Science - Análise de Evasão de Clientes (Churn) | Telecom X

Este repositório contém a solução para o desafio proposto pela **Telecom X**, com foco na **análise de evasão de clientes (churn)**. O objetivo é entender os fatores que influenciam a saída de clientes da empresa, utilizando Python e bibliotecas de análise de dados.

---


## 🎯 Objetivo

A empresa Telecom X está enfrentando um alto índice de cancelamentos de contratos. Este projeto tem como objetivo:

- Coletar e tratar os dados de clientes disponibilizados via API.
- Explorar e entender o comportamento dos clientes.
- Identificar padrões e possíveis causas de evasão.
- Preparar os dados para modelagens futuras e auxiliar na tomada de decisão.
- Apoiar a empresa com **insights estratégicos** para redução da evasão.
  
---

## 🧹 Limpeza e Tratamento de Dados

As principais etapas de preparação dos dados incluíram:

- ✅ Importação e normalização de um arquivo JSON estruturado por API.
- ✅ Separação de campos aninhados em colunas planas.
- ✅ Remoção de registros com valores ausentes em colunas críticas.
- ✅ Padronização de colunas e conversão de variáveis binárias ("Yes"/"No" → 1/0).
- ✅ Criação da variável `contas_diarias`, baseada na fatura mensal.

---

## 🔍 Análise Exploratória de Dados (EDA)

A análise exploratória revelou importantes padrões de comportamento entre os clientes.

---

### 📌 Churn por Variáveis Categóricas

- Clientes com **contrato mensal** apresentam **alta taxa de churn**.
- A forma de pagamento **"Electronic Check"** está fortemente ligada à evasão.
- Clientes que **não utilizam serviços extras** (como suporte técnico ou backup) evadem mais.

---

# ✅ Recomendações

- Oferecer **incentivos para contratos de longo prazo**.
- Estimular o uso de serviços complementares.
- Adotar formas de pagamento automáticas (como débito ou cartão).
- Focar nos **primeiros meses do cliente**, com ações proativas de engajamento.

---

## 🔧 Tecnologias e Ferramentas

- Python 3.10+
- Pandas
- NumPy
- Google Colab 
- Matplotlib
- Seaborn
- Plotly

---

## 🧪 Etapas do Projeto

- ✅ Extração de dados da API (formato JSON)
- ✅ Tratamento e normalização dos dados (ETL)
- ✅ Análise da estrutura do dataset
- ✅ Verificação e correção de inconsistências
- ✅ Criação de colunas derivadas (como `contas_diarias`)
- 🔄 Padronização de colunas e variáveis
- 🚧 Análise exploratória de dados (EDA) [em andamento]
- 🚀 Modelagem preditiva (etapa futura)

---

## 📁 Estrutura dos Dados

O dataset inclui colunas como:

- `customer_id`, `churn`, `tenure`, `monthly_charges`, `contract`, `internet_service`, entre outras.
- Serviços adicionais: `tech_support`, `streaming_tv`, `online_backup`, etc.
- Coluna criada: `contas_diarias` → estimativa do gasto diário do cliente.



