# Husky and Lint-staged - pre-commit hook managers

- [Husky](https://typicode.github.io/husky/)
- [Lint-staged](https://www.npmjs.com/package/lint-staged)

### Installation (Husky v9+)

```bash
npm install --save-dev prettier husky lint-staged eslint
npx husky init
```

### Sample `package.json`:

```json
{
  "scripts": {
    "prepare": "husky"
  },
  "eslintConfig": {
    "parser": "@typescript-eslint/parser",
    "rules": {
      "no-unused-vars": "off"
    }
  },
  "prettier": {
    "singleQuote": true,
    "arrowParens": "avoid"
  },
  "lint-staged": {
    "src/**/*.{js,jsx,ts,tsx,json,css}": ["prettier --write", "eslint --fix"]
  }
}
```

### Configure pre-commit hook

After running `npx husky init`, edit `.husky/pre-commit`:

```bash
npx lint-staged
```
