# demo-java

This is a minimal example project to demonstrate the Java + Gradle development workflow - a starting point for learning or testing the build system.
- **Main class**: `com.example.demo.App`
- **Main method**: Prints "Hello World!" to the console when executed
- **Helper method**: `getGreeting()` returns "Hello World!" (used for testing)
- **Tests**: Unit tests verify that `getGreeting()` works correctly

## Project Structure

```
demo-java/
├── build.gradle      # Gradle build script
├── settings.gradle   # Gradle settings file
├── gradlew          # Gradle wrapper script (Unix)
├── gradlew.bat      # Gradle wrapper script (Windows)
├── gradle/
│   └── wrapper/     # Gradle wrapper files
└── src/
    ├── main/
    │   └── java/
    │       └── App.java      # Main application class
    └── test/
        └── java/
            └── AppTest.java  # Unit tests
```

## Prerequisites

- **Java JDK 17 or higher**
  - **Note**: Java 25 requires Gradle 9.0 or higher.
- **Gradle 7.6 or higher**

Tested with:
- Java: `OpenJDK 25`
- Gradle: `9.2.1`

## Setup
First, generate the Gradle wrapper scripts:
```bash
gradle wrapper
```
This will create the `gradlew` script.

## Build
To build the project and run tests using the wrapper:
```bash
./gradlew build
```

## Test
To run only the tests:
```bash
./gradlew test
```
Test reports are generated in `build/reports/tests/test/index.html`.

## Run
To run the application using the wrapper:

```bash
./gradlew run
```


