# Trabajo Práctico 1 - Intro al Machine Learning

## Consigna

A partir de lo trabajado en el seminario, para este trabajo deberan entregar en un Jupyter Notebook lo siguiente:

- El origen del conjunto de datos que eligieron para la clasificación binaria.
- Justificación del problema de clasificación.
- Descripción del dataset y su adecuada exploración de los datos.

- Utilizando Scikit Learn, construir los siguientes modelos:

  - A partir de solo los atributos numericos continuos

    - Un modelo de Regresión Logistica para clasificación.
    - Un modelo de Arboles de Decisión.
  
  - A partir de tanto los atributos numericos continuos como los atributos categoricos del dataset

    - Otro modelo de Regresión Logistica para clasificación
    - Otro modelo de Arboles de Decisión

    Para este último modelo de Arbol de Decisión se debe hacer una exploración de sus posibles hiperparametros para hayar la mejor performance en Validación. Se puede hacer uso de algúna de las técnica de Validación vistas en clase. Con utilizar un _Holdout Set_ basta, pueden probar Cross Validation.

- Para todos los modelos se debe evaluar:
  - La performance haciendo uso de las metricas Precision y ROC AUC ambas ya implementadas en SK-Learn.
  - Mostrar una Matriz de Confusión sobre los datos de Test.
  - Interpretar la Importancia de Atributos, en el caso de Arboles investiguen como se puede obtener la "Feature Importance".

El notebook debe ejecutarse sin errores y debe incluir:

El nombre y apellido de los integrantes del grupo.
Una explicación de los pasos realizados y las conclusiones obtenidas.
Las visualizaciones generadas.
El código utilizado para responder a las preguntas y para generar las visualizaciones.

## 🔋 Bonus

Ajustar algúno de los modelos de Ensamble visto en clase, ya sea de Bagging o de Boosting. 
Recomiendo investigar la implementación de RandomForests de Scikit Learn para Bagging, y en cuanto a Boosting investigar XGBoost.

## Fecha de entrega

📅 Viernes 20 de Septiembre a las 23:59hs.

Se debe entregar en el siguiente [Google Forms](https://forms.gle/uojD9eTPsn2XyQ1A6) el Notebook con el análisis realizado.

## Links Útiles

https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#decisiontreeclassifier
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_score.html
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html
https://datascience.stackexchange.com/questions/116549/decision-tree-vs-logistic-regression-feature-importances

https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
https://xgboost.readthedocs.io/en/stable/

Ademas pueden utilizar los notebooks vistos en clase que están en este Repo de GitHub.
