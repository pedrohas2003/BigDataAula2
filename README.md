# BigDataAula2
# Validação de Modelos e Métricas de Avaliação

Este repositório traz um exercício de classificação de inadimplência em empréstimos de automóveis, com foco na **validação de modelos** e no cálculo das principais **métricas de avaliação**.

---

## 📝 Arquivos

- **`emp_automovel.csv`**  
  Conjunto de dados com 54 025 registros e 11 variáveis (ex.: receita do cliente, anuidade do empréstimo, scores e indicador de inadimplência).

- **`Validação e métricas de avaliação.ipynb`**  
  Notebook contendo todo o pipeline:
  1. Leitura e EDA (head, info, describe, visualizações)  
  2. Pré-processamento (normalização, codificação, split treino/validação/teste)  
  3. Treino de `DecisionTreeClassifier` (max_depth=10)  
  4. Validação cruzada (KFold e StratifiedKFold)  
  5. Cálculo de métricas:
     - Acurácia  
     - Precisão  
     - Recall  
     - F1-Score  
     - Matriz de Confusão  
     - Curva ROC e Precision-Recall  

---

## 🚀 Como Executar

1. Clone este repositório:  
   ```bash
   git clone https://github.com/SEU_USUARIO/seu-repo.git
   cd seu-repo
