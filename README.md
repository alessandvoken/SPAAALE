# SPA Portfolio – Alessandro Perchiazzi

Welcome!

> _TO DO:_

---

## -- For Developers --

This template comes with a minimal ESLint configuration:

```js
export default tseslint.config({
  extends: [
    ...tseslint.configs.recommendedTypeChecked,
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    parserOptions: {
      project: ["./tsconfig.node.json", "./tsconfig.app.json"],
      tsconfigRootDir: import.meta.dirname,
    },
  },
});
```
