# React useEffect Hook Missing Cleanup

This repository demonstrates a common error in React applications: forgetting to include a cleanup function in the `useEffect` hook. This can lead to memory leaks or unexpected side effects.

## The Bug

The `bug.js` file contains a component that uses `useEffect` to log a message to the console when the component mounts. However, it's missing the return statement that's necessary for cleanup. This means that the effect is never properly unmounted. 

## The Solution

The `bugSolution.js` demonstrates the correct way to use `useEffect`, including a cleanup function to handle component unmounting and preventing potential issues.

## How to reproduce
1. Clone the repository
2. Run `npm install`
3. Run `npm start`