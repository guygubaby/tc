# @bryce-loskie/tc

`tsconfig.json` base configs

[![NPM version](https://img.shields.io/npm/v/@bryce-loskie/tc?color=a1b858&label=)](https://www.npmjs.com/package/@bryce-loskie/tc)

## Install

```bash
pnpm i -D @bryce-loskie/tc
```

## Usage

### Library

#### Normal Library

```json
{
  "extends": "@bryce-loskie/tc/lib",
  "compilerOptions": {
    "rootDir": "./src",
    "outDir": "./dist"
  },
  "include": ["src"]
}
```

#### React Components Library

```json
{
  "extends": "@bryce-loskie/tc/lib-react",
  "compilerOptions": {
    "rootDir": "./src",
    "outDir": "./dist"
  },
  "include": ["src"]
}
```

### Project

#### React Project

```json
{
  "extends": "@bryce-loskie/tc/react",
  "include": ["src"]
}
```

#### Vue Project

```json
{
  "extends": "@bryce-loskie/tc/vue",
  "include": ["src"]
}
```

## Optimizations

```json
{
  "compilerOptions": {
    // upgrade output syntax target
    "target": "es6",
    // generate declaration source map
    "declarationMap": true
    // ...
  }
}
```

## License

[MIT](./LICENSE) License © 2023 [guygubaby](https://github.com/guygubaby)
