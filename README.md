# TaskManager_AnnotationProcessing :clipboard:

This project is part of the practical work for the course "Automating Software Applications in the Java Language" at NaUKMA. It is a simple console-based task manager application implemented as a multi-module Gradle project.
This project demonstrates the usage of custom annotations and an annotation processor in Java. It allows you to define your own classes, methods, and annotations, and leverage annotation processing to generate new classes and perform runtime logic processing and verification.

## Structure :open_file_folder:

The project consists of 3 modules:

1. **core**: This module contains the main business logic of the application including annotations and annotation processor.
2. **data**: This module is responsible for persisting tasks to a file using Google's Gson library.
3. **ui**: This module contains the user interface logic for interacting with tasks via a command-line interface.

## Features :gear:

- **Custom Classes and Methods**: Create your own regular classes and methods to implement the desired functionality specific to your project.
- **Custom Annotations**: Define your own annotations to add metadata and behavior to your classes and methods.
- **Annotation Processor**: Develop a custom annotation processor that processes the annotations in your codebase and performs actions based on them.
- **Code Generation**: Utilize the annotation processor to generate new classes dynamically based on the annotated elements in your code.
- **Runtime Logic Processing**: Leverage your custom annotations to process and verify the logic of your code during runtime.

## Setup :wrench:

To generate annotated classes, jar and build core module of the project.
1. ./gradlew :core:jar
2. ./gradlew :core:build
