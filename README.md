React & React Native Snippets [![Build Status](https://travis-ci.org/pranavchary/atom-react-rnative-snippets.svg?branch=master)](https://travis-ci.org/pranavchary/atom-react-rnative-snippets)]
----

An Atom plugin that turns shorthand text into code that is commonly used in React & React Native development. It also contains a few general-purpose JavaScript snippets as well.

## Description
Latest snippet count by category is as follows:
 - React Import: 4
 - React Component: 5
 - React Lifecycle: 5
 - React Hooks: 3
 - React Native: 26
 - General-purpose JavaScript: 6
 - Total: **49**

I would greatly appreciate any suggestions for snippets that aren't yet available for this package, or if any naming conventions appear odd to anyone. My goal is for this package to become a powerful & effective tool for web/mobile application developers.

## Snippets
 After typing the snippet, pressing 'Enter' for Windows users and 'Return' for Macintosh users will write the code to the file. Alternatively, users can also press 'Tab' instead.

---- indicates that a user will be able to enter any text they'd like once the snippet has written the desired code in the file.


#### React Import Snippet List
 - **eimr:** _import ---- from 'react';_
 - **enimr:** _import { ---- } from 'react'_
 - **imr:** _import React from 'react';_
 - **imrn:** _import React, { ---- } from 'react';_

#### React Component Snippet List
 - **rcc:** _const ---- = React.createClass({ ... });_
 - **rcerc:** _class ---- extends React.Component { ... }_
 - **rcec:** _class ---- extends Component { ... }_
 - **rfc:** _const ---- = (----) => { ... }_
 - **rfcf:** _const ---- = function(----) { ... }_

#### React Lifecycle Method Snippet List
 - **rcon:** _creates a constructor_
 - **rcons:** _creates a constructor with an empty state object_
 - **rcmd:** _componentDidMount() { ---- }_
 - **rcdu:** _componentDidUpdate(----) { ---- }_
 - **rcwu:** _componentWillUnmount() { ---- }_

#### React Hooks Snippet List
 - **rhs:** _const [----, ----] = useState(----);_
 - **rhr:** _const [----, ----] = useReducer(----, { ---- });_
 - **rhe:** _useEffect(() => { ---- }, ----);_

#### React Native Snippet List
 - **eimrn:** _import ---- from 'react-native';_
 - **nimrn:** _import { ---- } from 'react-native';_
 - **rncss:** _const styles = StyleSheet.create({ ---- });_
 - **rnnnav:** _navigation.navigate('----');_
 - **rnnpush:** _navigation.push('----');_
 - **rnngb:** _navigation.goBack();_
 - **rnnpop:** _navigation.pop(----);_
 - **rnnptt:** _navigation.popToTop();_
 - **rnnrep:** _navigation.replace(----);_
 - **rnnjt:** _navigation.jumpTo('----');_
 - **rnnod:** _navigation.openDrawer();_
 - **rnncd:** _navigation.closeDrawer();_
 - **rnntd:** _navigation.toggleDrawer();_
 - **rnv:** _\<View ---- >----\</View>_
 - **rnvsc:** _\<View ---- />_
 - **rnt:** _\<Text ---- >----\</Text>_
 - **rnimg:** _\<Image source={----} ---- />_
 - **rnti:** _\<TextInput onChangeText={----} value={----} ---- />_
 - **rnsv:** _\<ScrollView ---- >----\</ScrollView>_
 - **rnbtn:** _\<Button onPress={----} ---- />_
 - **rnto:** _\<TouchableOpacity ---- >----\</TouchableOpacity>_
 - **rnpick:** _\<Picker selectedValue={----} onValueChange={----} ---- >----\</Picker>_
 - **rnpitem:** _\<Picker.Item label=---- value=---- />_
 - **rnsw:** _\<Switch value={----} onValueChange={----} ---- />_
 - **rnfl:** _\<FlatList keyExtractor={----} data={----} renderItem={----} />_
 - **rnsl:** _\<SectionList sections={----} keyExtractor={----} renderItem={----} renderSectionHeader={----} />_

#### Misc Snippet List
 - **eim:** _import ---- from '----';_
 - **log:** _console.log(----);_
 - **logt:** _console.log('----');_
 - **logm:** _console.log('----', ----);_
 - **exdef:** _export default ----;_
 - **modexp:** _module.exports = ----;_
