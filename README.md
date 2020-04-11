# React Native Starter

This project can be used to fast start your React Native development. It contains a React Native project configured with sensible list of packages almost any project needs.

### React Native

This project is based on React Native 0.62.2 and is using the TypeScript enabled template.

### Commits

Each commit represent addition of a different package so you can easily pull from the commit you want. Each commit message describe what package was added to the project

### Tags

There are also a few tags you can pull from, each representing "a milestone" in the project. Each tag is built on top of the other.

#### BASE Tag

This tag contains the following packages:

- react-native-vector-icons
- @react-native-community/async-storage
- React Navigation (all required pacakges including Stack)
- axios
- @react-native-community/react-native-device-info
- react-native-keyboard-aware-scroll-view

#### BASE_PLUS_REDUX Tag

This tag adds the redux packages:

- redux
- react-redux
- @reduxjs/toolkit

#### BASE_LOADED

This tag adds the following packages:

- react-hook-form
- react-native-animatable
- react-native-spin-kit
- @react-native-community/react-native-permissions
- react-native-splash-screen

#### Additional Instructions

To utilize react-native-permissions you need to edit your Pod file, your info.plist file and AndroidManifest.xml and enable the permission you want to ask for. I left all the possible options commented out in each file

To edit the splash screen, you need to follow a few steps such as:

- replace the icons with your own icons both in iOS and Android
- Edit the background color of the splash screen (currently #424242)

Check out the tutorial at this link: https://medium.com/@appstud/add-a-splash-screen-to-a-react-native-app-810492e773f9
