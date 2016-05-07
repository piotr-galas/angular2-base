
This code based on https://github.com/danielschmitz/angular2-codes



This app could be strat project when you learn angular2. Project contains only necessary files and config  



* `angular2`
* `typescript`
* `systemjs`


### Install

To run do:


* `npm install` (then install necessary dependiencies in my case are below)
* `npm install reflect-metadata@0.1.2 --S`
* `npm install rxjs@5.0.0-beta.6 --S`


Then run server with hot reload:

* `npm run-script typescript` (or `tsc --watch --sourceMap` )
* `npm start` ( or live-server)


### Explanation


#### Commands
* `live-server` this command run server with hot-reload. To install it type `npm install -g live-server` 
* `tsc --watch --sourceMap` this command compile typescript to js and also generates `*.map.js` files to allow debugging typescript in browser

#### files
* `tsconfig.json` config for tsc command (compile ts files to js)
* `app.component.ts` , `boot.ts` very basic angular files
* `index.html`  is contains config to Systemjs config is the same like in oficial angular tutorial

#### packages

* `angular2` self descriptive
* `es6-shim` Provides compatibility shims so that legacy JavaScript engines behave as closely as possible to ECMAScript 6 (Harmony).
* `reflect-metadata` allow use decorators 
* `rxjs` The Reactive Extensions for JavaScript 
* `systemjs` allow import and export modules betwen files
* `zone.js`  You can think of it as thread-local storage for JavaScript VMs 

