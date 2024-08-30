## Continuando con la actividad de la semana pasada:

- Utilizando solo los atributos numericos, construir y entrenar un Arbol de Decisión para la clasificación con Sklearn.
- Evaluar el modelo y comparar los resultados con los de la Regresión Logistica

- Manejar las variables categoricas como vimos en clase para poder incorporarlas como variables predictoras a un nuevo modelo de Regresión Logistica
- Entrenar otro Arbol de Decisión ahora utilizando tambien las variables categóricas (además de las numéricas).
- Evaluar los nuevos modelos y comparar los resultados.

Tip: Pueden hacer uso del `LabelEncoder` y el `OneHotEncoder` de Scikit Learn para el preprocesamiento de las variables categóricas.

[`LabelEncoder` https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html)

```{python}
from sklearn.preprocessing import LabelEncoder
# Pueden Instanciar un LabelEncoder de sklearn
le = LabelEncoder()

# Le pasan los valores categóricos que conocen
le.fit(["paris", "paris", "tokyo", "amsterdam"])
list(le.classes_) # ['amsterdam', 'paris', 'tokyo']

# Pueden entonces pasar nuevos valores y genera una lista de nros por cada valor (por ejemplo paris:2, tokyo: 1, etc)
le.transform(["tokyo", "tokyo", "paris"]) # => array([2, 2, 1]...)

# Tambien pueden hacer la inversa, pasarle una lista de nros de labels y devuelve la clase en str original
list(le.inverse_transform([2, 2, 1]))  # => ['tokyo', 'tokyo', 'paris']
```

[`OneHotEncoder` https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
