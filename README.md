# React useEffect Cleanup Function Issue

This repository demonstrates a common error in React's `useEffect` hook where the cleanup function is not called when the component unmounts, leading to potential memory leaks or unexpected side effects.  The issue stems from incorrectly omitting dependencies in the dependency array.