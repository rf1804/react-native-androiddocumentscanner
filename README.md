
# react-native-androiddocumentscanner

## Getting started

`$ npm install react-native-androiddocumentscanner --save`

### Mostly automatic installation

`$ react-native link react-native-androiddocumentscanner`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.rf1804.documentscanner.RNAndroiddocumentscannerPackage;` to the imports at the top of the file
  - Add `new RNAndroiddocumentscannerPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-androiddocumentscanner'
  	project(':react-native-androiddocumentscanner').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-androiddocumentscanner/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-androiddocumentscanner')
  	```


## Usage
```javascript
import RNAndroiddocumentscanner from 'react-native-androiddocumentscanner';

// TODO: What to do with the module?
RNAndroiddocumentscanner;
```
  