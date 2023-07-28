# ESLint config

- Me basei no eslint disponibilizado pela Rocketseat, porém fiz algumas alterações para que se adeque ao meu estilo de código.

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i @smooke09/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@smooke09/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @smooke09/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@smooke09/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @smooke09/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@smooke09/eslint-config/node"
}
```

### Native

Install dependencies:
```
npm i -D eslint @smooke09/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@smooke09/eslint-config/native"
}
```