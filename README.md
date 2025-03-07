# replica

# React Native Replica Project

This project serves as a minimal base to replicate issues encountered in the main project, specifically related to React Native Firebase and iOS pod installation issues.

## Issues Addressed

- **[invertase/react-native-firebase#8248](https://github.com/invertase/react-native-firebase/issues/8248)**: New setup guide for iOS Credentials in RN 0.77.
- **[invertase/react-native-firebase#8390](https://github.com/invertase/react-native-firebase/issues/8390)**: Problem installing pods for iOS build with non-standard / unsupported modular_headers.

## Project Setup

To create the replica project, use the following command:

```sh
npx @react-native-community/cli@latest init replica --version 0.77.1
```

## Dependencies

The `package.json` file for this replica project includes the following dependencies:

```json
{
  "name": "agendaT",
  "version": "0.0.1",
  "private": true,
  "scripts": {
    "android": "react-native run-android",
    "ios": "react-native run-ios",
    "lint": "eslint .",
    "start": "react-native start",
    "test": "jest"
  },
  "dependencies": {
    "@gorhom/bottom-sheet": "^4.6.4",
    "@notifee/react-native": "^9.1.8",
    "@react-native-async-storage/async-storage": "^2.1.1",
    "@react-native-community/blur": "^4.4.1",
    "@react-native-community/datetimepicker": "^8.3.0",
    "@react-native-community/geolocation": "^3.4.0",
    "@react-native-firebase/app": "^21.10.1",
    "@react-native-firebase/auth": "^21.10.1",
    "@react-native-firebase/messaging": "^21.10.1",
    "@react-navigation/bottom-tabs": "^7.2.0",
    "@react-navigation/material-top-tabs": "^7.1.0",
    "@react-navigation/native": "^7.0.14",
    "@react-navigation/stack": "^7.1.1",
    "formik": "^2.4.6",
    "install": "^0.13.0",
    "npm": "^11.1.0",
    "react": "18.3.1",
    "react-native": "0.77.1",
    "react-native-animatable": "^1.4.0",
    "react-native-compressor": "^1.10.4",
    "react-native-config": "^1.5.5",
    "react-native-fast-image": "^8.6.3",
    "react-native-fs": "^2.20.0",
    "react-native-geolocation-service": "^5.3.1",
    "react-native-gesture-handler": "^2.23.1",
    "react-native-get-random-values": "^1.11.0",
    "react-native-google-places-autocomplete": "^2.5.7",
    "react-native-google-signin": "^2.1.1",
    "react-native-image-picker": "^8.1.0",
    "react-native-keyboard-aware-scroll-view": "^0.9.5",
    "react-native-linear-gradient": "^2.8.3",
    "react-native-maps": "^1.20.1",
    "react-native-pager-view": "^6.7.0",
    "react-native-permissions": "^5.2.5",
    "react-native-reanimated": "^3.16.6",
    "react-native-safe-area-context": "^5.2.0",
    "react-native-screens": "^4.7.0",
    "react-native-svg": "^15.11.1",
    "rn-fetch-blob": "^0.12.0",
    "yup": "^1.6.1"
  },
  "devDependencies": {
    "@babel/core": "^7.25.2",
    "@babel/preset-env": "^7.25.3",
    "@babel/runtime": "^7.26.9",
    "@react-native-community/cli": "15.0.1",
    "@react-native-community/cli-platform-android": "15.0.1",
    "@react-native-community/cli-platform-ios": "15.0.1",
    "@react-native/babel-preset": "0.77.1",
    "@react-native/eslint-config": "0.77.1",
    "@react-native/metro-config": "0.77.1",
    "@react-native/typescript-config": "0.77.1",
    "@types/jest": "^29.5.13",
    "@types/react": "^18.2.6",
    "@types/react-test-renderer": "^18.0.0",
    "eslint": "^8.19.0",
    "jest": "^29.6.3",
    "prettier": "2.8.8",
    "react-test-renderer": "18.3.1",
    "typescript": "5.0.4"
  },
  "engines": {
    "node": ">=18"
  }
}
```

