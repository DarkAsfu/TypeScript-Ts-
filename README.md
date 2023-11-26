# TypeScript

TypeScript is an object-oriented programming language built on top of JavaScript, providing additional features.

## Table of Contents

- [JavaScript Limitations](#javascript-limitations)
- [Benefits of Using TypeScript](#benefits-of-using-typescript)
- [TypeScript Types](#typescript-types)
- [Drawbacks of Using TypeScript](#drawbacks-of-using-typescript)
- [Install TypeScript](#install-typescript)
  - [Check NodeJs Version](#check-nodejs-version)
  - [Install TypeScript](#install-typescript-1)
  - [Check TypeScript Version](#check-typescript-version)
  - [First TypeScript Code (index.ts)](#first-typescript-code-indexts)
  - [Configure TypeScript](#configure-typescript)

## JavaScript Limitations

- Dynamically Typed language
- Very difficult to maintain large codebase
- Hard to find bugs
- Catch errors only in runtime
- Version transpile problem

## Benefits of Using TypeScript

- Support for older browsers
- Type Safety
- Increased Productivity
- Fewer bugs and less testing

## TypeScript Types

**JavaScript types in TypeScript:**
- Number
- String
- Boolean
- Null
- Undefined
- Object
- Symbol

**TypeScript's Own Types:**
- Interface
- Void
- Array
- Tuple
- Enum
- Union
- Intersection

## Drawbacks of Using TypeScript

- Type Complexities
- Limited library Support
- Over Engineering
- Migration Challenges

## Install TypeScript 

### Check NodeJs Version

1. Check Version 
    ```bash 
    node --version 
    ```

2. Install NVM (Node Version Manager)
    ```bash
    https://github.com/coreybutler/nvm-windows/releases/download/1.1.12/nvm-setup.exe
    ```
   Download and install.

3. Check NVM version
    ```bash
    nvm --v
    ```
   Switch to any Node.js version (Example: `nvm install 18.17.0`)

4. Install TypeScript

    Install locally:
    ```bash
    npm i typescript --save-dev
    ``` 
    Install globally:
    ```bash
    npm i -g typescript
    ```

5. Check TypeScript version
    ```bash
    tsc -v
    ```

### First TypeScript Code (index.ts)

    ```bash
    let name = 'Ashraful Islam';
    console.log(name);
    ```
Run it using:

    ```bash
    tsc index.ts
    node index.js
    ```
### Configure TypeScript
    ```bash
    tsc --init
    ```
Change the root directory location (rootDir)
Change the output directory location (outDir)