1. initialize project 
> npm init --y
2. install dependencies
> npm i react typescript @types/react -D

3. initialize typescript
> npx tsc --init

4. add settings to tsconfig.json
    "jsx": "react",
    "module":"ESNext",
    "declaration": true,
    "declarationDir": "types",
    "sourceMap": true,
    "outDir": "dist",
    "moduleResolution": "node",
    "allowSyntheticDefaultImports": true,
    "emitDeclarationOnly": true,

5. install rollup and plugins
> npm i rollup @rollup/plugin-node-resolve @rollup/plugin-commonjs @rollup/plugin-typescript rollup-plugin-dts
 -D