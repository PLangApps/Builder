
# Builder Application

## Introduction
Welcome to the Builder Application! This application is designed to help you create and manage software projects efficiently using the Plang programming language. Whether you're a seasoned developer or a beginner, this tool will streamline your project development process.

## Before you run
Before you can run the Builder Application, you need to have Plang installed on your system. Plang is a natural language programming language that allows you to write code in a more intuitive way. To install Plang, please follow the instructions provided in the [Plang Installation Guide](https://github.com/PLangHQ/plang/blob/main/Documentation/Install.md).

## How to run
To run the Builder Application, open your terminal or command prompt and navigate to the application folder. Once there, execute the following command:
```bash
plang
```
If you have an OpenAI API key, you can enhance the application's capabilities by running:
```bash
plang --llmservice=openai
```

## How to build
If the application does not run as expected, it may be necessary to rebuild it. This can occur because Plang is still in early development, and code built with a previous version may not run. To rebuild the application, use the following command:
```bash
plang build
```

## Github Repository
The source code for the Builder Application is hosted on GitHub. You can find it at the following URL: [Builder GitHub Repository](https://github.com/ingig/Builder)

## Help with Plang
If you have any questions or need assistance with Plang, feel free to join the discussion board at [PLangHQ Discussions](https://github.com/PLangHQ/apps/discussions). Additionally, you can contribute to the development of Plang by visiting the [Plang GitHub Repository](https://github.com/PLangHQ) or the [Plang website](https://plang.is).

## Summary of code
- **Start.goal**: Initializes the application by starting a window app with dimensions 1400x950 and calls the `TlDraw` goal to render the main template.
- **BuildGui.goal**: Handles the building process of the application, including reading sketches and descriptions, generating database setup, user interface, and logic files, and saving them to the appropriate directories. It also provides an option to open the project in VS Code.
