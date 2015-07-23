# canon-bootstrap canon-legacy demo

**This demo is intended to demonstrate a hybrid consumption of Canon and canon-bootstrap.  If you follow the direction below to clone and install this repository on your local machine, you can then run the demo and view the output.**

## What this will show you

You will see a control panel landing page that is framed using canon-bootstrap.  This demonstrates how teams starting with Canon-bootstrap would initiate their site.

Inside of that initial bootstrap based markup, you will see Canon markup building out a typical Canon application, including navigation and content.  This demonstrates that you can use Canon markup inside Canon-bootstrap.

Inside of that, you will see canon-bootrap again, being used for faceting and a table list.  This demonstrates that you can use Canon-bootstrap inside Canon.

## Developing

Canon Bootstrap requires the following dependencies:

- Node.js v0.10 or higher

Once all dependencies are installed, begin development with the following
commands:

```
$ git clone https://github.com/racker80/cb-legacy-demo
$ cd cb-legacy-demo
$ npm install
$ npm start
```

Visit `http://0.0.0.0:8000` to see documentation and a live demo of
this approach.
