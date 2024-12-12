# Expo AsyncStorage Deprecation Error

This repository demonstrates a common error encountered when using AsyncStorage in Expo and provides a solution using the recommended MMKV alternative. AsyncStorage is deprecated in Expo in favor of MMKV due to performance and reliability improvements.  This example shows how to upgrade your code to avoid the deprecation warning and ensure continued functionality.

## Setup

1. Clone the repository.
2. Run `npm install` or `yarn install` to install dependencies.
3. Start the Expo development server.

## Error Reproduction

The `bug.js` file showcases code that will trigger the deprecation warning.  You can run this to see the error message in your Expo development console.

## Solution

The `bugSolution.js` file demonstrates the corrected code using `@react-native-async-storage/async-storage`, the recommended replacement for AsyncStorage. This revised code will function correctly without any deprecation warnings. 
