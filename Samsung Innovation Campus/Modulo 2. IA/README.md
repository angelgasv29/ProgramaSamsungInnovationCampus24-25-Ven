# 🤖 Módulo 2: Ciencia de Datos e Inteligencia Artificial

Este módulo marca mi inmersión profunda en el ecosistema de la Inteligencia Artificial. A diferencia de la programación tradicional, aquí el enfoque cambió: aprendí a preparar los datos, entender la matemática detrás de los algoritmos y entrenar modelos capaces de encontrar patrones y predecir resultados.

El recorrido abarca desde la manipulación avanzada de datos hasta la implementación de redes neuronales profundas.

### 🧠 Habilidades y Conceptos Clave

He dividido las competencias adquiridas en cuatro grandes pilares:

**1. Matemáticas, Estadística y Procesamiento de Datos**
*   **Álgebra Lineal Aplicada:** Manipulación de vectores y matrices con NumPy (matrices identidad, simétricas, cálculo de producto punto para medir similitud de imágenes y matrices inversas).
*   **Regresión Lineal desde cero:** Implementación del cálculo de vectores de pesos usando la fórmula matricial `(A^T A)^-1 A^T b` sin usar librerías de ML.
*   **Pandas y EDA:** Limpieza de datos, agrupaciones (`groupby`), tablas pivote y visualización de tendencias con Matplotlib.
*   **Estadística Inferencial:** Pruebas de hipótesis (errores Tipo I), cálculo de intervalos de confianza usando distribución T de Student (Scipy) y distribuciones de probabilidad (Binomial).

**2. Machine Learning (Aprendizaje Automático)**
*   **Aprendizaje Supervisado:** Implementación de Regresión Lineal, Árboles de Decisión (CART, CHAID), Naïve Bayes, KNN y Máquinas de Vectores de Soporte (SVM), entendiendo el ajuste de hiperparámetros como el parámetro `C` y `gamma`.
*   **Aprendizaje No Supervisado:** Algoritmos de agrupamiento (Clustering) como K-Means, DBSCAN y Agrupamiento Jerárquico. Aplicación del método del codo y BIC para elegir el número óptimo de clústeres.
*   **Evaluación de Modelos:** Diagnóstico de sobreajuste (*overfitting*), uso de validación cruzada y métricas de evaluación (precisión, recall).

**3. Procesamiento de Lenguaje Natural (NLP)**
*   **Minería de Texto:** Preprocesamiento, reducción de palabras a su raíz (*Stemming*) y conceptos de corpus.
*   **Modelos Lingüísticos:** Cálculo de la Frecuencia de Términos (TF) para determinar la importancia de palabras en un texto.

**4. Redes Neuronales y Deep Learning**
*   **Fundamentos:** Estudio del Perceptrón, tensores, propagación hacia atrás (*backpropagation*) y funciones de activación (implementación matemática de la función *Softmax* usando NumPy).
*   **Arquitecturas Avanzadas:** Exploración de Redes Neuronales Convolucionales (CNN) para imágenes (ej. dataset MNIST), Redes Recurrentes (RNN) para secuencias y Redes Generativas Antagónicas (GAN).
*   **Optimización:** Técnicas de preprocesamiento de datos (escalado y normalización) y métodos para evitar el sobreajuste, como el *Dropout* y los Autoencoders.

### 🏆 Proyecto Destacado (Capstone Project): EcoClass - Clasificador de Imágenes con CNN

El punto culminante del programa fue **EcoClass**, nuestro proyecto final desarrollado para el **Hackathon de cierre del Samsung Innovation Campus (SIC 2024-2025)**. La temática central del evento era la "Recuperación Económica Post-Pandemia" con impacto social, y nuestro equipo decidió aportar nuestro grano de arena al problema del reciclaje.

**El desafío:**
¿Cómo podemos usar la IA para crear conciencia ambiental y facilitar el reciclaje a usuarios comunes? Construimos una solución que permite a cualquier persona subir una foto (o usar la cámara en vivo) de un residuo, y el modelo lo clasifica automáticamente en 5 categorías (cartón, vidrio, metal, papel y plástico), brindando información útil sobre cómo desecharlo correctamente.

**Mi rol en el equipo:**
Fui responsable de la **ciencia de datos y el entrenamiento** detrás del modelo:
*   🧹 **Preprocesamiento del Dataset:** Limpieza, aumento de datos (*data augmentation*) y preparación de las imágenes para la red neuronal.
*   💡 **Ideas y pruebas de entrenamiento:** Experimentación con la arquitectura de la CNN (usando TensorFlow/Keras) y ajuste de hiperparámetros.
*   📈 **Monitoreo y ajuste de resultados:** Análisis de las curvas de pérdida y precisión, y ajuste del modelo para evitar el sobreajuste y mejorar la exactitud en la clasificación final.

**El Hito:**
El proyecto fue presentado en vivo ante un **jurado nacional y una audiencia internacional** a través de Zoom durante el Hackathon de cierre. Logramos llevar un prototipo funcional con una **interfaz gráfica (Tkinter)** que permitía interactuar con el modelo en tiempo real.

*   **Tecnologías usadas:** Python, TensorFlow, Keras, OpenCV, Scikit-Learn, Tkinter.
*   **Dataset:** [Waste Classification Data (Kaggle)](https://www.kaggle.com/datasets/techsash/waste-classification-data)
*   **🔗 Repositorio del proyecto:** [EcoClass - Lights of Hope IA](https://github.com/JulioZambrano91/Lighs-of-Hope-IA)
*   **📺 Video Demo:** [EcoClass en YouTube](https://youtu.be/zuuZbU1gVeA)
