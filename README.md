# 3D-render-simulator
Developed a scratch-built 3D rendering engine that visualizes geometry using ASCII characters, mapping calculated pixel luminance to character density.

# Running the demo
## Requirements
- linux
- java 22+
- Graal 23.1+

```shell
git clone https://github.com/PinkNekoFist/3D-render-simulator.git
cd 3D-render-simulator/src/main/java
javac -cp .:jline-3.26.2-SNAPSHOT.jar org/example/GameController.java
java -cp .:jline-3.26.2-SNAPSHOT.jar org/example/GameController 
```
- use w, s to move forward and backward
- use a, d to turn left and right
- use j, k to move up and down
