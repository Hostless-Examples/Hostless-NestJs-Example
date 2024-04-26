# Nestjs

Nest (NestJS) is a framework for building efficient, scalable Node.js server-side applications. It uses progressive JavaScript, is built with and fully supports TypeScript (yet still enables developers to code in pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).
Check out their official documentation [here](https://docs.nestjs.com/)

## Deploy a NestJS App

1. Fork/Clone this [Hostless-NestJS-Example](https://github.com/Hostless-Examples/Hostless-NestJs-Example) repo from github
2. Click on 'Create New App'
3. Choose a suitable app name
4. Choose your github account
5. Choose the forked github repo/the cloned remote repo
6. Choose a build system

    1. 'Detect automatically with Nixpicks' - automatically detects the programming language and builds the app
    2. 'Docker' - looks for a Dockerfile in the root of the project and build based on the instructions

7. Input a start command(optional) - By default uses ``yarn start``
8. The PORT environment variable is set by Hostless but add ``process.env.PORT`` in your main.ts file
9. The HOST environment variable should be set to '0.0.0.0' but add ``process.env.HOST`` in your main.ts file

#### Sample configuration
![sample](https://res.cloudinary.com/do58rrxug/image/upload/v1714127761/Screenshot_2024-04-26_at_11.19.52_uuaxcv.png)

#### Example project
An example project is hosted on [https://hostless-nestjs-example.hostless.app/](https://hostless-nestjs-example.hostless.app/)

#### Note
- You may need to increase the memory of the app in the settings page. NestJS app may not run with 128MB memory allocated to it.

