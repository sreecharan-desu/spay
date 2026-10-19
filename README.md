# spay

payments app experiments in a turborepo: a next.js user app with next-auth and shared ui and config packages.

## stack

turborepo · next.js 15 · next-auth · react 19 · tailwind css 4 · typescript

```
apps/user-app            next.js app
packages/ui              shared react components
packages/eslint-config   shared lint config
packages/typescript-config
```

## run locally

```bash
npm install
npm run dev
npm run build
```

## env

none required to start. next-auth needs its usual variables once providers are configured.
