
# Juego 4 - Cannon

## Descripción del repositorio

Este repositorio contiene el archivo `cannon.py`, que corresponde al videojuego Cannon desarrollado en Python, y el archivo 
`README.md`, donde se describen las modificaciones realizadas.

El juego consiste en lanzar proyectiles mediante clics con el mouse para intentar alcanzar los balones que se desplazan por la 
pantalla. El jugador debe calcular la dirección de sus disparos para conseguir acertar a los objetivos en movimiento.

## Modificaciones realizadas

### 1. Aumento de la velocidad del proyectil y los balones

Se modificó el juego para que tanto los proyectiles como los balones se desplacen a mayor velocidad. Esto hace que los objetivos se 
muevan más rápido por la pantalla y que el jugador tenga que calcular mejor el momento y la dirección de sus disparos.

### 2. Reposicionamiento de los balones

Se agregó una función para que los balones que salgan por el lado izquierdo de la ventana vuelvan a aparecer por el lado derecho, en una 
altura aleatoria. Además, se eliminó la condición que detenía el juego cuando los balones salían de la pantalla, permitiendo que la 
partida continúe sin un límite de tiempo.
