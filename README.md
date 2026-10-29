# TypeScript Learning

A hands-on TypeScript learning repository covering core concepts, practical exercises, and small projects.

## Tech Stack

- Node.js
- TypeScript
- npm
- Git

## Project Structure

```text
typescript-learning/
├── src/
│   └── index.ts
├── dist/              # Generated build output (not committed)
├── node_modules/      # Installed dependencies (not committed)
├── .gitignore
├── package.json
├── package-lock.json
└── tsconfig.json
```

## Getting Started

### 1. Install dependencies

```powershell
npm install
```

### 2. Build the project

```powershell
npm run build
```

TypeScript checks the source files and compiles them into the `dist/` directory.

### 3. Run the program

```powershell
npm start
```

Expected output:

```text
200
India
```

### 4. Clean generated output

```powershell
npm run clean
```

Run `npm run build` again to regenerate the output.

## Concepts Practiced

### Type inference

TypeScript can infer a variable's type from its initial value.

```typescript
let score = 100;

score = 200; // Valid
// score = "hello"; // Error: string is not assignable to number
```

Here, TypeScript infers `score` as `number`.

### Literal types with `const`

```typescript
const country = "India";
```

TypeScript can infer the literal type `"India"` because the variable cannot be reassigned.

### Compilation and execution

- `src/index.ts` contains the TypeScript source.
- `npm run build` compiles the source into JavaScript.
- `dist/index.js` contains the generated JavaScript.
- `npm start` runs the compiled JavaScript using Node.js.

### Strict type checking

The project enables `strict` mode in `tsconfig.json` to catch more type errors during development.

## Learning Approach

Each topic will include explanations, code examples, practical exercises, and notes on important concepts.
