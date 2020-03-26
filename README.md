React & React Native Snippets [![Build Status](https://travis-ci.org/pranavchary/atom-react-rnative-snippets.svg?branch=master)](https://travis-ci.org/pranavchary/atom-react-rnative-snippets)
----

An Atom plugin that turns shorthand text into code that is commonly used in React & React Native development. It also contains a few general-purpose JavaScript snippets as well. Almost every snippet in this package uses ES6 or higher syntax.

## Description
Latest snippet count by category is as follows:
 - React Import: 4
 - React Component: 5
 - React Lifecycle: 5
 - React Hooks: 5
 - React Native: 28
 - General-purpose JavaScript: 15
 - Total: **62**

I would greatly appreciate any suggestions for snippets that aren't yet available for this package, or if any naming conventions appear odd to anyone. My goal is for this package to become a powerful & effective tool for web/mobile application developers.

## Snippets
 After typing the snippet, pressing 'Enter' for Windows users and 'Return' for Macintosh users will write the code to the file. Alternatively, users can also press 'Tab' instead.

---- indicates that a user will be able to enter any text they'd like once the snippet has written the desired code in the file.


#### React Import Snippet List
 - **eimr:** `import ---- from 'react';`
 - **enimr:** `import { ---- } from 'react'`
 - **imr:** `import React from 'react';`
 - **imrn:** `import React, { ---- } from 'react';`

#### React Component Snippet List
 - **rcc:** `const ---- = React.createClass({ ... });`
 - **rcerc:** `class ---- extends React.Component { ... }`
 - **rcec:** `class ---- extends Component { ... }`
 - **rfc:** `const ---- = (----) => { ... }`
 - **rfcf:** `const ---- = function(----) { ... }`

#### React Lifecycle Method Snippet List
 - **rcon:** `creates a constructor`
 - **rcons:** `creates a constructor with an empty state object`
 - **rcmd:** `componentDidMount() { ---- }`
 - **rcdu:** `componentDidUpdate(----) { ---- }`
 - **rcwu:** `componentWillUnmount() { ---- }`

#### React Hooks Snippet List
 - **rhs:** `const [----, ----] = useState(----);`
 - **rhr:** `const [----, ----] = useReducer(----, { ---- });`
 - **rhe:** `useEffect(() => { ---- }, ----);`
 - **rccont:** `const ---- = React.createContext({ ---- });`
 - **rhc:** `const ---- = useContext({ ---- });`

#### React Native Snippet List
 - **eimrn:** `import ---- from 'react-native';`
 - **nimrn:** `import { ---- } from 'react-native';`
 - **rncss:** `const styles = StyleSheet.create({ ---- });`
 - **rnnnav:** `navigation.navigate('----');`
 - **rnnpush:** `navigation.push('----');`
 - **rnngb:** `navigation.goBack();`
 - **rnnpop:** `navigation.pop(----);`
 - **rnnptt:** `navigation.popToTop();`
 - **rnnrep:** `navigation.replace(----);`
 - **rnnjt:** `navigation.jumpTo('----');`
 - **rnnod:** `navigation.openDrawer();`
 - **rnncd:** `navigation.closeDrawer();`
 - **rnntd:** `navigation.toggleDrawer();`
 - **rnv:** `<View ---- >----</View>`
 - **rnvsc:** `<View ---- />`
 - **rnvt:** `<View ---- ><Text ---- >----</Text></View>`
 - **rnt:** `<Text ---- >----</Text>`
 - **rnimg:** `<Image source={----} ---- />`
 - **rnti:** `<TextInput value={----} onChangeText={----} onEndEditing={----} ---- />`
 - **rnsv:** `<ScrollView ---- >----</ScrollView>`
 - **rnsvt:** `<ScrollView ---- ><Text ---- >----</Text></ScrollView>`
 - **rnbtn:** `<Button title='----' onPress={----} ---- />`
 - **rnto:** `<TouchableOpacity ---- >----</TouchableOpacity>`
 - **rnpick:** `<Picker selectedValue={----} onValueChange={----} ---- >----</Picker>`
 - **rnpitem:** `<Picker.Item label='----' value={----} />`
 - **rnsw:** `<Switch value={----} onValueChange={----} ---- />`
 - **rnfl:** `<FlatList keyExtractor={----} data={----} renderItem={----} />`
 - **rnsl:** `<SectionList sections={----} keyExtractor={----} renderItem={----} renderSectionHeader={----} />`

#### Misc Snippet List
 - **eim:** `import ---- from '----';`
 - **enim:** `import { ---- } from '----';`
 - **tcb:** `try { ----} catch (----) { ---- }`
 - **tcfb:** `try { ---- } catch (----) { ---- } finally { ---- }`
 - **olarr:** `const ---- = (----) => ----;`
 - **arr:** `const ---- = (----) => { ---- }`
 - **afunc:** `function(----) { ---- }`
 - **cfunc:** `const ---- = function(----) { ---- }`
 - **vfunc:** `var ---- = function(----) { ---- }`
 - **lfunc:** `let ---- = function(----) { ---- }`
 - **log:** `console.log(----);`
 - **logt:** `console.log('----');`
 - **logm:** `console.log('----', ----);`
 - **exdef:** `export default ----;`
 - **modexp:** `module.exports = ----;`
