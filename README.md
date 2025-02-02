# React Native Unhandled JS Exception: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common React Native error and its solution. The error occurs when attempting to access a property of an object that is currently undefined.

## Problem
The `bug.js` file showcases code that attempts to access a property before it has been assigned.  This often happens with asynchronous operations or during component mounting before data has fully loaded.  This results in an `Unhandled JS Exception: Cannot read properties of undefined (reading 'property')`.

## Solution
The `bugSolution.js` file demonstrates several approaches to resolving the issue:

1. **Conditional Rendering:** Check for the existence of the property before attempting to access it.
2. **Default Values:** Assign default values to the state or props that might be undefined.
3. **Asynchronous Handling:** Ensure data has loaded before using it in the component's render method, often using a loading state and conditional rendering.

Feel free to explore both files to understand how to avoid this common issue.