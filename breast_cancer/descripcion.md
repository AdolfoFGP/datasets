# Breast Cancer Wisconsin (Diagnostic)

Conjunto original de datos: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

## Descripción
Este conjunto de datos contiene características computadas a partir de imágenes digitalizadas de aspirados con aguja fina (FNA) de masas mamarias. Cada registro representa una muestra de tejido mamario, clasificada como **benigna** o **maligna** según el diagnóstico realizado.  
Las características numéricas se obtienen mediante el análisis de imágenes de núcleos celulares presentes en la muestra.

El objetivo principal de este dataset es **clasificar tumores mamarios** en benignos o malignos en función de las características morfológicas de las células.

## Atributos
- `ID`: identificador único de la muestra.
- `Diagnostico`: tipo de tumor (B = Benigno, M = Maligno).
- `Radio`: media del radio (distancia desde el centro al perímetro) de los núcleos.
- `Textura`: desviación estándar de los valores de tono de gris.
- `Perimetro`: media del perímetro de los núcleos.
- `Área`: media del área de los núcleos.
- `Suavidad`: variación local de la longitud del radio.
- `Compacidad`: relación entre perímetro² y área - 1.0.
- `Concavidad`: gravedad de las porciones cóncavas del contorno.
- `Puntos_cóncavos`: número de porciones cóncavas del contorno.
- `Simetría`: simetría de los núcleos.
- `Dimensión_fractal`: aproximación de la “línea de costa” de los contornos.

Cada una de estas 10 características se mide en tres formas diferentes:
- **Media** (por ejemplo, `radio_mean`),
- **Desviación estándar** (por ejemplo, `radius_se`),
- **Valor máximo** o “peor” caso (por ejemplo, `radius_worst`).

En total, el dataset contiene **30 variables numéricas** derivadas de estas características, más el identificador y el diagnóstico.

## Información adicional
- **Número de instancias:** 569  
- **Número de atributos:** 32 (30 numéricos + ID + diagnóstico)  
- **Clases objetivo:**  
  - `M`: Maligno (212 casos)  
  - `B`: Benigno (357 casos)
