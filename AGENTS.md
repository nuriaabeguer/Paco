# PACO — Guía del proyecto

## Dirección
PACO es un minijuego arcade pequeño, absurdo y jugable, protagonizado por Paco, un unicornio presumido y divertido. La pantalla de juego debe ocupar el centro de la experiencia; no convertir el proyecto en landing page, portfolio ni recorrido de secciones.

## Tecnologías permitidas
Usar exclusivamente HTML5 y CSS3. JavaScript está prohibido en todas sus formas: sin archivos `.js`, etiquetas `script`, manejadores de eventos ni código ejecutable embebido. No añadir frameworks, librerías, motores, dependencias, fuentes ni recursos externos.

## Identidad visual de Paco
Paco debe reconocerse claramente como unicornio equino, con cuerpo, cuatro patas, cuerno visible en el centro de la frente, crin y cola, cara expresiva y gafas de sol. Mantener su aire presumido y gracioso. Dibujarlo con CSS o conservar los recursos gráficos existentes; no convertirlo en caballo sin cuerno, perro, humanoide ni criatura irreconocible.

Paleta arcade pastel: tinta `#17152b`, azul noche `#27234a`, crema `#fff4d6`, rosa `#ff6f9f`, coral `#ff8c69`, oro `#ffd45c`, turquesa `#57d6c5` y violeta `#9a7bff`. Favorecer marcos pixelados, sombras duras y tipografía de sistema.

## Interacciones honestas
Elegir mecánicas que CSS pueda implementar realmente con controles nativos (`radio`, `checkbox`, `button`, `label`), enlaces locales, `:checked`, `:hover`, `:active`, `:focus-visible` y animaciones CSS. Las acciones del usuario deben cambiar un estado visible y comprensible. No afirmar ni imitar de manera engañosa colisiones, física, puntuación dinámica, vidas, generación procedural, cámara, guardado o reinicio cuando no existan. Explicar brevemente las limitaciones de la mecánica.

## Accesibilidad y calidad
Usar HTML semántico en español; asociar controles con etiquetas; mantener navegación por teclado, foco visible, contraste suficiente, diseño adaptable y `prefers-reduced-motion`. No cargar recursos remotos. Antes de entregar, revisar rutas locales, ausencia total de JavaScript y dependencias y, cuando sea posible, abrir `index.html` directamente en un navegador.

## Estructura
Mantener `AGENTS.md`, `index.html` y `styles.css` en la raíz. No crear archivos adicionales si no son necesarios.
