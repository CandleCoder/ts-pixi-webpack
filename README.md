# PIXI, Typescript & Webpack

## Introduction

This Repository Uses Pixi 5+ , Latest Webpack and Typescript. 


1. Make your own Model ,View Controller According to your requirement and work on it. For now only sample index.ts has been provided.


  2. For loading assets Webpack is needed to be modified.
  3. Postload is not implemented.
  4. Resize is implemented and Snipped is Provided below.
  5. The Pixi Sound Manager has been Incorporated.

## Entry Point

>  const app = new Application({
    autoStart: false,
    resizeTo: window
    });
    document.body.appendChild(app.view);

## Installation / Important Commands

> npm i - After Cloning this Repo , Run this Command.

> npm run build - This command makes build of the Application. It compiles from ts to js.

> npm run start - This starts to server at port 9000 after building the app.