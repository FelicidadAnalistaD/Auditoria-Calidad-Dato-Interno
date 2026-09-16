# 📊 Proyecto: Auditoría e Incremento de la Calidad del Dato Interno
**Analista:** FelicidadAnalistaD

---

## 🎯 Declaración de Trabajo (SOW) y Enfoque SMART
El objetivo de este proyecto es auditar, diagnosticar y corregir las inconsistencias críticas en el repositorio central de datos maestros de clientes (CRM) de la organización. Se busca garantizar la integridad de la información para evitar errores operativos en el equipo de ventas y asegurar reportes financieros 100% fiables para la dirección.

* **Específico y Medible:** Detectar el volumen exacto de registros duplicados, normalizar formatos de texto/fechas y aislar de forma automática las direcciones de correo electrónico inválidas.
* **Relevante:** Demostrar el impacto directo de la calidad y la gestión del dato en el cálculo de los ingresos reales del negocio.
* **Acotado:** Implementar una rutina de limpieza y validación visual en hojas de cálculo para reducir el índice de error por debajo del 2% en un plazo de 4 semanas.

---

## 🔍 Diagnóstico de la Auditoría (El "Antes")
Al recibir el repositorio original de 101 filas, se identificaron los siguientes fallos críticos universales que ponían en riesgo la operativa del negocio:
1. **Registros Duplicados:** Filas idénticas repetidas que inflaban artificialmente las métricas de clientes.
2. **Caos en Atributos de Texto:** Nombres mal formateados escritos en mayúsculas, minúsculas y con espacios en blanco dobles/triples indeseados que rompían las búsquedas.
3. **Correos Electrónicos Inválidos:** Direcciones de contacto rotas debido a la falta del carácter esencial `@`.
4. **Fechas Inconsistentes e Importes Nulos:** Fechas registradas en múltiples formatos mezclados y celdas de compras vacías que bloqueaban cualquier cálculo matemático global.

---

## 🛠️ Solución y Habilidades Aplicadas (El "Después")
Para resolver los fallos de la auditoría de forma eficiente y segura, se aplicaron las siguientes técnicas del curso de Google en la pestaña de datos limpios:

* **Depuración de Duplicados:** Se identificaron y eliminaron **21 filas duplicadas**, reduciendo la base de datos a **80 registros únicos y válidos** (eliminando un 21% de datos basura).
* **Normalización de Texto:** Uso de funciones avanzadas de texto combinadas (`NOMPROPIO` y `ESPACIOS`) para unificar y corregir el formato de los nombres de los clientes de golpe.
* **Validación Lógica:** Implementación de una fórmula condicional (`REGEXMATCH`) para cazar correos sin `@`, aplicando un **Formato Condicional visual en color rosa fucsia** para alertar de los errores en el cuadro de mando.
* **Tratamiento Estadístico de Vacíos (Imputación por la Media):** Se calculó el promedio global del negocio mediante la fórmula `=PROMEDIO` (dando un valor de **179,45 €**). Este dato se utilizó estratégicamente para rellenar los huecos vacíos sin alterar la media estadística de la empresa.
* **Cálculo Financiero de Cierre:** Se aplicó la función `=SUMA` sobre la columna depurada, obteniendo un valor real de ingresos de **14.176,58 €**.

---

## 🚀 Conclusión del Proyecto
Este ejercicio demuestra el valor real del control del dato: limpiar la base de datos no solo mejoró la calidad operativa del archivo, sino que permitió calcular con precisión quirúrgica el estado financiero real de la organización.

👉 **[Haz clic aquí para abrir la Hoja de Cálculo interactiva con las fórmulas en Google Sheets](https://docs.google.com/spreadsheets/d/1duecVLqiy1KxExTSZUg9Wwcli2t0nCKH4F49oMvb2jM/edit?usp=sharing)**
