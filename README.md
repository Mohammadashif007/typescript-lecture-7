## Organizing a TypeScript Project

### Project Structure

- Create two folders: `src` for source files and `public` for deployment files.

### Deployment

- Place all files intended for deployment in the `public` folder.
- Store files not intended for deployment in the `src` folder.

### Configuration

- Initialize a TypeScript configuration file by running `tsc --init`.
- In the generated `tsconfig.json` file, specify the root directory and output directory. This determines where the TypeScript compiler will find `.ts` files and where the compiled files will be placed.