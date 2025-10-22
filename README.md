# Prueba_Conciliacion
Repositorio con la prueba técnica de conciliación entre DB  y Report FX, con normalización y control de efectivo 
# 🧾 Conciliación de Datos – Prueba Técnica

Este proyecto presenta una prueba técnica de conciliación de datos realizada en **Microsoft Excel**, aplicando herramientas de **Power Query**, **tablas dinámicas** y **fórmulas de normalización**.  

El objetivo principal fue **procesar y conciliar información proveniente de distintas fuentes**, detectando inconsistencias y asegurando la correspondencia entre registros.  

---

## 📂 Estructura del archivo

**Archivo principal:** `Conciliacion_Prueba.xlsx`

El libro incluye las siguientes secciones:

- **Bases RAW:** hojas con los datos originales de entrada.  
- **Bases Normalizadas:** procesamiento y limpieza mediante Power Query y fórmulas.  
- **Conciliación:** hoja central donde se integran y comparan los datos de distintas fuentes.  
- **Control_Cash:** hoja dedicada al cálculo de la **comisión deducida por la tarjeta**, en función del valor del comprobante (`mov_amount`) y el CUIT (`pay_collector_document`).  
- **Resumen final:** incluye los resultados conciliados y un gráfico de presentación.  

> 🟢 *Se incorporó un gráfico resumen con el objetivo de mejorar la presentación visual del análisis y facilitar la interpretación de los resultados conciliados. Esta mejora no formaba parte de la consigna original.*

---

## 🔍 Alcance y observaciones

- Se respetaron los lineamientos de la consigna técnica, ajustando el modelo para que las fórmulas y transformaciones sean totalmente reproducibles.  
- Para optimizar el tamaño del archivo y facilitar su uso en el repositorio, se redujo la cantidad de registros de las bases de datos originales (**muestra de 100 filas por tabla**).  
- Algunas inconsistencias detectadas en los datos originales fueron **ajustadas mínimamente** para lograr un ejemplo representativo de conciliación completa.  
- Los nombres de archivos y hojas fueron **estandarizados** para mayor claridad.  
- Las fórmulas fueron diseñadas para poder ejecutarse en versiones de Excel anteriores a **Microsoft 365**.  

---

## ⚙️ Herramientas utilizadas

- Microsoft Excel (versión desktop, no 365)  
- Power Query para conexión, transformación y normalización de datos  
- Tablas dinámicas y fórmulas de búsqueda y validación  
- Gráficos para visualización de resultados  

---

## 📈 Resultado final

El archivo final refleja un proceso completo de conciliación con estructura profesional, adaptable a escenarios reales de **control financiero** o **auditoría de movimientos**, incluyendo el cálculo de comisiones y la validación cruzada entre fuentes de datos.  

---

👤 **Autor/a:** CraQAControl  
📅 **Versión:** Octubre 2025  
📎 **Archivo:** `Conciliacion_Prueba.xlsx`

