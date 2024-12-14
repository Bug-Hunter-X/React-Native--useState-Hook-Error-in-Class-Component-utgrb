# React Native: useState Hook Error in Class Component

This repository demonstrates a common error in React Native development: attempting to use the `useState` hook inside a class component.  The `useState` hook is only functional within functional components.

## Problem
The `bug.js` file shows an incorrect implementation where `useState` is used within a class component. This will lead to errors and unexpected behavior.

## Solution
The solution is to refactor the code to use functional components or, if necessary for legacy reasons, to manage state within the class component using `this.state` and lifecycle methods.

## How to run
1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npx react-native run-android` or `npx react-native run-ios`.