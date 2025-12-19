# Java Sample Project

This is a simple Java Gradle project.

## Created Files

- **build.gradle**: Gradle build script.
- **settings.gradle**: Gradle settings file.
- **App.java**: Main application class with a `main` method and a `getGreeting` method.
- **AppTest.java**: Unit test ensuring `App` works as expected.

## Prerequisites
- Java JDK 17 or higher
- Gradle 7.0 or higher (for initial setup only)

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


