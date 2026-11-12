# Programming Mentor

**Usá la IA para aprender a programar, no solo para conseguir código.**

Una skill de mentoría que te ayuda a pensar el problema, proponer un plan y escribir tu propia solución. El objetivo no es terminar más rápido: es entender lo que estás haciendo.

**La autoría de la idea original es de [Alan Buscaglia](https://github.com/Alan-TheGentleman).** Este repositorio adapta esa idea a una skill reutilizable.

## Cómo empezar

La skill está en [`skills/programming-mentor/SKILL.md`](skills/programming-mentor/SKILL.md).

Cargala siguiendo el mecanismo de skills de tu agente. Si tu herramienta no admite skills, podés usar su contenido como instrucciones de conversación, sin instalación automática.

Después, contale qué sabés y qué querés aprender:

> Quiero que seas mi mentor de programación. Sé lo básico de JavaScript, pero me cuestan los arrays. Quiero aprender a filtrar una lista de productos. Guiame paso a paso sin darme la solución.

## Cómo funciona

| Etapa | Qué hace el mentor |
| --- | --- |
| **Objetivo** | Te pregunta qué querés lograr y por qué. |
| **Plan juntos** | Te pide una propuesta antes de ofrecer alternativas. |
| **Dudas** | Se detiene ante conceptos que no entendés y los explica con ejemplos simples. |
| **Tu código** | Te da un paso chico y espera que lo escribas vos. |
| **Revisión** | Señala aciertos, errores y mejoras, explicando el porqué. |
| **Cierre** | Resume lo trabajado y propone qué practicar después. |

## Ayuda sin saltar a la solución

Si te trabás, la ayuda avanza por niveles:

1. **Una pregunta** que te haga pensar.
2. **Una pista concreta**, si pedís más ayuda.
3. **Un fragmento mínimo**, explicado línea por línea, si lo pedís nuevamente.

El mentor no debería subir de nivel sin que se lo pidas.

### ¿Y si necesito ver la solución?

Escribí **`MOSTRAME`**.

El mentor puede mostrar el código completo del problema actual y explicarlo línea por línea. Después te pide que lo reescribas sin mirar.

Esto permite mostrar la solución, **no editar tus archivos de código**.

## Tu registro de aprendizaje

Al cerrar una sesión, el mentor agrega una entrada a `APRENDIZAJE.md` con:

- Los conceptos trabajados.
- Las decisiones tomadas y sus motivos.
- Qué practicar después.

Las sesiones anteriores se conservan. Si el agente no puede escribir archivos, te entrega la entrada en Markdown para que la guardes vos.

## Qué no hace

- No implementa el proyecto por vos.
- No te dice que algo está bien cuando está mal.
- No debería avanzar si estás aceptando algo que no entendés.

Es una guía de comportamiento para un agente de IA, no una garantía de que siempre la siga correctamente. Si se adelanta, pedile que vuelva al último paso que entendiste.

## Estructura

```text
.
├── README.md                         # Presentación y uso
├── prompt.md                         # Prompt de origen
└── skills/
    └── programming-mentor/
        └── SKILL.md                  # Skill autocontenida
```

## Origen y créditos

La idea original es de **[Alan Buscaglia](https://github.com/Alan-TheGentleman)**. Esta skill adapta el enfoque de mentoría recogido en [`prompt.md`](prompt.md), con una idea central:

> Tu trabajo es que yo entienda, no que el código exista.
