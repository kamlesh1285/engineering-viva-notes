Experiment 8: React Counter Application using useState Hook

What is a React Hook?
A special function (introduced in React 16.8) that lets functional components use state and lifecycle features.

What is useState()?
A Hook that adds state to functional components, returning the current value and a setter function.

What is State in React?
Component-specific data that influences rendering and can change over time.

Why is State important?
It enables interactive, dynamic UIs by storing values that cause re-render when updated.

What is event handling in React?
Handling user actions by passing event handlers (functions) to elements in JSX, e.g., onClick.

What is setState?
In class components, setState updates component state; in hooks, setter functions from useState update state.

What is setCount()?
The setter function returned by useState for updating a count state variable.

What is a Functional Component?
A React component defined as a function that may use hooks and returns JSX.

How does React update the UI?
React re-renders components when state or props change, diffs the Virtual DOM, and applies minimal DOM updates.

What is dynamic rendering?
Generating UI output that reflects changing data or user interactions.

What happens when state changes?
The component re-renders (and children as needed), React computes differences, and updates the real DOM.

What is a React event?
A synthetic wrapper around native browser events provided uniformly by React (e.g., onClick).

What is JSX?
(See above) — JavaScript syntax for describing UI structure.

Difference between Props and State?
(See above) — Props: external/immutable; State: internal/mutable.

Why is useState used?
To store and update component-local state so UI can respond to changes. 