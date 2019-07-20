# node-typescript-eslint-config


My personal eslint + prettier config for nodejs and typescript.

Run the following commands:

- `mkdir projectName && cd projectName`

- `yarn add eslint nodemon`

- `yarn add -D prettier typescript eslint-config-prettier eslint-plugin-prettier eslint-config-node eslint-plugin-node @typescript-eslint/eslint-plugin @typescript-eslint/parser ts-node-dev @types/node @types/express`

- `npx tsc --init`

Add the following to your package.json:

```json
 "scripts": {
    "start": "ts-node-dev --respawn src/index.ts",
    "dev": "nodemon --exec ts-node src/index.ts",
    "build": "tsc"
  },
```

Then create the **.eslintrc** and **.prettierrc** files using the provided config
