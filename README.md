# Awesome Codemods with stars

> A curated list of awesome codemod resources for various languages, libraries and frameworks

Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.

## Contents

* [JavaScript](#javascript)
* [ESNext](#esnext)
* [Typescript](#typescript)
* [Ruby](#ruby)
* [Frameworks](#frameworks)
* [Libraries](#libraries)
* [Organization specific Codemods](#organization-specific-codemods)
* [Editor Plugins](#editor-plugins)
* [Misc](#misc)
* [Awesome Lists](#awesome-lists)

## JavaScript

* [jest-codemods](https://github.com/skovhus/jest-codemods) ⭐ 888 | 🐛 35 | 🌐 TypeScript | 📅 2026-08-21 - Codemods for migrating to Jest .
* [5to6-codemod](https://github.com/5to6/5to6-codemod) ⭐ 300 | 🐛 26 | 🌐 JavaScript | 📅 2023-01-03 - A collection of codemods that allow you to transform your js code from ES5 to ES6.
* [codeshift-community](https://github.com/CodeshiftCommunity/CodeshiftCommunity) ⭐ 150 | 🐛 47 | 🌐 TypeScript | 📅 2026-04-18 - Community-owned global registry and documentation hub for codemods. Write & run codemodes, share them with your friends.
* [relative-to-alias](https://github.com/s-yadav/relative-to-alias) ⭐ 135 | 🐛 15 | 🌐 JavaScript | 📅 2023-01-03 - A codemod to do large-scale refactor of your relative path imports to alias.
* [js-transforms](https://github.com/jhgg/js-transforms) ⭐ 102 | 🐛 0 | 🌐 JavaScript | 📅 2015-10-22 - Some documented codemod experiments to help you learn.
* [aws-sdk-js-codemod](https://github.com/awslabs/aws-sdk-js-codemod) ⭐ 88 | 🐛 40 | 🌐 TypeScript | 📅 2026-08-01 - Codemod scripts to update AWS SDK for JavaScript APIs.
* [refactoring-codemods](https://github.com/jurassix/refactoring-codemods) ⭐ 80 | 🐛 5 | 🌐 JavaScript | 📅 2018-05-09 - Refactoring support for JavaScript via jscodeshift codemods.
* [JamieMason/codemods](https://github.com/JamieMason/codemods) ⭐ 64 | 🐛 2 | 🌐 JavaScript | 📅 2025-09-17 - A collection of transforms for use with JSCodeshift.
* [transform-imports](https://github.com/suchipi/transform-imports) ⭐ 53 | 🐛 9 | 🌐 JavaScript | 📅 2024-05-07 - Tools that make it easy to codemod imports/requires in your JS.
* [codemod-imports-sort](https://github.com/bfncs/codemod-imports-sort) ⭐ 38 | 🐛 3 | 🌐 JavaScript | 📅 2018-05-07 - Sort ES6 imports by type.
* [coffee-to-es2015-codemod](https://github.com/Hacker0x01/coffee-to-es2015-codemod) ⭐ 37 | 🐛 2 | 🌐 JavaScript | 📅 2016-03-04 - A set of JSCodeshift transforms that will help you transform your CoffeeScript codebase to ES2015.
* [es5-function-to-class-codemod](https://github.com/dhruvdutt/es5-function-to-class-codemod) ⭐ 34 | 🐛 3 | 🌐 JavaScript | 📅 2019-06-20 - Transform ES5 Functions to ES6 Classes.
* [eslint-transforms](https://github.com/eslint/eslint-transforms) ⭐ 30 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-11 - Codemods for the ESLint ecosystem.
* [async-await-codemod](https://github.com/sgilroy/async-await-codemod) ⭐ 29 | 🐛 18 | 🌐 JavaScript | 📅 2022-12-07 - Codemod script for migrating promise-based functions to use async/await syntax.
* [sinon-codemod](https://github.com/hurrymaplelad/sinon-codemod) ⭐ 28 | 🐛 2 | 🌐 JavaScript | 📅 2018-11-26 - Codemod scripts that update Sinon APIs .
* [undecorate-codemod](https://github.com/tizmagik/undecorate-codemod) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-02 - Transformers experimental ESNext decorators syntax to simple currying.
* [optional-chaining-codemod](https://github.com/NullVoxPopuli/optional-chaining-codemod) ⭐ 16 | 🐛 3 | 🌐 JavaScript | 📅 2023-12-15
* [chai-to-assert](https://github.com/twada/chai-to-assert) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-12 - A jscodeshift codemod that transforms from chai to Node assert.
* [chai-to-jasmine](https://github.com/AlexJuarez/chai-to-jasmine) ⭐ 12 | 🐛 2 | 🌐 JavaScript | 📅 2017-05-19 - A chai to jasmine codemod that includes additional transforms for jest migration.
* [js-codemod-import-absolute](https://github.com/bluedaniel/js-codemod-import-absolute) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2022-11-18 - Codemod to replace relative imports with absolute or custom paths.
* [jest-expect-codemod](https://github.com/devenbansod/jest-expect-codemod) ⭐ 9 | 🐛 3 | 🌐 JavaScript | 📅 2022-12-07 - CodeMods for migrating `chai.assert`, `chai.expect`, `assert` -based test assertions to jest's `expect` assertions.
* [expect-js-to-assert](https://github.com/twada/expect-js-to-assert) ⭐ 8 | 🐛 1 | 🌐 JavaScript | 📅 2017-04-28 - A jscodeshift codemod that transforms from expect.js to Node assert.
* [immutablejs-eraser-codemod](https://github.com/mariosanchez/immutablejs-eraser-codemod) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-13 - A codemod to rescue you from a Immutable.js abuse.
* [co-to-async](https://github.com/albinekb/co-to-async) ⚠️ Archived - Take the step from co.wrap to async/await automagically.
* [webpack-babel-codemod](https://github.com/agirton/webpack-babel-codemod) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2016-02-27 - Convert anonymous webpack commonjs require statements to es2015 import statements.
* [js-codemods](https://github.com/yangshun/js-codemods) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-21 - Some codemod scripts to transform code for good styling.
* [amd-to-commonjs-codemod](https://github.com/skratchdot/amd-to-commonjs-codemod) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-09 - A codemod to transform amd style includes into commonjs includes.
* [class-props-codemod](https://github.com/zertosh/class-props-codemod) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2016-01-17 - Transform old-style assigned static properties to class static properties.
* [node-dep-codemod](https://github.com/joyeecheung/node-dep-codemod) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-18 - A collection of JSCodeshift codemod scripts for migrating code that uses deprecated Node.js APIs.
* [js-codemod](https://github.com/cpojer/js-codemod/) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-06 - Codemod scripts to transform code to next generation JS.
* [flow-comments-codemod](https://github.com/escaton/flow-comments-codemod) ⭐ 4 | 🐛 14 | 🌐 TypeScript | 📅 2023-01-03 - Convert flowtype syntax to valid JS.
* [sort-class-members-codemod](https://github.com/pastelsky/sort-class-members-codemod) ⭐ 4 | 🐛 6 | 🌐 JavaScript | 📅 2020-05-08 - A codemod for automatically fixing issues reported by eslint-plugin-sort-class-members.
* [nikgraf/js-codemod](https://github.com/nikgraf/js-codemod) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2015-10-13 - A collection of codemods.
* [relekang/codemods](https://github.com/relekang/codemods) ⭐ 4 | 🐛 3 | 🌐 JavaScript | 📅 2016-10-19
* [vasco3/cuadrante-codemods](https://github.com/vasco3/cuadrante-codemods) ⭐ 4 | 🐛 4 | 🌐 JavaScript | 📅 2017-03-04 - Converts ES6 imports to commonJS requires.
* [apitsummit-codemods](https://github.com/perjansson/aptisummit-codemods) ⭐ 4 | 🐛 2 | 🌐 JavaScript | 📅 2018-07-26
* [DrewML/codemods](https://github.com/DrewML/codemods) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2016-07-02
* [cleaner-codemods](https://github.com/peoplenarthax/cleaner-codemods) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2017-11-08 - Simple codemods to destructure prop types.
* [underscore-to-native](https://github.com/zackargyle/codemods) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2016-09-21 - Underscore to native codemods.
* [rxjs-codemod](https://github.com/sergi/rxjs-codemod) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-04 - Codemod scripts to transform older RxJS code to RxJS5-compatible code.
* [dsgkirkby/js-codemods](https://github.com/dsgkirkby/js-codemods) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2016-10-05 - Wrap switch statements in a code block.
* [autobots](https://github.com/geekjuice/autobots) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2016-11-07 - Codemods for great good!.
* [ce-codemods](https://github.com/dogoku/ce-codemods) ⚠️ Archived - Codemods for custom elements.
* [skratchdot-codemods](https://github.com/skratchdot/skratchdot-codemods) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-14 - A collection of utility codemods.
* [styletron/codemods](https://github.com/styletron/codemods) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-08 - Codemods for styletron.
* [EDITD/codemods](https://github.com/EDITD/codemods) ⚠️ Archived - Radium to Glamour codemod.
* [bradencanderson/codemods](https://github.com/bradencanderson/codemods) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2016-07-31
* [knoopx/codemods](https://github.com/knoopx/codemods) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-12
* [bseber/codemods](https://github.com/bseber/codemods) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2016-08-12 - Codemods for Jasmine refactoring.
* [rm-debugger](https://www.npmjs.com/package/rm-debugger) - Codemod for removing `debugger;`.
* [AMD Transformer](https://bitbucket.org/atlassian/amd-codemod/src) - Converts JS into AMDified JS (by Atlassian).
* [peakon/codemods](https://github.com/peakon/codemods) - I18n Context, Locale, No immutable class codemods.
* [strudel-codemod](https://github.com/strudeljs/strudel-codemod) - Strudel codemod scripts.

## ESNext

* [idx-to-optional-chaining](https://github.com/cdlewis/idx-to-optional-chaining) ⭐ 18 | 🐛 11 | 🌐 JavaScript | 📅 2023-01-05 - JSCodeShift codemod that transforms usage of idx to the draft optional chaining standard.
* [generator2async-codemod](https://github.com/shimohq/generator2async-codemod) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2019-11-06
* [async-await-codemod](https://github.com/vivek12345/async-await-codemod) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2019-02-16 - Codemod to add try catch to all the async await statements.
* [codemod-get-to-optional-member-expression](https://github.com/eschaefer/codemod-get-to-optional-member-expressions) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2018-06-10 - Change Lodash `get` functions to ES7 optional member expressions.
* [5to6](https://github.com/jamischarles/5to6) ⭐ 2 | 🐛 3 | 🌐 JavaScript | 📅 2015-12-23 - A collection of codemods that allow you to transform your js code from ES5 to ES6.
* [lebab-as-babel-plugins](https://github.com/rajatvijay/lebab-as-babel-plugins) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-26 - Codemod to transform ES5 code to ES6/7 and uses babel plugins.

## Typescript

* [tsmod](https://github.com/WolkSoftware/tsmod) ⚠️ Archived - Refactor TypScript code programmatically using codemods.
* [ts-codemod](https://github.com/tusharmath/ts-codemod) ⭐ 74 | 🐛 0 | 🌐 TypeScript | 📅 2019-11-07 - Typescript based codemods.
* [tscodeshift](https://github.com/KnisterPeter/tscodeshift) ⚠️ Archived - A tscodeshift is a toolkit for running codemods over multiple TS files.
* [js-to-typescript-codemod](https://github.com/mattlewis92/js-to-typescript-codemod) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2019-11-20 - A simple codemod for helping migrate from babel to typescript. Converts default imports to wildcards.
* [flowshift](https://github.com/albertywu/flowshift) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2019-02-10 - Flow to typescript codemods.
* [type-import-codemod](https://github.com/IanVS/type-import-codemod) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2022-06-07 - Combine type and value imports using Typescript 4.5 type modifier syntax.
* [ts-codemod-scripts](https://github.com/buildo/ts-codemod-scripts) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-25 - Collection of basic JS/React codemod scripts to prepare for TS on a codebase.
* [flowToTs](https://github.com/MarcoPolo/flowToTs) ⭐ 1 | 🐛 2 | 🌐 TypeScript | 📅 2019-10-29 - Flow to Typescript codemods.
* [codemod-cli-ts](https://github.com/jmdejno/codemod-cli-ts) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2019-03-20 - CLI for generating codemods written in Typescript.
* [riceburn](https://github.com/kenotron/riceburn) - A Typescript, JSON, and text file Code Mod Utility.

## Ruby

* [codeshift](https://github.com/rajasegar/codeshift) ⭐ 49 | 🐛 1 | 🌐 Ruby | 📅 2023-02-28 - JSCodeshift equivalent for Ruby.
* [ruby\_crystal\_codemod](https://github.com/DocSpring/ruby_crystal_codemod) ⭐ 44 | 🐛 2 | 🌐 Ruby | 📅 2024-05-17 - A codemod / transpiler that can help you convert Ruby into Crystal.
* [Ruby AST Explorer](https://github.com/rajasegar/ruby-ast-explorer) ⭐ 17 | 🐛 26 | 🌐 JavaScript | 📅 2023-03-01 - AST Explorer for Ruby.
* [cybertron](https://github.com/rajasegar/cybertron) ⭐ 6 | 🐛 1 | 🌐 Ruby | 📅 2025-07-22 - Codemod CLI to bootstrap Ruby codemods (transforms).

## Frameworks

### React.js

* [react-codemod](https://github.com/reactjs/react-codemod) ⭐ 4,410 | 🐛 57 | 🌐 JavaScript | 📅 2026-02-22 - React codemod scripts to update React APIs.
* [ast-18n](https://github.com/sibelius/ast-i18n) ⭐ 231 | 🐛 9 | 🌐 TypeScript | 📅 2024-06-18 - Easily migrate your existing React codebase to use i18n.
* [rn-update-deprecated-modules](https://github.com/lucasbento/rn-update-deprecated-modules) ⭐ 72 | 🐛 16 | 🌐 JavaScript | 📅 2023-01-03 - Codemod to update import declarations as per react-native > 0.59.x deprecations.
* [rackt-codemod](https://github.com/reactjs/rackt-codemod) ⚠️ Archived - Codemod scripts for Rackt libraries.
* [babel-plugin-hyperscript-to-jsx](https://github.com/RIP21/babel-plugin-hyperscript-to-jsx) ⭐ 20 | 🐛 14 | 🌐 JavaScript | 📅 2023-01-04 - This plugin transforms react-hyperscript into JSX. Intended to be used as codemod.
* [codemod-react-proptypes-to-flow](https://github.com/jamiebuilds/codemod-react-proptypes-to-flow) ⭐ 18 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-08
* [js2tsx](https://github.com/sjy/js2tsx) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-25 - A toolkit provide some codemod scripts based on jscodeshift to migrating react code base to typescript.
* [metal-to-react](https://github.com/bryceosterhaus/metal-to-react) ⭐ 13 | 🐛 3 | 🌐 JavaScript | 📅 2019-03-08 - Codemods for migrating metal-jsx to react.
* [yannvr/codemods](https://github.com/yannvr/codemods) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-30 - JS/React transforms because life is too short.
* [cjsx-codemod](https://github.com/jsdf/cjsx-codemod) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2016-10-03 - A codemod for migrating off of coffee-react CJSX.
* [babel-plugin-codemod-react-css-modules](https://github.com/Craga89/babel-plugin-codemod-react-css-modules) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2019-01-29 - Converts React components using imported CSS stylesheets to equivalent CSS Modules syntax.
* [react-hot-loader-codemod](https://github.com/sibelius/react-hot-loader-codemod) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2019-02-10
* [over\_react\_codemod](https://github.com/Workiva/over_react_codemod) ⭐ 3 | 🐛 13 | 🌐 Dart | 📅 2026-08-14 - Codemods to help consumers of over\_react automate the migration of UI component code.
* [react-native-paper-codemod](https://github.com/callstack/react-native-paper-codemod) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2018-09-03
* [react-codemod-pure-component-to-class](https://github.com/orzarchi/react-codemod-pure-component-to-class) ⭐ 3 | 🐛 2 | 🌐 JavaScript | 📅 2018-04-21 - A react codemod to transform stateless/pure/functional components to class components.
* [mukeshsoni/codemods](https://github.com/mukeshsoni/codemods) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2018-05-10 - Adds a data-test-id attribute to all jsx html elements.
* [react-native-fix-inline-styles](https://github.com/ignacioola/react-native-fix-inline-styles) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2018-12-11 - Fix inline styles in react native components.
* [js-react-codemods](https://github.com/nicholas-b-carter/js-react-codemods) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2017-05-27 - A boilerplate of JS 5/6/7 transforms for react/redux/js/etc.
* [proptypes-to-flow](https://github.com/mikhail-hatsilau/proptypes-to-flow-codemod) ⭐ 1 | 🐛 4 | 🌐 JavaScript | 📅 2022-12-07 - Codemod to tranform react proptypes to flow.
* [mst-codemod-to-0.10](https://github.com/mobxjs/mst-codemod-to-0.10) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2017-08-17 - A codemod to migrate to MobX-State-Tree 0.10 from previous versions.
* [react-with-hooks-removal-codemod](https://github.com/polizz/react-with-hooks-removal-codemod) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2018-11-18 - Remove the react-with-hooks library code when React 16.7.0 is released.
* [react-style-px-suffix-codemod](https://github.com/conorhastings/react-style-px-suffix-codemod) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2016-04-04 - Append px to shorthand values in style objects in react in prep for react 15 warning.
* [denvned/codemod](https://github.com/denvned/codemod) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2016-02-19 - Relay Mutation - didResolveProps.

### Ember.js

* [ember-watson](https://github.com/abuiles/ember-watson) ⭐ 303 | 🐛 30 | 🌐 JavaScript | 📅 2022-12-30 - An Ember.js codemod to make upgrades automatic.
* [ember-i18n-to-intl-migrator](https://github.com/DockYard/ember-i18n-to-intl-migrator) ⭐ 21 | 🐛 3 | 🌐 JavaScript | 📅 2020-01-22 - Migrate ember-i18n to ember-intl .
* [react-destructuring-assignment-codemod](https://github.com/thibaudcolas/react-destructuring-assignment-codemod) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2019-02-02 - A WIP jscodeshift codemod to destructure assignments of props, state, and context.
* [test-selectors-codemod](https://github.com/lorcan/test-selectors-codemod) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2018-05-29 - A codemode for fixing the ember-test-selectors testSelector helper deprecation.
* [ember-action-codemods](https://github.com/lennyburdette/ember-action-codemods) ⭐ 5 | 🐛 14 | 🌐 JavaScript | 📅 2023-01-04 - Codemods for converting uses of action to the {{on}} modifier.
* [ember-k-codemod](https://github.com/cibernox/ember-k-codemod) ⭐ 5 | 🐛 2 | 🌐 JavaScript | 📅 2018-07-04 - Removes all usages of Ember.K.
* [ember-computed-decorators-codemod](https://github.com/bwittenbrook3/ember-computed-decorators-codemod) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2018-09-10 - Codemod to update ember-computed-decorators to ember-decorators.
* [ember-cli-mirage-faker-codemod](https://github.com/caseywatts/ember-cli-mirage-faker-codemod) ⭐ 2 | 🐛 5 | 🌐 JavaScript | 📅 2019-04-23
* [lil-codemods](https://github.com/jmdejno/lil-codemods) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2019-04-01 - Ember codemods.
* [ember-component-jquery](https://github.com/patocallaghan/ember-component-jquery) ⭐ 1 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-04 - A codemod for migrating Ember Component code from `this.$()` to `$(this.element)`.
* [jmdejno/ember-codemods](https://github.com/jmdejno/ember-codemods) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2019-03-18 - Ember code Transforms.
* [legacy-tests-codemod](https://github.com/patocallaghan/legacy-tests-codemod) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2018-12-20 - A collection of codemod's for legacy-tests-codemod.
* [ember-codemods](https://github.com/ember-codemods) - Official organization for Ember.js Codemods.

### Preact.js

* [preact-codemod](https://github.com/vutran/preact-codemod) ⭐ 40 | 🐛 1 | 🌐 JavaScript | 📅 2018-05-04 - Shave some bytes by using Preact.

### Vue.js

* [vue-codemods](https://github.com/SergioCrisostomo/vue-codemods) ⭐ 25 | 🐛 11 | 🌐 JavaScript | 📅 2023-01-06 - Collection of codemod scripts that help update and refactor Vue and JavaScript files.

### Angular.js

* [angular-codemods](https://github.com/arthurflachs/angular-codemods) - Codemods for refactoring legacy angular applications.

## Libraries

### Lodash

* [optional-chaining-codemod](https://github.com/villesau/optional-chaining-codemod) ⭐ 113 | 🐛 15 | 🌐 JavaScript | 📅 2023-03-04 - Codemod to migrate from Lodash get and logical and expressions to optional chaining.
* [lodash-codemods](https://github.com/jfmengels/lodash-codemods) ⭐ 32 | 🐛 9 | 🌐 JavaScript | 📅 2017-01-19 - Codemods to simplify upgrading Lodash versions.
* [js-transforms](https://github.com/gunar/js-transforms) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2016-05-24 - Codemod to replace lodash for lodash/fp.
* [modular-lodash-codemod](https://github.com/dgrijuela/modular-lodash-codemod) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-16 - Makes all your lodash imports modular.
* [kevinbarabash/codemods](https://github.com/kevinbarabash/codemods) ⭐ 7 | 🐛 2 | 🌐 JavaScript | 📅 2016-08-09 - Lodash/Underscore to native.
* [lodash-to-lodash-amd-codemods](https://github.com/OliverJAsh/lodash-to-lodash-amd-codemods) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2015-11-07 - Lodash to [lodash-amd](https://github.com/lodash/lodash-amd) ⚠️ Archived codemods.

### Mocha

* [mocha-to-jest-codemod](https://github.com/paularmstrong/mocha-to-jest-codemod) ⭐ 42 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-04 - Convert Mochan TDD with Chai assert tests to Jest.
* [mocha2ava-codemod](https://github.com/shimohq/mocha2ava-codemod) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-04 - A tranformer for migrating tests from Mocha to Ava.
* [ts-codemods](https://github.com/labarilem/ts-codemods) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2023-10-20 - Transformers for migrating callback-based Mocha tests to async/await based tests.

### AVA

* [jscodeshift-ava-tester](https://github.com/jfmengels/jscodeshift-ava-tester) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-14 - Codeshift wrapper to write smaller and better tests for your codemods using AVA.

### Styled Components

* [styled-components-codemods](https://github.com/styled-components/styled-components-codemods) ⭐ 52 | 🐛 11 | 🌐 JavaScript | 📅 2026-07-07 - Automatic codemods to upgrade your styled-components code to newer versions.
* [styled-components-v3-to-v4-codemod](https://github.com/RIP21/styled-components-v3-to-v4-codemod) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2018-11-12 - Codemod to migrate deprecated .extend API in favor of only styled functions.

### react-router

* [@putout/plugin-react-router](https://github.com/coderaiser/putout/tree/master/packages/plugin-react-router) ⭐ 796 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-23 - Putout plugin adds ability to migrate to latest version of react router.
* [react-router-v6-codemods](https://github.com/rajasegar/react-router-v6-codemods) ⭐ 10 | 🐛 2 | 🌐 JavaScript | 📅 2023-01-09 - Codemods for migrating react-router from v5 to v6.
* [react-router-v4-codemods](https://github.com/rajasegar/react-router-v4-codemods) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2023-01-08 - Codemods for migrating react-router from v3 to v4.

### material-ui

* [@mui/codemod](https://github.com/mui/material-ui/tree/master/packages/mui-codemod) ⭐ 98,914 | 🐛 1,494 | 🌐 JavaScript | 📅 2026-08-24 - A collection of codemod scripts based for use with jscodeshift that help update MUI APIs.

### ant-design

* [codemod-v4](https://github.com/ant-design/codemod-v4) ⭐ 99 | 🐛 55 | 🌐 JavaScript | 📅 2022-11-24 - Codemod cli for antd v4 upgrade.
* [antd-codemod](https://github.com/ant-design/antd-codemod) ⭐ 20 | 🐛 8 | 🌐 JavaScript | 📅 2021-03-01 - Antd codemod scripts.
* [codemod-v5](https://github.com/ant-design/codemod-v5) ⭐ 18 | 🐛 10 | 🌐 JavaScript | 📅 2023-04-19 - Codemod cli for antd v5 upgrade.

## Organization specific Codemods

This is the list of codemods used by a particular organization for their code transformations.

* [salesforce/lwc-codemod](https://github.com/salesforce/lwc-codemod) ⭐ 20 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-04 - Codemods for Lightning Web Components.
* [shopify-codemod](https://github.com/shopify-graveyard/shopify-codemod) ⚠️ Archived - A collection of Codemods written with JSCodeshift that will help update our old, crusty JavaScript to nice, clean JavaScript.
* [uber-codemods](https://github.com/uber-web/uber-codemods) ⭐ 12 | 🐛 11 | 🌐 JavaScript | 📅 2023-01-12 - Because Code Changes and Evolves.
* [artsy/codemods](https://github.com/artsy/codemods) ⭐ 11 | 🐛 2 | 🌐 TypeScript | 📅 2025-11-10 - Various codemods used around Artsy.
* [@freshworks/ember-codemods](https://github.com/freshdesk/ember-freshdesk-codemods) ⭐ 4 | 🐛 10 | 🌐 JavaScript | 📅 2026-03-27 - A collection of codemods used in Freshworks.
* [tune-codemods](https://github.com/TUNE-Archive/tune-codemods) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-31 - A collection of codemods we use at tune.
* [yapp-codemods](https://github.com/yappbox/yapp-codemods) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-18 - Yapp's codemods.
* [civicsource/codemod](https://github.com/civicsource/codemod/) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-12

## Editor Plugins

* [vscodemod](https://github.com/mikaelbr/vscodemod) ⭐ 30 | 🐛 6 | 🌐 JavaScript | 📅 2017-12-03 - VSCode extension for doing codemod on selected text.
* [atom-codemod](https://github.com/rosswarren/atom-codemod) ⭐ 2 | 🐛 25 | 🌐 JavaScript | 📅 2017-05-24 - Atom plugin for running codemods.
* [nmn/atom-codemod](https://github.com/nmn/atom-codemod) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2016-04-05 - Simple commands to apply specific Babel plugins/codemods on your code.

## Misc

* [mrm](https://github.com/sapegin/mrm) ⭐ 1,646 | 🐛 11 | 🌐 JavaScript | 📅 2024-10-30 - Codemods for your project config files.
* [django-codemod](https://github.com/browniebroke/django-codemod) ⭐ 190 | 🐛 8 | 🌐 Python | 📅 2026-08-24 - A tool to automatically fix Django deprecations.
* [ratchet](https://github.com/mskelton/ratchet) ⭐ 145 | 🐛 5 | 🌐 TypeScript | 📅 2024-04-07 - Codemod to convert React PropTypes to TypeScript types.
* [next-codemod](https://github.com/zeit/next-codemod) ⚠️ Archived - Codemod transformations to help upgrade Next.js codebases.
* [js-codemods](https://github.com/entria/js-codemods) ⭐ 44 | 🐛 0 | 🌐 TypeScript | 📅 2025-05-11 - Node.js/JavaScript codemods used at @entria.
* [strapi/codemods](https://github.com/strapi/codemods) ⚠️ Archived - CLI to help you migrate your Strapi applications & plugins from v3 to v4.
* [graphql2ts](https://github.com/sibelius/graphql2ts) ⭐ 41 | 🐛 20 | 🌐 TypeScript | 📅 2023-01-04 - Transform .graphql to graphql-js typescript.
* [babel-plugin-glamorous-to-emotion](https://github.com/TejasQ/babel-plugin-glamorous-to-emotion) ⭐ 34 | 🐛 4 | 🌐 JavaScript | 📅 2023-01-04 - A codemod to migrate existing React or Preact codebases from glamorous to emotion.
* [PHP-Codeshift](https://github.com/Atanamo/PHP-Codeshift) ⭐ 32 | 🐛 0 | 🌐 PHP | 📅 2022-10-23 - A small PHP toolkit for running codemods (code transformations) over multiple PHP files.
* [webpack-codemods](https://github.com/okonet/webpack-codemods) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-27 - JS Codemod to automatically convert webpack config from v1 to v2.
* [webdriverio/codemod](https://github.com/webdriverio/codemod) ⭐ 28 | 🐛 18 | 🌐 JavaScript | 📅 2024-07-15 - A codemod to transform Protractor into WebdriverIO tests.
* [gen-codemod](https://github.com/noahsug/gen-codemod) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-28 - Generate codemods by specifying your starting -> desired JavaScript.
* [mithril-codemods](https://github.com/MithrilJS/mithril-codemods) ⚠️ Archived
* [flow-codemod](https://github.com/flowtype/flow-codemod) ⚠️ Archived - Jscodeshift-powered <mithril@0.2.x> to <mithril@1.x> transformations .
* [babel-plugin-localize](https://github.com/amerani/babel-plugin-localize) ⭐ 12 | 🐛 3 | 🌐 JavaScript | 📅 2018-07-21 - Codemod to localize static strings.
* [date-fns-upgrade-codemod](https://github.com/date-fns/date-fns-upgrade-codemod) ⭐ 11 | 🐛 14 | 🌐 JavaScript | 📅 2023-01-04 - Code mods for upgrading date-fns versions.
* [generator-codemod](https://github.com/jamestalmage/generator-codemod) ⭐ 11 | 🐛 4 | 🌐 JavaScript | 📅 2016-04-19 - A generator to create codemods quickly.
* [create-codemod-app](https://github.com/dangreenisrael/create-codemod-app) ⭐ 11 | 🐛 13 | 🌐 JavaScript | 📅 2023-01-04 - Create Codemod App, a codemod generator and runner.
* [rxdart\_codemod](https://github.com/brianegan/rxdart_codemod) ⭐ 11 | 🐛 2 | 🌐 Dart | 📅 2019-11-28 - A collection of codemods to upgrade your RxDart code from one version to the next.
* [titanium-codemods](https://github.com/ewanharris/titanium-codemods) ⭐ 10 | 🐛 14 | 🌐 JavaScript | 📅 2023-01-03 - Codemod scripts for Titanium Applications.
* [codemodes-tycoon](https://github.com/myshov/codemodes-tycoon) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2024-11-11 - Codemods from Tycoon.
* [can-migrate](https://github.com/canjs/can-migrate) ⭐ 7 | 🐛 23 | 🌐 JavaScript | 📅 2021-11-23 - CLI & codemod scripts for upgrading to CanJS 3, 4 and 5.
* [jasmine-to-chai-codemod](https://github.com/vansosnin/jasmine-to-chai-codemod) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2017-12-28 - Codemod for jscodeshift to migrate your tests from Jasmine to Chai syntax.
* [pkg-upgrader](https://github.com/benmonro/pkg-upgrader) ⭐ 6 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-03 - Easily build codemod CLIs using jscodeshift. fork of lib-upgrader.
* [direct-import-codemod](https://github.com/limpbrains/direct-import-codemod) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2019-01-21 - Use direct imports to save JS bundle size.
* [gnome-shell-extension-es6-class-codemod](https://github.com/zhanghai/gnome-shell-extension-es6-class-codemod) ⚠️ Archived - A jscodeshift transform that helps migrating GNOME Shell extensions to 3.32.
* [generator-jscodeshif](https://github.com/scalvert/generator-jscodeshift) ⭐ 4 | 🐛 1 | 🌐 JavaScript | 📅 2018-04-14 - A yeoman generator for a jscodeshift codemod.
* [viewtools/codemods](https://github.com/viewstools/codemods) ⭐ 2 | 🐛 3 | 🌐 JavaScript | 📅 2023-01-27 - Helpers to migrate your code to newer versions of Views Tools.
* [d3-upgrade-codemods](https://github.com/expobrain/d3-upgrade-codemods) ⭐ 2 | 🐛 8 | 🌐 JavaScript | 📅 2026-01-21 - Codemods to upgrade d3 from version 3.x.
* [closure-codemod](https://github.com/toshi-toma/closure-codemod) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2020-08-31 - Closure codemod scripts.
* [tds-codemod](https://github.com/telus/tds-codemod) ⚠️ Archived - TELUS Design System.
* [bottender-codemod](https://github.com/bottenderjs/bottender-codemod) ⭐ 0 | 🐛 16 | 🌐 JavaScript | 📅 2023-01-05 - Bottender codemod scripts.
* [gsa-codeshift](https://github.com/bjoernricks/gsa-codeshift) - GSA codemod scripts.

## Awesome Lists

* [awesome-jscodeshift](https://github.com/sejoker/awesome-jscodeshift) ⭐ 415 | 🐛 5 | 📅 2023-10-22
* [awesome-ast](https://github.com/cowchimp/awesome-ast) ⭐ 238 | 🐛 0 | 📅 2020-05-18

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
