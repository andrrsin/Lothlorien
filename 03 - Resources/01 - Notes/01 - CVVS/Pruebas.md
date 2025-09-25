---
tags:
  - "#resource"
  - "#note"
date: 2025-09-25
area:
  - "[[CVVS]]"
aliases:
  - Testing
---
> [!quote]
> Hay que tener cuidado con las definiciones de pruebas, ya que las definiciones clásicas no definen bien el actual concepto.

E.g:
La **prueba** (testing) es el **proceso de ejecutar** un programa con la intención de encontrar fallos - Glenford J.Myers

# Clasificación de una prueba
- **Clasificación por ejecución**
	- [[Pruebas Dinámicas]]
	- [[Pruebas Estáticas]]
- **Clasificación por visibilidad interna**
	- Caja Negra: No es visible
	- Caja Blanca: Es visible

# Anatomía de una prueba
Una prueba está dividida en ciertos aspectos como los [[Casos de Prueba]]. Estos casos de prueba son buenos cuando:
- Tiene **alta probabilidad** de detectar un [[Fallo]]
- Un [[Casos de Prueba|CP]] es exitoso si detecta un [[Fallo]] nuevo.

Las pruebas se hacen bajo unas condiciones a probar también llamadas [[Condiciones de Prueba]]

# Definiciones Oficiales
- Activity in which a system or component is executed under specified conditions, the results are observed or recorded, and an **evaluation** is made of some aspect of the system or component (IEEE 829-2008 IEEE Standard for Software and System Test Documentation) 
- Concepto extendido de Prueba: A technical investigation of the product under test conducted to **provide stakeholders** with **quality- related information** (Cem Kaner, BBST)
- Set of activities conducted to facilitate **discovery** and/or **evaluation** of properties of one or more test items. Note: Testing activities ==could== include **planning, preparation, execution, reporting**, and management activities, insofar as they are directed towards testing. (ISO/IEC/IEEE 29119-1:2013 Systems and software engineering – Software Testing - Part 1: Concepts and definitions)
	- ==Dynamic testing: testing that requires the execution of the test item ==
	- ==Static testing: testing in which a test item is examined against a set of quality or other criteria without code being executed==
- The process consisting of all lifecycle activities, both **static and dynamic**, concerned with **planning, preparation and evaluation** of software products and related work products to determine that they **satisfy specified requirements**, to demonstrate that they are **fit for purpose and to detect defects** (ISTQB Standard glossary of terms used in Software Testing, Version 2.1)