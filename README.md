# PGV - TheLastShelter
Videojuego creado por 
- Marina Muñoz Cano
- Mario López González
- David Correa Rodríguez
- Ignacio Yuste López

## Descripción 

El proyecto consiste en un prototipo de videojuego del estilo "Tower Defense" en Unreal Engine 4.


## Instrucciones para ejecutar el proyecto 

1. Para ejecutar el proyecto, descarguélo y colóquelo en la ruta que desee.
2. Colóquese en la ruta especificada y ejecute el archivo "TheLastShelter.uproject".
3. Pulse en "Play" para comenzar el juego. 

## Objetivos conseguidos / Goals achieved

- Diseño y construcción del mapa.
- Tiro parabólico.
- Tiro lineal.
- Diseño de los 3 tipos de torres.
- Spawn de enemigos siguiendo un spline.
- Detección de los enemigos por parte de las torretas.
- Disparo a los enemigos.
- Barras de vida en los enemigos.
- Daño hacia los enemigos.
- Colocación de todos los tipos de torres con preview.
- Menú principal.
- Menú de créditos.
- Menú de niveles.
- Botón y menú de pausa.
- Botón y funcionalidad de "Acelerar juego".
- Botones para las diferentes torretas y ataques especiales.
- Contador de tiempo para lanzar oleada. Botón para lanzar oleada.

# Manual del Juego
_Last Shelter_ es un juego del estilo Tower Defense cuyo objetivo es proteger la torre de los enemigos. Al iniciar el juego aparecen tres botones: _Start_, para mostrar los niveles y seleccionar el deseado; _Credits_, muestra la información de los desarrolladores del juego; y, _Exit_, para salir del juego.

Al pulsar sobre _Start_ se cargan los diferentes niveles, si seleccionamos cualquiera de ellas comenzará el juego. Dentro de la partida, en el HUD, se puede observar distinta información:

-	__Lanzar Oleada__: boton arriba a la izquierda de la pantalla que permite lanzar la oleada. Cuanta con un contador que se decrementa y cuando llega a cero se lanza de forma automaticamente la oleada.
-   __Construir Torretas__: botones que se ubican en la parte inferior izquierda de la pantalla. Al hacer click muestran una previsualización de donde colocar la torreta.
-	__Lanzar Ataque Especial__: botones que se ubican en la parte inferior derecha de la pantalla. Al hacer click muestran una previsualización del area de efecto.
-	__Botones de Ajustes__: se ubican en la parte superior derecha de la pantalla. Hay dos botones: el primero, pausa el juego y aparece un menú para reanudar, reiniciar el nivel y salir; el segundo, aumenta la velocidad del juego y si se vuelve a pulsar la velocidad vuelve a su estado normal.

## Torretas
Se utilizan para dañar y eliminar a los enemigos. Para colocarlas hay que pulsar sobre las torretas que aparecen en el HUD. Una vez se pulsa una se entra en modo construcción y se iluminan unas baldosas que indican donde se puede colocar dicha torreta. Hay tres tipos de torres:
-	__Tipo 1__: ametralladora que realiza un tiro lineal que aplica 10 de daño a los enemigos. Tiene 300 puntos de vida. 
-	__Tipo 2__: mortero que realiza un tiro parabólico lento que aplica 75 de daño a los enemigos. Tiene 400 puntos de vida.
-	__Tipo 3__: ametralladora de poca cadencia que realiza un tiro lineal que aplica 15 de daño a los enemigos. Tiene 600 puntos de vida.

## Ataques especiales
Se utilizan para dañar y eliminar a los enemigos. Para lanzarlos hay que pulsar sobre los ataques especiales que aparecen en el HUD. Hay dos tipos de ataques especiales:
-	__Tipo 1__: bomba que aplica un daño de 150 a los enemigos en un área circular.

## Bichos
Caminan hacia la base para intentar destruirla. Hay tres tipos de bichos:
-	__Tipo 1__: aplica 10 de daño a los objetivos, tiene 100 puntos de vida y es el más rápido. 
-	__Tipo 2__: aplica 15 de daño a los objetivos, tiene 200 puntos de vida y tiene una velocidad media. 
-	__Tipo 3__: aplica 45 de daño a los objetivos, tiene 300 puntos de vida y es el más lento. 

## Base
Estructura que hay que proteger de los ataques de los bichos. Tiene 4000 puntos de vida.
