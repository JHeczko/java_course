# Java Laboratory Projects

This repository contains a collection of Java projects developed as part of laboratory exercises. Each project demonstrates different concepts and techniques in Java programming, including design patterns, GUI development, concurrent programming, and more.

## Projects Overview

### 1. Leap Year Calculator (`leap_year`)
A simple program that determines whether a given year is a leap year according to the Gregorian calendar rules.

### 2. Game of Life Simulation (`life_game`)
An implementation of Conway's Game of Life with a twist - creatures (bears, cats, wolves) engage in a battle royal on the game board.

### 3. Decorator Design Pattern (`decorator_design_pattern`)
A demonstration of the Decorator design pattern applied to student resources, allowing dynamic addition of features like comments and ratings.

### 4. Online Store Simulation (`online_store_simulation`)
A concurrent online store simulation that addresses synchronization issues in multi-threaded environments, including inventory management and shopping cart operations.

### 5. Star Map JavaFX Application (`star_map_javafx`)
A graphical user interface application built with JavaFX for visualizing and managing star maps. Features include loading star data from JSON files, interactive star placement and movement, constellation management, and data persistence.

### 6. Chatbot Application (`chatbot`)
A web-based chatbot that communicates via sockets. Users can send commands, and the bot responds with information retrieved from a database.

### 7. Parallel Taxi Dispatcher (`parallel_taxi_distributory`)
A multi-threaded implementation of a taxi dispatch system, demonstrating parallel processing concepts in Java.

## Getting Started

Each project folder contains its own `README.md` with specific instructions, build commands, and usage examples. Most projects use Maven for dependency management and can be built with:

```bash
mvn clean compile
```

## Technologies Used

- **Java**: Core programming language
- **Maven**: Build automation and dependency management
- **JavaFX**: GUI development for desktop applications
- **JUnit**: Unit testing framework
- **Sockets**: Network communication for client-server applications
- **Concurrency**: Multi-threading and synchronization techniques

## Project Structure

Each project follows standard Maven directory structure:
- `src/main/java/` - Source code
- `src/test/java/` - Test code
- `src/main/resources/` - Configuration files and resources
- `pom.xml` - Maven configuration

## Contributing

This repository contains laboratory exercises. Each exercise is developed in its own branch as mentioned in the original description.
