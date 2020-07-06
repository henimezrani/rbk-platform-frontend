<p align="center">
  <a href="https://example.com/">
    <img src="https://via.placeholder.com/72" alt="Logo" width=72 height=72>
  </a>

  <h3 align="center">Logo</h3>

  <p align="center">
    Short description
  </p>
</p>

# RBK E-Learning Plateform

> Dashboard based on paper dashboard UI template + vue-router

This project is a vue version of [Paper-dashboard](https://www.creative-tim.com/product/paper-dashboard)
designed for vue js.The dashboard includes vue-router

## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Contribution Guide](#contributing)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)

## Quick start

### Installation Guidelines
### Prerequisites

If you don’t havee any of these tools installed already, you will need to:
```
 Download and install git
 Download and install nodejs https://nodejs.org
```


### Get Started
You will need to clone source code of client GitHub repository. To do this open console and execute following lines:

```shell
git clone https://github.com/Ogui99/Flow-backend.git
```
### Installing Node Modules
You will need to clone source code of client GitHub repository. To do this open console and execute following lines:

```
 cd Flow-backend
 npm install
```

### Running local copy
To run local copy in development mode, execute:
```
 npm start
```
your http://localhost:3000 will be running for API calls


### Setting your environment

The file _.env.dev_ is meant to set the environment variables, _.dev_ is meant to reference the development environment,
If you need to set a new one, make a copy of the same file and rename it to environment you need to work on.
ex: _.env.prod_ .
In which, you'll set the environment variables you need to work on.
To tell express which environment to follow, go to _app.js_
and change the line 
```
require('custom-env').env('dev');
```
to
 
```
require('custom-env').env('prod');
```

### Build Setup

#### install dependencies
```
npm install
```
#### serve with hot reload at localhost:8080
```
npm run dev
```
#### build for production with minification
```
npm run build
```
#### lint
```
npm run lint
```

## Status

RBK E-Learning Plateform is in developmennt process


## What's included

Here is the folder structure

```text
├───config
|
├───Controllers
|
├───models
|
├───operations
|
├───public
|
├───routes
│   └───api
├───Services
│  
├───uploads
|
├───views
```


Check the [Live Demo here](https://link-to-live-demo.com).

## Template Documentation
Link to [Documentation](http://vuejs.creative-tim.com/vue-paper-dashboard/documentation/)



## Contribution guide
* Fork the repository
* `npm install` or `yarn install`
* Make changes
* Create a new branch with your name and the feature name e.g: ```branch name : your-name-feature-name```
* Open Pull Request

For detailed explanation on how things work, checkout the [guide](https://github.com/vuejs/vue-cli/blob/dev/docs/README.md)

Please read through our [Endpoint guidelines](). Included are directions for making an endpoint and notes on development.

Please Read our coding style and contribution [guidelines]().

Moreover, all Javascript should conform to the [Code Guide](), maintained by [standard](https://github.com/standard/standard).

## Creators

[Heni Mezrani]()
[Zied Barhoumi]()

## Thanks

Thanks to the team

## Copyright and license

Enjoy :metal:
