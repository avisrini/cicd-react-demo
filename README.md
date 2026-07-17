# cicd-react-demo

Demonstrate CI/CD for a React project using GitHub Actions.

This project uses [Vite](https://vite.dev/) with React 18 and TypeScript, and
[Vitest](https://vitest.dev/) for testing. It was originally bootstrapped with
Create React App and migrated to Vite.

## Requirements

- Node.js **20+** (see `.nvmrc`)

## Available Scripts

In the project directory, you can run:

### `yarn dev`

Runs the app in development mode with hot module replacement.<br />
Open the URL printed in the console (default [http://localhost:5173](http://localhost:5173)).

`yarn start` is kept as an alias for `yarn dev`.

### `yarn test`

Runs the test suite once with [Vitest](https://vitest.dev/).<br />
Use `yarn test:watch` for interactive watch mode.

### `yarn build`

Type-checks with `tsc` and builds the app for production into the `dist` folder.<br />
The build is minified and filenames include content hashes.

### `yarn preview`

Serves the production build from `dist` locally to preview it before deploying.

## Learn More

- [Vite documentation](https://vite.dev/guide/)
- [Vitest documentation](https://vitest.dev/guide/)
- [React documentation](https://react.dev/)
