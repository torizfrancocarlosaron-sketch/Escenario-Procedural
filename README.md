# Escenario-Procedural

<img width="1919" height="1021" alt="Captura de pantalla 2026-02-25 212003" src="https://github.com/user-attachments/assets/19e295c0-03d3-472f-a59c-23a60265c139" />

Se elimina para que este la pagina en blanco

El primer comando selecciona absolutamente todos los objetos que existan en la escena actual. El segundo comando los elimina. Esto es una buena práctica para evitar que, si ejecutas el script varias veces, se acumulen objetos duplicados en el espacio de memoria.

<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/03c0618d-ecbb-4262-ac29-f49c4d62ffda" />

Crea una función reutilizable para generar texturas de color y define dos colores específicos usando el modelo RGB.
La función recibe el nombre del material y sus valores Rojo, Verde y Azul (RGB). En Blender, estos valores van de 0.0 a 1.0. El 1.0 final en diffuse_color representa el canal Alfa (opacidad). Al encapsular esto en una función, se aplica el paradigma orientado a objetos: creamos las instancias mat_base y mat_acento guardándolas en variables sin tener que reescribir toda la lógica de creación cada vez.

<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/d449419f-9ccd-4e33-ab68-4d8300b46cf2" />

Construye una fila de cubos a lo largo del eje Y, alternando sus colores y alturas.

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/3d6ac898-d927-4276-ae5f-7ab0d45aaeb9" />

Cierra el pasillo creando la pared del lado derecho y coloca la superficie sobre la que se asientan.
(el codigo original tenia un pequeño error y lo corregi con ayuda de un asistente de IA)

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/1fb18cd9-371c-4bdc-b5f9-819f57c369bd" />

Coloca una fuente de luz para que los materiales y las formas sean visibles al renderizar.
