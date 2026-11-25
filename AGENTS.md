# PACO — Guía del proyecto

## Concepto
PACO es un minijuego arcade tipo test, pequeño, absurdo y jugable en una sola pantalla. El jugador responde cinco preguntas con controles HTML nativos. Cada respuesta seleccionada con `:checked` cambia la etapa visible, el indicador de progreso y la posición de Paco. La última respuesta muestra uno de tres finales prediseñados; no se calcula una puntuación total.

## Tecnologías
Usar exclusivamente HTML5 y CSS3. JavaScript está prohibido: no crear archivos `.js`, etiquetas `<script>`, manejadores de eventos ni código ejecutable embebido. No añadir frameworks, librerías, motores, fuentes remotas, dependencias ni recursos externos. Debe poder abrirse `index.html` directamente.

## Paco e identidad visual
Paco debe reconocerse claramente como unicornio equino: cuerpo, cuello y hocico equinos, cuatro patas, cuerno centrado en la frente, crin, cola, cara expresiva y gafas de sol. Su personalidad es presumida y divertida. Mantener el estilo pixel art y la paleta rosa, morada, azul y pastel. No convertirlo en caballo sin cuerno, perro, humanoide ni criatura irreconocible.

## Mecánica CSS honesta
Usar grupos `radio` con `label`, `:checked`, `:has()`, enlaces y botones nativos. Las respuestas reales hacen avanzar el test entre cinco etapas. El botón de reinicio debe ser un `button type="reset"`. Las animaciones CSS pueden ilustrar vuelo, salto y celebración, pero no sumar puntuación, guardar respuestas ni calcular un resultado según todas las respuestas. Describir estas limitaciones con claridad.

## Pantallas y movimiento
La secuencia de presentación puede animarse con CSS; no fingir carga de recursos que no existen. El juego debe mantener cada pregunta y sus opciones a la vista sin desplazamiento manual. Paco debe cambiar de posición al mostrar cada etapa. Los ritmos desfasados de CSS son animaciones predefinidas, no aleatorias.

## Accesibilidad y calidad
Escribir HTML semántico en español; asociar correctamente etiquetas y controles; permitir teclado con foco visible; mantener contraste, diseño adaptable y `prefers-reduced-motion`. Sin dependencias externas. Revisar enlaces locales, cinco etapas, estados seleccionables, final, reinicio y ausencia total de JavaScript antes de entregar. Probar en navegador cuando el entorno lo permita.

## Estructura
Mantener `AGENTS.md`, `index.html` y `styles.css` en la raíz. No añadir archivos innecesarios.
