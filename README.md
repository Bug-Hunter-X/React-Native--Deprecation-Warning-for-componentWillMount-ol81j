# React Native componentWillMount Deprecation

This repository demonstrates the deprecation of the `componentWillMount` lifecycle method in React Native and provides a solution using the `useEffect` hook.  `componentWillMount` is unreliable and can cause unexpected behavior.  Switching to `useEffect` ensures consistency across different React Native versions and platforms.

## Bug Report

The original code uses `componentWillMount`, triggering a deprecation warning.

## Solution

The solution uses `useEffect` hook with an empty dependency array to achieve similar functionality to `componentWillMount`, ensuring cleaner and more reliable code.

## How to Run

1. Clone the repository.
2. Navigate to the project directory: `cd react-native-componentWillMount`
3. Install dependencies: `npm install`
4. Run the app: `npx react-native run-android` or `npx react-native run-ios`