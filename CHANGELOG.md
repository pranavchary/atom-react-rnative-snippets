### atom-react-rnative-snippets Changelog

v0.1.0
------

Initial commit

_v0.1.1 through 0.1.7 were changes to solve the issue of being unable to view package settings & README in Atom; they consisted of trying different changes to files and the addition of new files in an attempt to troubleshoot the issue._

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

v0.3.0
------
- **NEW REACT SNIPPETS**
  - Create and use context
- **NEW REACT NATIVE SNIPPETS**
  - Templates for View & ScrollView components with embedded text
- **NEW JAVASCRIPT SNIPPETS**
  - Templates for try/catch & try/catch/finally blocks
  - Templates for one-line & multi-line arrow functions
  - Template for anonymous keyword function
  - Template for named keyword function (with const/var/let)
- Modified the descriptive text for some of the React snippets
- Modified the React effect hook snippet so that the whitespace became part of the dependencies tabstop
-  Modified the React Native named import snippet so that `View, Text, Stylesheet` is now part of a tabstop so they can be removed if desired
- Wrapped values of certain React Native component props in brackets as per typical usage
- Modified the descriptive text of one of the JavaScript `console.log()` snippets

v0.3.1
------
- Fixed a spelling mistake in the React component constructor Snippets
- Moved the comma in navigation functions into the tabstop for params (React Native snippets)
- Changed the tabstop order for View with embedded Text and ScrollView with embedded Text in React Native snippets
