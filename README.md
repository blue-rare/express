# Simple express App

This project was created to practice some backend basics.
Here are the commands that were used to install necessary software

- yarn init --yes
- yarn add express dotenv cors
- yarn add nodemon --dev
- yarn add nodemon typescript ts-node @types/node @types/express @types/cors jest ts-jest @types/jest supertest @types/supertest --dev
- yarn tsc --init

This command is used to monitor errors while compiling typescript into js
- yarn tsc -w

And this one is for monitoring node execution in DevTools with the ability to put breakpoints and debug
- yarn nodemon --inspect dist/index.js