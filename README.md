# 100-ejercicios-web
Prácticas de desarrollo web codificadas a mano (sin vibe coding) para repasar fundamentos y aprender nuevos temas. Abierto como referencia o guía de ejercicios.

# Prácticas de Desarrollo Web (Codificación a Mano)

Repositorio de prácticas de desarrollo web escritas a mano —sin *vibe coding*—, pensadas para afianzar fundamentos, recordar conceptos olvidados y explorar nuevas herramientas de forma progresiva.

El código está público por si te sirve como referencia, para comparar enfoques o para usar estos mismos ejercicios como guía de práctica.

Aquí tengo los ejercicios por si quieres seguirlos:

> 100 ejercicios estructurados por nivel de dificultad, diseñados para cubrir desde la manipulación básica del DOM y eventos hasta lógica compleja, persistencia de datos y consumo de APIs.

---

## Nivel Inicial: Fundamentos del DOM y Eventos (1–25)

### Selección y Modificación de Texto/Estilos
1. **Hola Mundo dinámico:** Botón que cambia un `<h1>` de "Hola" a "¡Hola, JavaScript!".
2. **Cambiador de color de fondo:** Botón que altera el `backgroundColor` del `body` a un color aleatorio en hexadecimal.
3. **Contador simple:** Tres botones (Incrementar, Decrementar, Resetear) y un `<span>` que muestra el valor.
4. **Ocultar/Mostrar elementos:** Botón tipo toggle que oculta o muestra un párrafo (`display: none` o clase `hidden`).
5. **Cambiador de imagen:** Dos botones que alternan el atributo `src` de un elemento `<img>`.

### Manejo de Clases y Estilos
6. **Modo Oscuro / Modo Claro:** Toggle que añade/remueve la clase `.dark-mode` al `body`.
7. **Acordeón simple:** Al hacer clic en un encabezado, muestra u oculta el párrafo que tiene debajo.
8. **Resaltador de texto:** Botón que cambia el tamaño de fuente y color de todos los párrafos `<p>`.
9. **Barra de navegación responsiva:** Botón hamburguesa que añade/quita la clase `.active` al menú.
10. **Indicador de estado:** `div` que cambia de rojo a verde y actualiza su texto a "Conectado" al pulsar un botón.

### Eventos de Teclado y Formularios
11. **Reflejo de texto:** `<input>` tipo texto cuyo contenido se escribe en tiempo real dentro de un `<span>`.
12. **Contador de caracteres:** Input de texto con un límite de 100 caracteres que muestra cuántos quedan disponibles.
13. **Deshabilitar botón de envío:** Checkbox "Acepto términos" que habilita/deshabilita el botón de submit.
14. **Detector de tecla presionada:** Muestra en pantalla la tecla y el código (`e.key`, `e.code`) presionado por el usuario.
15. **Validación de coincidencia de clave:** Dos inputs de contraseña que muestran un mensaje en rojo si no coinciden.

### Listas y Manipulación de Nodos
16. **Agregar elementos a una lista:** Formulario con input y botón que añade un `<li>` a una `<ul>`.
17. **Eliminar primer/último elemento:** Botones para remover el primer o último hijo de una lista.
18. **Eliminar elemento específico:** Al hacer clic en cualquier `<li>` de una lista, este se elimina (`event.target`).
19. **Marcar como completado:** Al hacer clic en un `<li>`, se le alterna la clase CSS `.completed` (tachado).
20. **Clonar elementos:** Botón que duplica un `div` existente en el DOM con todo su contenido.

### Cálculos Simples en Tiempo Real
21. **Calculadora de IVA:** Input numérico que calcula el IVA (21%) y muestra el total en un párrafo.
22. **Conversor de temperatura:** Input para Celsius que actualiza automáticamente otro campo en Fahrenheit.
23. **Calculadora de propinas:** Inputs para monto de cuenta y % de propina, mostrando el total a pagar.
24. **Selector de color (RGB):** Tres sliders (`<input type="range">`) para R, G y B que cambian el color de un `div`.
25. **Generador de divs:** Input numérico y botón que crea N cuadros con colores aleatorios dentro de un contenedor.

---

## Nivel Intermedio: Dinámicas, Persistencia y UI (26–60)

### Formularios y Validación
26. **Validación de Email:** Formulario que valida mediante Regex si el correo es correcto antes de enviar.
27. **Mostrar/Ocultar contraseña:** Icono o checkbox al lado de un input password que cambia su tipo a text.
28. **Formulario de registro paso a paso:** Stepper que oculta el paso 1 y muestra el paso 2 sin recargar la página.
29. **Selección múltiple con límite:** Checkboxes donde solo se permite seleccionar un máximo de 3 opciones.
30. **Select dinámico dependiente:** Seleccionar un país en un `<select>` carga sus ciudades correspondientes en otro.

### Manipulación de Colecciones y Listas
31. **Lista To-Do con filtros:** Lista de tareas con botones para ver "Todas", "Pendientes" y "Completadas".
32. **Filtro de búsqueda en tiempo real:** Input que filtra una lista de nombres estática visible en pantalla.
33. **Ordenamiento de lista:** Botones para ordenar alfabéticamente (A-Z, Z-A) una lista de elementos `<li>`.
34. **Tabla con eliminación de filas:** Tabla HTML donde cada fila tiene un botón "Eliminar".
35. **Edición in-line:** Al hacer doble clic en un texto, este se convierte en input para editarlo y guardarlo con Enter.

### Componentes de Interfaz de Usuario (UI)
36. **Modal / Ventana emergente:** Botón que abre un modal con overlay oscuro y botón para cerrarlo (X o clic fuera).
37. **Pestañas (Tabs):** Menú de pestañas donde solo el contenido correspondiente a la pestaña activa es visible.
38. **Galería de imágenes con Lightbox:** Al hacer clic en una miniatura, se abre en tamaño completo en un modal.
39. **Slider/Carrusel de imágenes:** Botones "Anterior" y "Siguiente" para rotar imágenes de un array.
40. **Carrusel automático:** Slider que avanza automáticamente cada 3 segundos con `setInterval`.
41. **Sistema de valoración por estrellas:** 5 estrellas hover/click que guardan el puntaje seleccionado.
42. **Tooltip personalizado:** Elemento que muestra un `div` flotante con información al pasar el mouse (`mouseenter`/`mouseleave`).
43. **Notificación Toast:** Botón que despliega una alerta flotante en la esquina inferior que desaparece a los 3 segundos.
44. **Barra de progreso de lectura:** Barra fija superior que se llena según el porcentaje de scroll vertical de la página.
45. **Botón "Volver arriba":** Botón flotante que solo aparece tras hacer scroll hacia abajo y desplaza suavemente al inicio.

### Eventos de Mouse y Drag & Drop
46. **Seguidor de cursor:** Un `div` circular que sigue las coordenadas `clientX` y `clientY` del mouse.
47. **Arrastrar y soltar básico:** Mover un `div` de un contenedor A a un contenedor B usando la API Drag and Drop.
48. **Reordenar lista mediante arrastre:** Lista cuyos ítems se pueden reordenar arrastrándolos.
49. **Área de Drop para archivos:** `div` que cambia de estilo al arrastrar un archivo encima (`dragover`, `dragleave`).
50. **Pinta con el mouse:** Canvas o rejilla de divs donde se dibuja manteniendo presionado el clic del mouse.

### Almacenamiento Local (LocalStorage)
51. **To-Do List con LocalStorage:** Lista de tareas que guarda, lee y elimina datos en `localStorage`.
52. **Guardado de preferencia de tema:** El estado del modo oscuro se mantiene al recargar la página.
53. **Borrador de formulario:** Guarda el contenido de un `<textarea>` en `localStorage` conforme el usuario escribe.
54. **Historial de búsquedas:** Almacena los últimos 5 términos buscados y los muestra como sugerencias.
55. **Carrito de compras persistente:** Agregar/quitar productos de una lista y mantener la cuenta en `localStorage`.

### Temporizadores y Asincronía Básica
56. **Cronómetro:** Iniciar, pausar y reiniciar con precisión de décimas de segundo (`setInterval`).
57. **Temporizador de cuenta regresiva:** Input para minutos que descuenta segundo a segundo hasta llegar a cero.
58. **Reloj digital:** Muestra la hora actual (HH:MM:SS) actualizada cada segundo.
59. **Reloj analógico básico:** Mueve las manecillas (divs rotados con CSS) en función de la hora del sistema.
60. **Deshabilitar botón por tiempo:** Botón de descarga que requiere esperar una cuenta regresiva de 10 segundos.

---

## Nivel Avanzado: APIs, Estado y Proyectos Lógicos (61–100)

### Consumo de APIs (Fetch / Async-Await)
61. **Buscador de usuarios GitHub:** Fetch a la API pública de GitHub para mostrar foto, bio y repos de un usuario.
62. **Generador de citas aleatorias:** Consume una API de frases y permite copiarlas al portapapeles con un botón.
63. **App del Clima:** Consulta una API de clima por ciudad y dibuja en el DOM la temperatura y el icono.
64. **Conversor de divisas en vivo:** API de tipos de cambio que calcula la conversión entre dos monedas elegidas.
65. **Buscador de películas (OMDb / TMDB):** Renderiza una cuadrícula de pósters según el término buscado.
66. **Carga infinita (Infinite Scroll):** Pide más datos a una API e inserta nuevos nodos cuando el scroll llega al final.
67. **Cargador con Skeleton Screen:** Muestra divs animados grisáceos mientras la petición fetch está pendiente.
68. **Paginación dinámica:** Muestra datos de una API divididos en páginas con botones "< Anterior" y "Siguiente >".
69. **Buscador de Pokémon (PokeAPI):** Muestra stats, tipo e imagen del Pokémon buscado por nombre o ID.
70. **Manejo de errores de red:** Muestra un componente visual de "Sin conexión" o "Error 404" si la API falla.

### Manipulación Compleja del DOM y Estado
71. **Tabla de datos paginada y ordenable:** Renderiza un JSON local en una tabla con orden por columnas y paginación.
72. **Generador de Tablas HTML:** Inputs para filas y columnas que generan una tabla ejecutable mediante código.
73. **Generador de Memes:** Carga una imagen, permite escribir texto superior/inferior y lo dibuja en un Canvas.
74. **Exportar tabla a CSV:** Botón que lee los nodos de una tabla en el DOM y descarga un archivo `.csv`.
75. **Árbol de directorios (TreeView):** Renderiza un objeto JSON anidado como un árbol con carpetas desplegables.
76. **Generador de código CSS:** Sliders de `border-radius`, `box-shadow`, etc., que actualizan un box y muestran el CSS listo para copiar.
77. **Validador de fuerza de contraseña:** Evalúa longitud, símbolos y números, pintando una barra de rojo a verde.
78. **Selector de asientos de cine:** Matriz de asientos donde hacer clic cambia su estado (libre/ocupado) y calcula el precio total.
79. **Filtro multidimensional:** Filtra una lista de productos por categoría, rango de precio y disponibilidad simultáneamente.
80. **Constructor de formularios:** Interfaz donde el usuario añade inputs, labels y botones para diseñar un formulario personalizable.

### Juegos y Lógica de Aplicación
81. **Juego de Memoria (Memory Match):** Rejilla de cartas boca abajo donde hay que encontrar las parejas coincidentes.
82. **Juego del Ahorcado:** Adivinar la palabra secreta pulsando letras antes de agotar los intentos.
83. **Tres en Raya (Tic-Tac-Toe):** Detecta combinaciones ganadoras, turnos de jugadores y empate.
84. **Juego de Mecanografía (Speed Typing):** Muestra un texto, mide las palabras por minuto (WPM) y resalta errores en rojo.
85. **Juego del Esquivo (Evade los bloques):** Controlar un objeto con las flechas del teclado dentro de un área determinada.
86. **Simon Says:** Secuencia de colores y sonidos aleatorios que el usuario debe repetir en orden.
87. **Juego de Piedra, Papel o Tijera:** Contra la computadora con marcador de puntos persistente durante la sesión.
88. **Quiz interactivo:** Preguntas con respuesta múltiple, barra de progreso y puntuación final.
89. **Buscaminas simplificado:** Rejilla de 5x5 con minas ocultas y contadores numéricos.
90. **Juego de la Serpiente (Snake):** Implementación en HTML5 Canvas o mediante matriz de divs en el DOM.

### APIs del Navegador y Herramientas Avanzadas
91. **Lector de voz (Web Speech API):** Lee el texto de un `<textarea>` usando la voz del navegador.
92. **Reconocimiento de voz:** Convierte el habla del micrófono en texto dentro de un input.
93. **Copiado al portapapeles con feedback:** Botón que usa `navigator.clipboard` y muestra un tooltip de "¡Copiado!".
94. **Detector de estado de red:** Muestra un banner flotante cuando la ventana pasa a estar offline u online.
95. **Lector y vista previa de imágenes (FileReader):** Muestra una vista previa instantánea de una foto seleccionada en un `<input type="file">`.
96. **Reproductor de audio personalizado:** Controles propios (play, pause, barra de progreso, volumen) para un elemento `<audio>`.
97. **Geolocalización en mapa:** Obtiene las coordenadas del usuario (`navigator.geolocation`) y las muestra en pantalla.
98. **Editor de Markdown simple:** Textarea que convierte sintaxis Markdown a HTML en tiempo real dentro de un preview div.
99. **Dashboard interactivo con charts:** Integra una librería como Chart.js y actualiza el gráfico al modificar datos desde un formulario.
100. **Kanban Board:** Tablero con columnas (Por hacer, En proceso, Hecho) con funcionalidad completa de arrastrar y soltar tareas.
