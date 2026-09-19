# 📊 Proyecto: Auditoría e Incremento de la Calidad del Dato Interno
**Analista:** FelicidadAnalistaD

---

##  Declaración de Trabajo (SOW) y Enfoque SMART
En este proyecto he realizado una auditoia completa de una base de datos de 100 clientes de una empresa. Mi objetivo ha sido limpiar y ordenar la iformación que estaba duplicada o mal escrita.  Al corregir estos fallos , he conseguido que el equipo comercial no pierda tiempo con datos incorrectos y que la dirección sepa con tootal exactitud el dinero real del negocio, que asciende a 14.176,58€

* **Específico y Medible:** Detectar la cantidad de registros duplicados, adecuar los formatos dee textos y fechas, y aislar los correos electrónicos que no eran validos.
* **Relevante:** Demostrar que tener los datos limpios es fundamenta para calcular el dinero real del negocio, que en este caso ascendio exactamente a 14.175,58€.
* **Acotado:** Aplicar una rutina de limpieza de datos y revisión visual en la hoja de calculo para bajar el nivel de errores por debajo del 2% en un periodo de 4 semanas. 

---

##  Diagnóstico de la Auditoría (El "Antes")
Al recibir el archivo original de 101 filas, investigué a fondo y detecté los siguientes fallos graves que ponían en riesgo el dia a dia del negocio.
1. **Registros Duplicados:** Filas que estaban repetidas exactamente igual y que hacian creer que existian más clientes de los reales.
2. **Caos en Atributos de Texto:** Nombres de clientes mal escritos, mezclando mayúsculas y minusculas sin orden, y con espacios en blanco de más que rompian las busquedas.
3. **Correos Electrónicos Inválidos:** Direcciones de correos de contacto rotas, por no contener @, o emails mal escritos.
4. **Fechas Inconsistentes e Importes Nulos:** Fechas registradas en formatos muy diferentes mezclados entre si, y celdas de dinero vacías que bloqueaban cualquier cálculo matemático de la empresa.

---

##  Solución y Habilidades Aplicadas (El "Después")
Para resolver estos fallos de forma segura y eficaz, apliqué las técnicas que he aprendido en el Certificado de Google, para dejar los datos totalmente limpios.

* **Depuración de Duplicados:** Identifique y elimine 21 filas repetidas. Así reduje la base de datos a , 80 registros unicos y reales, limpiando un 21% de datos basura.
* **Normalización de Texto:** Utilice funciones avanzadas combinadas como NOMPROPIO Y ESPACIOS para unificar y corregir el formato de los nombres de los clientes de una sola vez.
* **Validación Lógica:** Aplique una formula condicional con REGEXMARCH para cazar los correos sin @, usando el formato condicional rosa fucsia para que saltaran a la vista las alertas en mi cuadro de mando-
* **Tratamiento Estadístico de Vacíos** Para no alterar los ingresos de la empresa de forma negativa, calculé el promedio global del negocio mediante la fórmula PROOMEDIO dando un valor de 179,45€ y use este dato estratégicamente para rellenar los huecos vacios.
* **Cálculo Financiero de Cierre:** Aplique la función `=SUMA` sobre la columna limpia y depurada, obteniendo un valor real de ingresos de **14.176,58 €**.

---

##  Conclusión del Proyecto
Este ejercicio demuestra el valor real de controlar y limpiar los datos.  Arreglar esta vase de datos no solo mejoró el trabajo diario del archivo, sino que me permitió calcuar con total precisión la situación financiera real de la organización. 

 **[Haz clic aquí para abrir la Hoja de Cálculo interactiva con las fórmulas en Google Sheets](https://docs.google.com/spreadsheets/d/1duecVLqiy1KxExTSZUg9Wwcli2t0nCKH4F49oMvb2jM/edit?usp=sharing)**
