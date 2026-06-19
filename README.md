# Árvore de Decisão 

Um dos algoritmos mais interpretáveis de ML: o modelo aprende uma sequência de perguntas sobre as features e vai dividindo os dados até chegar numa classificação. Dá pra visualizar literalmente cada decisão que ele toma, o que é raro no mundo de ML.

Exercício focado em entender como a árvore cresce, onde ela erra e como controlar isso.

# No Notebook


Pré-processamento e análise das features mais relevantes
Treinamento com DecisionTreeClassifier do scikit-learn
Visualização da árvore gerada com plot_tree ou export_graphviz
Análise da importância de cada feature (feature_importances_)
Experimentos com max_depth pra controlar overfitting


Sem restrição nenhuma, a árvore cresce até classificar perfeitamente cada ponto do treino e aí ela para de generalizar. O parâmetro max_depth limita o quanto ela pode crescer, e encontrar o valor certo é parte do exercício. É um dos exemplos mais didáticos de bias-variance tradeoff na prática.
