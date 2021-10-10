# Lyr's TS Config

![GitHub package.json version](https://img.shields.io/github/package-json/v/lyr-7d1h/tsconfig?label=npm)

## Configuration

```bash
npm i -D @lyr_7d1h/tsconfig
```

Example tsconfig tsconfig

```json
{
  "extends": "@lyr_7d1h/tsconfig.json",

  "compilerOptions": {
    "outDir": "dist"
  },

  "include": ["src/**/*.ts"],
  "exclude": ["node_modules", "dist"]
}
```
