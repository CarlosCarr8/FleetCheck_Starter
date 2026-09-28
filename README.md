# FleetCheck – Build Systems Lab

This project is intentionally incomplete. Follow the worksheet in the order given.

Expected final application output:

```
FleetCheck 1.0
Vehicles loaded: 4
Vehicles requiring service: 2
Average mileage: 37000 km
```

Do not copy the solution POM. The objective is to observe how each build change alters the result.



Step 1: 
[ERROR] /C:/Users/grima/Documents/2026-27/Software Quality/TP4/FleetCheck_Starter/FleetCheck_Starter/src/main/java/pt/upt/fleetcheck/App.java:[4,38] package com.fasterxml.jackson.databind does not exist

Step 2: This error is better because the compilation succeeded, which indicates that the missing depedency was resolved. 


Step 3: 
[INFO] \- com.fasterxml.jackson.core:jackson-databind:jar:2.22.2:compile
[INFO]   +- com.fasterxml.jackson.core:jackson-annotations:jar:2.22:compile
[INFO]   \- com.fasterxml.jackson.core:jackson-core:jar:2.22.2:compile


Step 4: 
no main manifest attribute, in target/fleetcheck-1.0.0.jar

Step 5:
Removes the assumption that my computer has a manually installed version of Maven and it forces the download/usage of the right version for this project.