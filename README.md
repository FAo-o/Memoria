
# Categorización de los tipos de ciberbullying presentes en publicaciones de redes sociales.

Este repositorio contiene el código desarrollado para la memoria de título enfocada en la **detección y categorización de ciberacoso en publicaciones de redes sociales** mediante técnicas de procesamiento de lenguaje natural (NLP) y aprendizaje automático.

## Descripción del Proyecto

Se implementó un pipeline de clasificación multiclase para identificar distintos tipos de ciberacoso en tuits, utilizando un conjunto de modelos supervisados y técnicas de agrupamiento no supervisado para explorar patrones temáticos presentes en los datos.

Los modelos fueron entrenados, evaluados y comparados considerando métricas estándar de clasificación y se optimizaron mediante validación cruzada.

## Modelos Implementados

### Modelos supervisados:
- Regresión Logística
- Support Vector Machine (SVM)
- Árbol de Decisión
- Random Forest
- k-Nearest Neighbors (k-NN)
- Naive Bayes
- Multilayer Perceptron (Red Neuronal)

### Modelos no supervisados:
- K-Means
- DBSCAN
- LDA (Latent Dirichlet Allocation)
- Agglomerative Clustering
  

## Principales librerías utilizadas:

- `scikit-learn`
- `matplotlib`, `seaborn`
- `pandas`, `numpy`
- `nltk`, `spacy`

## Notas

- El dataset utilizado contiene ejemplos reales de ciberacoso, por lo que algunos textos pueden ser ofensivos. Todo el contenido es tratado con fines exclusivamente académicos.
- El proyecto fue desarrollado en el marco de una memoria de título de ingeniería.

---

Proyecto desarrollado por Fernanda Juliana Avendaño Jara — 2025.
