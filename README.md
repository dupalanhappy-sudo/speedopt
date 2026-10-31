# Speed Optimizer - Crystal + Anchor optimizer, speed 1-10 (Fabric 1.21.11, client-side)

## Build
Needs JDK 21 and Gradle 8.14+ (or drop src/ into the Fabric 1.21.11 example mod).
  gradle build
Jar: build/libs/speedoptimizer-1.2.0+mc1.21.11.jar -> put in .minecraft/mods
Fabric API is NOT needed, only Fabric Loader 0.18+.

## Chat commands (never sent to the server)
.speedopt crystal <1-10>
.speedopt anchor <1-10>
.speedopt setdelay crystal|anchor <level> <ticks>
.speedopt toggle | togglecrystal | toggleanchor | status

10 = fastest (0 ticks), 1 = slowest. Config: .minecraft/config/speedoptimizer.json

## Get the .jar without installing anything (GitHub)
1. Make a free GitHub account, create a new repository, and upload everything in this folder
   (keep the .github folder).
2. Open the Actions tab -> "Build mod jar" -> wait for the green check.
3. Open the finished run, download "speedoptimizer-jar" at the bottom, unzip it.
   Use the file that does NOT end in -sources.jar. Put it in .minecraft/mods.
