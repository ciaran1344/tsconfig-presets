# tsconfig-presets

A set of base [tsconfig.json](https://www.typescriptlang.org/tsconfig) files for TypeScript projects.

1. `tsconfig-base.json`: A good TSConfig starting point.
1. `tsconfig-esm.json`: A TSConfig for use with ESM projects.

## Usage

In your `tsconfig.json`:

```json
{
  "extends": "@ciaran1344/tsconfig-presets/tsconfig-esm.json",
  // Rest of your tsconfig options here
  "include": ["src"]
}
```
