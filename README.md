# Twitter Clone using React Navigation v5 and React Native Paper 

## About this project

This is an updated fork of the React Native TwitterClone app implemented for 
[this blog post](https://reactnavigation.org/blog/2020/01/29/using-react-navigation-5-with-react-native-paper/)

![screenshot demo](./assets/app.gif)

This fork meant to be used as a starter for experimenting with ideas for apps with a social media component.
It uses a modern React Native code, with React Navigation for navigation, and React Native Paper for styling.
The user interface works on iOS, Android, and web. 

There is no back end so this can run "out of the box". The sample data is imported from a local JSON file.

## Getting Started

Clone or fork this repository, and install everything.

```
git clone https://github.com/criesbeck/twitterClone.git
cd twitterClone
npm install
```

Run with Expo.

```
expo start
```

## Usage

Develop a clear idea of your app, with a concrete payoff. I like to use 
[four-panel storyboards](http://allcritiquesgreatandsmall.blogspot.com/2015/01/the-4-panel-storyboard.html)
for this purpose.

Once you have an idea for your app, modify the JSON data and code to implement and demonstrate the example
payoff. 

Then modify the app to fetch and store dynamic data on a real database.

## Changes to original code

Updated Expo and various libraries.

Replaced `route.state.name` with `getFocusedRouteNameFromRoute()`, and `useSafeArea()` with `useSafeAreaInsets()`.

Moved sample data from JavaScript to a Firebase-compatible JSON file. Updated URL for Evan Bacon's profile image in sample data.

## Bugs

Notifications and Messages screens are blank the first time you navigate to them in the web interface. 
This doesn't happen on iOS and Android, though there is a noticable pause before they display.

## Acknowledgments

[React Navigation v5 + React Native Paper = ❤️](https://reactnavigation.org/blog/2020/01/29/using-react-navigation-5-with-react-native-paper/)

