**Uso de redes sociales y su relación con indicadores de salud mental en jóvenes (18–22 años)** 📲

## 🎯 Contexto
Este proyecto realiza un análisis exploratorio detallado sobre uso de redes sociales con el objetivo de identificar factores clave que afectan a salud mental en jóvenes (18–22 años)

## 📊 Dataset
- **Fuente:**: https://www.kaggle.com/datasets/bertnardomariouskono/social-media-and-mental-health
- **Descripción:** El conjunto de datos incluye 8000 registros y 15 columnas.
- **Diccionario:**
      User_ID: Unique identifier.
      Age: User age 
      Gender: Biological sex (Male/Female).
      User_Archetype: Persona category (e.g., 'Digital Minimalist', 'Hyper-Connected').
      Primary_Platform: The app where the user spends the most time.
      Daily_Screen_Time_Hours: Total active screen time per day.
      Dominant_Content_Type: Main genre consumed (e.g., Gaming, Lifestyle).
      Activity_Type: 'Active' (posting) vs 'Passive' (scrolling).
      Late_Night_Usage: 1 if user is active after 12:00 AM, 0 otherwise.
      Social_Comparison_Trigger: 1 if content consumed typically induces envy/insecurity.
      Sleep_Duration_Hours: Average nightly sleep.
      GAD_7_Score: Anxiety score (0-21).
      GAD_7_Severity: Categorical interpretation (Minimal to Severe).
      PHQ_9_Score: Depression score (0-27).
      PHQ_9_Severity: Categorical interpretation (None to Severe).

## 🛠️ Metodología
1.  **Limpieza:**
   - No se identificaron valores nulos, faltantes ni registros duplicados en ninguna de las columnas
   - Se corrigió el formato numérico de las columnas “Daily_Screen_Time_Hours” y “Sleep_Duration_Hours”
   - Para facilitar su interpretación, se generó una nueva columna a partir de “Late_Night_Usage” donde se "transforman" el 1 como Activo y el 0 como No Activo y la llamamos "Late_Night_Usage_String"
   - Se realizó el mismo proceso con la columna "Social_Comparasion_Trigger" donde 0 representa ausencia de comparación social y 1 indica que el contenido visualizado sí la genera
3.  **Visualización:** Cambiamos el nombre de la columna GAD Score a Anxiety Score para poder entenderlo mejor a la hora del análisis descriptivo. 
4.  **Análisis:**

    Tras el proceso de depuración y transformación de los datos, se analizaron los patrones de comportamiento de jóvenes de entre 18 y 22 años, tanto hombres como mujeres en diversas plataformas de redes sociales (Facebook, TikTok, Snapchat, Instagram, YouTube, Twitter/X y LinkedIn), así como las características asociadas en su salud mental.
    
    La distribución por género dentro de la muestra es prácticamente equitativa: un 50,35% corresponde a mujeres y un 49,65% a hombres. El tiempo medio diario dedicado al uso de redes sociales es de 4,5 horas. TikTok se posiciona como la plataforma más utilizada, seguida de Instagram y Twitter/X. El tipo de contenido más consumido es el relacionado con Lifestyle y Fashion.
    
    El 37,94% de los participantes continúa activo en redes sociales después de las 00:00. En relación con este comportamiento, se observa que el promedio de horas de sueño se sitúa en torno a las 6 horas diarias.
En cuanto a los indicadores de salud mental, los resultados preliminares muestran que el 8,15% de los encuestados obtuvo una puntuación de 0 en la escala de ansiedad (máximo 21 puntos), mientras que únicamente el 0,11% alcanzó la puntuación máxima. Respecto a la escala de depresión, el 23,23% obtuvo una puntuación de 0, y solo el 0,03% alcanzó la puntuación máxima de 22.

## 📈 Hallazgos Principales

          Caracterización de la muestra
      La muestra analizada está compuesta por 8.000 jóvenes con edades comprendidas entre los 18 y 22 años. La distribución por género es prácticamente equitativa, con un 50,35% de mujeres y un 49,65% de hombres, lo que permite analizar los resultados sin un sesgo significativo asociado a esta variable.
      En cuanto al perfil digital, TikTok se posiciona como la plataforma predominante, seguida de Instagram y Twitter/X. El tipo de contenido más consumido se asocia principalmente a categorías de Lifestyle y Fashion, lo que sugiere una orientación hacia contenidos aspiracionales, de imagen y estilo de vida.
          Hábitos de uso de redes sociales
      El tiempo promedio de uso diario de redes sociales se sitúa en 4,5 horas. Esta cifra representa aproximadamente el 19% del total de horas del día, lo que indica una integración intensiva de las plataformas digitales en la rutina cotidiana de los participantes.
      Asimismo, el 37,94% de los encuestados declara permanecer activo en redes sociales después de las 00:00 horas. Este comportamiento nocturno se relaciona con una reducción del descanso, observándose un promedio de 5,8 horas de sueño diario, cifra inferior a las recomendaciones habituales para este grupo etario.
      Estos datos evidencian un patrón de uso elevado y potencialmente invasivo en términos de tiempo y descanso.
          Indicadores de ansiedad
      La distribución de la escala de ansiedad muestra que una proporción reducida de la muestra presenta puntuaciones extremas. El 8,15% obtiene una puntuación mínima (0), mientras que el porcentaje de personas que alcanza la puntuación más alta posible en la escala es muy bajo, prácticamente residual dentro de la muestra.
      Sin embargo, el análisis categórico permite observar una presencia relevante de niveles leves y moderados, lo que sugiere que una parte significativa de la muestra experimenta sintomatología ansiosa en distintos grados.
      Lo más relevante no son los casos extremos, sino la cantidad de jóvenes que presentan niveles leves o moderados de ansiedad, lo que sugiere que este tipo de sintomatología podría estar relativamente extendida y “normalizada” en la muestra.
          Indicadores de depresión
      En relación con la escala de depresión, el 23,23% de los participantes presenta puntuación mínima (0), mientras que los valores máximos son prácticamente residuales.
      Al igual que en el caso de la ansiedad, la mayor parte de la distribución se concentra en niveles leves y moderados, lo que indica la presencia extendida de síntomas depresivos no severos dentro de la muestra.
      Esta distribución sugiere que, si bien los casos severos no son predominantes, sí existe una base amplia de sintomatología leve o moderada que podría requerir atención preventiva.
          Observaciones descriptivas integradas
      De manera agregada, los resultados muestran:
      •	Uso intensivo de redes sociales (4,5 horas diarias).
      •	Alta prevalencia de uso nocturno.
      •	Reducción promedio de horas de sueño.
      •	Presencia significativa de sintomatología ansiosa y depresiva en niveles leves y moderados.
      Los resultados descriptivos evidencian la presencia simultánea de patrones elevados de uso digital y una proporción considerable de indicadores de malestar psicológico.
      Es importante precisar que este estudio describe patrones y distribuciones dentro de la muestra, pero no permite afirmar que el uso de redes sociales sea la causa de los niveles de ansiedad o depresión identificados.

## 🛠️ Tecnologías
-Excel 

