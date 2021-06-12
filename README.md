# Live Coding Test Boilerplate

This is a test template for coding tests. It contains a bunch of folders each folder contains two files. One for the function which demonstrates the algorithm and the other one is the test file. You can add more test in the test file and run them to see if your algorithm is working properly.

This project template will make it easier to do the coding interviews.

## Running Tests

To run each algorithm you should go to the excercises folder and type below commands

```shell
yarn jest <forlder>/test.js
```

## Debugging the Algorithm

To debug the algorithm you can launch google chrome, navigate to 'chrome://inspect/#devices' and click on 'Open dedicated DevTools for Node'. Then run the following commands

```shell
node --inspect-brk <forlder>/index.js
```

## Restoring modules

To restore the modules please cd into the excercises folder and use

```shell
yarn install
```
