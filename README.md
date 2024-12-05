# Next.js 15 Hydration Error with Simple Component

This repository demonstrates a hydration error encountered in a Next.js 15 App Directory application when using a seemingly simple component. The error message provided by Next.js is not very informative, making debugging difficult.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the hydration error in the browser console.

## Expected Behavior

The application should render the "Hello" message without any errors.

## Actual Behavior

Next.js throws a hydration error, indicating a mismatch between the server-rendered HTML and the client-side JavaScript.

## Solution

The solution often involves carefully reviewing the component's structure and ensuring that any dynamic data is handled correctly to prevent hydration mismatches.