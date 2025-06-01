# Previsão de Curtidas no Spotify com Árvore de Decisão

Este projeto utiliza uma **Árvore de Decisão** para prever se uma música será curtida ou não no Spotify, com base em características do áudio.

## 📌 Objetivo
Desenvolver um modelo preditivo simples e interpretável que, a partir de variáveis como energia, dança, acústica, entre outras, consiga indicar se uma música será marcada como "curtida" (`liked`) pelos usuários.

## 📂 Dados
- **Arquivo:** `data.csv`
- **Variável alvo:** `liked` (1 = curtida, 0 = não curtida)
- **Pré-processamento:** remoção de valores nulos.

## 🧠 Técnicas Utilizadas
- `DecisionTreeClassifier` (critério Gini, profundidade máxima = 3)
- Divisão treino/teste (80/20)
- Avaliação com:
  - Matriz de Confusão
  - Acurácia
  - Precisão e Recall
  - Relatório de Classificação
- Visualização da árvore de decisão com `plot_tree`

## 📊 Visualizações
O modelo final é exibido graficamente, permitindo uma leitura fácil de como as decisões são tomadas com base nos atributos das músicas.

## 📎 Requisitos
- Python 3.7 ou superior
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 👤 Autor
Garbellini
Vinicius Araujo
