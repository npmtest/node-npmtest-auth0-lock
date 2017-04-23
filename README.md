# npmtest-auth0-lock

#### basic test coverage for  [auth0-lock (v10.14.0)](https://github.com/auth0/lock#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-auth0-lock.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-auth0-lock) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-auth0-lock.svg)](https://travis-ci.org/npmtest/node-npmtest-auth0-lock)

#### Auth0 Lock

[![NPM](https://nodei.co/npm/auth0-lock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/auth0-lock)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-auth0-lock/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-auth0-lock/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-auth0-lock/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-auth0-lock/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-auth0-lock/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-auth0-lock/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-auth0-lock/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-auth0-lock/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-auth0-lock/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-auth0-lock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-auth0-lock/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-auth0-lock/build/test-report.html](https://npmtest.github.io/node-npmtest-auth0-lock/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-auth0-lock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-auth0-lock/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-auth0-lock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-auth0-lock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-auth0-lock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-auth0-lock/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-auth0-lock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-auth0-lock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Auth0",
        "url": "http://auth0.com"
    },
    "bugs": {
        "url": "https://github.com/auth0/lock/issues"
    },
    "cdn-component": {
        "name": "lock",
        "cdn": "https://cdn.auth0.com",
        "mainBundleFile": "lock.min.js",
        "bucket": "assets.us.auth0.com",
        "localPath": "build"
    },
    "dependencies": {
        "auth0-js": "8.5.0",
        "blueimp-md5": "2.3.1",
        "fbjs": "^0.3.1",
        "idtoken-verifier": "^1.0.1",
        "immutable": "^3.7.3",
        "jsonp": "^0.2.0",
        "password-sheriff": "^1.1.0",
        "react": "^15.0.0 || ^16.0.0",
        "react-addons-css-transition-group": "^15.0.0 || ^16.0.0",
        "react-dom": "^15.0.0 || ^16.0.0",
        "superagent": "^3.3.1",
        "trim": "0.0.1",
        "url-join": "^1.1.0"
    },
    "description": "Auth0 Lock",
    "devDependencies": {
        "babel-core": "^6.17.0",
        "babel-loader": "^6.2.5",
        "babel-plugin-stylus-compiler": "^1.4.0",
        "babel-plugin-transform-css-import-to-string": "0.0.2",
        "babel-plugin-version-inline": "^1.0.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.3.13",
        "babelify": "^7.2.0",
        "bump-version": "^0.5.0",
        "component-cdn-uploader": "github:auth0/component-cdn-uploader#1.1.0",
        "cross-env": "^3.1.4",
        "css-loader": "^0.26.1",
        "dotenv": "^4.0.0",
        "enzyme": "2.7.0",
        "eslint": "3.16.0",
        "eslint-config-auth0-base": "6.0.0",
        "eslint-plugin-import": "1.16.0",
        "expect.js": "^0.3.1",
        "flat": "^2.0.1",
        "grunt": "^0.4.5",
        "grunt-babel": "^6.0.0",
        "grunt-cli": "^0.1.13",
        "grunt-concurrent": "^2.3.1",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-env": "^0.4.4",
        "grunt-exec": "^0.4.6",
        "grunt-webpack": "^2.0.1",
        "jest": "19.0.0",
        "json-beautify": "^1.0.1",
        "jsonwebtoken": "^7.3.0",
        "mochify": "^2.12.0",
        "prettier": "0.18.0",
        "react-addons-test-utils": "^15.0.0 || ^16.0.0",
        "react-test-renderer": "15.4.2",
        "semver": "^5.3.0",
        "sinon": "^1.15.4",
        "stylus": "^0.54.5",
        "stylus-loader": "^2.3.1",
        "uglify-js": "^2.7.4",
        "uncommitted": "1.0.0",
        "unminified-webpack-plugin": "^1.1.1",
        "unreleased": "^0.1.0",
        "watchify": "^3.7.0",
        "webpack": "^2.2.1",
        "webpack-core": "^0.6.8",
        "webpack-dev-server": "^2.3.0",
        "zuul": "3.10.1",
        "zuul-ngrok": "4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e6bd9173de3f90771c20c500a324e05f6c454c1b",
        "tarball": "https://registry.npmjs.org/auth0-lock/-/auth0-lock-10.14.0.tgz"
    },
    "engines": {
        "node": ">=6.9.1"
    },
    "gitHead": "b07f59b84db203ed8ae6756eed5b787bfb7f3e47",
    "homepage": "https://github.com/auth0/lock#readme",
    "jest": {
        "modulePaths": [
            "<rootDir>/src/",
            "<rootDir>/src/__tests__"
        ],
        "coveragePathIgnorePatterns": [
            "/node_modules/",
            "<rootDir>/test/",
            "<rootDir>/lib/",
            "<rootDir>/src/__tests__/testUtils.js"
        ],
        "testPathIgnorePatterns": [
            "/node_modules/",
            "<rootDir>/test/",
            "<rootDir>/lib/",
            "<rootDir>/src/__tests__/testUtils.js"
        ],
        "coverageReporters": [
            "lcov",
            "text-summary"
        ]
    },
    "keywords": [
        "auth0",
        "auth",
        "openid",
        "authentication",
        "passwordless",
        "browser",
        "jwt"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "auth0npm"
        },
        {
            "name": "cristiandouce"
        },
        {
            "name": "glena"
        },
        {
            "name": "hzalaz"
        },
        {
            "name": "iaco"
        },
        {
            "name": "jfromaniello"
        },
        {
            "name": "mgonto"
        }
    ],
    "name": "auth0-lock",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/auth0/lock.git"
    },
    "scripts": {
        "assert-uncomitted": "uncommitted",
        "build": "grunt build",
        "check-lint-and-format": "npm run format && npm run lint && npm run assert-uncomitted",
        "design": "grunt design",
        "dev": "grunt dev",
        "dist": "grunt dist",
        "format": "prettier --write --print-width 100 --single-quote 'src/**/*.js' 'src/**/*.jsx'",
        "i18n:translate": "grunt dist; node scripts/complete-translations.js",
        "lint": "eslint src",
        "prepublish": "cross-env BABEL_ENV=npm grunt dist",
        "publish:cdn": "ccu",
        "release": "scripts/release.sh",
        "start": "grunt dev",
        "test": "cross-env BABEL_ENV=test zuul -- test/**/*.test.js",
        "test:browser": "cross-env BABEL_ENV=test zuul --local 8080 --disable-tunnel -- test/**/*.test.js",
        "test:cli": "cross-env BABEL_ENV=test mochify --extension=.jsx --transform=babelify test/**/*.test.js",
        "test:jest": "jest --coverage",
        "test:jest:watch": "jest --watch --coverage",
        "test:watch": "cross-env BABEL_ENV=test mochify --watch --extension=.jsx --transform=babelify test/**/*.test.js"
    },
    "version": "10.14.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
