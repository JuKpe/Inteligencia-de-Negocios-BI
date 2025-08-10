# ✈️ Análisis de Vuelos de Aerolíneas en India - Power BI

Este proyecto presenta un análisis visual interactivo sobre datos de vuelos nacionales en India. A través de un dashboard en Power BI, se responden preguntas clave relacionadas con precios, aerolíneas, horarios, ciudades, clases y comportamiento de compra anticipada.

Conjunto de datos de vuelos de aerolíneas para diferentes ciudades
El conjunto de datos de reservas de vuelos de varias aerolíneas se extrae por fecha de un sitio web 
conocido en un formato estructurado. Contiene los registros de detalles de vuelos entre ciudades de la India. 
Incluye diversas características, como ciudad de origen y destino, hora de llegada y salida, duración y precio del 
vuelo, etc.

Estas son las principales características/columnas disponibles en el conjunto de datos:

1) Aerolínea: El nombre de la aerolínea se almacena en la columna "Aerolínea". Es una característica categórica que 
incluye 6 aerolíneas diferentes.

2) Vuelo: Vuelo almacena información sobre el código de vuelo del avión. Es una característica categórica.

3) Ciudad de origen: Ciudad desde la que despega el vuelo. Es una característica categórica con 6 ciudades únicas.

4) Hora de Salida: Esta es una característica categórica derivada que se obtiene agrupando períodos de tiempo en 
intervalos. Almacena información sobre la hora de salida y tiene seis etiquetas de tiempo únicas.

5) Paradas: una característica categórica con 3 valores distintos que almacena el número de paradas entre las ciudades 
de origen y destino.

6) Hora de llegada: Esta es una característica categórica derivada que se crea agrupando intervalos de tiempo en 
contenedores. Tiene seis etiquetas de tiempo distintas y guarda información sobre la hora de llegada.

7) Ciudad de destino: Ciudad donde aterrizará el vuelo. Es una característica categórica con 6 ciudades únicas.

8) Clase: Característica categórica que contiene información sobre la clase del asiento; tiene dos valores distintos: 
Business y Economy.

9) Duración: una característica continua que muestra la cantidad total de tiempo que lleva viajar entre ciudades en 
horas.

10) Días restantes: es una característica derivada que se calcula restando la fecha del viaje a la fecha de reserva.

11) Precio: La variable objetivo almacena información del precio del billete.
---

## 🎯 Objetivos del Proyecto

- Explorar las diferencias de precio entre aerolíneas, horarios y clases.
- Visualizar la distribución de vuelos por ciudad de origen, destino y horario.
- Comprender cómo los días de anticipación afectan el precio del pasaje.
- Comparar precios según combinaciones de ruta y clase.
- Generar insights útiles para viajeros y compañías aéreas.

---

## 📊 Preguntas Respondidas

**P.1.** ¿Cuáles son las aerolíneas incluidas en el conjunto de datos, junto con sus frecuencias?
- Se analizaron 6 aerolíneas, siendo **Vistara** la que tiene mayor cantidad de vuelos, seguida por **Air India** e **Indigo**.

**P.2.** ¿Cómo se distribuyen los vuelos según hora de salida y llegada?
- La mayoría de vuelos salen en la **mañana y madrugada**, y llegan en la **noche y tarde**.

**P.3.** ¿Cuál es la distribución de vuelos por ciudad de origen y destino?
- **Delhi y Mumbai** lideran tanto en salidas como en llegadas, seguidas por Bangalore, Kolkata, Hyderabad y Chennai.

**P.4.** ¿El precio varía según la aerolínea?
- Sí. **Vistara y Air India** tienen los precios más altos, mientras que **AirAsia y Indigo** ofrecen precios más bajos en promedio.

**P.5.** ¿El precio varía según la hora de salida y llegada?
- Sí. Los vuelos que salen o llegan en la **noche o madrugada** tienden a ser más caros, mientras que los del mediodía o tarde suelen ser más económicos.

**P.6.** ¿Cómo varía el precio según origen y destino?
- Por ciudad de origen, **Chennai y Kolkata** presentan los precios más altos. Por destino, destacan **Kolkata y Chennai** también.

**P.7.** ¿Cómo influye la anticipación en el precio del pasaje?
- Se observó que los precios pueden ser **más bajos o más altos** dependiendo del número de días de anticipación. En algunos casos, los pasajes comprados **2–5 días antes** tienen picos de precio.

**P.8.** ¿Cómo varía el precio entre clases?
- La **clase Business** tiene un precio promedio de **53 mil**, mientras que **Economy** es de solo **7 mil**.

**P.9.** ¿Cuál es el precio promedio de la aerolínea Vistara para un vuelo de Delhi a Hyderabad en clase ejecutiva?
- El precio promedio para esta combinación es de **55 mil**.

---

## 🛠️ Herramientas Utilizadas

- **Power BI Desktop**
- Transformación de datos en Power Query
- Visualizaciones: gráficos de barras, líneas, tarjetas KPI, mapas y segmentadores

---

## 📂 Archivos del Proyecto

- `vuelos_aerolineas.pbix`: Archivo de Power BI
- `vuelos de aerolíneas.pdf`: Vista previa del dashboard

---

## 📎 Fuente del Dataset

[Airlines Flights Dataset en Kaggle](https://www.kaggle.com/code/rohitgrewal/airlines-flights-data-analysis-with-python-dsl)

---
