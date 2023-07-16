# Codex ESLint config

## Whats included?

- Standard config base;
- React plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies:
```
npm install eslint @codex-remote/eslint-config -D
```
or

```
yarn add eslint @codex-remote/eslint-config -D
```
or

```
pnpm install eslint @codex-remote/eslint-config -D
```

2. Create a `.eslintrc.json` file extending the config:

React
```
{
  "extends": "@codex-remote/eslint-config/react"
}
```

Node.js
```
{
  "extends": "@codex-remote/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.