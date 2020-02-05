# Te Morís!

Te Morís es un juego de cartas en donde el objetivo es evitar perder a toda costa.  
Se utiliza un mazo de cartas españolas de 40 cartas. Aunque podría jugarse de igual manera con 8s y 9s. Es recomendable usarlos cuando se quiere jugar con más de 5 jugadores.    

## Objetivo del Juego
El objetivo del juego es evitar completar la frase “Te Morís”.  

### Valor de las cartas

Cada carta tiene su valor numérico sin importar su palo. Es decir el 12 es mayor que el 11, que es mayor que el 10, etc. Exceptuando por los 1s (anchos) que valen más que todas las otras cartas.  

## Desarrollo del juego

En cada ronda, se reparten 3 cartas a cada jugador. Cada ronda tendrá 3 manos y cada mano tendrá dos partes, una primera de cambios y otra de juego. El/los jugadores que tengan la carta de número más baja al finalizar la parte de juego perderán esa mano. Los jugadores que tengan más manos perdidas cuando se termina la ronda (se terminan las 3 cartas) sumarán una letra. El/Los primeros jugadores en completar la frase “Te Morís” pierden el juego.

### Cambios

Durante la primera parte de una mano (los cambios) cada jugador en el sentido de la ronda puede decidir entre 2 opciones:  

 1. Quedarse sus cartas.  
 2. Cambiar una de las cartas de su mano con el jugador siguiente.  

En el caso de haber elegido **2** el jugador siguiente elige una carta de su mano para intercambiar y estas se cambian sin mostrárselas al resto de los jugadores.  

Luego de realizar **una** de estas dos acciones pasa el turno al siguiente jugador en el sentido de la ronda.  

Luego de que todos los jugadores hayan hecho su turno en los cambios se sigue a la siguiente _etapa de juego_.  

### Juego

La segunda parte de una mano (el juego) cada jugador debe tirar una carta por turnos.  

## Cartas Especiales

Durante el desarrollo del juego se pueden utilizar ciertas cartas especiales:

- Los 3: cuando se tira un 3 en la etapa de juego, este tiene la obligación de cambiar la carta por otra carta jugada que sea del mismo palo. Si no hay ninguna no se hace nada. Si hay mas de una el jugador que tiró el 3 puede elegir con cual cambiar.  
- Los 5: cuando un jugador utiliza el “poder”  de un 5 durante la etapa de cambio este le permite robarle una carta a **cualquier** jugador a cambio del 5 en cuestión.  
- Los 6: cuando alguien intenta cambiar una carta con un jugador en la etapa de cambio este puede mostrar un 6 y evitar tener que acceder al cambio, o ceder ninguna carta. Observación: mostrar una 6 evita el robo de una carta con el 5.  
- El “Te Morís” (12 de copas): el “Te Morís” puede jugarse en la etapa de juego. El jugador que lo tira debe gritar “Te Morís” e indicar a otro de los jugadores, haciéndole perder la mano automáticamente, sin importar las cartas que hubiera en juego. 
Si un jugador se olvida de usar el “Te Morís” y lo juega como una carta normal, cualquiera puede recordárselo gritándole “Te Morís” a él, haciéndolo perder.  

Los “poderes” de las cartas especiales solo se pueden usar _una vez por ronda_.   
Las cartas especiales deben mostrarse al resto de los jugadores al ser usadas.

## Casos Especiales

- Si todas las cartas tiradas en la etapa de juego son del mismo palo, las mismas **rotan** una posición en el sentido de la ronda.  
Esta regla _anula_ el “poder” del 3. Es decir que si se tira un 3 y son todas del mismo palo, no se cambia de lugar el 3 sino que solamente rotan todas las cartas.  

- En caso de que todas las cartas sean del mismo palo y se juegue el “Te morís”, **no** se rota ya que el “Te morís” tiene prioridad.