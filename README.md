This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Overview
This react native project is built and developed with macOS and iOS simulator.

It is a pre-cursor for the WeatherApp project, which features a switch that enables user to convert weather temperature data back and forth between Celsius and Fahrenheit. The figures below displays such feature in action:

<kbd><img width="350" alt="show-and-tell-F" src="https://github.com/user-attachments/assets/7e321bcf-ae73-47ac-bf60-bf78d962c1e4"/></kbd>
<kbd><img width="350" alt="show-and-tell-C" src="https://github.com/user-attachments/assets/964865ef-74d5-4f83-be22-d31ae92ade6a"/></kbd>



# Getting Started

After cloning this repo on local device, do the following: 

## Requirements to set up your environment
For the following,
   
   - **Development OS:** macOS
   
   - **Taget OS:** iOS

### Installing dependencies

1) Install Node and Watchman with [**Homebew**](https://brew.sh) in a terminal before installing the below with Homebrew:
   - `brew install node`
   - `brew install watchman`
  
2) Install **Xcode** from the [**Mac App Store**](https://apps.apple.com/us/app/xcode/id497799835?mt=12)

   Install the iOS simulator and other tools to build iOS app.

   a) Install the Xcode Command Line Tools
   
   Open Xcode -> Settings (or Preferences) -> Locations panel -> Select most recent version of Command Line Tools from the drop down menu

   b) Install iOS Simulator in Xcode

   Open Xcode -> Settings (or Preferences) -> Platforms (or Components) tab -> click "+" icon -> Select simulator that you wish to use


3) Install CocoaPods
   - `sudo gem install cocoapods`

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need navigate to the root directory of this project, then start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.


## Congratulations! :tada:

You've successfully run the React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
