# pathfind
[Java Swing] 

Visualise pathfinding algorithms (A* search, Dijkstra's algorithm) on a grid.

* A* is implemented 'naïvely' with Arraylists, but is fast in practice since the graphs (grids) are fairly small.

* Dijkstra is implemented 'efficiently' with a Fibonacci Heap, but is slower on these grids because of overheads.


Compatible with any OS, but only tested on Mac so far.

# Build

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

# Use

1. Select the size of grid using the sliders. ```10x10``` is recommended for first use.

1. *\[Optional] Change ```delay``` to set the pause after each step of the algorithm.*

1. Press start.

1. *\[Optional] Click on squares to turn them into walls (white squares).*

1. *\[Optional] Click on start/end-point (red/blue square) and click elsewhere to move it.*

1. Press ```A*``` or ```Dijkstra``` to run the pathfinding algorithms.

1. *\[Optional] Press ```clear``` and repeat any of steps 4-6.*

1. *\[Optional] Look at statistics in terminal (e.g. length of path found, execution time)*

# Looks like this

![GUI Sample Image](../master/screenshots/complete-path.png?raw=true "Looks like this")
