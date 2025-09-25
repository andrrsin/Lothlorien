---
tags:
  - project
date: 2025-09-25
area: "[[CVVS]]"
aliases:
---
# A [[CVVS]] Project
## TODO
- [ ] Enviar correo con preguntas sobre dudas
- [ ] Añadir respuesta a Raquel a quien encuentra defectos y quien fallos.
- [ ] Crear el proceso de las [[Pruebas Dinámicas]]
- [ ] Al terminar la asignatura quitar las ``[!success]`` por los recursos
## Dudas
- [ ] Quien encuentra los defectos y quien los fallos.
- [ ] Correcta diferencia entre error, defecto y fallo?
- [ ] Correcta entre diferencia validacion y verificacion

# Preguntas de Examen

> [!question]- ¿Cuál es la diferencia entre error, defecto y fallo?
> **[[Error]]**: Al ser una accion humana o [[Error|Alucinación]] en caso de la IA, ==esto es algo indetectable.==
> **[[Defecto]]**: Un defecto es un desperfecto que ==puede== causar un comportamiento indeseado en el programa. No tiene porque alterar el funcionamiento de dicho programa.
> **[[Fallo]]**: 

> [!question]- ¿Cuál es la diferencia entre [[Verificación]] y [[Validación]]?
> La diferencia principal esta en el punto de partida de cada uno. La verificación se centra en los **requisitos especificados**. Mientras que la validación se centra en los **requisitos pretendidos y/o las necesidades del usuario**, aunque no haya nada escrito previamente.

> [!question]- ¿Qué implica obtener [[Calidad]]?
> Podemos entender que implica que X tiene la habilidad de cumplir con lo que el cliente pide.

> [!question]- ¿Se puede decir que las pruebas estáticas son de caja negra y las dinámicas de caja blanca?
> No, son distintos tipos de clasificación y ambas pueden ser de ambas. En una nos centramos en la visibilidad y en otra por el tipo de ejecucción.

## Related Resources
```dataview
LIST rows.file.link
FROM [[]] OR outgoing([[]])
WHERE !contains(tags, "area")
FLATTEN area AS groups GROUP BY groups

```




