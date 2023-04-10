## [getting started with react native](https://reactnative.dev/docs/getting-started)

### Name three Core Components of React Native and describe what they do.
- View - View is the most basic component in React Native, and it's similar to the div element in HTML. It's used to create a container that can hold other components, including other views. It's essentially a blank canvas that can be styled and arranged as needed.

- Text - Text is another essential component in React Native, and it's used to display text on the screen. It's similar to the span element in HTML, and it supports basic styling like font size, font weight, and color.

- Image - Image is used to display images in a React Native app. It supports both local and remote images, and it provides several props for controlling the image size, aspect ratio, and other attributes.

### What problem does React Native solve (why call it native)?
React Native solves this problem by providing a unified framework for building mobile apps using a single codebase. By using JavaScript and React, developers can write once and deploy to both iOS and Android, which significantly reduces the time and effort required to build mobile apps
### What are the building blocks of a React Native app? How does that compare to a React app?

Components - Components are the building blocks of both React and React Native apps. They are reusable UI elements that encapsulate a set of functionality and can be combined to create more complex UIs. However, React Native components are optimized for mobile screens and touch-based interactions, which means that they have some differences in terms of how they are rendered and styled compared to React components.

Views, Text, Images , Styles, APIs .

Compared to a React app, the main differences in building blocks for a React Native app are the focus on mobile screens and touch-based interactions, and the use of native components and APIs

## [expo](https://expo.dev)

### What solution does expo provide?
Expo provides a complete solution for developing, building, and publishing mobile apps using React Native.

### Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.
`convention over configuration`

### What is the difference between React Native and Expo?
React Native is a framework for building mobile apps, while Expo is a set of tools and services that makes it easier to build and deploy React Native apps.


## [expo snack](https://snack.expo.dev/)

### Checkout this tool. What does snack allow you to do?
Snack is a web-based tool provided by Expo that allows developers to quickly prototype, test, and share React Native code in a web browser. With Snack, developers can create and preview mobile apps without having to set up a local development environment or run the app on a physical device.

## [ejecting](https://docs.expo.dev/archive/glossary/#eject?redirected)

### What does “eject” mean within the context of Expo?
"Ejecting" an Expo app will generate a new native iOS and Android project in the background, and copy over all the relevant configuration and code from your Expo app. This way, you will have a native project that's independent from Expo and can be configured and customized to your needs. You can then use the native project to add new native code, integrate with additional native libraries, and take full control of your project's dependencies.

### When should you not eject?
- When you're starting a new project
- When you're not familiar with native development
- When you need to move quickly
- When you want to minimize complexity


### Why might you choose to eject?
- When you need to add custom native modules
- When you need to integrate with third-party native libraries
- When you need to optimize app performance
- When you need to access native APIs
- When you need to take full control of your project's dependencies

