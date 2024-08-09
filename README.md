#Juego de Piedra, Papel o Tijera

Este es un juego simple de Piedra, Papel o Tijera implementado en Python. El usuario juega contra la computadora, y el primero en ganar 2 rondas es declarado ganador.

Cómo Ejecutar el Juego
Requisitos Previos
Python 3.x instalado en tu sistema.
Instrucciones
Clona o Descarga el Repositorio:

Clona el repositorio usando Git o descarga el archivo ZIP y extráelo.
bash
Copiar código
git clone https://github.com/RafaelHinojosaH/curso-python-pip.git
cd curso-python-pip
Ejecuta el Juego:

Abre una terminal o el símbolo del sistema.
Navega al directorio game dentro del repositorio clonado.
Ejecuta el script main.py usando Python:

```sd
python game/main.py
```

Cómo Jugar:

El juego te pedirá que ingreses una de las siguientes opciones: piedra, papel o tijera.
Escribe tu elección y presiona Enter.
La computadora seleccionará su opción de manera aleatoria.
El juego comparará la opción del usuario con la opción de la computadora y anunciará al ganador de la ronda.
El primer jugador en ganar 2 rondas será declarado el ganador general, y el juego terminará.
Lógica del Juego:

piedra vence a tijera.
papel vence a piedra.
tijera vence a papel.
Si tanto el usuario como la computadora eligen la misma opción, la ronda es un empate.
Salir del Juego:

El juego termina automáticamente cuando el usuario o la computadora gana 2 rondas.
También puedes salir del juego en cualquier momento cerrando la terminal o presionando Ctrl + C.
Personalización
Puedes modificar el número de rondas necesarias para ganar cambiando las condiciones en la función run_game.
Las opciones del juego (piedra, papel, tijera) se pueden cambiar editando la función choose_options.
Licencia
Este proyecto está licenciado bajo la Licencia MIT.

Autor
Rafael Hinojosa - Perfil de GitHub
Este archivo README proporciona instrucciones en español sobre cómo configurar, ejecutar y personalizar el juego. Si necesitas alguna otra información o ajuste, ¡dímelo!
