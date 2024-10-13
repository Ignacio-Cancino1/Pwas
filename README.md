# Laberinto Aleatorio con Aumento de Dificultad

Esta es una aplicación interactiva creada en **p5.js** que genera laberintos aleatorios usando el algoritmo **Depth-First Search (DFS)**. El jugador puede moverse por el laberinto utilizando las teclas de dirección o `W`, `A`, `S`, `D`, con el objetivo de llegar a la meta. A medida que el jugador avanza de nivel, la dificultad del laberinto aumenta reduciendo el tamaño de las celdas.

## Características

- **Generación de Laberintos Aleatorios**: Los laberintos se generan aleatoriamente utilizando el algoritmo DFS.
- **Control del Jugador**: El jugador se puede mover usando las teclas de dirección (`↑`, `↓`, `←`, `→`) o las teclas `W`, `A`, `S`, `D`.
- **Aumento de Dificultad**: El tamaño de las celdas del laberinto se reduce cada 5 niveles, haciendo el laberinto más difícil.
- **Efectos de Sonido**: Se incluyen efectos de sonido para los movimientos del jugador, al chocar contra las paredes y al llegar a la meta.
- **Texturas Personalizadas**: El fondo, las paredes, el jugador y la meta tienen texturas personalizadas.
- **Sistema de Niveles**: Cada vez que el jugador llega a la meta, el nivel aumenta y se genera un nuevo laberinto.

## Controles

- **Teclas de dirección** o **WASD** para moverse por el laberinto:
  - `W` / `↑` - Moverse hacia arriba.
  - `A` / `←` - Moverse hacia la izquierda.
  - `S` / `↓` - Moverse hacia abajo.
  - `D` / `→` - Moverse hacia la derecha.

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
 git clone https://github.com/tu-usuario/laberinto-dfs.git

  Navega hasta el directorio del proyecto:
cd laberinto-dfs
Asegúrate de que tengas una estructura de carpetas similar a la siguiente para almacenar las imágenes y sonidos:

Copiar código
laberinto-dfs/
├── images/
│   ├── cesped.jpg
│   ├── ladrillos.jpg
│   ├── player.png
│   └── meta.png
├── sounds/
│   ├── movement.mp3
│   ├── complet.mp3
│   └── chocarpared.mp3
└── index.html
Abre el archivo index.html en tu navegador para comenzar a jugar.

Personalización
Cambiar Texturas
Si deseas cambiar las texturas del laberinto, jugador o meta:

Reemplaza las imágenes en la carpeta images/ con las nuevas imágenes.
Asegúrate de que los nombres de archivo coincidan con los que se usan en el código (cesped.jpg, ladrillos.jpg, player.png, meta.png).
Cambiar Sonidos
Si deseas cambiar los efectos de sonido:

Reemplaza los archivos en la carpeta sounds/ con tus propios archivos de sonido.
Asegúrate de que los nombres de archivo coincidan con los que se usan en el código (movement.mp3, complet.mp3, chocarpared.mp3).
Tecnologías Utilizadas
p5.js: Librería de JavaScript para crear gráficos interactivos.
p5.sound: Extensión para incluir sonido en aplicaciones p5.js.
Contribuciones
Si quieres contribuir a este proyecto, siéntete libre de hacer un fork del repositorio y abrir un pull request con tus cambios.

Licencia
Este proyecto está bajo la licencia MIT. Puedes leer más en el archivo LICENSE.

markdown
Copiar código

### Instrucciones generales:
1. **Descripción General**: Se explica de qué trata la aplicación (laberinto generado aleatoriamente con aumento de dificultad).
2. **Controles**: Las teclas que el jugador puede utilizar.
3. **Estructura de carpetas**: Se indica dónde colocar las imágenes y sonidos personalizados.
4. **Instrucciones de Instalación**: Para que cualquiera pueda clonar y ejecutar la aplicación.
5. **Personalización**: Cómo cambiar las imágenes y sonidos.
6. **Licencia**: Se incluye la licencia MIT como ejemplo.

Puedes modificarlo según tus necesidades y preferencias. ¡Espero que te sea útil!
