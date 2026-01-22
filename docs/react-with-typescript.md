# Set up React with TypeScript

[React Documentation](https://react.dev/)

> **Note:** Create React App is deprecated. Modern alternatives recommended by React team:

### Installation

#### Vite (Recommended - Fast & Modern)

```bash
npm create vite@latest my-app-name -- --template react-ts
cd my-app-name
npm install
npm run dev
```

#### Next.js (Full-stack Framework)

```bash
npx create-next-app@latest my-app-name --typescript
```

#### Remix (Full-stack Framework)

```bash
npx create-remix@latest my-app-name --typescript
```

### Legacy: Create React App (Deprecated)

```bash
# Not recommended - CRA is deprecated as of 2023
npx create-react-app my-app-name --template typescript
```

### Additional Libraries

- [fp-ts](https://github.com/gcanti/fp-ts) - Typed functional Programming in TypeScript
- [io-ts](https://github.com/gcanti/io-ts) - Provides safe encoding/decoding
- [Zod](https://zod.dev/) - TypeScript-first schema validation
- [Prettier, ESLint, Husky](/pre-commit-hooks.md) - Format your code
