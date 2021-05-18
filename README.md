# shibaemon-next

ShibaEmon New Production Sample
Next.js Vacel Blog

## List
Setup Next.js project
TypeScript Integration
ESLint Prettier
Build Home
Setting Head

### Setup Next.js project & TypeScript Integration
$ npx create-react-app

Buid command
$ yarn dev

$ touch tsconfig.json

Need TypeScript compiler
$ yarn add -D typescript @types/react @types/node
(-D = Develop)

If you get error when update to node 
Now I use LTS version V14.17.0

Check your build
$ yarn dev

OK to go
setting Typescript to tsconfig.json for absolute pass.
add "baseUrl": ".", in tsconfig.json

### ESLint Prettier

$ npx eslint --init


? How would you like to use ESLint? … 
  To check syntax only
❯ To check syntax and find problems
  To check syntax, find problems, and enforce code style

  ✔ How would you like to use ESLint? · problems
? What type of modules does your project use? … 
❯ JavaScript modules (import/export)
  CommonJS (require/exports)  None of these

  ✔ What type of modules does your project use? · esm
? Which framework does your project use? … 
❯ React
  Vue.js
  None of these

  ✔ Which framework does your project use? · react
? Does your project use TypeScript? › No / ❯ Yes

✔ Does your project use TypeScript? · No / ❯ Yes
? Where does your code run? …  (Press <space> to select, <a> to toggle all, <i> to invert selection)
✔ Browser
✔ Node

✔ Where does your code run? · browser? What format do you want your config file to be in? … 
❯ JavaScript
  YAML
  JSON

  ✔ What format do you want your config file to be in? · JavaScript

Local ESLint installation not found.
The config that you've selected requires the following dependencies:

eslint-plugin-react@latest @typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest eslint@latest
? Would you like to install them now with npm? › No / ❯ Yes

Run ESlint
Write in package.json
"lint": "eslint . --ext .js, .ts, .tsx" 👈NG
"lint": "eslint --ext .js,.jsx,.ts,.tsx" 👈OK
https://qiita.com/karak/items/12811d235b0d8bc8ad00

Setting OFF in .eslintrc.js

Check $ yarn lint

$ yarn add -D prettier eslint-plugin-prettier eslint-config-prettier

$ yarn lint --fix

### Build Home

test make index.tsx & add Head

add favicon
https://emojipedia.org/

#### make index.tsx by static server generation
#### make blog page by next.mdx remote module

