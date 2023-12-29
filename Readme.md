# TypeScript Express Server

This is a simple TypeScript project that utilizes the Express framework to create a basic server. The server responds with a "Hello Client" message when accessed at the root endpoint ("/").

## Prerequisites

Before running the project, make sure you have Node.js and npm installed on your machine.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Rasheek16/Node-Typescript.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Node-Typescript
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

   This command installs the necessary dependencies, including Express and TypeScript.

## Usage

1. Run the TypeScript server:

   ```bash
   npm start
   ```

   This command uses `ts-node` to transpile and run the TypeScript code directly. The server will start, and you can access it at [http://localhost:8080](http://localhost:8080).

2. Open your web browser and navigate to [http://localhost:8080](http://localhost:8080). You should see the "Hello Client" message.

## Project Structure

- `src/index.ts`: Main entry point of the TypeScript application.
- `tsconfig.json`: TypeScript configuration file with compiler options.
- `package.json`: Configuration file for Node.js project, including dependencies and scripts.

## Dependencies

- [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [@types/express](https://www.npmjs.com/package/@types/express): TypeScript type definitions for Express.
- [ts-node](https://www.npmjs.com/package/ts-node): TypeScript execution and REPL for Node.js.

## Scripts

- `npm start`: Transpiles and runs the TypeScript code using `ts-node`.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Follow the [contribution guidelines](CONTRIBUTING.md) for more details.

