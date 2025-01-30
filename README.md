# Análise Exploratória e Modelo Preditivo: Dataset `load_breast_cancer`

Este projeto realiza uma análise exploratória de dados (EDA) e a construção de um modelo preditivo utilizando o dataset [`load_breast_cancer`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html), fornecido pelo Scikit-learn. O objetivo é explorar os padrões dos dados, entender as distribuições das variáveis e construir um modelo de árvore de decisão para prever se um tumor é **maligno** (`0`) ou **benigno** (`1`).

---

## 🔍 **Etapas do Projeto**

### **1. Análise Exploratória de Dados (EDA)**
- **Estatísticas descritivas**:  
  Resumo geral das variáveis com valores como média, desvio padrão, valores mínimos e máximos.
- **Visualização das distribuições**:  
  Histogramas comparando as distribuições das variáveis entre tumores malignos e benignos.
- **Matriz de correlação**:  
  Análise de correlação entre as variáveis para identificar relações lineares.
- **Boxplots**:  
  Identificação de outliers e análise das diferenças entre classes para cada característica.

### **2. Construção e Avaliação do Modelo**
- **Modelo preditivo**:  
  Algoritmo de árvore de decisão para prever a variável-alvo (`target`).
- **Acurácia do modelo**:  
  Avaliação no conjunto de teste.
- **Validação cruzada**:  
  Validação cruzada com 5 folds para medir a performance geral do modelo.

---

## 🛠️ **Ferramentas Utilizadas**
- **Linguagem**: Python  
- **Bibliotecas**:
  - `pandas`: Manipulação de dados.
  - `matplotlib` e `seaborn`: Visualização dos dados.
  - `scikit-learn`: Carregamento do dataset, construção do modelo e validação.
- **Ambiente**: Jupyter Notebook.

---

## 🚀 **Como Executar**
1. Certifique-se de ter as bibliotecas necessárias instaladas:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn jupyter

## Abra o arquivo do Jupyter Notebook:
jupyter notebook analise_breast_cancer.ipynb
Execute as células do notebook para realizar a análise exploratória e treinar o modelo preditivo.

📊 Resultados
1. Análise Exploratória de Dados
Distribuições:
Histogramas e boxplots mostraram diferenças claras nas distribuições das variáveis entre tumores malignos e benignos.
Matriz de correlação:
Variáveis fortemente correlacionadas foram identificadas, auxiliando na análise do dataset.
2. Modelo Preditivo
Acurácia do Modelo:
No conjunto de teste: 94,74%.
Validação Cruzada:
Acurácia média (5 folds): 91,73%.

📂 Arquivos do Projeto
analise_breast_cancer.ipynb: Contém o código completo para EDA e construção do modelo preditivo.
