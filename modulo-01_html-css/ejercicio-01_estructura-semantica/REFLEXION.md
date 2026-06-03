# REFLEXION — Ejercicio 1.1: Estructura Semántica HTML

> **Instrucciones:** Completá este archivo DESPUÉS de terminar tu solución. Escribí con tus propias palabras. Respuestas copiadas de internet o generadas por IA sin elaboración propia no son válidas.
>
> Tiempo esperado para completar esta reflexión: 20–30 minutos.

---

## Sección 1 — Explicación de mi solución

*Describí en 150–250 palabras qué hace tu archivo HTML y cuáles fueron las decisiones de estructura que tomaste. No copies el código, explicá el razonamiento.*

> ✏️ **Tu respuesta aquí:**
>
> [Estructuralmente, en el HTML aprovecho etiquetas semánticas de HTML5 para organizar el contenido de forma significativa: un <header> global con navegación, un <main> que contiene el artículo principal, y un <footer> con información del sitio. El artículo en sí está marcado con <article>, y dentro de él usé etiquetas <section> para dividir el contenido en tres bloques temáticos diferenciados, más una sección de comentarios. Elegí <blockquote> para citar a Richard Stallman con su atributo cite apuntando a la fuente original, y <figure> con <figcaption> para la imagen ilustrativa. Los datos estadísticos los presenté en una lista <ul>, y en un <aside> destaqué una estadística relevante fuera del flujo principal del texto. Los metadatos de autoría y fecha los estructuré con <address> y <time> respectivamente, mientras que apliqué Schema.org mediante microdata (itemscope, itemtype, itemprop) para enriquecer semánticamente el artículo, el autor y los comentarios, facilitando su interpretación por motores de búsqueda.]

---

## Sección 2 — Preguntas conceptuales

Respondé cada pregunta. Las respuestas deben ser tuyas. Podés investigar, pero explicá con tus palabras.

### 2.1 — ¿Cuál es la diferencia entre `<section>` y `<article>`? ¿Cuándo usarías cada uno?

> ✏️ **Tu respuesta:**
<section> describe una sección del documento o de una parte del documento, mientras que <article> describe un artículo. Usaría <section> para dividir algún elemento en secciones bien definidas, y <article> para artículos.
---

### 2.2 — ¿Por qué es importante el atributo `datetime` en la etiqueta `<time>`? ¿Quién lo usa?

> ✏️ **Tu respuesta:**
El atributo datetime pone esa fecha/horario en un formato legible para máquinas, y lo utilizan los motores de búsqueda.
---

### 2.3 — Tu página tiene `<header>` en dos lugares: uno para la página y uno dentro del `<article>`. ¿Eso es válido? ¿Por qué?

> ✏️ **Tu respuesta:**
Sí, es válido, la etiqueta <header> se usa para encerrar contenido introductorio, ya sea del documento o como en este caso de un artículo.
---

### 2.4 — Un motor de búsqueda como Google lee tu HTML. ¿Qué ventaja le da usar etiquetas semánticas versus usar solo `<div>` con clases?

> ✏️ **Tu respuesta:**
Que las etiquetas semánticas son más fáciles de leer para motores de búsqueda, los humanos saben interpretar qué es cada cosa en una página aunque sólo use <div> pero una máquina necesita más indicaciones para darse cuenta de que una etiqueta está encerrando información de contacto.
---

### 2.5 — Encontrá **un error semántico** en el siguiente fragmento y explicá cómo lo corregirías:

```html
<div class="navigation">
  <div class="nav-item"><a href="/home">Inicio</a></div>
  <div class="nav-item"><a href="/about">Nosotros</a></div>
</div>

<div class="main-content">
  <div class="post-title">Mi primer artículo</div>
  <div class="post-body">
    <p>Contenido del artículo...</p>
  </div>
</div>
```

> ✏️ **Tu respuesta:**
El primer <div> que contiene un menú de navegación, lo cambiaría por un <nav> y a sus <div> hijos por una lista desordenada <ul>.
---

## Sección 3 — Decisiones técnicas

### 3.1 — ¿Qué etiqueta usaste para el logo y por qué? ¿Hay alternativas?

> ✏️ **Tu respuesta:**
Usé la etiqueta <img> porque es la utilizada para insertar una imagen, pero hay varias alternativas: <picture>, poner la imagen de fondo con CSS, un <svg> con <image>, <object>, <embed>, <canvas> para manipulación con JavaScript.
---

### 3.2 — ¿Elegiste `<ul>` u `<ol>` para tu lista? ¿Por qué esa y no la otra?

> ✏️ **Tu respuesta:**
Elegí <ul> porque los elementos que listé no tenían un orden específico.
---

### 3.3 — Si alguien accede a tu página solo con un lector de pantalla (sin ver el HTML), ¿podría navegar y entender el contenido? ¿Qué cambiarías para mejorar la experiencia?

> ✏️ **Tu respuesta:**
Se podría mejorar el orden visual y el tamaño de las imagenes.
---

## Sección 4 — Declaración de uso de IA

Marcá con una `x` lo que corresponda:

```
[ ] Resolví el ejercicio completamente sin ayuda de IA
[ x ] Usé IA para entender algún concepto, pero escribí el código yo
[ ] Usé IA para generar un borrador que luego modifiqué y entendí
[ ] Usé IA extensamente y completé la reflexión para entender lo que hice
```

*Si usaste IA, describí brevemente cómo:*

> ✏️ **Tu respuesta (opcional si no usaste IA):**
Usé la IA para generar el texto de relleno del artículo y de los comentarios.
---

## Sección 5 — Autoevaluación

En una escala del 1 al 5, ¿cuánto entendés ahora el concepto de HTML semántico?

```
[ ] 1 — Muy poco, necesito repasar
[ ] 2 — Entiendo lo básico
[ ] 3 — Lo entiendo bien
[ x ] 4 — Lo entiendo bien y puedo explicárselo a otro
[ ] 5 — Podría dar una clase sobre esto
```

*¿Qué parte te resultó más difícil?*

> ✏️ **Tu respuesta:**
Aprender a poner bien los meta datos, específicamente la microdata de schema.org.