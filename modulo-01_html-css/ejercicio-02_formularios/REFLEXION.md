# REFLEXION — Ejercicio 1.2: Formularios Accesibles

> **Instrucciones:** Reemplazá `[NÚMERO]` y `[NOMBRE]` con el número y nombre del ejercicio correspondiente. Completá este archivo DESPUÉS de terminar tu solución. Escribí con tus propias palabras.

---

## Sección 1 — Explicación de mi solución

*Describí en 150–250 palabras qué hace tu solución y cuáles fueron las decisiones principales que tomaste.*

> ✏️ El archivo HTML5 tiene un header con navegación que reutilicé del ejercicio anterior, al igual que el footer, y una sección principal <main> con título y subtítulo donde se encuentra el <form>. Todos los inputs tienen su label correspondiente que se linkea con for utilizando su id, aquellos que son requeridos tienen el atributo required y los campos de mail y telefono tienen el atributo pattern para validación básica. Cada input tiene un atributo type lo más específico posible, así como su <span> correspondiente con el mensaje de error. Para seguir las pautas WCAG, en CSS apliqué estilos diferenciados para :focus, :hover, :disabled, :valid e :invalid. Además, corroboré que la navegación por teclado sea correcta (siga el orden visual del formulario) y que se pueda enviar haciendo enter desde cualquiera de los inputs.

---

## Sección 2 — Preguntas conceptuales

*Las preguntas conceptuales específicas de este ejercicio están en el `SPEC.md`. Respondé cada una aquí.*

### 2.1 — [Pregunta del SPEC]

> ✏️ Las preguntas conceptuales no están en el SPEC.md del ejercicio.

### 2.2 — [Pregunta del SPEC]

> ✏️ Las preguntas conceptuales no están en el SPEC.md del ejercicio.

### 2.3 — [Pregunta del SPEC]

> ✏️ Las preguntas conceptuales no están en el SPEC.md del ejercicio.

---

## Sección 3 — Decisiones técnicas

### 3.1 — ¿Qué fue lo más difícil de este ejercicio y cómo lo resolviste?

> ✏️ Lo más difícil fueron todos los conceptos y pautas nuevas, que resolví investigando en páginas recomendadas.

### 3.2 — ¿Qué cambiarías si tuvieras que hacerlo de nuevo?

> ✏️ Mejoraría un poco más los estilos y validaría mejor los radio buttons opcionales.

### 3.3 — ¿Qué alternativas consideraste y por qué las descartaste?

> ✏️ Las únicas alternativas que tuve que descartar fueron los pattern de validación para email y teléfono que había usado inicialmente porque eran expresiones regex puras que usaban símbolos no válidos para HTML5.

---

## Sección 4 — Declaración de uso de IA

```
[ ] Resolví el ejercicio completamente sin ayuda de IA
[ ] Usé IA para entender algún concepto, pero escribí el código yo
[ x ] Usé IA para generar un borrador que luego modifiqué y entendí
[ ] Usé IA extensamente y completé la reflexión para entender lo que hice
```

*Si usaste IA, describí brevemente cómo:*

> ✏️ Usé la IA únicamente para generar los estilos CSS básicos del documento, le pedí correcciones y otras cosas corregí manualmente.

---

## Sección 5 — Autoevaluación

En una escala del 1 al 5, ¿cuánto entendés ahora el concepto central de este ejercicio?

```
[ ] 1 — Muy poco, necesito repasar
[ ] 2 — Entiendo lo básico
[ ] 3 — Lo entiendo bien
[ x ] 4 — Lo entiendo bien y puedo explicárselo a otro
[ ] 5 — Podría dar una clase sobre esto
```
