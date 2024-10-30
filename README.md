# TypeScript Node Starter

This is a starter project for building Node.js applications using TypeScript. It includes configurations for ESLint and Prettier to ensure code quality and consistency.

## Getting Started

### Prerequisites

-   Node.js (>= 16.0.0)
-   pnpm (or npm/yarn)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/Frhaanaziz/typescript-node-starter.git
    cd typescript-node-starter
    ```

2. Install dependencies:

    ```sh
    pnpm install
    ```

### Scripts

-   **Build**: Compile the TypeScript code to JavaScript.

    ```sh
    pnpm run build
    ```

-   **Start**: Run the compiled JavaScript code.

    ```sh
    pnpm run start
    ```

-   **Dev**: Watch for changes and recompile the TypeScript code.

    ```sh
    pnpm run dev
    ```

-   **Lint**: Run ESLint to check for code quality issues.

    ```sh
    pnpm run lint
    ```

-   **Format**: Run Prettier to format the code.

    ```sh
    pnpm run format
    ```

## Configuration

### TypeScript

The TypeScript configuration is defined in [tsconfig.json](tsconfig.json). The compiled output is directed to the `build` directory.

### ESLint

ESLint is configured in [eslint.config.mjs](eslint.config.mjs). It includes recommended settings for JavaScript and TypeScript, as well as Prettier integration.

### Prettier

Prettier is configured in [.prettierrc](.prettierrc). It ensures consistent code formatting across the project.

## Dependencies

-   TypeScript
-   ESLint
-   Prettier
-   @typescript-eslint/eslint-plugin
-   @typescript-eslint/parser
-   @eslint/js
-   globals

## License

This project is licensed under the MIT License.
