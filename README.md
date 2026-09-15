# fundamentos-web-equipo-03

### Página 2 (tema2.html)

**Errores y advertencias encontradas:**
1. **Error (Elementos `<a>` dentro de `<button>`):** Se usaron etiquetas de enlaces `<a>` dentro de elementos `<button>` para la navegación (`<button><a href="...">...</a></button>`), lo cual es incorrecto en HTML semántico.
2. **Advertencia (Atributo `border` obsoleto):** Se utilizó el atributo `border="1"` en la etiqueta `<table>`, el cual está en desuso/obsoleto en HTML5.

**Correcciones a realizar:**
1. Se debe remover el elemento `<button>` en la barra de navegación y se dejar únicamente las etiquetas de enlace `<a>` simples, cumpliendo además con la norma de no utilizar CSS ni JavaScript en el proyecto.
2. Eliminar el atributo `border="1"` de la etiqueta `<table>` para dejar el elemento en HTML5 puro.