---
tags:
  - "#resource"
  - "#note"
date: 2025-09-25
area:
  - "[[CVVS]]"
aliases:
  - CP
  - Caso de prueba físico
  - Caso de prueba lógico
---
> [!success]
> **Nunca** mencionar en el [[Examen CVVS Teoría]] que las pruebas físicas son de hardware y las lógicas de software, ni que las pruebas físicas son la implementación de las logicas

# Caso de prueba lógico
Los casos de prueba lógicos **no describen los valores exactos** de las [[Situación de Prueba|Situaciones de prueba]] a introducir. Esto los hace unos casos de  prueba mucho más flexibles pero complicado para [[Continuous Integration]] y para proyectos a gran escala.
# Caso de prueba físico
Los casos de prueba físicos describen **valores exactos** de las [[Situación de Prueba|Situaciones de Prueba]] a introducir. Estos son mucho más fáciles de ejecutar pero también generan una rigidez que puede afectar a la capacidad de detectar [[Defecto]], por eso se ha de cambiar de vez en cuando dichos valores

> [!success]
> De cara al [[Laboratorio de CVVS]] Raquel recomienda empezar describiendo Casos de prueba lógicos y luego ir transformandolos a físico