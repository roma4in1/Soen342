# Soen342

# Members:
Romain Corbel 40257534<br> (Leader)
Mahdi Djellab 40254945<br>
Jose Nehme 40158603<br>
## Prerequisites

- Java JDK 11 or higher
- The SQLite JDBC driver (`sqlite-jdbc-3.36.0.3.jar`) is included in the `lib/` folder

## How to Run

All commands should be run from the **project root** (the `IterationX/ProofOfConcept/` folder).

**1. Collect all source files:**
```bash
dir /s /b src\*.java > sources.txt
```

**2. Compile:**
```bash
javac -cp "lib\sqlite-jdbc-3.36.0.3.jar" -d out @sources.txt
```

**3. Run:**
```bash
java -cp "out;lib\sqlite-jdbc-3.36.0.3.jar" taskmanager.Main
```

> **Note:** These commands are for **Windows Command Prompt**. On Mac/Linux, replace `;` with `:` in the classpath and use `find` instead of `dir` for step 1.
