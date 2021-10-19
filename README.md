# Measurements
Contains the obtained measurements

folder|description
-|-
[cfs](https://github.com/bachelor-thesis-resources/measurements/tree/main/cfs) | measurement data of 5 jvms using CFS
[eteam](https://github.com/bachelor-thesis-resources/measurements/tree/main/eteam) | measurement data of 5 jvms using eteam scheduler
[native-image](https://github.com/bachelor-thesis-resources/measurements/tree/main/native-image) | measurement data of the native-image version of the java app, using CFS and eteam

## Plots

Contains plots of the obtained measurements

folder|description
-|-
[plots-cfs](https://github.com/bachelor-thesis-resources/measurements/tree/main/plots-cfs) | histogram and density plots of the jvms using CFS
[plots-eteam](https://github.com/bachelor-thesis-resources/measurements/tree/main/plots-eteam) | histogram and density plots of the jvms using eteam
[plots-native-image](https://github.com/bachelor-thesis-resources/measurements/tree/main/plots-native-image) | histogram and density plots of the native-image version of the java app, using CFS and eteam

Every directory listed above contains two folders:

folder | description
-|-
densitites | density plots 
histograms | histogram plots

## Ulysses16.tsp

`ulysses16.tsp` is a reduced version of a symmetric TSP that served as input data to the program

## Java Versions 

Descriptor | `java --version` / `native-image --version`
-|-
*Corretto* | OpenJDK Runtime Environment Corretto-11.0.12.7.1 (build 11.0.12+7-LTS) <br/> OpenJDK 64-Bit Server VM Corretto-11.0.12.7.1 (build 11.0.12+7-LTS, mixed mode)
*Graal_CE* | OpenJDK Runtime Environment GraalVM CE 20.3.3 (build 11.0.12+6-jvmci-20.3-b20) <br/> OpenJDK 64-Bit Server VM GraalVM CE 20.3.3 <br/> (build 11.0.12+6-jvmci-20.3-b20, mixed mode, sharing)
*Graal_EE* | Java(TM) SE Runtime Environment GraalVM EE 20.3.3 (build 11.0.12+8-LTS-jvmci-20.3-b18) <br/> Java HotSpot(TM) 64-Bit Server VM GraalVM EE 20.3.3 <br/> (build 11.0.12+8-LTS-jvmci-20.3-b18, mixed mode, sharing)
*Hotspot CE* | OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9) <br/> OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9,  mixed mode)
*Hotspot EE* | Java(TM) SE Runtime Environment 18.9 (build 11.0.12+8-LTS-237) <br/> Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.12+8-LTS-237, mixed mode)
*Native CE*| GraalVM 20.3.3 Java 11 (Java Version 11.0.12+6-jvmci-20.3-b20)
*Native EE*| GraalVM 20.3.3 Java 11 (Java Version 11.0.12+8-LTS-jvmci-20.3-b18)
