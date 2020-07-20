### atom-react-rnative-snippets Changelog

v2.0.0 (actually v1.0.0 - misabled due to a versioning error on my end)
- **NEW REACT SNIPPETS**
	- `componentWillMount` & `componentWillReceiveProps` lifecycle methods (prefixed by `UNSAFE_` tabstop for React 16.9.0+)
	- `useRef` hook
	- default props object
	- prop types object
- **NEW JAVASCRIPT SNIPPETS**
	- Template for anonymous one-line arrow function
	- Templates for one-line & multi-line arrow functions using `var` and `let`
	- Templates for destructuting objects (with `const`/`var`/`let`)
- **SNIPPET CHANGES**
	- `cfunc` is now `func`
- Added descriptive placeholders for the `useState` hook (React Hooks snippets)
- Added a space before props on `SectionList` and `FlatList` components (React Native snippets)

v0.3.1
------
- Fixed a spelling mistake in the React component constructor Snippets
- Moved the comma in navigation functions into the tabstop for params (React Native snippets)
- Changed the tabstop order for `View` with embedded `Text` and `ScrollView` with embedded `Text` in React Native snippets

v0.3.0
------
- **NEW REACT SNIPPETS**
  - Create context and `useContext` hook
- **NEW REACT NATIVE SNIPPETS**
  - Templates for `View` & `ScrollView` components with embedded text
- **NEW JAVASCRIPT SNIPPETS**
  - Templates for `try`/`catch` & `try`/`catch`/`finally` blocks
  - Templates for one-line & multi-line arrow functions
  - Template for anonymous keyword function
  - Template for named keyword function (with `const`/`var`/`let`)
- Modified the descriptive text for some of the React snippets
- Modified the React effect hook snippet so that the whitespace became part of the dependencies tabstop
-  Modified the React Native named import snippet so that `View, Text, Stylesheet` is now part of a tabstop and can be removed if desired
- Wrapped values of certain React Native component props in brackets as per typical usage
- Modified the descriptive text of one of the JavaScript `console.log()` snippets

v0.2.0
------

- Added the JavaScript snippet for an empty named import (`import { ---- } from '----';`)
- Added whitespace between `const` and the opening bracket of the state and reducer React Hooks
- Removed the new line character after each of the following snippets:
  - React Native core components
  - React Navigation method calls
  - JavaScript exports
- Modified React Native core component snippets:
  - Removed the whitespace before the `props` tabstop and added it to the tabstop itself. This allows it to be deleted along with `props` if desired
- Replaced the new line character after each `console.log()` snippet with a tabstop

_v0.1.1 through 0.1.7 were changes to solve the issue of being unable to view package settings & README in Atom; they consisted of trying different changes to files and the addition of new files in an attempt to troubleshoot the issue._

v0.1.0
------

Initial commit
