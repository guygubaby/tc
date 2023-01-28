# @bryce-loskie/tc

`tsconfig.json` base configs

## Install

```bash
pnpm i -D @bryce-loskie/tc
```

## Usage

### Library

#### Library

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

MIT
