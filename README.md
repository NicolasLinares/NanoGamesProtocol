# Protocolo NanoGames (Cliente/Servidor)
El objetivo de este proyecto consiste en el desarrollo y el diseño de dos protocolos de comunicación de nivel de aplicación en un sistema de juegos de red, 
denominado NanoGames. El sistema está formado por un conjunto de clientes que desean conectarse al servidor de juegos. Para hacer uso de estos protocolos de 
comunicación se han diseñado dos juegos: RockPaperScissorsLizardSpock y MathQuestions. El primero es un juego sin turnos que consiste en el clásico “Piedra, 
papel o tijera” pero con dos opciones más que lo hacen más dinámico, y acabará cuando un jugador alcance la puntuación máxima. El segundo es un juego por 
turnos basado en preguntas sobre operaciones matemáticas, donde el jugador deberá resolver cada operación antes de que se acabe el tiempo y ganará el que 
haya respondido más preguntas correctamente.

El proyecto se ha centrado en el diseño del protocolo de comunicación por lo que se han dejado de lado ciertas cosas, como la implementación de una interfaz. 
Por ello, se puede apreciar en el video demostración (demostracion.mp4) como se hace uso de la terminal de ubuntu para ejecutar el programa. Se puede observar
en el lado izquierdo una terminal que corresponde al Servidor de juegos que imprime las interacciones con los clientes, en el lado derecho dos terminales que
corresponden a dos clientes que van a jugar en el servidor.