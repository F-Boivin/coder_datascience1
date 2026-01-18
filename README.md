# Wine Quality Analysis - Coderhouse Data Science 🍷

Este proyecto forma parte del curso de **Data Science de Coderhouse**. El objetivo es analizar las propiedades fisicoquímicas de diferentes variantes de vino y su relación con la calidad percibida.

## 📊 Origen de los Datos
Los datos provienen del **UCI Machine Learning Repository**:
* **Dataset:** [Wine Quality](https://archive.ics.uci.edu/dataset/186/wine+quality)
* **Paper de Referencia:** *Modeling wine preferences by data mining from physicochemical properties* (P. Cortez et al., 2009). Publicado en *Decision Support Systems*.

---

## 🧪 Descripción del Dataset
El dataset contiene información sobre variantes de vino tinto y blanco. Las muestras fueron evaluadas por expertos y se les asignó una calificación de calidad.

### Diccionario de Variables

| Variable | Tipo | Descripción |
| :--- | :--- | :--- |
| **Fixed acidity** | Input | Ácidos fijos del vino |
| **Volatile acidity** | Input | Cantidad de ácido acético |
| **Citric acid** | Input | Ácido cítrico |
| **Residual sugar** | Input | Azúcar restante tras el fin de la fermentación. |
| **Chlorides** | Input | Cantidad de sal en el vino. |
| **Free sulfur dioxide** | Input | Forma libre de SO2. |
| **Total sulfur dioxide** | Input | Cantidad total de SO2. |
| **Density** | Input | Densidad del vino. |
| **pH** | Input | Describe qué tan ácido o alcalino es el vino (escala 0-14). |
| **Sulphates** | Input | Aditivo que actúa como antimicrobiano y antioxidante. |
| **Alcohol** | Input | Porcentaje de contenido de alcohol. |
| **Quality** | **Output** | Puntaje de calidad (entre 0 y 10). |

### 📝 Notas sobre el Dataset
El archivo original obtenido de UCI Machine Learning Repository utilizaba puntos y coma (`;`) como delimitador. 

Para permitir la visualización interactiva en GitHub, el dataset incluido en este repositorio ha sido modificado:
* **Separador de columnas:** Se cambió de `;` a `,`.
* **Decimales:** Se mantuvieron como punto (`.`).
