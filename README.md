# **nodejs-with-typescript**

## **uses**

```
nodejs@20.11.0 (to support "watch mode" need >18.11.0)
npm@10.2.4
typescript@5.3.3
```

## **do it yourself**

1. Run command **npm install -g typescript** in terminal to install **typescript** globally.
2. Create **src** and **dist** directories.
3. Create **index.ts** file in **src** directory.
4. Run command **tsc --init** in terminal to create **tsconfig.json** file.
5. Set values in **tsconfig.json** file:
    ```javascript
    "rootDir": "./src",
    "outDir": "./dist",   
    ```
6. Add to **index.ts** file:
    ```javascript
    console.log(`Current date: ${new Date().toLocaleString()}`)
    ```
7. Run command **tsc** in terminal to compile **./src/index.ts** to **./dist/index.js**.
8. Run command **node ./dist/index** in terminal to launch app.