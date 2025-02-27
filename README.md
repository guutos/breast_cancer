Decision Tree 🌳

Breast Cancer Wisconsin (Diagnostic) Data Set  
O Data Set de câncer de mama é utilizado para estudar e desenvolver modelos de diagnóstico e prognóstico do câncer de mama.
Este Data Set contêm informações sobre características de tumores mamários, que são classificados como benignos ou malignos.
O objetivo dessa atividade será construir um modelo de classificação para detecção da doença.

Carregamento e Tratamento de Dados 📊

✔ Carrega o Breast Cancer Wisconsin (Diagnostic) Data Set
✔ Resumo dos dados
✔ Divisão treino e teste
✔ Redução Dimensionalidade com PCA
✔ Criar os datasets X_train_pca e X_test_pca, transformados pelo PCA.
✔ Busca de Hiperparâmetros com Validação Cruzada
✔ Método Esemble


Tecnologias Utilizadas 🛠

✔ Python
✔ Pandas
✔ Scikit-Learn
✔ GridSearchCV, RandomizedSearchCV
✔ Esemble


Resumo do Modelo 📌

🔹A acurácia média da melhor combinação de hiperparâmetros foi de 92,19%
🔹Após aplicar o PCA, 3 componentes representam 70% da variância dos dados
🔹A combinação de hiperparâmetros do melhor modelo encontrado foi max_depth: 3, min_samples_split: 2 
🔹Após aplicar o método ensemble Bagging, encontramos uma acurácia de 95,90%
