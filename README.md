# predicao chuva
Neste projeto, o código foi simplificado para rodar facilmente no Jupyter Notebook, mas também pode ser adaptado para .py. Fiz a leitura do dataset, limpei duplicatas e, como não havia valores ausentes, não precisei imputar NaNs. O pré-processamento incluiu escalonamento e codificação, usando Pipeline e ColumnTransformer, e a separação treino/teste foi de 80/20.

Testei Logistic Regression e RandomForest, pois o dataset é pequeno e RandomForest ajuda a reduzir overfitting. No fim, optei pelo RandomForest otimizado com GridSearchCV, que obteve acurácia de 0.9375 e precision 1.0, acertando praticamente todas as previsões.
