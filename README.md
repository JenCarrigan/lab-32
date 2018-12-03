![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 32 - Forms

### Author: Jen Carrigan

### Links and Resources
* [sandbox](https://codesandbox.io/s/r02x67pp1p)

### Modules
#### `index.js`
renders the store and App.js

#### `store/index.js`
exports the store

#### `record-actions.js`
exports the actions: GET, POST, PUT, DELETE

#### `record-reducers.js`
sets the initial state and exports new state based on incoming action

#### `App,js`
class App has constructor for state.
App methods are delete, edit, and render for markup

#### `record.js`
class Record has methods handleSubmit and render for markup
global functions are mapStateToProps and mapDispatchToProps

#### UML
![UML](https://raw.githubusercontent.com/JenCarrigan/data-structures-and-algorithms/master/%3Aassets/FormsUML.jpg)
