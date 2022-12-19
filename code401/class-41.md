# React Native

## Getting started with react native

1. Name three Core Components of React Native and describe what they do.

   - `<View>` => the building block of react native, basically a div
   - `<Text>` => displays, styles, and nests strings of text
   - `<TextInput>` => Allows the user to enter text

2. What problem does React Native solve (why call it native)?

   - React Native allows programmers to create an app using JavaScript, and render it to native platform UI. Native refers to apps that are created for specific OS (iOS, Android, Web)

3. What are the building blocks of a React Native app? How does that compare to a React app?

   - `<Text>` and `<View>` => `<p>` and `<div>`
   - React native has their own core components while React uses JSX elements.

## expo

1. What solution does expo provide?

   - Expo is a bundle of tools used to help you start a React Native app very fast.

2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the \_\_\_\_ workflow.

   - _managed_

3. What is the difference between React Native and Expo?

   - Expo is a framework to help you build react native apps. Expo offers the `expo-cli` and Expo client, which allows you to see and test the app you are working on on your own device.

## expo snack

1. Checkout this tool. What does snack allow you to do?

   - Expo snack allows you to quickly share and test react native apps straight from the web browser.

## ejecting

1. What does “eject” mean within the context of Expo?

   - Essentially you can take your expo project, which is written in pure JS, and can open it with Xcode or Android Studio in order to use specific native capabilities.

2. When should you not eject?

   - Just need to distribute the app in the iTunes Store or Google Play.
   - Are uncomfortable writing native code.
   - You require Expo's push notification services.
   - You rely on asking for help in the Expo community.

3. Why might you choose to eject?

   - If your Expo project needs a native module that Expo does not currently support.
