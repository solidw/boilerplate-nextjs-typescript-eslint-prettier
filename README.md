# Boilerplate with Next.js + TypeScript + Eslint + Prettier

## Next.js + TypeScript

```bash
yarn create-next-app -e with-typescript boilerplate-nextjs-typescript-eslint-prettier
```

## Eslint + Prettier

This boilerplate use airbnb style eslint.

```bash
yarn add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-prettier eslint-import-resolver-alias eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks 
```

For run eslint

```bash
yarn lint
// or to fix it
yarn lint:fix
```

## You should

```bash
yarn
```

Install `eslint` and `prettier` on your VSCode.
Then in the `.vscode/settings.json` support auto-fix when you press save(Ctrl + s).

## You can

You can import files with absolute path using `#` when it is under `/src`

```javascript
import SomeComponent from '#/components/SomeComponent';
```

\# means `./src`.
Above import statement meaning

```javascript
import SomeComponent from './src/components/SomeComponent';
```

But aware that './src/components/SomeComponents' isn't work.
Only `#` is allowd when using import with absolute path.