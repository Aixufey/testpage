# TestPage

Minimal setup for setting up github pages on GitHub

1. `echo {} > package.json`
2. `npm i -D vite typescript prettier`
3. `npm i react react-dom`
4. Build with check and formatting
5. `npm pkg set scripts.build="npm run check && vite build"`
6. `npm pkg set scripts.check="prettier --check . && tsc --noEmit`
7. TypeScript with React `npx tsc --init --jsx react`
8. Create index.html with root
9. Prettify before build `npx prettier --write .`
10. Build the app `npm run build`
