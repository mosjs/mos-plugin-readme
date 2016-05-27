<!--@h1([pkg.name])-->
# mos-plugin-readme
<!--/@-->

<!--@blockquote([pkg.description])-->
> A mos plugin for generating README
<!--/@-->

<!--@shields('npm', 'travis', 'coveralls')-->
[![npm version](https://img.shields.io/npm/v/mos-plugin-readme.svg)](https://www.npmjs.com/package/mos-plugin-readme) [![Build Status](https://img.shields.io/travis/mosjs/mos-plugin-readme/master.svg)](https://travis-ci.org/mosjs/mos-plugin-readme) [![Coverage Status](https://img.shields.io/coveralls/mosjs/mos-plugin-readme/master.svg)](https://coveralls.io/r/mosjs/mos-plugin-readme?branch=master)
<!--/@-->

## Installation

```sh
npm i -D mos-plugin-readme
```

## Usage

```js
const mosPluginReadme = require('mos-plugin-readme')
```

## License

[MIT](./LICENSE) © [Zoltan Kochan](http://kochan.io)

* * *

<!--@dependencies({ shield: true })-->
## <a name="dependencies">Dependencies</a> [![dependency status](https://img.shields.io/david/mosjs/mos-plugin-readme/master.svg)](https://david-dm.org/mosjs/mos-plugin-readme/master)

- [babel-runtime](https://github.com/babel/babel/blob/master/packages): babel selfContained runtime

<!--/@-->

<!--@devDependencies({ shield: true })-->
## <a name="dev-dependencies">Dev Dependencies</a> [![devDependency status](https://img.shields.io/david/dev/mosjs/mos-plugin-readme/master.svg)](https://david-dm.org/mosjs/mos-plugin-readme/master#info=devDependencies)

- [babel-cli](https://github.com/babel/babel/blob/master/packages): Babel command line.
- [babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports): Fix babel/babel#2212
- [babel-plugin-transform-runtime](https://github.com/babel/babel/blob/master/packages): Externalise references to helpers and builtins, automatically polyfilling your code without polluting globals
- [babel-preset-es2015](https://github.com/babel/babel/blob/master/packages): Babel preset for all es2015 plugins.
- [babel-register](https://github.com/babel/babel/blob/master/packages): babel require hook
- [chai](https://github.com/chaijs/chai): BDD/TDD assertion library for node.js and the browser. Test framework agnostic.
- [cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog): Commitizen adapter following the conventional-changelog format.
- [eslint](https://github.com/eslint/eslint): An AST-based pattern checker for JavaScript.
- [eslint-config-standard](https://github.com/feross/eslint-config-standard): JavaScript Standard Style - ESLint Shareable Config
- [eslint-plugin-promise](https://github.com/xjamundx/eslint-plugin-promise): Enforce best practices for JavaScript promises
- [eslint-plugin-standard](https://github.com/xjamundx/eslint-plugin-standard): ESlint Plugin for the Standard Linter
- [ghooks](https://github.com/gtramontina/ghooks): Simple git hooks
- [istanbul](https://github.com/gotwarlost/istanbul): Yet another JS code coverage tool that computes statement, line, function and branch coverage with module loader hooks to transparently add coverage when running tests. Supports all JS coverage use cases including unit tests, server side functional tests
- [mocha](https://github.com/mochajs/mocha): simple, flexible, fun test framework
- [mos](https://github.com/mosjs/mos): A pluggable module that injects content into your markdown files via hidden JavaScript snippets
- [semantic-release](https://github.com/semantic-release/semantic-release): automated semver compliant package publishing
- [validate-commit-msg](https://github.com/kentcdodds/validate-commit-msg): Script to validate a commit message follows the conventional changelog standard

<!--/@-->
