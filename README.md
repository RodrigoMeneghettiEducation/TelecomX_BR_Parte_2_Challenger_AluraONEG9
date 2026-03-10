<div align="center">

# 🧾 Relatório TelecomX BR - Parte 2
## Análise de Evasão de Clientes - Projeto "Churn de Clientes"

🎯 **Desafio** - Este projeto tem como objetivo desenvolver um pipeline de **Machine Learning** para prever a evasão de clientes (Churn) da empresa **Telecom X**. Após uma análise exploratória inicial bem-sucedida, a missão agora é construir modelos preditivos robustos para antecipar quais clientes têm maior chance de cancelar seus serviços.

💡 **Objetivo**:

<div align="left">

* Preparar os dados para a modelagem (tratamento, encoding, normalização).
* Realizar análise de correlação e seleção de variáveis.
* Treinar dois ou mais modelos de classificação.
* Avaliar o desempenho dos modelos com métricas.
* Interpretar os resultados, incluindo a importância das variáveis.
* Criar uma conclusão estratégica apontando os principais fatores que influenciam a evasão.

</div>

---

💻 **Desenvolvedor:** Rodrigo Meneghetti

📧 **E-mail:** [rodrigo.meneghetti.education@gmail.com](mailto:rodrigo.meneghetti.education@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/meneghettirodrigo](https://www.linkedin.com/in/meneghettirodrigo)  
🐙🐱 **GitHub:** [github.com/RodrigoMeneghettiEducation](https://github.com/RodrigoMeneghettiEducation)

---

![Python](https://img.shields.io/badge/Python-3.10%2B-yellow)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Science-blue)
![NumPy](https://img.shields.io/badge/NumPy-Data%20Analysis-purple)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Viz-brightgreen)
![SeaBorn](https://img.shields.io/badge/Seaborn-Interactive%20Charts-brown)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orangered)
![GoogleColab](https://img.shields.io/badge/Google_Colab-Notebook-orange)
![Github](https://img.shields.io/badge/github-Repository-lightgrey?logo=github)
![ONE](https://img.shields.io/badge/ONE_G9-Alura+Oracle-darkred)

</div>

---

## <center>🧠 **Projeto**</center>  

Este projeto tem como objetivo analisar os dados de clientes da ***Telecom X*** para identificar os principais fatores que levam à evasão de clientes (Churn). Através de uma abordagem de ***Análise Exploratória de Dados (EDA)***, buscamos extrair insights valiosos que possam auxiliar a equipe de Data Science na construção de modelos preditivos e no desenvolvimento de estratégias de retenção.

- 📥 **Importação e Manipulação de Dados**  
- 💻 **Aplicação dos Conceitos de ELT*****(Extraction, Transformation and Loading)***
- 📊 **Criação de Visualizações de Dados**  
- 🔎 **Realização de Análises Exploratórias de Dados (EDA)**  

---

## 🚀 Tecnologias Utilizadas

- **Linguagem:** Python 3.x
- **Bibliotecas Principais:**
  - `pandas`, `numpy` (Manipulação de dados)
  - `matplotlib`, `seaborn` (Visualização)
  - `scikit-learn` (Machine Learning e Métricas)
  - `imbalanced-learn` (Balanceamento de classes - SMOTE)

---

## 📂 Estrutura do Repositório

```text
TelecomX_Churn_Prediction/ 
 ├── TelecomX_Data_Tratados.csv 
 ├── Challenger_TelecomX_BR_Parte2.ipynb 
 ├── Graficos
 |   ├── DistribuicaoDeChurn
 |   ├── MatrizDeCorrelacao
 |   ├── TempoDeContratoVsEvasao
 |   ├── TotalDeGastosVsEvasao
 |   └── ImportanciaDasVariaveis_RandomForest
 └── README.md 

```

---

## 📊 Metodologia

### **Pré-processamento**
* **Limpeza:** Remoção de identificadores únicos (customerID).
* **Encoding:** Aplicação de One-Hot Encoding em variáveis categóricas.
* **Balanceamento:** Uso da técnica SMOTE para lidar com o desbalanceamento de classes (Churn vs. Não Churn).
* **Normalização:** Aplicação de StandardScaler para modelos baseados em distância (Regressão Logística).

---

### **Modelagem**
Foram treinados dois modelos distintos para comparação:

1. Regressão Logística: Modelo linear, interpretável, requer normalização.
2. Random Forest: Modelo baseado em árvores, robusto a escalas, captura interações não lineares.

---

### **Avaliação**
Os modelos foram avaliados utilizando:

* Acurácia
* Precisão
* Recall
* F1-Score
* Matriz de Confusão

---

### **Fatores Críticos de Evasão**

Com base na análise de importância das variáveis (Feature Importance), identificamos:

1. Tempo de Contrato (tenure): Clientes com menos tempo de casa tendem a cancelar mais.
2. Tipo de Contrato: Contratos "Month-to-month" apresentam maior risco que contratos anuais.
3. Serviços Adicionais: A ausência de serviços como Segurança Online e Backup aumenta a probabilidade de churn.
4. Método de Pagamento: Pagamentos via "Electronic Check" correlacionam-se com maior evasão.
---

### 🔹 1. Distribuição de Churn 

<img src="https://github.com/RodrigoMeneghettiEducation/TelecomX_BR_Parte_2_Challenger_AluraONEG9/blob/main/Graficos/DistribuicaoDeChurn.png?raw=true" alt="Placeholder 150x150">

---

### 🔹 2. Matriz de Correlação 

<img src="https://github.com/RodrigoMeneghettiEducation/TelecomX_BR_Parte_2_Challenger_AluraONEG9/blob/main/Graficos/MatrizDeCorrelacao.png?raw=true" alt="Placeholder 150x150">

---

### 🔹 3. Tempo de Contrato vs Evasão   
<img src="https://github.com/RodrigoMeneghettiEducation/TelecomX_BR_Parte_2_Challenger_AluraONEG9/blob/main/Graficos/TempoDeContratoVsEvasao.png?raw=true" alt="Placeholder 150x150">

---

### 🔹 4. Total de Gastos vs Evasão  

<img src="https://github.com/RodrigoMeneghettiEducation/TelecomX_BR_Parte_2_Challenger_AluraONEG9/blob/main/Graficos/TotalDeGastosVsEvasao.png?raw=true" alt="Placeholder 150x150">

---

### 🔹 5. Importância das Variáveis (Ramdom Forest)  

<img src="https://github.com/RodrigoMeneghettiEducation/TelecomX_BR_Parte_2_Challenger_AluraONEG9/blob/main/Graficos/ImportanciaDasVariaveis_RandomForest.png?raw=true" alt="Placeholder 150x150">

### 🔹 6. Relatório de Análise de Dados - Alura Store  
Criação do relatório de análise dos dados das lojas da rede Alura Store e recomendação ao cliente de qual das unidade é a melhor opção da ser vendida. 

---

# 📊 Relatório de Conclusão

---

## ✅ Conclusão Estratégica
A empresa deve focar suas estratégias de retenção em:

* **Campanhas de Fidelização:** Para clientes com tenure inferior a 12 meses.
* **Ofertas de Upgrade:** Incentivar a contratação de serviços adicionais (Streaming, Segurança) para aumentar o custo de troca.
* **Monitoramento de Pagamento:** Oferecer alternativas de pagamento para clientes que utilizam "Electronic Check".
O modelo de **Random Forest** demonstrou ser o mais robusto para esta base de dados, capturando melhor as relações complexas entre as variáveis.

---

## <center>🧰 **Tecnologias Utilizadas**</center>

| Ferramenta | Função |
|-------------|--------|
| 🐍 **Python 3** | Linguagem principal |
|</> **HTML**| Estrutura e organização |
|M⬇️ **Markdown**| Formatação de texto e legibilidade |
| 📦 **Pandas** | Manipulação e análise dos dados |
| 🔢 **NumPy** | Cálculos matemáticos, lógicos e estatísticos em larga escala |
| 📈 **Matplotlib** | Criação dos gráficos e visualizações |
| 📊 **Seaborn** | Gráficos atraentes e informativos |
| 🧮 **Jupyter Notebook** | Ambiente interativo de desenvolvimento local|
| 📙 **Google Colab Notebook**| Ambiente virtual interativo online de desenvolvimento|
