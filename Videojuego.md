---
layout: default
title: Videojuego
nav_order: 6
---

# Mi proceso para hacer un videojuego



**Github**

Antes de empezar con el proyecto, tuve que hacer un nuevo repositorio en Github para que el código del videojuego se separe del de la página web.

-----

**Prompt**

Luego, empecé el proyecto metiendole un prompt a chat gpt+ con las especificaciones que nos dio el profesor.


Este es el prompt utilizado (cabe aclarar que también utilicé chat gpt para perfeccionar el prompt):

Desarrolla un videojuego inspirado en Geometry Dash, usando HTML, CSS y JavaScript, que pueda publicarse en GitHub Pages. Quiero un juego funcional, no solamente una maqueta.

Temática y estilo:
Usa un nombre original: Neon Jump.
Diseña un mundo geométrico con colores neón, fondo oscuro y efectos de luz.
El personaje será un cubo que gira al saltar.
Usa diseños y sonidos originales, sin copiar recursos de Geometry Dash.

Dinámica del juego:
El cubo avanza automáticamente y el jugador controla los saltos.
Permite saltar con la barra espaciadora, flecha arriba, clic o toque en pantalla.
Solo permite saltar cuando el personaje esté sobre una superficie.
Incluye pinchos, plataformas y huecos que el jugador deba superar.
Si el cubo choca con un peligro o cae en un hueco, pierde y puede reiniciar inmediatamente.
Usa colisiones justas: tocar visualmente el borde de un efecto luminoso no debe causar una derrota.
Crea tres niveles diseñados manualmente: fácil, intermedio y difícil. Aumenta progresivamente la velocidad y la dificultad.
Asegúrate de que todos los saltos sean posibles con la física del juego. Evita obstáculos aleatorios que produzcan situaciones imposibles.
Al llegar al final de un nivel, muestra una pantalla de victoria.

Pantallas y controles:
Menú inicial con título, botón «Jugar», selección de nivel e instrucciones breves.
Durante la partida, muestra progreso en porcentaje, intentos y botón de pausa.
Al perder, muestra el porcentaje alcanzado y botones para reintentar o volver al menú.
Permite reiniciar con R y pausar con Escape.
Incluye control de sonido y guarda el mejor progreso de cada nivel con localStorage.
Todos los textos deben estar en español.

Diseño y experiencia:
Haz que funcione en computadora y celular, con controles táctiles cómodos.
Mantén al personaje y los próximos obstáculos visibles en distintos tamaños de pantalla.
Incluye partículas al saltar, un efecto breve al perder y transiciones sencillas.
Añade música o sonidos originales, activados después de que el usuario interactúe con el juego.
Prioriza controles precisos y animaciones fluidas sobre efectos decorativos.

Implementación:
Usa Canvas para representar el juego y HTML/CSS para los menús.
Organiza el proyecto en index.html, style.css, script.js y una carpeta de recursos si hace falta.
No uses backend, servicios de pago ni herramientas que requieran compilación.
Usa rutas relativas compatibles con GitHub Pages.
Usa requestAnimationFrame y calcula el movimiento según el tiempo transcurrido para que la velocidad no dependa de la frecuencia de la pantalla.
Separa claramente la física, colisiones, controles, niveles y pantallas.
Incluye comentarios útiles y un README.md con instrucciones, controles y publicación.

Pruebas e iteraciones:
Antes de entregarlo, prueba y corrige:
Saltos, aterrizajes y colisiones con cada obstáculo.
Reinicio después de perder y transición al ganar.
Pausa y regreso al juego sin movimientos inesperados.
Controles de teclado, ratón y pantalla táctil.
Ajuste de pantalla, sonido y guardado del progreso.
Que los tres niveles puedan completarse y no tengan saltos imposibles.
Que no haya errores en la consola ni archivos faltantes.
Realiza al menos dos rondas de pruebas y mejoras. Explica brevemente qué probaste, qué corregiste y qué no pudiste verificar.


Publicación y entrega:
Entrega todos los archivos completos.
Publica el proyecto en un repositorio de mi cuenta de GitHub y activa GitHub Pages si tienes acceso autorizado.
Si falta acceso o algún dato necesario, pídemelo después de tener el juego listo y probado.
Incluye la URL del videojuego en el README y en la sección «About» del repositorio.
Añade dentro del juego un enlace al repositorio.
Al terminar, dame el enlace para jugar y el enlace del repositorio. No afirmes que está publicado hasta comprobar que la página funciona.
Toma decisiones razonables sobre los detalles restantes y empieza a construir el juego.

-----

**Resultados del prompt**

El prompt funcionó a la perfección, Chat gpt+ me lo dió para descargarlo directamente. El resultado incluye un videojuego de 3 niveles progresivamente complicados. Se pueden utilizar las teclas de espacio o flecha hacia arriba para saltar. La tecla de escape para pausar, y la de "r" para reiniciar. Incluye música de fondo, y la posibilidad de apagarla.


-----

**Link para el videojuego**

Aquí puedes jugar mi videojuego llamado NeonJump!

http://127.0.0.1:8765/

