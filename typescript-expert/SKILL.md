# TypeScript Expert Skill

## Description
This skill provides instructions and best practices for developing TypeScript applications, both frontend (React, Vue, etc.) and backend (Node.js).

## Core Mandates
- **Strict Typing:** Always enable `"strict": true` in `tsconfig.json`. Avoid using `any`; use `unknown` if the type is truly not known.
- **Linting & Formatting:** Use `eslint` and `prettier`. Adhere strictly to the project's existing linting rules.
- **Project Structure:** Keep source files in `src/`. Organize by feature or module rather than by file type (e.g., group a component, its styles, and its tests together).
- **Testing:** Write unit tests using `jest` or `vitest`. Ensure high test coverage for critical business logic.

## Workflows
1. **Setup:** Ensure `package.json` and `tsconfig.json` are properly configured.
2. **Implementation:** Write clean, modular TypeScript code with descriptive variable names.
3. **Type Checking:** Run `tsc --noEmit` frequently to catch type errors early.
4. **Formatting:** Run `npm run format` or `prettier --write .` before finalizing changes.
