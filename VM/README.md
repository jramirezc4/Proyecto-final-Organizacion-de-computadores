# Maze Intelligence

Proyecto en Jack para Nand2Tetris: un laberinto simple con jugador, enemigo con heurística de persecución y control por estados.

## Controles

- WASD para mover al jugador.
- R para reiniciar después de ganar o perder.
- Q para salir.

## Estructura

- Main.jack: punto de entrada.
- Game.jack: ciclo principal, estados y flujo del juego.
- Maze.jack: representación del mapa, validación de colisiones y renderizado.
- Player.jack: movimiento y dibujo del jugador.
- Enemy.jack: lógica de persecución y dibujo del enemigo.

## Nota técnica

Jack no soporta arreglos bidimensionales de forma directa, así que el mapa se representa como un arreglo lineal indexado por fila y columna.