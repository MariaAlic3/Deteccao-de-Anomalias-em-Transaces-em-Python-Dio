# Detecçao de Anomalias em Transações em Python - Dio
Este projeto aborda o desafio clássico da detecção de fraudes em cartões de crédito utilizando algoritmos de aprendizado de máquina. O principal objetivo é identificar transações fraudulentas com precisão, lidando com o cenário real de extremo desbalanceamento de classes (onde as fraudes representam uma fração mínima do total de movimentações).

# Link do google colab:

https://colab.research.google.com/drive/1ZOOYbLB5z3FWhGyO4GDIcm7hCmZonvPA?usp=sharing

## 🛠️ Tecnologias e Ferramentas Utilizadas
Linguagem: Python

Manipulação e Análise de Dados: Pandas, NumPy

Pré-processamento e Métricas: Scikit-Learn

Balanceamento de Dados: Imbalanced-Learn (SMOTE, Undersampling)

Modelagem Preditiva: Logistic Regression, Random Forest, XGBoost

Explicabilidade do Modelo: SHAP (SHapley Additive exPlanations)

Visualização de Dados: Matplotlib

## 🚀 Etapas do Pipeline Desenvolvido
Análise de Classe Desbalanceada: Diagnóstico inicial da proporção de fraudes no dataset.

Engenharia de Recursos (Feature Engineering): Transformação logarítmica de variáveis financeiras (Amount_log) e padronização com StandardScaler.

Modelagem Baseline: Construção de um modelo inicial com Regressão Logística.

Avaliação Focada no Negócio: Uso de métricas apropriadas para fraude (F1-Score, Curva Precision-Recall e Recall), evitando a armadilha da falsa alta acurácia.

Tratamento de Desbalanceamento: Aplicação e estudo de técnicas de subamostragem (Undersampling) e superamostragem sintética (SMOTE).

Modelos Avançados e Otimização: Treinamento de Random Forest e XGBoost com ajuste de hiperparâmetros via GridSearchCV.

Explicabilidade: Implementação de SHAP plots para interpretar quais variáveis são determinantes para o modelo indicar uma fraude.
