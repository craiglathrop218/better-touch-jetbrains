# JetBrains Magic Touch Bar
This is a portion of a configuration for the **Better Touch Tool Bar**. 

## Usage
1. The easiest way to use this is to first create a couple of Touch Bar settings in Better Touch for the various JetBrains plugins you want to use. 
2. Export your settings.
3. Open the exported `.json` file.
4. Find the portion of JSON that has the settings for your app. For example
```json
"BTTAppBundleIdentifier" : "com.jetbrains.pycharm",
"BTTAppName" : "PyCharm",
"BTTAppSpecificSettings" :
```
5. Edit the provided JSON fragment so that the `BTTAppBundleIdentifier` and `BTTAppName` match, then replace the entire section of content.
