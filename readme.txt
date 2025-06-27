INSTRUCCIONES DE EJECUCIÓN:
-------------------------------
1. Abrir JMeter.
2. Cargar el archivo "Test Plan.jmx".
3. Asegurarse de que el archivo "users.csv" esté en la misma ruta definida en el CSV Data Set Config del script.
4. Ejecutar la prueba.
5. Al finalizar, revisar el listener "Summary Report" dentro de JMeter.

VALIDACIONES QUE REALIZA LA PRUEBA:
-----------------------------------
- El tiempo de respuesta no debe superar los 1.5 segundos por solicitud.
- La tasa de error aceptada es menor al 3%.
- La prueba está configurada para alcanzar un mínimo de 20(TPS) usando múltiples hilos ("Threads" en el Test Plan).

ARCHIVOS INCLUIDOS:
--------------------------------------
- "Test Plan.jmx" → Script de prueba de carga para JMeter.
- "users.csv" → Archivo CSV con credenciales de prueba.
- Aggregate Report.png → Detalle por cada request con promedio, errores y rendimiento.
- Summary Report.png → Estadísticas como tiempo promedio, errores y número de peticiones procesadas por segundo.
- Response Time Graph.png → Gráfica visual del tiempo de respuesta a lo largo de la prueba.
- View Results in tablepng →  Detalle de cada petición con tiempo de respuesta y estado.
- "conclusiones.txt" → Análisis y hallazgos de la prueba.
- "readme.txt" → Instrucciones de ejecución.

DATOS DE ENTRADA PARAMETRIZADOS (desde "users.csv"):
donero,ewedon
kevinryan,kev02937@
johnd,m38rmF$
derek,jklg*56
mor_2314,83r5^

