# AWS 

- It is important to include the --save-dev flag because it saves TypeScript as a development dependency. This means that TypeScript is absolutely required for the development of your project.
```
npm install --save-dev @types/node
```
- you can initialize your TypeScript project by using the following command:
```
npx tsc --init
```
- Uncomment and update tsconfig.json for `outDir` param
- install aws sdk
```
npm install aws-sdk
```
- compile
```
npx tsc
```