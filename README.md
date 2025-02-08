# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications where an infinite rendering loop occurs due to a missing dependency in the `useEffect` hook.  The `useEffect` hook is incorrectly used without specifying dependencies which should explicitly defined in the second argument to `useEffect` hook, causing it to re-run on every render, leading to an infinite loop and likely a crashing app.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary packages.
4. Run `npm start` to start the development server.
5. Observe the console log and the infinite rendering.