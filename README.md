# Measurements
Contains the obtained measurements

folder|description
-|-
[cfs](https://github.com/bachelor-thesis-resources/measurements/tree/main/cfs) | measurements of 5 jvms using CFS
[eteam](https://github.com/bachelor-thesis-resources/measurements/tree/main/eteam) | measurements of 5 jvms using CFS
[native-image](https://github.com/bachelor-thesis-resources/measurements/tree/main/native-image) | measurements native image version of the java app using CFS and eteam

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
