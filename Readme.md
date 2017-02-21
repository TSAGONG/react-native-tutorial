# React-Native Getting Started (iOS/macOS)

###Build Native Mobile Apps using JavaScript and React
React Native lets you build mobile apps using only JavaScript. It uses the same design as React, letting you compose a rich mobile UI from declarative components.

````
import React, { Component } from 'react';
import { Text, View } from 'react-native';

class WhyReactNativeIsSoGreat extends Component {
  render() {
    return (
      <View>
        <Text>
          If you like React on the web, you'll like React Native.
        </Text>
        <Text>
          You just use native components like 'View' and 'Text',
          instead of web components like 'div' and 'span'.
        </Text>
      </View>
    );
  }
}

````

###Installing Dependenies
We recommend installing Node and Watchman using Homebrew. Run the following commands in a Terminal after installing Homebrew:

`````
brew install node
brew install watchman
`````
[Watchman](https://facebook.github.io/watchman/) is a tool by Facebook for watching changes in the filesystem. It is highly recommended you install it for better performance.


### The React Native CLI

````
npm install -g react-native-cli
````
If you get an error like Cannot find module 'npmlog', try installing npm directly: curl -0 -L http://npmjs.org/install.sh | sudo sh.

####Xcode
Make sure to install Xcode via [Mac App Store](https://itunes.apple.com/us/app/xcode/id497799835?mt=12). Installing Xcode will also install the iOS simulator and all the necessary tools to build your iOS app.

###Testing your React Native Installation
Use the React Native command line interface to generate a new React Native project called "MoreCoffeePlease", then run react-native run-ios inside the newly created folder.

````
react-native init MoreCoffeePlease
cd AwesomeProject
react-native run-io
````

You should see your new app running in the iOS Simulator shortly.

`react-native run-ios` is just one way to run your app. You can also run it directly from within Xcode or [Nuclide.](https://nuclide.io/)

####Modifying Your App
Now that you have successfully run the app, let's modify it.

Open `index.ios.js` in your text editor of choice and edit some lines.
Hit `Command⌘ + R` in your iOS Simulator to reload the app and see your change!

####That's It
Congratulations! You've successfully run and modified your first React Native app

![Congrats Homie](https://facebook.github.io/react-native/img/react-native-congratulations.png "Congrats Homie")

Source: [React-Native](https://facebook.github.io/react-native/docs/getting-started.html#content)
