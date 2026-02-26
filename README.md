# 🧠 Projeto Python IA — Previsão de Score de Crédito

## 📌 Contexto do Projeto
Neste projeto, simula-se um **case real do setor bancário**, onde o objetivo é criar um modelo de **Inteligência Artificial** capaz de prever o **score de crédito de clientes**, classificando-os como:

- ❌ Ruim  
- ⚠️ Ok  
- ✅ Bom  

O modelo é treinado a partir de dados históricos de clientes e, posteriormente, utilizado para prever o score de **novos clientes**.

---

## 🎯 Objetivo
Analisar os dados dos clientes de um banco e desenvolver um modelo de Machine Learning que consiga:
- Aprender padrões de comportamento financeiro
- Classificar automaticamente o score de crédito
- Comparar diferentes algoritmos de classificação

---

## 🛠️ Tecnologias Utilizadas
- **Python**
- **Pandas** — manipulação e análise de dados
- **Scikit-learn** — construção e avaliação de modelos de Machine Learning
- **LabelEncoder** — codificação de variáveis categóricas

---

## 📊 Base de Dados
O projeto utiliza dois arquivos principais:
- `clientes.csv` → base histórica para treino e teste do modelo
- `novos_clientes.csv` → base utilizada para previsões

Os dados incluem informações como:
- Profissão
- Mix de crédito
- Comportamento de pagamento
- Score de crédito (variável alvo)

Arquivos utilizados no estudo disponibilizados pela :contentReference[oaicite:0]{index=0}.

---

## 🔄 Etapas do Projeto

### 1️⃣ Leitura e Análise dos Dados
- Importação dos dados com Pandas
- Análise da estrutura e tipos das colunas

### 2️⃣ Tratamento de Dados
- Conversão de variáveis categóricas em valores numéricos usando `LabelEncoder`
- Separação entre variáveis independentes (`X`) e variável alvo (`y`)

### 3️⃣ Divisão da Base
- Separação em dados de treino e teste
- Proporção: 70% treino e 30% teste

### 4️⃣ Criação dos Modelos
Foram testados dois algoritmos de classificação:
- 🌳 **Random Forest Classifier**
- 📍 **K-Nearest Neighbors (KNN)**

### 5️⃣ Avaliação dos Modelos
- Métrica utilizada: **Acurácia (Accuracy Score)**
- Comparação do desempenho entre os modelos

### 6️⃣ Previsão de Novos Clientes
- Aplicação do modelo treinado para classificar novos clientes
- Uso do mesmo padrão de codificação das variáveis

---

## 📈 Resultados
Após o treinamento e teste dos modelos:
- O **Random Forest** apresentou melhor desempenho em relação ao KNN
- O modelo escolhido foi utilizado para realizar previsões em novos clientes

---

## ▶️ Como Executar o Projeto

### 1️⃣ Clone o repositório
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
