# npmtest-rabbot

#### basic test coverage for  [rabbot (v1.1.0)](https://github.com/arobson/rabbot#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rabbot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rabbot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rabbot.svg)](https://travis-ci.org/npmtest/node-npmtest-rabbot)

#### Abstractions to simplify working with the RabbitMQ

[![NPM](https://nodei.co/npm/rabbot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rabbot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rabbot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rabbot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rabbot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rabbot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rabbot/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-rabbot/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-rabbot/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rabbot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rabbot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rabbot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rabbot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rabbot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rabbot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rabbot/build/test-report.html](https://npmtest.github.io/node-npmtest-rabbot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rabbot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rabbot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rabbot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rabbot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rabbot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rabbot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rabbot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rabbot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alex Robson"
    },
    "bugs": {
        "url": "https://github.com/arobson/rabbot/issues"
    },
    "contributors": [
        {
            "name": "Alex Robson",
            "url": "http://github.com/arobson"
        },
        {
            "name": "Derick Bailey",
            "url": "http://derickbailey.com/"
        },
        {
            "name": "Randy Groff",
            "url": "http://randygroff.com"
        },
        {
            "name": "Joseph Frazier",
            "url": "https://github.com/josephfrazier"
        },
        {
            "name": "Mario Kozjak",
            "url": "https://github.com/mkozjak"
        },
        {
            "name": "Doug Neiner",
            "url": "http://code.dougneiner.com"
        },
        {
            "name": "Brian Edgerton",
            "url": "https://github.com/brianedgerton"
        },
        {
            "name": "Ryan Niemeyer",
            "url": "http://knockmeout.net"
        },
        {
            "name": "Jim Cowart",
            "url": "http://github.com/ifandelse"
        },
        {
            "name": "Sean Corrales",
            "url": "https://github.com/droidenator"
        },
        {
            "name": "Matthew Martin",
            "url": "http://matmar10.com"
        },
        {
            "name": "Tom Kirkpatrick",
            "url": "https://github.com/mrfelton"
        },
        {
            "name": "Bill Matson",
            "url": "https://github.com/bmatson"
        },
        {
            "name": "Scott Walters",
            "url": "http://github.com/LeankitScott"
        },
        {
            "name": "Eric Satterwhite",
            "url": "http://codedependant.net/"
        },
        {
            "name": "Leonardo Bispo de Oliveira",
            "url": "http://blog.bispooliveira.de"
        },
        {
            "name": "Michael Tuttle",
            "url": "https://github.com/openam"
        },
        {
            "name": "John Mathis",
            "url": "http://github.com/JohnDMathis"
        },
        {
            "name": "Dj Walker-Morgan",
            "url": "http://www.codepope.com"
        },
        {
            "name": "Austin Young",
            "url": "http://github.com/LeankitAustin"
        }
    ],
    "dependencies": {
        "amqplib": "~0.5.1",
        "debug": "^2.2.0",
        "lodash": "^4.15.0",
        "machina": "^2.0.0",
        "monologue.js": "^0.3.5",
        "postal": "^2.0.5",
        "uuid": "^3.0.0",
        "when": "^3.7.7",
        "whistlepunk": "^0.3.2"
    },
    "description": "Abstractions to simplify working with the RabbitMQ",
    "devDependencies": {
        "biggulp": "0.3.x",
        "chai": "^3.4.1",
        "chai-as-promised": "^5.1.0",
        "gulp": "^3.9.0",
        "request": "^2.79.0",
        "sinon": "^1.17.2",
        "sinon-as-promised": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "42b5e58d5c120abea4fac70b66aae36f84e12342",
        "tarball": "https://registry.npmjs.org/rabbot/-/rabbot-1.1.0.tgz"
    },
    "gitHead": "a5ccc4dd9652298e8f7e11cf2e08cb4ddb12bf22",
    "homepage": "https://github.com/arobson/rabbot#readme",
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "arobson"
        }
    ],
    "name": "rabbot",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/arobson/rabbot.git"
    },
    "scripts": {
        "build-image": "docker build -t rabbot .",
        "lint": "jshint ./",
        "start-image": "docker run -d --name rabbot -p 15672:15672 -p 5672:5672 rabbot",
        "test": "gulp test"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
