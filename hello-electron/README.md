# hello-electron

An Electron introduction, courtesy of the [docs](https://www.electronjs.org/).

In the root directory of the application:

1. Generate a Node application by running `npm init` or `npm init -y`.

2. Install the dependency Electron by runnning `npm i electron --save-dev`.

3. Create an index.html

4. Create a `main.js` script that runs our main process, which controls our app
    and runs in a Node.js environment. In this script, we used Electron's app
    and BrowserWindow modules to create a browser window that displays web
    content in a separate process (the renderer).

5. In order to access certain Node.js functionality in the renderer, we attached
    a preload script to our BrowserWindow constructor.
