# JavaScript (Node.js, v0.10.x)
## ev3dev-lang-js
The Node.js example is based on the [ev3dev-lang-js](https://github.com/WasabiFan/ev3dev-lang-js) JavaScript module for the ev3. 

## API documentation
The online documentation can be found here: 

- Node.js Language Binding: http://wasabifan.github.io/ev3dev-lang-js/
- ev3dev language bindings: http://ev3dev-lang.readthedocs.io/en/latest/

## Setting up the EV3 Brick
In order to use ev3dev-lang-js on the ev3, ev3dev-lang-js has to be installed via npm. 

```bash
npm install ev3dev-lang
```


## Development environment
It's up to you how you want to develop. This section is just a suggestion how you could setting up your JavaScript (Node.js) environment.

First download Node.js (https://nodejs.org).

Next you need editor, you could use the 30-day WebStrom trail version (https://www.jetbrains.com/webstorm/) or a simple editor like Brackets (http://brackets.io).

When you want autocomplection in WebStrom you can install the JavaScript ev3 language bindings on your local machine.

```bash
cd framework/javascript
npm install
```

## Execute the program
1.) Copy the Node.js program (Robot.js) to the EV3 brick.

2.) Make the start script executable.
```bash
chomd 755 robot.js
```

## Basic Robot Example
An example program that is written in JavaScript and that uses the ev3dev-lang-js lib can be found here. 
- [robot.js](robot.js)