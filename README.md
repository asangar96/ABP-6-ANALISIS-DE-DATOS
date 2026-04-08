# Análisis Estadístico y Modelado: Bienestar y Éxito Académico Universitario

## 1. Descripción del Proyecto
Este repositorio documenta un estudio estadístico integral realizado sobre una muestra de 400 jóvenes universitarios. El objetivo principal fue cuantificar mediante rigor científico cómo los hábitos de vida —específicamente el sueño, la actividad física y el estrés— impactan en el rendimiento académico (medido en una escala de 1.0 a 7.0).

Este proyecto forma parte de mi portafolio de análisis de datos y demuestra la capacidad de transformar observaciones empíricas en evidencia estadística válida para la toma de decisiones institucionales, complementando mis proyectos anteriores en Inteligencia de Negocios y análisis predictivo.

### Variables Analizadas:
* **Variable Dependiente:** Promedio académico.
* **Variables Independientes:** Horas de sueño diarias, minutos de actividad física semanal, nivel de estrés percibido (escala 1-10).
* **Variables de Control:** Edad, género y frecuencia de consumo de comida chatarra.

## 2. Limpieza de Datos y Análisis Descriptivo
Para asegurar la calidad de las inferencias, se aplicaron técnicas de preprocesamiento estructurado (utilizando lógicas de herramientas como Pandas/Python):
* **Tratamiento de Nulos y Outliers:** Se imputaron valores faltantes en la base de datos mediante la media poblacional y se corrigieron valores atípicos detectados en la variable de rendimiento académico.
* **Hallazgos Iniciales:**
  * **Sueño:** La media se situó en 6.5 horas, detectando privación de sueño recurrente en el 15% de la muestra.
  * **Estrés:** La mediana reportada fue de 6/10, evidenciando una tendencia hacia el agotamiento emocional en periodos de evaluación.
  * **Actividad Física:** Se observó una alta dispersión, marcando una fuerte polarización entre estudiantes sedentarios y aquellos que cumplen las métricas de la OMS.

## 3. Análisis Probabilístico e Inferencia Estadística
Se modeló el comportamiento de la población universitaria utilizando herramientas de estadística avanzada:
* **Distribuciones Paramétricas:** Se validó mediante la Campana de Gauss que el rendimiento académico sigue una distribución normal, permitiendo el uso de pruebas paramétricas.
* **Intervalos de Confianza (95%):** Se estimaron los límites reales poblacionales para las horas de sueño y el promedio, obteniendo una estrechez de intervalos que confirma el bajo error estándar de la muestra.
* **Contraste de Hipótesis (T de Student):** Se evaluó a dos grupos independientes (sueño $\ge 7h$ vs. $< 7h$). El P-valor resultante permitió rechazar la hipótesis nula, demostrando de forma estadísticamente significativa que la higiene del sueño es un predictor del éxito.

## 4. Correlación y Modelado Predictivo
Se determinó la fuerza de asociación entre las variables de estudio implementando modelos matemáticos:
* **Análisis de Correlación (Pearson):** Se identificó una correlación negativa clara entre el nivel de estrés y el promedio académico obtenido.
* **Regresión Lineal Múltiple:** Se construyó un modelo algorítmico para predecir el promedio de un estudiante en función de sus horas de sueño y nivel de estrés. El coeficiente de determinación ($R^2$) indica que, aunque hay múltiples factores en juego, la salud explica una porción sustancial del desempeño.

## 5. Conclusiones y Recomendaciones Estratégicas
Aplicando principios de *Data Storytelling* para conectar los datos con decisiones del mundo real, se proponen las siguientes acciones a nivel directivo:
* **Priorización de la Higiene del Sueño:** El análisis probabilístico demuestra que la falta de sueño no es un caso aislado, sino un factor crítico correlacionado con bajas notas.
* **Gestión Institucional del Estrés:** Dado su impacto matemático negativo en el rendimiento, se recomienda dotar de mayores recursos a las unidades de apoyo psicológico durante épocas de exámenes.
* **Hacia una Universidad Saludable:** Los datos prueban empíricamente que la salud física y mental es el cimiento de la eficiencia intelectual; por tanto, las políticas de bienestar deben integrarse de forma obligatoria en la estrategia académica institucional.
