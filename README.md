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

Run ESlint
Write in package.json

Setting OFF in .eslintrc.js

Check $ yarn lint

$ yarn add -D prettier eslint-plugin-prettier eslint-config-prettier

$ yarn lint --fix

### Build Home

test make index.tsx & add Head

add favicon

#### make index.tsx by static server generation
#### make blog page by next.mdx remote module

md file →　mdx file
need two library

$ yarn add next-mdx-remote gray-matter

gray-matter = calling 'front matter'
get perse top of the meta md file 

next-mdx-remote 
persed articles change jsx

dynamic routing
