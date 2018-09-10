User Stories Mario Level 1:

1.	Como jugador deseo poder recorrer el nivel para progresar en este.
Criterios de Aceptación:
•	Cuando se presione la tecla “→”(derecha) me debo movilizar a la izquierda.
•	Cuando se presione la tecla “←”(izquierda) me debo movilizar a la derecha.
•	Cuando se presione la tecla “A” debo saltar.
•	Cuando se presione la tecla “S” debo aumentar mi velocidad.
•	El jugador no debe poder atravesar objetos sólidos (tubos y bloques)


2.	Como jugador deseo poder comer hongos, plantas y estrellitas para mejorar mis habilidades.
Criterios de Aceptación:
•	Cuando el jugador colisione con un hongo o una planta, adquirirá el próximo poder correspondiente.
•	Cuando un jugador colisione con una estrellita, obtendrá inmunidad por un periodo determinado y destruirá automáticamente a cualquier enemigo con el cual colisione en este periodo.


3.	Como jugador deseo poder matar a enemigos para obtener puntaje y facilitar mi recorrido en el juego.
Criterios de Aceptación:
•	Deben instanciarse enemigos en el mapa.
•	Cuando salto encima de un hongo, este es destruido.
•	Cuando salto encima de una tortuga, esta deja un caparazón. Al saltar nuevamente sobre este, se desplazara en una dirección y es destruida.
•	Cuando un enemigo se encuentra encima de un bloque y yo salto debajo y lo rompo o lo levanto, el enemigo que se encuentra sobre este bloque será destruido automáticamente.
•	Al destruir a un enemigo, se le asignara el correspondiente puntaje al jugador.


4.	Como jugador deseo poder ver el tiempo que me queda para poder culminar un nivel.
Criterios de Aceptación:
•	Se inicializa la partida con 400 segundos.
•	En la parte superior derecha del HUD se debe visualizar el tiempo restante para finalizar el mapa en segundos.
•	Si el jugador se queda sin tiempo, el  jugador pierde una vida.
•	Cuando el jugador toca la bandera de finalización del nivel, el tiempo se detiene y es “convertido” a puntaje. (convertido se refiere a multiplicado por una constante de puntaje por segundo)


5.	Como jugador deseo poder visualizar el menú de inicio para seleccionar el modo de juego.
Criterios de Aceptación:
•	Al inicializar el juego, debo visualizar dicho menú.
•	En el menú me deben aparecer las opciones seleccionables: 1 player y 2 player.
•	El menú debe mostrar el mejor puntaje del jugador.
•	El menú debe mostrar las monedas obtenidas del jugador
•	El menú debe mostrar el mundo y nivel inicial.
•	El menú debe mostrar una imagen inicial.


6.	Como jugador deseo poder visualizar la cantidad de vidas que me quedan para medir que tantos riesgos puedo tomar.
Criterios de Aceptación:
•	Al morir, se me deben mostrar la cantidad de vidas que me quedan.
•	Se debe mostrar un Mario que multiplica a la cantidad de vidas que me quedan.
 
 
7.	Como jugador deseo poder ver cuantas monedas he recolectado en total para aumentar una vida.
Criterios de Aceptación:
•	En la parte superior se muestra el total de monedas obtenidas durante el juego.
•	A la izquierda del número de monedas, se muestra una animación de una moneda.


8.	Como jugador deseo que al colisionar con un enemigo se ejecute la acción correspondiente y me reste una vida si estoy como Mario pequeño, esto para darle sentido al juego.
Criterios de Aceptación:
•	Si estoy en modo Mario pequeño y colisiono con un enemigo, se ejecuta la animación de muerte y se me resta una vida.
•	Si estoy en modo Mario grande o de fuego y colisiono con un enemigo, vuelvo a Mario pequeño.


9.	Los hongos y plantas deben de salir por la parte superior de un bloque especial designado al golpear este mismo.
Criterios de Aceptación:
•	Los bloques especiales deben tener un signo de interrogación y la animación correspondiente.
•	Los hongos, plantas y estrellitas deben de salir por la parte superior de un bloque especial designado al golpear este mismo.
•	Al salir el hongo, este inicializara a desplazarse hacia la derecha.
•	Si un hongo colisiona con un objeto sólido, su dirección cambiara. 


10.	Como jugador deseo que existan distintos tipos de enemigos para que la dificultad del juego varíe.
Criterios de Aceptación:
•	Existen 2 tipos de enemigos
•	La tortuga tiene 2 vidas (caparazón y cuerpo)
•	Si golpeas a una tortuga por 1ra vez, este se esconde en su caparazón por un tiempo determinado.
•	Si la vuelves a golpear, esta se desplaza.
•	El enemigo básico es una especie de ratón.
•	El enemigo básico solo se desplaza de derecha a izquierda y solo posee una vida.


11.	Como jugador deseo poder llegar al final del nivel.
Criterios de Aceptación:
•	Localizar la asta con la bandera que indica el punto final del nivel.
•	Al tocar la asta en cualquier posición prosiga la animación de llegada del final del nivel.


12.	Como jugador deseo que, al finalizar el nivel, se me otorguen puntos proporcionalmente a la cantidad de tiempo que me sobro para motivarme a terminarlo más rápido.
Criterios de Aceptación:
•	Que se visualice el tiempo restante durante todo el desarrollo del nivel
•	Que otorgue el puntaje restando el tiempo total del nivel menos el tiempo que me demoré en realizarlo.


13.	Como jugador deseo que si me caigo se realicen las animaciones correspondientes y automáticamente pierdo una vida.
•	Al caer y salir de los límites del nivel del juego pierdo una vida.
•	Al perder una vida regreso al checkpoint más cercano ya superado.
•	Al caer y antes que el personaje reaparezca, se tiene que visualizar una animación de muerte del personaje.


14.	Como jugador deseo que mientras más alto salte en la bandera de fin de nivel, se me otorgue más puntaje para motivarme.
Criterios de Aceptación:
•	Al colisionar con la asta de la bandera dependiendo la posición se otorgue un puntaje que se adicione al puntaje final del nivel.
•	Al colisionar en la parte más elevada de la asta otorga el máximo puntaje mientras que se va reduciendo si se colisiona mas cercano al pie de la asta.


15.	Como jugador deseo que existan distintos objetos ocultos para hacer el juego más interesante y misterioso.
Criterios de Aceptación:
•	En lugares accesibles para el personaje existan rutas u objetos especiales
•	En cada nivel pueda existir 1 o más rutas u objetos.
