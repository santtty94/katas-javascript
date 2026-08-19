# Proyecto 2 — Katas JavaScript

Máster en Ciberseguridad · The Power Education
Autor: **Santiago Londoño** (`santtty94`)
Entrega objetivo: **30 de agosto de 2026**

---

## Qué contiene

56 katas de JavaScript repartidas en tres bloques, según la estructura que pide el enunciado:

| Carpeta | Bloque | Katas | Estado |
|---|---|:--:|:--:|
| `ejercicios-basicos-avanzados/` | Ejercicios básicos y avanzados | 42 | 0 / 42 |
| `ejercicios-dom/` | Ejercicios de DOM | 5 | 0 / 5 |
| `ejercicios-es6-asincronia/` | Ejercicios de ES6+ y asincronía | 9 | 0 / 9 |
| **Total** | | **56** | **0 / 56** |

---

## Cómo ejecutar las katas

### Bloques de consola (básicos/avanzados y ES6+/asincronía)

Cada kata es un archivo `.js` independiente, ejecutable con Node.js:

```bash
node ejercicios-basicos-avanzados/kata-01.js
node ejercicios-es6-asincronia/kata-01.js
```

Comprobado con Node.js 24.15.

### Bloque de DOM

Cada kata vive en su propia carpeta con `index.html` y `script.js`. Se abre el
`index.html` en el navegador:

```
ejercicios-dom/
  kata-01/
    index.html
    script.js
```

---

## Convención de los archivos

Cada kata empieza con el enunciado literal como comentario, para que se pueda
leer el archivo sin tener que volver a la plataforma:

```js
/*
 * Kata 01 — <enunciado literal del ejercicio>
 */
```

Los comentarios del cuerpo explican los pasos y las partes que no son obvias.

---

## Estructura del repositorio

```
katas-javascript/
├── ejercicios-basicos-avanzados/   42 katas · un .js por kata
├── ejercicios-dom/                 5 katas · una carpeta por kata (index.html + script.js)
├── ejercicios-es6-asincronia/      9 katas · un .js por kata
├── .gitignore
└── README.md
```

---

## Entrega

- Repositorio público e individual.
- Correo a `antonio.rosales@thepower.education`
- Asunto exacto: `Proyecto 2: Katas JavaScript - Santiago Londoño`
- Cuerpo: **solo el enlace de este repositorio**. Sin adjuntos.
