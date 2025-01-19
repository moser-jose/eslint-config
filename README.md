# ESLint Configurations

This package provides shared ESLint configurations for Node.js and React Native projects.

## Installation

```bash
# Using npm
npm install -D @mosmmy/eslint-config

# Using yarn
yarn add -D @mosmmy/eslint-config

# Using pnpm
pnpm add -D @mosmmy/eslint-config
```

## Configurations

### Node.js Configuration

Add the following to your `.eslintrc.json` or `.eslintrc.js`:

```json
{
  "extends": ["@mosmmy/eslint-config/node"]
}
```

### React Native Configuration

Add the following to your `.eslintrc.json` or `.eslintrc.js`:

```json
{
  "extends": ["@mosmmy/eslint-config/react-native"]
}
```


## VS Code Integration

For the best experience, install these VS Code extensions:

1. ESLint
2. Prettier

Add these settings to your VS Code settings:

```json
{
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```


## Licence

This project is governed by the [MIT](LICENSE.md). Just remember to be a nice person and send back any modifications, corrections or improvements. ✌️

## Author

| [<img src="https://avatars0.githubusercontent.com/u/8234620?" width="115"><br><sub>@moser-jose</sub>](https://github.com/moser-jose) |
| :---: |
