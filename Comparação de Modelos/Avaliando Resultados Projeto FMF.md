# Avaliando resultados dos modelos após diminuir o tamanho do datasset (já com undersample), de 50.000 para 10.000 dados:

SVC

             precision    recall  f1-score   support

    positive       0.87      0.89      0.88      1678
    negative       0.88      0.86      0.87      1622

    accuracy                           0.88      3300
    macro avg      0.88      0.88      0.88      3300
    weighted avg   0.88      0.88      0.88      3300
   



Árvore de Decisões

             precision    recall  f1-score   support

    positive       0.70      0.69      0.70      1678
    negative       0.69      0.70      0.69      1622

    accuracy                           0.70      3300
    macro avg      0.70      0.70      0.70      3300
    weighted avg   0.70      0.70      0.70      3300
    
   



Regressão Logística

           precision    recall  f1-score   support

    positive       0.87      0.89      0.88      1678
    negative       0.88      0.86      0.87      1622

    accuracy                           0.87      3300
    macro avg      0.87      0.87      0.87      3300
    weighted avg   0.87      0.87      0.87      3300
   



Matrizes de Confusão de SVC, Árvore de Decisões e Regressão Logística , respectivamente:

<img src="../Comparação de Modelos/Matriz_Conf_2.jpg" width="1400">


# Observações
- Mesmo com um menor número de dados, os modelos obtiveram métricas satisfatórias comparadas as do projeto base;
- O modelo de Regressão Logística tem performance tão boa quanto ao de SVC, mas roda em menos tempo.

# Conclusão:
- O modelo ideal a ser usado será o de Regressão Logística
