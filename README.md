# UnitTestingReactNative
A 6 step tutorial on how to get unit testing working on a React Native project.

### Setup
Run the following command to install all npm dependencies:
```
$ npm install
```


### Updating React Native
In order to update react-native you have to update react and react-dom. Add a ^ in front of the required version for each of these in package.json and run the following command:
```
$ react-native upgrade
```
After running the upgrade you can remove react and react-dom  in package.json and explicitly install the versions of react and react-dom needed by react native. (See Known Issues) You can now also update/install other packages as necessary. After updating react-native make sure that all your npm dependencies are met.

#### Known Issues :
If you are having troubles with running your react-native project make sure that the versions of react and react-dom are version locked in package.json and the same as the version required by react-native. Otherwise your react-native project won't package properly.


### Unit Tests
Run the following command to execute unit tests with coverage reports :
```
$ npm test
```
