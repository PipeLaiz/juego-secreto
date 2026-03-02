🎯 Juego Secreto – Adivina el Número

Este proyecto es un pequeño juego web interactivo donde el usuario intenta adivinar un número secreto generado aleatoriamente. Ideal para practicar HTML, CSS y JavaScript básico, y pertenece a un curso de desarrollo web ofrecido en Alura Latam.

🧩 ¿Cómo jugar?

La página web genera automáticamente un número secreto entre 1 y 10.

El usuario ingresa un número en el campo de texto.

Al enviar, el juego indica si el número es mayor o menor que el secreto.

El juego cuenta cuántos intentos se hicieron y muestra cuando el usuario acierta.

Hay un botón para reiniciar la partida y generar un nuevo número.

📁 Estructura del proyecto

El repositorio contiene:

/
├── index.html        # Interfaz del juego
├── style.css         # Estilos visuales
└── app.js            # Lógica del juego
🧠 Breve descripción de los archivos

index.html: contiene la estructura básica de la página y los elementos de entrada/salida para jugar.

style.css: define el diseño visual (colores, posiciones, tipografía).

app.js: lógica completa del juego: generación de número secreto, comparación con la entrada del usuario, control de intentos y reinicio.

💻 Tecnologías

El juego está construido con:

HTML – estructura de la interfaz.

CSS – estilos de la página.

JavaScript – lógica de juego y eventos.

No requiere servidor ni configuraciones complejas: basta abrir index.html en un navegador para jugar.

🎮 Lógica principal (resumen)

El archivo app.js implementa:

Generación de un número aleatorio entre 1 y 10 sin repetir números.

Comparación entre la cifra ingresada y el número secreto.

Mensajes que guían al jugador (“El número secreto es mayor/menor”).

Conteo de la cantidad de intentos y habilitación de botón para reiniciar cuando se acierta.

🧪 Experiencia de juego

Este pequeño proyecto ofrece una experiencia:

🔹 Sencilla y pedagógica — ideal para principiantes que están aprendiendo lógica en JavaScript.
🔹 Enganchadora — el jugador recibe retroalimentación inmediata que lo mantiene motivado.
🔹 Rejugable — gracias al reinicio aleatorio del número secreto.

Además, añadir validaciones adicionales (por ejemplo: manejar entradas no numéricas o mejorar la interfaz) puede ser un excelente ejercicio de mejora.

📌 Conclusión

Este juego básico de “adivina el número” es una excelente introducción para quienes están empezando con el desarrollo web. Su código claro y su lógica simple pero funcional lo hacen ideal para aprender y expandir en proyectos más complejos.

Si te interesa mejorar este proyecto, podrías considerar:

Añadir validación de entrada (solo números válidos).

Mostrar un historial de intentos.

Agregar animaciones o mejores mensajes UX.
