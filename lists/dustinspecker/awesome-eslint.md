<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="http://github.com/dustinspecker/awesome-eslint">dustinspecker/awesome-eslint</a> with ranks
</p>
---
# Awesome ESLint [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)

[<img src="http://eslint.org/img/logo.svg" width="160" align="right" alt="eslint">](http://eslint.org)

> A list of awesome ESLint configs, plugins, etc.

If you want to contribute, please read the [contribution guidelines](https://github.com/dustinspecker/awesome-eslint/blob/master/contributing.md).

## Contents

- [Configs](#configs)
- [Parsers](#parsers)
- [Plugins](#plugins)
  - [Frameworks and Libraries](#frameworks-and-libraries)
  - [Misc.](#misc)
  - [Practices](#practices)
  - [Style](#style)
- [Preconfigured Tools with ESLint Set up](#preconfigured-tools-with-eslint-set-up)
- [Tools](#tools)
- [Tutorials](#tutorials)

## Configs

- [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Shareable config for [Airbnb's style guide ★52729](https://github.com/airbnb/javascript)
- [Canonical](https://github.com/gajus/eslint-config-canonical) – Shareable config for [Canonical style guide ★13](https://github.com/gajus/canonical)
- [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) - Shareable config for ESLint's default settings
- [ES ★3](https://github.com/thenativeweb/eslint-config-es) - Shareable config for very strict code
- [Facebook](https://www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.
- [Google ★547](https://github.com/google/eslint-config-google) - Shareable config for the [Google style](http://google.github.io/styleguide/javascriptguide.xml)
- [Shopify](https://github.com/Shopify/eslint-plugin-shopify) - Shareable config for [Shopify's style guide ★118](https://github.com/Shopify/javascript)
- [Standard](https://github.com/feross/eslint-config-standard) - Shareable config for JavaScript [Standard Style ★11789](https://github.com/feross/standard)
- [Supermind ★1](https://github.com/supermind/eslint-config-supermind) - Shareable config for Supermind style
- [XO](https://github.com/sindresorhus/eslint-config-xo) - Shareable config for [XO ★2621](https://github.com/sindresorhus/xo)

## Parsers

- [Babel ★1436](https://github.com/babel/babel-eslint) - Use Babel's parser for linting all Babel features

## Plugins

### Frameworks and Libraries

- [Angular](https://github.com/Gillespie59/eslint-plugin-angular) - Linting rules to adhere to the [John Papa's Angular Styleguide ★22704](https://github.com/johnpapa/angular-styleguide)
- [AVA](https://github.com/sindresorhus/eslint-plugin-ava) - Linting rules for AVA
- [Backbone ★90](https://github.com/ilyavolodin/eslint-plugin-backbone) - Linting rules for Backbone
- [Chai ★5](https://github.com/turbo87/eslint-plugin-chai-expect) - Linting rules for Chai
- [Ember ★73](https://github.com/netguru/eslint-plugin-ember) - Linting rules for Ember
- [Hapi ★15 ⏳1Y](https://github.com/continuationlabs/eslint-plugin-hapi) – Linting rules for hapi
- [Jasmine ★32](https://github.com/tlvince/eslint-plugin-jasmine) - Linting rules for Jasmine
- [JSDoc ★87](https://github.com/gajus/eslint-plugin-jsdoc) - Linting rules for JSDoc comments
- [Lodash ★111](https://github.com/wix/eslint-plugin-lodash) - Lodash specific linting rules
- [Lodash/fp ★77](https://github.com/jfmengels/eslint-plugin-lodash-fp) - Lodash/fp specific linting rules
- [Meteor ★87](https://github.com/dferber90/eslint-plugin-meteor) - Meteor specific linting rules
- [Mocha ★124](https://github.com/lo1tuma/eslint-plugin-mocha) - Linting rules for Mocha
- [Mongodb ★12 ⏳1Y](https://github.com/nfroidure/eslint-plugin-mongodb) - Mongodb native nodejs driver linting rules
- [React ★2651](https://github.com/yannickcr/eslint-plugin-react) - Linting rules for React and JSX
- [React Native ★195](https://github.com/Intellicode/eslint-plugin-react-native) - React Native specific linting rules
- [RequireJS ★21](https://github.com/cvisco/eslint-plugin-requirejs) - Linting rules for RequireJS
- [VueJS ★85](https://github.com/vuejs/eslint-plugin-vue) - Plugin for VueJS

### Misc

- [Babel ★181](https://github.com/babel/eslint-plugin-babel) - Adds replacements for built-in rules to include Babel features
- [Compat ★1592](https://github.com/amilajack/eslint-plugin-compat) - Lint browser compatability of APIs used ([caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin)
- [disable ★14](https://github.com/mradionov/eslint-plugin-disable) - Disable specified plugins using file path patterns and inline comments
- [es5 ★13](https://github.com/nkt/eslint-plugin-es5) - ESLint plugin for ES5 users (forbid ES2015+ usage)
- [Flow ★452](https://github.com/gajus/eslint-plugin-flowtype) - Flow type linting rules
- [Flow Errors ★289](https://github.com/amilajack/eslint-plugin-flowtype-errors) - Run Flow as an ESLint plugin
- [GraphQL](https://github.com/apollostack/eslint-plugin-graphql) - Check your GraphQL query strings against a schema
- [HTML ★113](https://github.com/BenoitZugmeyer/eslint-plugin-html) - Linting for JavaScript inside of HTML `<script>` tags
- [import ★745](https://github.com/benmosher/eslint-plugin-import) - Linting of ES2015+  import/export syntax, and prevent issues with misspelling of file paths and import names
- [JSON ★21](https://github.com/azeemba/eslint-plugin-json) - Lint your JSON files
- [Markdown ★92](https://github.com/eslint/eslint-plugin-markdown) - Linting JavaScript in Markdown
- [Node ★165](https://github.com/mysticatea/eslint-plugin-node) - Linting rules for Node.js (checking importing paths, ES syntax, ...)
- [Optimize Regex ★5](https://github.com/BrainMaestro/eslint-plugin-optimize-regex) - Optimize regex literals
- [SQL ★6](https://github.com/gajus/eslint-plugin-sql) – SQL linting rules for ESLint
- [TypeLint](https://github.com/yarax/typelint) - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors
- [unicorn ★141](https://github.com/sindresorhus/eslint-plugin-unicorn) - Various awesome ESLint rules
- [ESLint Comments ★19](https://github.com/mysticatea/eslint-plugin-eslint-comments) - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc...)

### Practices

- [fp ★224](https://github.com/jfmengels/eslint-plugin-fp) - ESLint rules for functional programming
- [Immutable ★652](https://github.com/jhusain/eslint-plugin-immutable) - Disable all mutation in JavaScript
- [JSX a11y ★469](https://github.com/evcohen/eslint-plugin-jsx-a11y) - Accessibility rules on JSX elements
- [new-with-error ★10 ⏳1Y](https://github.com/Trott/eslint-plugin-new-with-error) - Require errors to be thrown using `new`
- [no-inferred-method-name ★27 ⏳1Y](https://github.com/johnstonbl01/eslint-no-inferred-method-name) - Custom rule for ESLint that checks for inferred method names within object literals.
- [no-loops ★24](https://github.com/buildo/eslint-plugin-no-loops) - It's 2017 and you still use loops?
- [no-use-extend-native ★22](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) - Prevent using extended native objects
- [Promise ★152](https://github.com/xjamundx/eslint-plugin-promise) - Best practices when working with promises
- [Security ★484](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node Security
- [this ★1](https://github.com/matijs/eslint-plugin-this) - Write pure functions, don't allow `this`
- [XSS ★7](https://github.com/Rantanen/eslint-plugin-xss) - Tries to detect XSS issues in codebase before they end up in production

### Style

- [filenames ★56](https://github.com/selaux/eslint-plugin-filenames) - Ensure consistent filenames for your javascript files

## Preconfigured Tools with ESLint Set up

- [Node.js Standard Style ★2](https://github.com/geek/node-style) - Node.js core config.
- [prettier-standard ★92](https://github.com/sheerun/prettier-standard) - Prettier formatter with custom eslint rules allowed
- [Standard ★11789](https://github.com/feross/standard) - JavaScript Standard Style
- [Superlint ★0](https://github.com/supermind/superlint) - JavaScript Supermind Style
- [XO ★2621](https://github.com/sindresorhus/xo) - JavaScript happiness style linter ❤️

## Tools

- [eslint-cli ★29 ⏳1Y](https://github.com/mysticatea/eslint-cli) - This is the `eslint` command that executes a local installed ESLint.
- [eslint-find-rules ★64](https://github.com/sarbbottam/eslint-find-rules) - Find built-in ESLint rules you don't have in your custom config
- [eslint-index ★5](https://github.com/wagerfield/eslint-index) - CLI for finding and managing rules in ESLint config files
- [eslint-nibble ★96](https://github.com/IanVS/eslint-nibble) - Ease into ESLint, by fixing one rule at a time
- [eslint-rule-documentation ★11](https://github.com/jfmengels/eslint-rule-documentation) - Find the url for the documentation of an ESLint rule
- [eslint-watch ★73](https://github.com/rizowski/eslint-watch) - Run ESLint with watch mode
- [codacy-eslint ★5](https://github.com/codacy/codacy-eslint) - Docker used at [Codacy](https://www.codacy.com) to run ESLint

## Tutorials

- [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin
- [Lint Like It’s 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint
- [Linting JavaScript with ESLint](https://egghead.io/lessons/javascript-linting-javascript-with-eslint) - Video showing ESLint setup and basics
- [Linting React JSX with ESLint (in ES6)](https://egghead.io/lessons/react-linting-react-jsx-with-eslint-in-es6) - Video showing how to use React and JSX with ESLint
- [Plugin Module with Mixins](https://akullpp.com/eslint-integration) - Article on how to write a plugin as a node module containing modular mixin configuration
- [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="http://github.com/dustinspecker/awesome-eslint">dustinspecker/awesome-eslint</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>