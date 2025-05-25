# 🚖 Análisis de Datos de Yellow Taxi NYC (Marzo 2025)

## 📌 Descripción

Este proyecto forma parte del **Proyecto Integrador E1** del curso *Taller de Fortalecimiento al Egreso II - ICD*, Universidad del Valle de México.  
El objetivo es aplicar técnicas de **Minería de Datos** y **KDD (Knowledge Discovery in Databases)** para extraer conocimiento a partir de un dataset real del servicio de taxis amarillos de Nueva York.

---

## 🎯 Objetivo del Análisis

**Reducir el uso de efectivo** en los pagos de taxis amarillos en NYC, para:

- Mejorar la trazabilidad de transacciones
- Disminuir riesgos de seguridad
- Incrementar la eficiencia administrativa

### KPIs definidos:

| Indicador                          | Meta Esperada |
|-----------------------------------|---------------|
| % de pagos con tarjeta            | ≥ 70%         |
| % de pagos en efectivo            | ≤ 30%         |
| Tip promedio                      | > 10%         |
| % de pagos tipo “Dispute”         | < 2%          |
| Tendencia mensual en uso de tarjeta | Crecimiento sostenido |
| Ingresos brutos                   | Crecimiento sostenido |

---

## 📁 Archivos incluidos

- `yellow_tripdata_2025-03.parquet` – Dataset original descargado de [NYC TLC](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- `yellow_taxi_clean.csv` – Dataset limpio y transformado, listo para minería en Weka u otras herramientas
- `PIE1_ARC.ipynb` – Script en Python con todos los pasos de limpieza, imputación y transformación
- `PI_E1_ARC.pdf` – Documento académico con justificación, metodología y resultados

---

## 🧹 Proceso de Limpieza y Transformación

- Carga y exploración del dataset
- Validación de tipos de datos
- Imputación de valores nulos
- Eliminación de registros inconsistentes
- Derivación de nuevas variables (fecha, hora, duración)
- Reemplazo de códigos por etiquetas descriptivas
- Enriquecimiento geográfico con zonas y distritos
- Verificación de duplicados, negativos y outliers

---

## 🧠 Herramientas utilizadas

- **Python 3.10**
- **Pandas**
- **PyArrow**
- **Google Colab**


---

## 🔗 Fuentes y Referencias

> Ver sección de referencias en el documento `PI_E1_ARC.pdf`.

---

## 👤 Autor

**Antonio Rendón Córdova**  
Estudiante de Ingeniería en Ciencia de Datos  
Universidad del Valle de México – Campus Online

---

