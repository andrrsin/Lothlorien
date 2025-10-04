---
tags:
  - project
date: 2025-09-25
area: "[[CVVS]]"
aliases:
  - CVVS Teoría
isFinished: false
---
# Preguntas de Examen
## Tema 1: [[CVVS_Conceptos Generales.pdf|Conceptos Generales]]

> [!question]- ¿Cuál es la diferencia entre error, defecto y fallo?
> **[[Error]]**: Al ser una accion humana o [[Error|Alucinación]] en caso de la IA, ==esto es algo indetectable.==
> > [!hint] Corrección de **Raquel**
> > Yo concretaría que es algo indetectable por las pruebas de software. En otros campos ya no me voy a meter jeje.
> 
> **[[Defecto]]**: Un defecto es un desperfecto que ==puede== causar un comportamiento indeseado en el programa. No tiene porque alterar el funcionamiento de dicho programa.
> > [!hint] Corrección de **Raquel**
> > Más bien es que puede que nunca ejecutemos el programa con las entradas que hagan que ese defecto provoque el mal funcionamiento del programa. El defecto está, pero está oculto, y no vemos sus consecuencias al no dar las entradas necesarias para que se manifieste.
> 
> **[[Fallo]]**:  Provienen de un defecto y son descubiertos al ejecutar el programa.
> > [!hint] Corrección de **Raquel**
> > Los fallos son descubiertos cuando al ejecutar el programa se observa que el resultado es diferente al esperado.

> [!question]- ¿Cuál es la diferencia entre [[Verificación]] y [[Validación]]?
> La diferencia principal esta en el punto de partida de cada uno. La verificación se centra en los **requisitos especificados**. Mientras que la validación se centra en los **requisitos pretendidos y/o las necesidades del usuario**, aunque no haya nada escrito previamente.

> [!question]- ¿Qué implica obtener [[Calidad]]?
> Podemos entender que implica que X tiene la habilidad de cumplir con lo que el cliente pide.

> [!question]- ¿Se puede decir que las [[Pruebas Estáticas]] son de caja negra y las [[Pruebas Dinámicas]] de caja blanca?
> No, son distintos tipos de clasificación y ambas pueden ser de ambas. En una nos centramos en la visibilidad y en otra por el tipo de ejecucción.

# Info
## TODO
- [ ] Al terminar la asignatura quitar las ``[!success]`` por los recursos
- [ ] Terminar [[Valores Límites]]
- [ ] Rellenar y si es necesario Clippear para casos de prueba y para condicion de entrada
## Dudas
- [x] Diapositiva 3 Clases Equivalencia. Es lo mismo situación que situación a cubrir (test coverage Item)
## Related Resources
```dataview
LIST rows.file.link
FROM [[]] OR outgoing([[]])
WHERE !contains(tags, "area")
FLATTEN area AS groups GROUP BY groups

```




