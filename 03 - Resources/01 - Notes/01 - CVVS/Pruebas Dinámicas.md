---
tags:
  - "#resource"
  - "#note"
date: 2025-09-25
area:
  - "[[CVVS]]"
aliases:
---
# Proceso de las pruebas dinámicas
- **Paso 1**: ¿Qué queremos probar?
	- Cada cosa es una [[Situación de Prueba]] o [[Situación de Prueba|Test Coverage Item]]
- **Paso 2**: Están compuestos por ==entradas y salidas esperadas==.
	- Ejemplo de un [[Casos de Prueba|Caso de Prueba]]: Dadas X entradas debe salir Y salida.
- **Paso 3**: Comprobar si esto pasa o no pasa, es decir tiene el comportamiento esperado.
- **Paso 4**: Si no pasa nada, pasa a la fase de depuración.

Es importante saber que la fase de depuración, no es parte del trabajo de un tester. Las celdas resaltadas en amarillo es un ciclo llamado **Ciclo de retesting**.

![[Drawing 2025-09-26 16.50.29.excalidraw]]