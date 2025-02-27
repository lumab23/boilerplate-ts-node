# Node.js + TypeScript Boilerplate

A simple TypeScript boilerplate for Node.js applications.

## Features
- **TypeScript** for type safety
- **Express.js** for building APIs
- **ESLint & Prettier** for code quality and formatting
- **Environment Variables** support via `dotenv`
- **Build & Dev Commands** for easy development and production readiness

## Folder Structure
```
node_modules/
src/
  ├── app.ts        # App configuration
  ├── server.ts     # Entry point
.env                # Environment variables
.gitignore          # Ignored files (node_modules, etc.)
.prettierrc         # Prettier configuration
.eslint.config.mjs  # ESLint configuration
package.json        # Dependencies and scripts
README.md           # Documentation
```

## Requirements
- **Node.js** (v18+ recommended)
- **npm** 

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/lumab23/node-ts-boilerplate.git
   ```
2. Navigate into the project directory:
   ```sh
   cd node-ts-boilerplate
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Configuration
Create a `.env` file in the root directory:
```
PORT=3001
```

## Scripts
### Development
Start the development server with hot-reloading:
```sh
npm run dev
```

### Linting & Formatting
Run ESLint to check code quality:
```sh
npm run lint
```
Format code using Prettier:
```sh
npm run format
```

### Build & Run
Compile TypeScript:
```sh
npm run build
```
Run the compiled app:
```sh
npm run start:dist
```

## Contributing
Feel free to fork, improve, and make pull requests. Contributions are welcome!