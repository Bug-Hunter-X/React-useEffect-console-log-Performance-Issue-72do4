# React useEffect console.log Performance Issue
This repository demonstrates a common performance issue in React applications related to logging within the useEffect hook.  The `bug.js` file contains code that incorrectly logs the current count during every render. This can cause unnecessary re-renders and negatively impact the performance of the application, especially when the count updates frequently. The `bugSolution.js` file provides a corrected version that improves performance by avoiding excessive logging.

## How to reproduce:
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the console logs and performance.