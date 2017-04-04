# api documentation for  [grunt-karma (v2.0.0)](https://github.com/karma-runner/grunt-karma#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-karma.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-karma) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-karma.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-karma)
#### grunt plugin for karma test runner

[![NPM](https://nodei.co/npm/grunt-karma.png?downloads=true)](https://www.npmjs.com/package/grunt-karma)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-karma/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-grunt-karma_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-karma/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-karma/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-karma/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dave Geddes"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/grunt-karma/issues"
    },
    "contributors": [
        {
            "name": "Dave Geddes",
            "email": "davidcgeddes@gmail.com"
        },
        {
            "name": "Julian Motz",
            "email": "me@julianmotz.com"
        },
        {
            "name": "Michał Gołębiowski",
            "email": "m.goleb@gmail.com"
        },
        {
            "name": "Mark Ethan Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "dsuckau",
            "email": "denis.suckau@concepts-and-training.de"
        },
        {
            "name": "Daniel Herman",
            "email": "daniel.c.herman@gmail.com"
        },
        {
            "name": "Eddie Monge",
            "email": "eddie@eddiemonge.com"
        },
        {
            "name": "James Ford",
            "email": "jford@psyked.co.uk"
        },
        {
            "name": "Jonas Pommerening",
            "email": "jonas.pommerening@gmail.com"
        },
        {
            "name": "Julian",
            "email": "me@julianmotz.com"
        },
        {
            "name": "Luis Almeida",
            "email": "lmg.almeida@gmail.com"
        },
        {
            "name": "Matt Dean",
            "email": "matt@trabian.com"
        },
        {
            "name": "Max Riveiro",
            "email": "kavu13@gmail.com"
        },
        {
            "name": "Mike Dimmick",
            "email": "mike.dimmick@mnetics.co.uk"
        },
        {
            "name": "Nicolas Breitwieser",
            "email": "nicolas.breitwieser@googlemail.com"
        },
        {
            "name": "Olivier Amblet",
            "email": "olivier@amblet.net"
        },
        {
            "name": "Pascal Precht",
            "email": "pascal.precht@googlemail.com"
        },
        {
            "name": "Robin Hu",
            "email": "rhu@novus.com"
        },
        {
            "name": "Roman Morozov",
            "email": "romo@ciklum.com"
        },
        {
            "name": "Sahat Yalkabov",
            "email": "sakhat@gmail.com"
        },
        {
            "name": "Valentin Hervieu",
            "email": "valentin.hervieu@milanamos.com"
        },
        {
            "name": "Vlad Filippov",
            "email": "vlad.filippov@gmail.com"
        },
        {
            "name": "Vojta Jina",
            "email": "vojta.jina@gmail.com"
        },
        {
            "name": "enigmak",
            "email": "redingerkai@gmail.com"
        },
        {
            "name": "facboy",
            "email": "facboy@gmail.com"
        },
        {
            "name": "jiverson",
            "email": "jiverson222@gmail.com"
        },
        {
            "name": "joshrtay",
            "email": "joshrtay@gmail.com"
        },
        {
            "name": "kolesnik",
            "email": "andrii_kolesnyk@epam.com"
        },
        {
            "name": "Alexander Slansky",
            "email": "alexander@slansky.net"
        },
        {
            "name": "m7r",
            "email": "martin@figuro-theater.de"
        },
        {
            "name": "Alexey Kucherenko",
            "email": "alexei.kucherenko@gmail.com"
        },
        {
            "name": "Chris Gross",
            "email": "cgross@texeltek.com"
        },
        {
            "name": "Chris Wren",
            "email": "cthewren@gmail.com"
        },
        {
            "name": "Christian Reed",
            "email": "christian@rgbfab.com"
        },
        {
            "name": "Christoph Kraemer",
            "email": "chr.kraemer@sap.com"
        }
    ],
    "dependencies": {
        "lodash": "^3.10.1"
    },
    "description": "grunt plugin for karma test runner",
    "devDependencies": {
        "eslint": "^1.3.1",
        "eslint-config-standard": "^4.3.1",
        "eslint-plugin-react": "^3.3.1",
        "eslint-plugin-standard": "^1.3.2",
        "expect.js": "^0.3.1",
        "grunt": "^0.4.3",
        "grunt-bump": "0.5.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-conventional-changelog": "^3.0.0",
        "grunt-conventional-github-releaser": "^0.2.0",
        "grunt-eslint": "^17.1.0",
        "grunt-npm": "0.0.2",
        "karma": "1.x || ^0.13.0",
        "karma-chrome-launcher": "1.x || ^0.2.0",
        "karma-firefox-launcher": "1.x || ^0.1.3",
        "karma-mocha": "1.x || ^0.2.0",
        "load-grunt-tasks": "^3.2.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "753583d115dfdc055fe57e58f96d6b3c7e612118",
        "tarball": "https://registry.npmjs.org/grunt-karma/-/grunt-karma-2.0.0.tgz"
    },
    "gitHead": "afb752f3d261ad6e8afd51a9675976fea1683a8b",
    "homepage": "https://github.com/karma-runner/grunt-karma#readme",
    "keywords": [
        "gruntplugin",
        "karma",
        "grunt",
        "test",
        "unit",
        "runner",
        "TDD"
    ],
    "license": "MIT",
    "main": "tasks/grunt-karma.js",
    "maintainers": [
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "geddski",
            "email": "davidcgeddes@gmail.com"
        },
        {
            "name": "karmarunnerbot",
            "email": "karmarunnerbot@gmail.com"
        },
        {
            "name": "vojtajina",
            "email": "vojta.jina+npm@gmail.com"
        },
        {
            "name": "zzo",
            "email": "mark@zzo.com"
        }
    ],
    "name": "grunt-karma",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.x",
        "karma": "^0.13.0 || >= 0.14.0-rc.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/karma-runner/grunt-karma.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "2.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module grunt-karma](#apidoc.module.grunt-karma)



# <a name="apidoc.module.grunt-karma"></a>[module grunt-karma](#apidoc.module.grunt-karma)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
