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