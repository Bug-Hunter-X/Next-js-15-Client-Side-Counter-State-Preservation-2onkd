# Next.js 15 Client-Side Counter State Preservation

This repository demonstrates a common issue in Next.js applications involving preserving client-side state across page refreshes.  The example uses a simple counter that increments every second.  The challenge is to maintain the counter's value even after the page is refreshed.

## Problem
The provided `about.js` file contains a counter that increments every second using `useEffect` and `setInterval`. However, upon refreshing the page, the counter resets to 0 because the state is lost. 

## Solution
The solution involves using the browser's local storage to persist the counter's value. This approach ensures that the counter's state is retained even after a page refresh.

## Usage
1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open your browser and navigate to `http://localhost:3000/about`.
6. Observe the counter incrementing every second. Refresh the page to see that the counter value is preserved.
