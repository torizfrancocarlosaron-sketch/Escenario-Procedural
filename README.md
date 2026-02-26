# Escenario-Procedural

<img width="1919" height="1021" alt="Captura de pantalla 2026-02-25 212003" src="https://github.com/user-attachments/assets/19e295c0-03d3-472f-a59c-23a60265c139" />

Paso 1: Limpieza del Entorno y Preparación
Antes de construir, debemos asegurar que la escena esté vacía. Esto enseña a los alumnos la
importancia de la gestión de objetos en memoria.
 Lógica: Seleccionar todo y borrar.

<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/03c0618d-ecbb-4262-ac29-f49c4d62ffda" />

Paso 2: Definición de Materiales
Según el tema 1.4, utilizaremos el modelo RGB para dar vida al
escenario.
Lógica: Crear una función que genere materiales para no repetir código
<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/d449419f-9ccd-4e33-ab68-4d8300b46cf2" />

Paso 3: Construcción de Paredes con Ciclos
Usaremos un ciclo for para automatizar la
creación de un pasillo.

Lógica: Iterar para colocar cubos en el eje Y, alternando materiales según el índice del
ciclo.

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/3d6ac898-d927-4276-ae5f-7ab0d45aaeb9" />

Paso 4: Completando la Geometría
Para que parezca un videojuego, cerramos el pasillo y agregamos una superficie base.
Lógica: Replicar la pared en el lado positivo del eje X y añadir un plano escalado para el
suelo.

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/1fb18cd9-371c-4bdc-b5f9-819f57c369bd" />

Paso 5: Iluminación Básica
Un escenario de videojuego no está completo sin luz.
Lógica: Agregar una luz de tipo "Point" para iluminar el recorrido.
