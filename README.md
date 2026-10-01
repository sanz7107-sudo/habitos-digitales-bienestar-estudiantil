# Hábitos digitales y bienestar estudiantil

## 📊 Análisis exploratorio de datos

Proyecto correspondiente a la **Primera Entrega — Data Science II**.

El objetivo es analizar exploratoriamente la relación entre los hábitos digitales, los hábitos de vida y el bienestar de estudiantes.

## 🎯 Motivación

El uso de redes sociales y herramientas de Inteligencia Artificial forma parte de la vida cotidiana de los estudiantes.

Este proyecto busca explorar cómo estos hábitos digitales se relacionan con diferentes indicadores de bienestar, como el sueño, la actividad física y la salud mental y física.

## 👥 Público objetivo

El análisis está orientado a instituciones educativas, equipos de bienestar estudiantil y personas interesadas en comprender los hábitos digitales y de vida de los estudiantes.

## 📁 Dataset

El análisis utiliza el dataset:

**AI & Social Media Impact: Student Health & Grades**

Fuente: Kaggle

https://www.kaggle.com/datasets/srisyra02/ai-and-social-media-impact-student-health-and-grades

El dataset contiene:

- 16.000 estudiantes
- 10 variables originales
- Edad
- Género
- Nivel educativo
- Uso diario de redes sociales
- Uso diario de herramientas de IA
- Horas de sueño
- Actividad física
- Salud mental
- Salud física

## 🔎 Preguntas de análisis

El proyecto busca responder las siguientes preguntas:

1. ¿Existe una relación entre el uso de redes sociales y las horas de sueño?
2. ¿El uso de herramientas de IA se relaciona con el bienestar?
3. ¿Los estudiantes con mayor actividad física presentan mejores indicadores de bienestar?
4. ¿Existe una relación entre la intensidad del uso digital y el bienestar?
5. ¿Existen diferencias según el nivel educativo?

## 🧹 Preparación de los datos

Durante el análisis se realizaron:

- Verificación de valores nulos.
- Eliminación de registros duplicados.
- Verificación de errores.
- Corrección de tipos de datos.
- Creación del `Digital_Use_Index`.
- Creación del `Wellbeing_Index`.
- Creación del `AI_Use_Level`.

## 📈 Principales resultados

El análisis exploratorio permitió identificar diferentes asociaciones entre los hábitos digitales, los hábitos de vida y el bienestar estudiantil.

Entre los principales resultados se observa:

- Una asociación negativa entre el uso de redes sociales y las horas de sueño.
- Una asociación negativa entre el uso digital y el bienestar.
- Una asociación positiva entre la actividad física y el bienestar.
- Una disminución del bienestar promedio a medida que aumenta el nivel de uso de herramientas de IA.
- Una distribución similar del uso de IA entre los distintos niveles educativos.

> **Importante:** los resultados muestran asociaciones presentes en los datos analizados y no permiten establecer relaciones de causalidad.

## 📂 Archivos del proyecto

- `Primera_Entrega_Data_Science.ipynb` — Notebook con el análisis exploratorio, visualizaciones y resultados.
- `Presentacion_Habitos_Digitales.pdf` — Presentación ejecutiva con los principales resultados del análisis.

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Kaggle

## 🚀 Próximos pasos

Profundizar el análisis incorporando nuevas variables y explorando con mayor detalle los factores asociados al bienestar estudiantil.
