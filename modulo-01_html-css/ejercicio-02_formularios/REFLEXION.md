# REFLEXION — Ejercicio 1.2: Formularios Accesibles

> **Instrucciones:** Reemplazá `[NÚMERO]` y `[NOMBRE]` con el número y nombre del ejercicio correspondiente. Completá este archivo DESPUÉS de terminar tu solución. Escribí con tus propias palabras.

---

## Sección 1 — Explicación de mi solución

*Describí en 150–250 palabras qué hace tu solución y cuáles fueron las decisiones principales que tomaste.*

> ✏️ **Tu respuesta aquí:**
Para este ejercicio tomé la estructura del ejercicio 1 y dentro del <body> agregué un <form> con el action y método POST (protocolo HTTP). Adentro agregué varios <input> según lo pedido, un <select> con el motivo de contacto y un <textarea> para que el usuario tenga espacio para explayarse en su mensaje. 

Cada <input> está vinculado con un <label> (esto hace que, por ejemplo en los checkboxes, sea más fácil clickear). Usé required y aria-required en los obligatorios, y pattern para que el usuario no escriba datos inválidos. 

Agrupé los <label> y los <input> dentro de párrafos <p class='bloque-campo'> (clase que les da margen en el CSS). Al <label> le apliqué display: block para que su texto quede arriba del <input> y mantener un diseño limpio. 

Para mejorar la usabilidad, usé :hover para resaltar el borde al pasar el ratón, y :focus-visible para que, cuando el usuario navegue con la tecla 'Tab', el campo enfocado se marque claramente. También di estilos a :disabled (grises) para que se entienda que no se puede interactuar con el botón inactivo. 

Finalmente, usé la validación nativa (:valid e :invalid) para que el CSS aproveche las reglas de HTML (como pattern o required). Si el campo cumple las reglas, el borde se pone verde (:valid), y si no cumple, se pone rojo (:invalid).
---

## Sección 2 — Preguntas conceptuales

*Las preguntas conceptuales específicas de este ejercicio están en el `SPEC.md`. Respondé cada una aquí.*

### 2.1 — ¿Por qué es importante usar un label explícito con "for"?

> ✏️ **Tu respuesta:**

En el caso de una persona no vidente que usa el lector de pantalla, al usar la tecla Tab el cursor se coloca en el input; y gracias a que existe un label con un 'for' vinculado a ese input, el lector sabe cómo se llama esa caja y se lo lee al usuario. Además, aumenta el área interactiva para el clic de los ratones. 

### 2.2 — ¿Cuál es la diferencia entre aria-required y required?

> ✏️ **Tu respuesta:**

El required bloquea al navegador cuando un campo está vacío porque al hacer clic en "Enviar" cancela la petición y hace saltar la alerta visual. Por otro lado, el aria-required="true" es para los lectores de pantalla: le inyectamos la propiedad de "obligatorio" para que el software de voz lo traduzca en audio diciéndole a la persona: "Campo obligatorio", sin afectar la validación nativa. 


## Sección 3 — Decisiones técnicas

### 3.1 — ¿Qué fue lo más difícil de este ejercicio y cómo lo resolviste?

> ✏️ **Tu respuesta:**

Lo mas dificil fue entender como vincular los elementos del html con el archivo.css , 
sobre todo la parte de las validaciones (:valid).

### 3.2 — ¿Qué cambiarías si tuvieras que hacerlo de nuevo?

> ✏️ **Tu respuesta:**

Si lo haria devuelta le agregaria mas sentido a cada campo del formulario y 
le agregaria mas estilos para que se vea mas 'colorido'.

### 3.3 — ¿Qué alternativas consideraste y por qué las descartaste?

> ✏️ **Tu respuesta:**

No estoy seguro, intente hacerlo bajo los requerimientos pedidos y me enfoque en que cumpla , 
pero no pense en alternativas.

## Sección 4 — Declaración de uso de IA

```
[ ] Resolví el ejercicio completamente sin ayuda de IA
[x] Usé IA para entender algún concepto, pero escribí el código yo
[ ] Usé IA para generar un borrador que luego modifiqué y entendí
[ ] Usé IA extensamente y completé la reflexión para entender lo que hice
```

*Si usaste IA, describí brevemente cómo:*

> ✏️ **Tu respuesta (opcional si no usaste IA):**

Use la IA para tener ejemplos de como se usaban los elementos que pedian en cada requerimiento.
Tambien para corregir el codigo a medida que lo iba haciendo y consultarle sobre algunos conceptos. 
     

## Sección 5 — Autoevaluación

En una escala del 1 al 5, ¿cuánto entendés ahora el concepto central de este ejercicio?

```
[ ] 1 — Muy poco, necesito repasar
[ ] 2 — Entiendo lo básico
[ ] 3 — Lo entiendo bien
[x] 4 — Lo entiendo bien y puedo explicárselo a otro
[ ] 5 — Podría dar una clase sobre esto
```
