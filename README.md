# pathfind
[Java Swing] 

Visualise pathfinding algorithms (A* search, Dijkstra's algorithm) on a grid.

Compatible with any OS, but only tested on Mac so far.

**Build**

Compile simply with
```bash
  cd src
  javac Pathfind.java
```
and run with
```bash
  java -ea Pathfind
 ```

*Alternatively* use
```bash
  cd src
  chmod 711 make
  ./make
```
to create an executable .jar on Mac/Linux

**Use**

1. Select the size of grid using the sliders. ```10x10``` is recommended for first use.

1. *\[Optional] Change ```delay``` to set the pause after each step of the algorithm.*

1. Press start.

1. *\[Optional] Click on squares to turn them into walls (white squares).*

1. *\[Optional] Click on start/end-point (red/blue square) and click elsewhere to move it.*

1. Press ```A*``` or ```Dijkstra``` to run the pathfinding algorithms.

1. *\[Optional] Press ```clear``` and repeat any of steps 4-6.*
