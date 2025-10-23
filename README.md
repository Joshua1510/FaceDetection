


---


# Detección y Clasificación de Rostros con Machine Learning 🤖  

Este proyecto implementa un flujo completo de procesamiento de imágenes y clasificación para la detección y reconocimiento facial utilizando OpenCV y diversas técnicas de Machine Learning.  

---

## Descripción del proyecto  
El propósito de este proyecto es desarrollar un sistema capaz de detectar y clasificar rostros en imágenes. El flujo de trabajo incluye la detección facial mediante clasificadores, el preprocesamiento de las imágenes y la posterior extracción de características para su clasificación. Se prueban múltiples algoritmos supervisados como **KNN**, **Naive Bayes**, **LDA** y **PCA** para comparar su desempeño. Es complementado evaluando los modelos utilizando métricas y usando visualizaciones gráficas de los resultados.  

---

## Tecnologías utilizadas  
- **Python 3.12**  
**OpenCV - NumPy - Pandas - Matplotlib - Seaborn - Scikit-learn - Scipy - Scikit-image**  

---

## Flujo del código  
El proyecto comienza con la importación de las imágenes faciales, seguida de la detección de rostros utilizando el clasificador Haar Cascade. Los rostros detectados se recortan, redimensionan y se les aplica un filtro gaussiano para reducir el ruido y resaltar las características. Posteriormente, las imágenes procesadas se dividen en entrenamiento y prueba, se estandarizan y se entrenan diversos modelos de Machine Learning. Luego, se calculan métricas de rendimiento y matrices de confusión para comparar los resultados de los modelos. Finalmente, se presenta las visualizaciones y análisis de desempeño para cada algoritmo.  

---

## Resultados esperados  
Se genera un sistema de detección y reconocimiento de rostros capaz de identificar rostros a partir de un conjunto de imágenes. Muestra métricas comparativas de desempeño entre diferentes algoritmos y presenta los resultados mediante gráficos estadísticos, facilitando la interpretación del comportamiento de los modelos y su precisión en el reconocimiento facial.  

---

## Autor  
**Joshua Arango Fabbri**  
Ingeniero Electrónico  
Cali, Colombia  
[Email](mailto:joshuaarango82@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/joshua-arango-295589326/)  
