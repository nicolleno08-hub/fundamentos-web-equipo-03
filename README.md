# fundamentos-web-equipo-03
## Distribución del trabajo

| Integrante       | Responsabilidad                          |
|------------------|------------------------------------------|
| Arias Sofía      | Inteligencia Artificial y Automatización |
| Franco David     | Ciberseguridad                           |
| Ceballos Nicolle | Computación en la Nube                   |

### index.html

**Errores y advertencias encontradas:**
1. **Error (Elementos `<a>` dentro de `<button>`):** Se usaron etiquetas de enlaces `<a>` dentro de elementos `<button>` para la navegación (`<button><a href="...">...</a></button>`), lo cual es incorrecto en HTML semántico.
2. **Advertencia (Atributo `border` obsoleto):** Se utilizó el atributo `border="1"` en la etiqueta `<table>`, el cual está en desuso/obsoleto en HTML5.

**Correcciones a realizar:**
1. Se debe remover el elemento `<button>` en la barra de navegación y se dejar únicamente las etiquetas de enlace `<a>` simples, cumpliendo además con la norma de no utilizar CSS ni JavaScript en el proyecto.
2. Eliminar el atributo `border="1"` de la etiqueta `<table>` para dejar el elemento en HTML5 puro.

Correcciones realizadas:
- Se eliminaron los elementos <button> y se dejaron los enlaces <a> directamente dentro del <nav>.
- Se eliminaron los atributos border, cellpadding y cellspacing de la tabla para mantener una estructura HTML5 válida.

### ciberseguridad.html
Errores encontrados:
- Advertencia: El atributo `border` en la etiqueta `<table>` está obsoleto en HTML5 (Línea 69).
- Advertencia: El atributo `cellspacing` en la etiqueta `<table>` está obsoleto en HTML5 (Línea 69).
- Advertencia: El atributo `cellpadding` en la etiqueta `<table>` está obsoleto en HTML5 (Línea 69).

Correcciones realizadas:
