# REFLEXION — Ejercicio 1.3: Layout con Flexbox

> **Instrucciones:** Reemplazá `[NÚMERO]` y `[NOMBRE]` con el número y nombre del ejercicio correspondiente. Completá este archivo DESPUÉS de terminar tu solución. Escribí con tus propias palabras.

---

## Sección 1 — Explicación de mi solución

*Describí en 150–250 palabras qué hace tu solución y cuáles fueron las decisiones principales que tomaste.*

> ✏️ **Tu respuesta aquí:**

En este ejercicio hice un portfolio con tarjetas para una agencia. Para la solución planteé una sección para los botones y otra para las tarjetas; en este caso, las tarjetas las dividí en distintos articles, uno para cada tarjeta, y repetí la misma estructura en cada caso. Las imágenes las tomé de ‘placehold’ ya que intenté usar ‘picsum.photos’ pero no cargaban. Para la solución de este ejercicio nos pedían usar Flexbox para organizar los contenedores. En el caso de las tarjetas, usamos ‘flex-wrap’ para que se acomoden una al lado de la otra. 

Usé ‘flex-direction: column’ con la propiedad ‘margin-top: auto’ en el enlace "Ver más" para que el elemento de llamado a la acción (CTA) siempre se mantenga alineado en la base de la tarjeta. 

Usé ‘gap’ y ‘justify-content’ para que el espacio entre los elementos (como los botones de filtro o los tags) quedara uniforme sin necesidad de calcular márgenes manualmente, y me aseguro de que el diseño se mantenga simétrico en diferentes tamaños de pantalla. 

Para la gestión de estilos, opté por el uso de variables CSS definidas en :root (--color-primario, --color-fondo, --color-texto). Esto facilita cambios futuros de la agencia. 

Finalmente, agregué un efecto de elevación con ‘box-shadow’ y ‘transform’ en el estado :hover para mejorar la interactividad. 

## Sección 2 — Preguntas conceptuales

*Las preguntas conceptuales específicas de este ejercicio están en el `SPEC.md`. Respondé cada una aquí.*

### 2.1 — [flex-wrap hace]

> ✏️ **Tu respuesta: Flex-wrap es una propiedad que permite que los elementos se ajusten segun sea neceseario: 
Con "flex-wrap: nowrap" los elementos estaran en una sola línea, 
con "flex-wrap: wrap" se ajustarán a varias lineas de arriba a abajo y
con "flex-wrap: wrap-reverse" se ajustarán a varias lineas de abajo a arriba **



## Sección 3 — Decisiones técnicas

### 3.1 — ¿Qué fue lo más difícil de este ejercicio y cómo lo resolviste?

> ✏️ **Tu respuesta:**

Lo mas dificil fue aprender a usar Flexbox desde cero, tambien que el codigo css me quedo bastante largo ; ya que,
con todo lo que se fue sumando se hacia dificil de leer.

### 3.2 — ¿Qué cambiarías si tuvieras que hacerlo de nuevo?

> ✏️ **Tu respuesta:**

eligiria un diseño mas personal, con imagenes que me gusten a mi.

### 3.3 — ¿Qué alternativas consideraste y por qué las descartaste?

> ✏️ **Tu respuesta:**

Quizas tendria que aprender a usar mejor Flexbox y buscar mas alternativas ya que hay muchas cosas que se pueden hacer.

## Sección 4 — Declaración de uso de IA

```
[ ] Resolví el ejercicio completamente sin ayuda de IA
[x] Usé IA para entender algún concepto, pero escribí el código yo
[ ] Usé IA para generar un borrador que luego modifiqué y entendí
[ ] Usé IA extensamente y completé la reflexión para entender lo que hice
```

*Si usaste IA, describí brevemente cómo:*

> ✏️ **Tu respuesta (opcional si no usaste IA):**

use la IA como ayuda para entender Flexbox.

## Sección 5 — Autoevaluación

En una escala del 1 al 5, ¿cuánto entendés ahora el concepto central de este ejercicio?

```
[ ] 1 — Muy poco, necesito repasar
[ ] 2 — Entiendo lo básico
[ ] 3 — Lo entiendo bien
[x] 4 — Lo entiendo bien y puedo explicárselo a otro
[ ] 5 — Podría dar una clase sobre esto
```
