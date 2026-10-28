# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [28/10/2026] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como usuario, quiero buscar recetas por nombre, incluyendo ingredientes o excluyendo ingredientes, para obtener unas dietas, si las hay, que se ajusten a mis necesidades.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

Según recoge el acta de acuerdos, se debe seleccionar al menos un criterio, por lo que no tiene sentido hacer una historia que combine las 3 funcionalidades.

## US-01

**Título:** Buscar mediante una palabra o frase

Como usuario, quiero poder buscar recetas mediante palabras o frases, para encontrar una receta que se adecue a lo que deseo encontrar.

**Fuentes:** UR-08; UC-21; FR-085; acta, 2. Criterios de búsqueda.

### Criterios de aceptación

- **CA-01.** Dado que se introduce una palabra o frase, cuando se muestran los resultados de búsqueda, entonces una frase debe aparecer seguida y en el mismo orden.
- **CA-02.** Dado que se introduce una palabra o frase con mayúsculas o acentos, cuando se muestran los resultados de búsqueda, entonces se aprecia que no distingue entre mayúsculas o minúsculas y acentos.
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-02

**Título:** [Capacidad]

Como [rol], quiero [capacidad], para [beneficio].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-03

**Título:** [Capacidad]

Como [rol], quiero [capacidad], para [beneficio].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
