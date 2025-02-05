# Introducción al Aprendizaje Automático
## 1. Definición Oficial de Machine Learning
El Aprendizaje Automático (Machine Learning, ML) es un campo de la inteligencia artificial que permite a las computadoras aprender patrones a partir de datos sin ser programadas explícitamente. Según Arthur Samuel (1959), "Machine Learning es el campo de estudio que otorga a las computadoras la capacidad de aprender sin ser programadas de manera explícita."

Más formalmente, Tom Mitchell (1997) lo define así:
"Un programa de computadora aprende de la experiencia E con respecto a una tarea T y una medida de rendimiento P, si su desempeño en la tarea T, medido por P, mejora con la experiencia E."

# Tipos de Aprendizaje Automático y Modelos Comunes
## 2.1 Aprendizaje Supervisado
El modelo se entrena con datos etiquetados, es decir, ejemplos donde la respuesta correcta ya está disponible.

### 📌 Ejemplos prácticos:

Clasificación de correos electrónicos: Un modelo aprende a distinguir entre spam y no spam.
Reconocimiento de imágenes: Un modelo identifica si una imagen contiene un gato o un perro.
Predicción de precios de viviendas: Un modelo usa datos históricos (tamaño, ubicación, número de habitaciones) para estimar precios.
### 💡 Modelos típicos:

- Regresión Lineal: Predice valores numéricos (ej. precio de una vivienda).
- Árboles de Decisión: Clasifica datos en diferentes categorías.
- Máquinas de Soporte Vectorial (SVM): Encuentra el mejor límite entre clases de datos.
- Redes Neuronales Artificiales: Utilizadas en reconocimiento de imágenes y voz.

## 2.2 Aprendizaje No Supervisado
Aquí, el modelo no recibe etiquetas y descubre patrones en los datos por sí mismo.

### 📌 Ejemplos prácticos:

Segmentación de clientes: Un banco agrupa clientes según su comportamiento financiero.
Agrupación de noticias: Un algoritmo organiza artículos similares de diferentes fuentes.
Compresión de datos: Reducción de ruido en imágenes o textos.
### 💡 Modelos típicos:

- K-Means: Algoritmo de agrupación para identificar patrones en datos.
- Algoritmo de Clustering Jerárquico: Agrupa datos en una estructura de árbol.
- Reducción de Dimensionalidad (PCA): Extrae las características más relevantes de los datos.
- Modelos de Autoencoders: Utilizados en detección de anomalías o reducción de ruido.

## 2.3 Aprendizaje por Refuerzo
El modelo (agente) aprende interactuando con un entorno y recibiendo recompensas o penalizaciones según sus acciones.

### 📌 Ejemplos prácticos:

- Juegos y videojuegos: Un modelo aprende a jugar ajedrez mejorando su estrategia con cada partida.
- Robótica: Un robot optimiza su movimiento para caminar sin caerse.
- Optimización de tráfico: Un sistema de semáforos aprende a reducir la congestión.
### 💡 Modelos típicos:

- Q-Learning: Algoritmo básico de aprendizaje por refuerzo basado en tablas de valores.
- Deep Q-Networks (DQN): Variante que usa redes neuronales para aprender políticas óptimas.
- Algoritmo de Policy Gradient: Optimiza directamente las acciones a tomar.
- Modelo Actor-Crítico: Combinación de predicción y optimización para mejorar decisiones.
