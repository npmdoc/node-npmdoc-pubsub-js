# npmdoc-pubsub-js

#### api documentation for  pubsub-js (v1.5.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-pubsub-js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pubsub-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pubsub-js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pubsub-js)

#### Dependency free publish/subscribe library

[![NPM](https://nodei.co/npm/pubsub-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pubsub-js)

- [https://npmdoc.github.io/node-npmdoc-pubsub-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pubsub-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pubsub-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pubsub-js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pubsub-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pubsub-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pubsub-js",
    "version": "1.5.6",
    "description": "Dependency free publish/subscribe library",
    "main": "./src/pubsub.js",
    "directories": {
        "lib": "src",
        "test": "test"
    },
    "scripts": {
        "lint": "$(npm bin)/jslint src/**/*.js test/**/*.js",
        "test": "npm run lint && $(npm bin)/grunt test"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/mroderick/PubSubJS.git"
    },
    "keywords": [
        "pub/sub",
        "pubsub",
        "publish/subscribe",
        "publish",
        "subscribe"
    ],
    "author": {
        "name": "Morgan Roderick",
        "url": "http://roderick.dk"
    },
    "license": "MIT",
    "devDependencies": {
        "buster": "0.7.18",
        "grunt": "0.4.5",
        "grunt-buster": "0.3.2",
        "grunt-cli": "0.1.13",
        "grunt-contrib-concat": "0.5.0",
        "jslint": "0.7.2",
        "phantomjs": "1.9.13"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
