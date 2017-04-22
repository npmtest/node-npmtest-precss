# npmtest-precss

#### basic test-coverage for  [precss (v1.4.0)](https://github.com/jonathantneal/precss)  [![npm package](https://img.shields.io/npm/v/npmtest-precss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-precss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-precss.svg)](https://travis-ci.org/npmtest/node-npmtest-precss)

#### Use Sass-like markup in your CSS

[![NPM](https://nodei.co/npm/precss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/precss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-precss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-precss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-precss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-precss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-precss/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-precss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-precss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-precss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-precss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-precss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-precss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-precss/build/test-report.html](https://npmtest.github.io/node-npmtest-precss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-precss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-precss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-precss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-precss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-precss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-precss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-precss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-precss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Neal"
    },
    "bugs": {
        "url": "https://github.com/jonathantneal/precss/issues"
    },
    "dependencies": {
        "postcss": "^5.0.10",
        "postcss-advanced-variables": "1.2.2",
        "postcss-atroot": "^0.1.2",
        "postcss-color-function": "^2.0.0",
        "postcss-custom-media": "^5.0.0",
        "postcss-custom-properties": "^5.0.0",
        "postcss-custom-selectors": "^3.0.0",
        "postcss-extend": "^1.0.1",
        "postcss-media-minmax": "^2.1.0",
        "postcss-mixins": "^2.1.0",
        "postcss-nested": "^1.0.0",
        "postcss-nesting": "^2.0.6",
        "postcss-partial-import": "^1.3.0",
        "postcss-property-lookup": "^1.1.3",
        "postcss-selector-matches": "^2.0.0",
        "postcss-selector-not": "^2.0.0"
    },
    "description": "Use Sass-like markup in your CSS",
    "devDependencies": {
        "eslint": "^1.7.3",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "8d7c3ae70f10a00a3955287f85a66e0f8b31cda3",
        "tarball": "https://registry.npmjs.org/precss/-/precss-1.4.0.tgz"
    },
    "engines": {
        "iojs": ">=2.0.0",
        "node": ">=0.12.0"
    },
    "gitHead": "526e3048f127ecf378f4f120749ad3d954cd8726",
    "homepage": "https://github.com/jonathantneal/precss",
    "keywords": [
        "postcss",
        "css",
        "postcss-plugin",
        "sass",
        "variables",
        "conditionals",
        "ifs",
        "thens",
        "elses",
        "fors",
        "nesteds",
        "nestings",
        "eaches",
        "mixins",
        "imports",
        "extends",
        "placeholders"
    ],
    "license": "CC0-1.0",
    "maintainers": [
        {
            "name": "jonathantneal"
        }
    ],
    "name": "precss",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonathantneal/precss.git"
    },
    "scripts": {
        "fixtures": "tape test/*.js | tap-spec",
        "lint": "eslint . --ignore-path .gitignore",
        "test": "npm run lint && npm run fixtures"
    },
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
