# fundamentos-web-equipo-03
## Distribución del trabajo

| Integrante       | Responsabilidad                          |
|------------------|------------------------------------------|
| Arias Sofía      | Inteligencia Artificial y Automatización |
| Franco David     | Ciberseguridad                           |
| Ceballos Nicolle | Computación en la Nube                   |

## Convención CSS 
- Idioma de clases: inglés 
- Formato: kebab-case 
- Componentes: BEM cuando aplique 

## Paleta de color 
- Primary: #293356 
- Secondary: #203CA7 
- Accent: #89b9eb 
- Background: #16232C 
- Text: #14285B 

Justificación: La paleta fue seleccionada con tonos azules y fríos orientados a las tecnologías de la información (IA, Ciberseguridad y Nube). Esta combinación transmite seguridad, innovación y estructura. Además, la relación de contraste entre el fondo oscuro (`#16232C`), las tarjetas de acento claras (`#89b9eb`) y el texto oscuro garantiza una lectura cómoda y una navegación clara entre los tres módulos del sitio.

## Prueba de cascada Resultado del selector de elemento: 

`h2 { color: blue; }` 
**Resultado:** El texto aparece de color azul.
**Explicación:** Se aplica la regla del selector de etiqueta (`h2`), el cual asigna el estilo base inicial con especificidad.

`.demo-title { color: green; }` 
**Resultado:** El texto cambia a color verde.
**Explicación:** Cambia a verde porque el selector de clase (`.demo-title`) tiene una especificidad mayor (0,0,1,0) que el selector de etiqueta (`h2`), por lo que la cascada le da prioridad a la clase.

`#demo-title { color: purple; }`
**Resultado:** El texto vuelve a cambiar a color púrpura / morado.
**Explicación:** Cambia a morado debido a que los selectores de ID (`#demo-title`) tienen una prioridad y especificidad superior (0,1,0,0) frente a los selectores de clase y etiqueta.

`style="color: orange"`
**Resultado:** El texto cambia a color naranja.
**Explicación:** Los estilos definidos en línea (atributo `style` directo en el HTML) poseen la mayor especificidad en la cascada (1,0,0,0), sobreescribiendo las reglas definidas en la hoja de estilos externa CSS (etiqueta, clase e ID).

**Elimine el style en línea y el selector ID utilizado para la demostración.**
**Acción realizada:** Se removió el atributo `style` en línea del HTML y se borraron las reglas de ID (`#demo-title`) y etiqueta (`h2`) de prueba del archivo `styles.css`. En el código final se conservó una solución limpia mantenible utilizando únicamente selectores de clase (`.demo-title`).