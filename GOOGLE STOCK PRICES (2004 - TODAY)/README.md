# 📈 Google Stock Prices (2004 - Today) - Dashboard Power BI

Este proyecto presenta un análisis visual de los precios diarios de las acciones de **Alphabet Inc. (GOOGL)** desde 2004 hasta la fecha. El dashboard desarrollado en Power BI integra indicadores técnicos ampliamente utilizados en el análisis bursátil, como **SMA**, **RSI** y **MACD**, junto con métricas de precios y volumen.

---

## 🎯 Objetivo

Brindar una herramienta visual que permita:
- Analizar la evolución de precios y volúmenes de GOOGL.
- Identificar tendencias, niveles de soporte/resistencia y momentos clave del mercado.
- Aplicar indicadores técnicos para respaldar decisiones de inversión.

---

## 📊 Principales Métricas

- **Precio Máximo Promedio:** $177.32  
- **Precio Mínimo Promedio:** $172.90  
- **Volumen Promedio:** 36.93 millones de acciones negociadas  
- **SMA_20 promedio:** 45.87 mil (calculado sobre precios de cierre)

---

## 📈 Indicadores Técnicos Incluidos

### 🔹 SMA (Simple Moving Average - Media Móvil Simple)

<img width="725" height="201" alt="image" src="https://github.com/user-attachments/assets/dcd55cae-c65f-46cb-8649-b1fdea2796ef" />

- **Interpretación:** Muestra la tendencia general del precio eliminando fluctuaciones diarias. Un precio por encima de la SMA puede indicar tendencia alcista; por debajo, tendencia bajista.

---

### 🔹 RSI (Relative Strength Index)

<img width="730" height="293" alt="image" src="https://github.com/user-attachments/assets/df7c2234-43c2-4cc8-a85a-404ae6b32368" />

- **Interpretación:** Mide la fuerza y velocidad de los movimientos de precio.  
  - RSI > 70 → activo en **sobrecompra** (posible corrección bajista).  
  - RSI < 30 → activo en **sobreventa** (posible rebote alcista).

---

### 🔹 MACD (Moving Average Convergence Divergence)
- **Cálculo:**
  1. Calcular EMA de 12 días (rápida)
  2. Calcular EMA de 26 días (lenta)
  3. **MACD** = EMA(12) - EMA(26)
  4. **Línea de señal** = EMA(9) del MACD
  5. **Histograma** = MACD - Señal
- **Interpretación:**
  - Cruce de MACD por encima de la señal → posible compra.
  - Cruce de MACD por debajo de la señal → posible venta.

---

## 📉 Visualizaciones del Dashboard

- **Volumen de acciones negociadas por fecha** → identifica días de alta actividad.
- **Precios más altos y más bajos diarios** → detecta niveles extremos.
- **RSI por fecha** → identifica zonas de sobrecompra/sobreventa.
- **MACD, Signal y Histograma** → mide momentum y posibles cambios de tendencia.
- **Serie temporal de SMA_20** → tendencia suavizada del precio.

---

## 🛠️ Herramientas Utilizadas

- **Power BI Desktop**
- Power Query para limpieza y transformación de datos
- DAX para el cálculo de indicadores técnicos (SMA, RSI, MACD)
- Gráficos de líneas y áreas para series temporales
- Segmentadores por año y rango de fechas

---

## 📎 Fuente del Dataset

[Google Daily Stock Prices (2004 - Today) - Kaggle](https://www.kaggle.com/datasets/emrekaany/google-daily-stock-prices-2004-today)

---

## 📂 Archivos del Proyecto

- `google_stock_prices.pbix` → Archivo editable de Power BI
- `GOOGLE STOCK PRICES (2004 - TODAY).pdf` → Exportación del dashboard

---

## 📌 Conclusión

Este dashboard permite un monitoreo integral de la evolución histórica de GOOGL, combinando métricas de precio y volumen con indicadores técnicos para análisis financiero. La inclusión de SMA, RSI y MACD brinda una visión más profunda para quienes realizan análisis técnico y buscan optimizar decisiones de inversión.
