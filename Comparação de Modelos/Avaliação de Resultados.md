# Avaliando resultados do Projeto Base

SVC

             precision    recall  f1-score   support

    positive       0.89      0.90      0.90      8281
    negative       0.90      0.89      0.89      8219

    accuracy                           0.89     16500
    macro avg      0.89      0.89      0.89     16500
    weighted avg   0.89      0.89      0.89     16500




Árvore de Decisões

             precision    recall  f1-score   support

    positive       0.73      0.72      0.72      8281
    negative       0.72      0.73      0.72      8219

    accuracy                           0.72     16500
    macro avg      0.72      0.72      0.72     16500
    weighted avg   0.72      0.72      0.72     16500



Regressão Logística


                precision    recall  f1-score   support

    positive       0.89      0.90      0.90      8281
    negative       0.90      0.88      0.89      8219

    accuracy                           0.89     16500
    macro avg      0.89      0.89      0.89     16500
    weighted avg   0.89      0.89      0.89     16500


Matrizes de Confusão de SVC, Árvore de Decisões e Regressão Logística , respectivamente:
<img src="../Comparação de Modelos/Matriz_Conf_1.jpg" width="1400">


# Observações:
- O modelo SVC obteve um tempo de execução muito alto
- Os modelos que apresentaram as melhores métricas foram o de Regressão Logística e SVC, apresentando resultados de precisão, recall e f1 similares.


