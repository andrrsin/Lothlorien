---
tags:
  - "#resource"
  - "#note"
date: 2025-09-26
area:
  - "[[CVVS]]"
aliases:
  - Clases de Equivalencia
  - CE
  - Equivalence Partitioning
---
> [!quote]
> Representa un **conjunto de datos** para los que se supone que el programa tiene un **comportamiento similar**

Estos conjuntos de datos suelen formar parte de un [[Dominio]], en caso de que haya distintos [[Dominio|Dominios]]. Estos se dividirán en distintas Clases de Equivalencia que no tienen porque estar relacionadas.
# Identificación de  Clases de Equivalencias
## Enumeraciones
Cuando una [[Condiciones de Prueba|Condición de prueba]] es una enumeración. Se ha de plantear una clase de equivalencia para cada valor de ellos.
## Rangos
Para los rangos numéricos es mejor aplicar los [[Valores Límites]], 
## Valores lógicos
Los valores lógicos serán divididos en ambas opciones Verdadero o Falso.
## Jerarquía de clases
Cuando hay motivos para creer que los elementos de una clase, no van a ser tratados de la misma forma. ==Lo más sensato es dividir esa clase en otras más pequeñas==. Esto es la jerarquía de clases.

## Ejemplo: Problema 1
Para entender mejor qué son las clases de equivalencia y como se distribuyen, utilizaremos el problema 1 de las diapositivas de [[CVVS_Técnicas-CE1-Basic.pdf|Clases de equivalencia 1 - Básicas]]. En el identificaremos las distintas partes.
> [!question]- Problema 1
> Un sistema determina el tipo de interés aplicable a un crédito en función del importe del principal. Para valores menores de 10.000 euros se aplica el 4%, para valores mayores de 50.000 euros se aplica el 1%, en el resto de casos se aplica el 2%

- **[[Situación de Prueba]]**: Esto podemos definirlo como las entradas y las salidas,  es decir lo que usaremos para medir.
	- *Entrada*: Importe
	- *Salida*: Tipo de interés
- **[[Condiciones de Prueba]]**: Que queremos cubrir, en caso de que esto sean solo entradas se puede llamar [[Condiciones de Prueba|Condiciones de Entrada]]
	- En nuestro caso esto será el importe principal aplicado.
- **División en Clases de Equivalencia**: Esta fase final consiste en el desglose de las [[Condiciones de Prueba]]
	- Clases de Equivalencia **válidas**:
		- Hasta 10.000€
		- Entre 10.000€ y 5.000€
		- Más de 50.000€
	- Clases **inválidas**:
		- Importe Negativo
- Tras esto quedaría obtener los [[Casos de Prueba]]
