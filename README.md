Sure, here's the enhanced README with more details about TypeScript concepts such as singletons, abstract classes, and other advanced features used in your project:

---

# Understanding TypeScript - Project Management App

This project is a sample application developed as part of the [Understanding TypeScript](https://www.udemy.com/course/understanding-typescript/) course on Udemy by [Maximilian Schwarzmüller](https://www.udemy.com/user/maximilian-schwarzmuller/). The application allows users to create and manage projects with a drag-and-drop interface. The main focus of this project is to demonstrate the use of TypeScript features such as enums, interfaces, decorators, modules, code splitting, singletons, and abstract classes while mimicking some core concepts from React such as state management and reactivity.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [TypeScript Concepts](#typescript-concepts)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Project Overview
This project showcases the following TypeScript features:
- Enums
- Interfaces
- Validation using interfaces and classes
- Decorators for validation
- Modules
- Code splitting and bundling with Webpack
- Singletons
- Abstract classes

Additionally, this project implements a simple state management system that ensures reactivity and auto-rendering when the state changes, similar to how React operates.

## Features
- **Project Creation**: Users can create new projects by providing a title, description, and number of people.
- **Drag and Drop**: Projects can be moved between active and finished states using drag-and-drop.
- **Validation**: Form inputs are validated using custom decorators.
- **Reactivity**: The application automatically updates the UI when the state changes.

## TypeScript Concepts
- **Enums**: Used to define a set of named constants, such as project statuses.
- **Interfaces**: Define the structure of objects, ensuring type safety and consistency across the application.
- **Abstract Classes**: Serve as base classes that cannot be instantiated directly but can be extended by other classes. They can include abstract methods that must be implemented by derived classes.
- **Decorators**: Special functions that can modify the behavior of classes, methods, or properties. In this project, decorators are used for automatic binding and validation.
- **Modules**: Help organize the code into reusable pieces, each with its own scope.
- **Singletons**: Ensure a class has only one instance and provide a global point of access to it. The `ProjectState` class in this project is implemented as a singleton to manage the state of the application.
- **Code Splitting**: Used to split the code into smaller chunks that can be loaded on demand, improving the application's performance.

## Project Structure
- **base-component.ts**: Defines an abstract base class for UI components to enforce the DRY principle.
- **project-input.ts**: Manages the project input form and handles user input.
- **project-item.ts**: Represents individual project items and handles drag-and-drop events.
- **project-list.ts**: Manages the list of active and finished projects, including rendering and drag-and-drop areas.
- **project-state.ts**: Manages the application state and notifies listeners about state changes.
- **decorators**: Contains custom decorators for binding and validation.
- **models**: Defines interfaces and types used throughout the application.
- **util**: Contains validation logic.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage
1. Start the development server:
    ```bash
    npm start
    ```
2. Open your browser and navigate to `http://localhost:8080` to see the application in action.

## Scripts
- **start**: Starts the development server using Webpack Dev Server.
- **build**: Builds the project for production using Webpack.

## Dependencies
- [clean-webpack-plugin](https://www.npmjs.com/package/clean-webpack-plugin)
- [lite-server](https://www.npmjs.com/package/lite-server)
- [ts-loader](https://www.npmjs.com/package/ts-loader)
- [typescript](https://www.npmjs.com/package/typescript)
- [webpack](https://www.npmjs.com/package/webpack)
- [webpack-cli](https://www.npmjs.com/package/webpack-cli)
- [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server)

## Contributing
Contributions are welcome! Please create an issue or submit a pull request for any enhancements or bug fixes.

---

Feel free to customize this README further as per your project's specific needs and add any additional information that might be helpful for users.
