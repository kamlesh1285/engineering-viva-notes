Experiment 9: Fetching API Data using useEffect in React

What is useEffect()?
A Hook that runs side-effect logic (like data fetching, subscriptions, DOM updates) after render.

What is the purpose of useEffect()?
To perform and manage side effects in functional components and optionally clean them up.

What are side effects in React?
Operations outside pure rendering, e.g., network requests, timers, subscriptions, or manual DOM changes.

What is API fetching?
Requesting data from a remote server (API) over HTTP to use in an application.

What is Fetch API?
A browser API for making network requests that returns Promises (fetch()).

Why is API fetching done inside useEffect()?
To avoid running side effects during render and to control when the fetch runs via the dependency array.

What is a controlled component?
A form input whose value is driven by React state and updated via onChange handlers.

What is form validation?
Checking user input for correctness and completeness before processing or submission.

What is the dependency array in useEffect()?
The second argument to useEffect that lists values; the effect re-runs when any dependency changes.

What is state management?
Organizing and updating application state (local or global) and ensuring consistent UI updates.

What is asynchronous programming?
Writing code that handles operations (like network calls) that complete later without blocking execution, typically using callbacks, Promises, or async/await.

What is JSON data?
Structured text using key-value pairs and arrays for data interchange; commonly used in APIs.

What is an HTTP request?
A message sent by a client to a server using methods like GET, POST to request resources or perform actions.

What is an HTTP response?
The server’s reply containing a status code, headers, and an optional body with requested data.

Difference between useState() and useEffect()?
useState manages component state; useEffect runs side effects in response to render or state/prop changes.