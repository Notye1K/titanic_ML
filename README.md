# 🚢 Titanic Survival Prediction

Este projeto aplica técnicas de **machine learning** para prever quais passageiros sobreviveram ao acidente do Titanic, alcançando **74% de acurácia**.

## 📊 Descrição do Projeto
- Desenvolvimento de um **modelo de classificação preditiva** para identificar sobreviventes.
- Realização de **pré-processamento e análise exploratória de dados**, incluindo:
  - Limpeza e normalização dos dados.
  - Seleção de variáveis relevantes.
- Aplicação de técnicas de **balanceamento de classes** com **[SMOTE](ca://s?q=Explicar_SMOTE)**.
- Comparação de desempenho entre diferentes algoritmos:
  - **[SVM](ca://s?q=Explicar_SVM)**  
  - **[XGBoost](ca://s?q=Explicar_XGBoost)**  
  - **[Random Forest](ca://s?q=Explicar_Random_Forest)**
- Ajuste de hiperparâmetros com **[GridSearchCV](ca://s?q=Explicar_GridSearchCV)**.
- Validação cruzada com **[KFold](ca://s?q=Explicar_KFold)** e `cross_val_score`.
- Estruturação de um **pipeline completo de machine learning**, garantindo resultados consistentes e replicáveis.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Pandas** para manipulação de dados.
- **Seaborn** e **Matplotlib** para visualização.
- **Scikit-learn**:
  - `RandomForestClassifier`
  - `SVC`
  - `StandardScaler`
  - `GridSearchCV`
  - `cross_val_score`, `KFold`
- **XGBoost**
- **Imbalanced-learn (SMOTE)**

## 📈 Resultados
- Random Forest obteve a melhor pontuação em cross validation, mostrando maior estabilidade.
- SVM foi o modelo com melhor desempenho no site de avaliação (Kaggle).
- Melhor acurácia geral: 74%.
