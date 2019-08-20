# @captor/react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.

`@captor/react-scripts` is identical to `facebook react-scripts` but it adds loaders for mdx and wasm.

## How to use the `@captor/react-scripts`

To create a new app run:

```
npx create-react-app <app-name> --scripts-version @captor/react-scripts
```

Or change to `@captor/react-scripts` in an existing app. Change in package.json

```
  "dependencies": {
    "react-scripts": "x.x.x",
    "react": "^x.x.x",
    "react-dom": "^x.x.x"
  },
```

to

```
  "dependencies": {
    "@captor/react-scripts": "x.x.x",
    "react": "^x.x.x",
    "react-dom": "^x.x.x"
  },
```

## Fork instructions

[Follow this guide](https://auth0.com/blog/how-to-configure-create-react-app/)
