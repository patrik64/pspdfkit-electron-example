## pspdfkit-electron-example

to build and run:

using yarn:

1. yarn
2. copy node_modules/pspdfkit/dist/pspdfkit.js -> public/pspdfkit.js
3. copy node_modules/pspdfkit/dist/pspdfkit-lib -> public/pspdfkit-lib
4. yarn start


using npm:

```
npm i
cp -r node_modules/pspdfkit/dist/pspdfkit-lib ./public
cp node_modules/pspdfkit/dist/pspdfkit.js ./public
npm run start
```

using pnpm:
```
pnpm i
cp -r node_modules/pspdfkit/dist/pspdfkit-lib ./public
cp node_modules/pspdfkit/dist/pspdfkit.js ./public
pnpm run start
```
