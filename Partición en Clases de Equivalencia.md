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
---
> [!quote]
> Representa un **conjunto de datos** para los que se supone que el programa tiene un **comportamiento similar**

# Partes de una Clase de Equivalencia
Para entender mejor qué son las clases de equivalencia y como se distribuyen, utilizaremos el problema 1 de las diapositivas de [[CVVS_Técnicas-CE1-Basic.pdf|Clases de equivalencia 1 - Básicas]]. En el identificaremos las distintas partes.
> [!question]- Problema 1
> Un sistema determina el tipo de interés aplicable a un crédito en función del importe del principal. Para valores menores de 10.000 euros se aplica el 4%, para valores mayores de 50.000 euros se aplica el 1%, en el resto de casos se aplica el 2%

- [[Situación de Prueba]]:
# Notas de clase
Las clases de equivalencia son divisibles en jerarquias.
Si tengo un enumerado, cada uno de los valores deberia de ser una clase de equivalencia.
Miramos las condiciones de entrada las cuales salen de las entradas. Para los numeros mejor los valores limites


## Problema 1
Entradas:
Importe
Salida:
Tipo de interés
Condiciones de Prueba(al sacarla de la entrada solo, se puede llamar Condicione de entrada):
Importe del principal
Division en Clases de equivalencia[^1]:
Clases de Equivalencia
- Hasta 10.000€
- Entre 10.000 y 5.000
- Más de 50.000
Clases inválidas:
- Importe Negativo


[^1]: Hay que tener en cuenta tambien las clases de equivalencia negativas