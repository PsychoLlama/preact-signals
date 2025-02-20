# @preact/signals-react-transform

## 0.2.0

### Minor Changes

- [#458](https://github.com/preactjs/signals/pull/458) [`0c0d89f`](https://github.com/preactjs/signals/commit/0c0d89f181e7b38432d10ea0f79fa031774c2a27) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Only prepend useSignals call if we can't determine whether a function is a component or hook

* [#459](https://github.com/preactjs/signals/pull/459) [`06d4c10`](https://github.com/preactjs/signals/commit/06d4c10dbc2b3029ffe855d846afd7dc431ea749) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Wrap custom hooks in try/finally when using react-transform

- [#446](https://github.com/preactjs/signals/pull/446) [`09f3ed7`](https://github.com/preactjs/signals/commit/09f3ed7c5b7a5a3a86673dfc73cd868766e0eefc) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Use function expression name to determine if it is a Component and should be transformed.

### Patch Changes

- Updated dependencies [[`b0b2a5b`](https://github.com/preactjs/signals/commit/b0b2a5b54d0b512152171bb13c5bc4c593e7e444)]:
  - @preact/signals-react@1.3.8

## 0.1.1

### Patch Changes

- [#439](https://github.com/preactjs/signals/pull/439) [`fb6b050`](https://github.com/preactjs/signals/commit/fb6b050be305294fa3ea5b883c51a375f1720f78) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Remove top-level requirement from react-transform

* [#413](https://github.com/preactjs/signals/pull/413) [`ad6305c`](https://github.com/preactjs/signals/commit/ad6305c973160fb1272b6ad2e3783e6e3410f9de) Thanks [@XantreGodlike](https://github.com/XantreGodlike)! - Added 'module:' prefix to readme to babel recognized plugin correctly

- [#421](https://github.com/preactjs/signals/pull/421) [`f80b251`](https://github.com/preactjs/signals/commit/f80b251d7333e1a1d82e537969a15ba17657c82f) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Add an "all" mode to the react transform that transforms all components to be reactive to signals

* [#441](https://github.com/preactjs/signals/pull/441) [`4c433c3`](https://github.com/preactjs/signals/commit/4c433c32469d3a79b1a3e4d523f111b6bec3a187) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Add support for auto-transforming more ways to specify components: object methods, member assignments, export default components, components wrapped in HoCs like memo and forwardRef

- [#444](https://github.com/preactjs/signals/pull/444) [`2939812`](https://github.com/preactjs/signals/commit/2939812a972b62830e0a839dcc9a8024ab5c7bc8) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Add support for auto transforming Components declared as object properties

* [#442](https://github.com/preactjs/signals/pull/442) [`76babcb`](https://github.com/preactjs/signals/commit/76babcb520594bb200fd69ac4840a7df5f259752) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Add debug logging to inspect what components are transformed by plugin

* Updated dependencies [[`020982d`](https://github.com/preactjs/signals/commit/020982d2f3039817527aaa000a5697486a870c9d), [`fb6b050`](https://github.com/preactjs/signals/commit/fb6b050be305294fa3ea5b883c51a375f1720f78)]:
  - @preact/signals-react@1.3.7

## 0.1.0

### Minor Changes

- [#406](https://github.com/preactjs/signals/pull/406) [`71caaad`](https://github.com/preactjs/signals/commit/71caaad9c69da4bd6a1c9bf1926562162a109dfb) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Remove support for transforming CJS files

  Removing support for transforming CommonJS files since we have no tests for it currently

### Patch Changes

- [#406](https://github.com/preactjs/signals/pull/406) [`71caaad`](https://github.com/preactjs/signals/commit/71caaad9c69da4bd6a1c9bf1926562162a109dfb) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Register newly inserted import statement as a scope declaration in Babel's scope tracking

## 0.0.2

### Patch Changes

- [#401](https://github.com/preactjs/signals/pull/401) [`17e1491`](https://github.com/preactjs/signals/commit/17e1491a27afedc714c6b0ab1e9fbf88d0d6433c) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Lower required babel version required as a peer dependency

- Updated dependencies [[`24fa9f7`](https://github.com/preactjs/signals/commit/24fa9f791d70baba35bdce722f71ce63ac091a4d)]:
  - @preact/signals-react@1.3.6

## 0.0.1

### Patch Changes

- [#375](https://github.com/preactjs/signals/pull/375) [`59115d9`](https://github.com/preactjs/signals/commit/59115d9ea6dfa073255f9803dd7e8a09892d2acc) Thanks [@andrewiggins](https://github.com/andrewiggins)! - Initial alpha release

- Updated dependencies [[`cd3a22d`](https://github.com/preactjs/signals/commit/cd3a22d628c3a535108bc45b8151505dd6fc51c8), [`59115d9`](https://github.com/preactjs/signals/commit/59115d9ea6dfa073255f9803dd7e8a09892d2acc)]:
  - @preact/signals-react@1.3.5
