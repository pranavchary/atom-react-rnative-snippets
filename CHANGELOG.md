### atom-react-rnative-snippets Changelog

v0.1.0
------

Initial commit

_v0.1.0 through 0.1.7 were changes to solve the issue of being unable to view package settings & README in Atom; they consisted of trying different changes to files and the addition of new files in an attempt to troubleshoot the issue._

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
