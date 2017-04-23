# npmtest-react-native-datepicker

#### basic test coverage for  [react-native-datepicker (v1.4.7)](https://github.com/xgfe/react-native-datepicker#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-datepicker.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-datepicker) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-datepicker.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-datepicker)

#### react native datePicker component for both Android and IOS, useing DatePikcerAndroid, TimePickerAndroid and DatePickerIOS

[![NPM](https://nodei.co/npm/react-native-datepicker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-datepicker)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-datepicker/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-native-datepicker/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-datepicker/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-datepicker/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-datepicker/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-datepicker/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-datepicker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-datepicker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-datepicker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-datepicker/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-datepicker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-native-datepicker",
    "version": "1.4.7",
    "description": "react native datePicker component for both Android and IOS, useing DatePikcerAndroid, TimePickerAndroid and DatePickerIOS",
    "main": "index.js",
    "scripts": {
        "start": "node node_modules/react-native/local-cli/cli.js start",
        "mocha": "./node_modules/mocha/bin/_mocha ./test/*.test.js --watch",
        "test": "node ./node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha ./test/*.test.js",
        "coverage": "cat ./coverage/lcov.info | coveralls",
        "changelog": "conventional-changelog -p angular -i CHANGELOG.md -s",
        "lint": "eslint ."
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/xgfe/react-native-datepicker.git"
    },
    "keywords": [
        "react-native",
        "DatePicker"
    ],
    "author": "xgfe",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/xgfe/react-native-datepicker/issues"
    },
    "homepage": "https://github.com/xgfe/react-native-datepicker#readme",
    "dependencies": {
        "moment": "2.x.x"
    },
    "devDependencies": {
        "react": "~15.4.0",
        "react-native": "~0.39.0",
        "cz-conventional-changelog": "^1.1.6",
        "pre-commit": "^1.1.3",
        "babel-core": "^6.5.2",
        "babel-preset-react-native": "^1.8.0",
        "chai": "^3.5.0",
        "coveralls": "^2.11.9",
        "enzyme": "^2.4.0",
        "istanbul": "^1.0.0-alpha.2",
        "jsdom": "^9.4.1",
        "mocha": "^2.5.2",
        "react-addons-test-utils": "~15.4.0",
        "react-dom": "~15.4.0",
        "react-native-mock": "^0.2.8",
        "sinon": "^1.17.4"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "pre-commit": [
        "lint"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
