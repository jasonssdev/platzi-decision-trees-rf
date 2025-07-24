# 🌳 Árboles de Decisión y Random Forest con Scikit-learn

[![Python](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.4.2-orange)](https://scikit-learn.org/stable/)
[![License](https://img.shields.io/github/license/jasonssdev/platzi-decision-trees-rf)](https://github.com/jasonssdev/platzi-decision-trees-rf/blob/main/LICENSE)
[![Made with ♥ by jasonssdev](https://img.shields.io/badge/made%20by-jasonssdev-red)](https://github.com/jasonssdev)

Este repositorio contiene ejercicios y ejemplos prácticos del curso de **Árboles de Decisión y Random Forest con Scikit-learn**, parte de la Escuela de Data Science de [Platzi](https://platzi.com).

Aprenderás a:

* Construir árboles de decisión desde cero.
* Visualizar la estructura del árbol.
* Entender el criterio de partición Gini y Entropía.
* Aplicar Random Forest para reducir el overfitting.
* Comparar desempeño entre modelos.

## 📁 Estructura del repositorio

```bash
.
├── data/                   # Conjuntos de datos utilizados
├── notebooks/              # Jupyter Notebooks con ejemplos paso a paso
├── src/                    # Código fuente de funciones y clases reutilizables
└── README.md               # Este archivo
```

## 🚀 Requisitos

Puedes crear un entorno virtual usando Conda a partir del archivo `environment.yml` incluido en el repositorio:

```bash
conda env create -f environment.yml
conda activate platzi-trees-rf
```

## 🤪 Librerías clave

* `scikit-learn`
* `matplotlib`
* `pandas`
* `numpy`
* `graphviz`

> 💡 **Nota**: Para visualizar árboles de decisión con `graphviz`, es necesario instalarlo también a nivel del sistema. [Instrucciones aquí](https://graphviz.gitlab.io/download/).

## 📊 Ejemplo de uso

```python
from sklearn.tree import DecisionTreeClassifier

model = DecisionTreeClassifier(max_depth=3)
model.fit(X_train, y_train)
```

## 📌 Temas cubiertos

* ¿Qué es un árbol de decisión?
* Criterios de división: Gini vs Entropía
* Overfitting y pruning
* Random Forest: combinación de múltiples árboles
* Importancia de características
* Métricas de desempeño (accuracy, confusion matrix)

## 📚 Recursos adicionales

* [Documentación oficial de scikit-learn](https://scikit-learn.org/stable/modules/tree.html)
* [Visualización de árboles de decisión](https://scikit-learn.org/stable/modules/tree.html#tree)

## 🧐 Autor

**Jason** - [@jasonssdev](https://github.com/jasonssdev)

---

📬 ¿Dudas o sugerencias? ¡Siéntete libre de abrir un [issue](https://github.com/jasonssdev/platzi-decision-trees-rf/issues)!
