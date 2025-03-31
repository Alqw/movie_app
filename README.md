# Expo React Native App

Welcome to your Expo React Native project! This guide will help you set up, run, and export your app.

## 📌 Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (LTS recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/):
  
  ```bash
  npm install -g expo-cli
  ```

## 🚀 Getting Started

1. Install dependencies:
   
   ```bash
   npm install
   ```

2. Create a .env file in the root of your project to store environment variables like API keys, secret keys, and other sensitive data. Here’s an example .env file:

   ```ini
   EXPO_PUBLIC_MOVIE_API_KEY=your_movie_api_key
   EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id
   EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_appwrite_database_id
   EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

   Make sure to replace your_movie_api_key, your_appwrite_project_id, your_appwrite_database_id, and your_appwrite_collection_id with the actual values.

3. Start the development server:
   
   ```bash
   npx expo start
   ```

4. You can open your app in:
   - A [development build](https://docs.expo.dev/develop/development-builds/introduction/)
   - An [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
   - An [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/) (Mac only)
   - [Expo Go](https://expo.dev/go) on your physical device

## 📱 Running on a Mobile Device

To test your app on a real device:

1. Install the Expo Go app from the App Store (iOS) or Google Play Store (Android).
2. Start your Expo project using:
   
   ```bash
   npx expo start
   ```

3. Scan the QR code displayed in the terminal or Expo Developer Tools using Expo Go.

## 📦 Exporting the App

### Exporting for Web

To export your project for web deployment:

```bash
npx expo export:web
```

### Building Standalone Apps

To create a production build for Android or iOS:

- **Android**:
  
  ```bash
  eas build --platform android
  ```

- **iOS**:
  
  ```bash
  eas build --platform ios
  ```
  *(Requires a Mac with Xcode installed)*

For full instructions, check out [Expo Application Services (EAS)](https://docs.expo.dev/build/introduction/).

## 🛠 Resetting the Project

To get a fresh project setup, run:

```bash
npm run reset-project
```

This moves the starter code to the `app-example` directory and creates a blank `app` directory for development.

## 📚 Learn More

For more information, visit:

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Docs](https://reactnative.dev/)
- [Expo Router Guide](https://docs.expo.dev/router/introduction/)

## 👥 Join the Community

Connect with other developers and get support:

- [Expo GitHub](https://github.com/expo/expo)
- [Expo Discord](https://chat.expo.dev)

Happy coding! 🚀