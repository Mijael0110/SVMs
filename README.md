# Clasificación de Cáncer de Mama con SVM

Este proyecto implementa un modelo de **Máquinas de Vectores de Soporte (SVM)** para la **clasificación binaria** de diagnósticos de cáncer de mama, utilizando el conjunto de datos **Breast Cancer Wisconsin** de `scikit-learn`.

El objetivo es predecir si un tumor es **benigno** o **maligno** a partir de mediciones extraídas de imágenes digitalizadas de aspiraciones con aguja fina de masas mamarias. A parti de un data set propio de la librería sklearn sklearn.datasets.load_breast_cancer(*, return_X_y=False, as_frame=False)

---

## Dataset

- Fuente: `sklearn.datasets.load_breast_cancer`
- Clases:
  - **0** → Maligno
  - **1** → Benigno
- Número de características: 30 (medidas físicas de las células tumorales)
- Número de instancias: 569

---

## Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## Instalación y uso

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/usuario/cancer-mama-svm.git
   cd cancer-mama-svm
