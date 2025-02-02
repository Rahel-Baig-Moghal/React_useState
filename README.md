# Counter App

This is a simple counter application built with React.

## Features

- Increment the counter
- Decrement the counter

## Prerequisites

- Node.js
- npm or yarn

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/counter-app.git

## Code Explanation

The code consists of a simple React component that uses the `useState` hook to manage the counter state.

```javascript
import React, { useState } from "react";

function App() {
  const [count, setCount] = useState(0);

  function increase() {
    setCount(count + 1);
  }

  function decrease() {
    setCount(count - 1);
  }

  return (
    <div className="container">
      <h1>{count}</h1>
      <button onClick={increase}>+</button>
      <button onClick={decrease}>-</button>
    </div>
  );
}

export default App;
```

- `useState(0)`: Initializes the `count` state variable to `0`.
- `increase`: Increments the `count` by 1.
- `decrease`: Decrements the `count` by 1.
- The `App` component renders the current `count` and two buttons to increase and decrease the counter.

## Contributing

If you want to contribute to this project, feel free to submit a pull request or open an issue.

