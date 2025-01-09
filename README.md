# Next.js 15 Module Import Error

This repository demonstrates a bug in Next.js 15 where importing modules from the `pages` directory results in a `Cannot find module` error.  This issue only appears after upgrading from Next.js 14.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Attempt to run the application using `npm run dev`.

## Expected Behavior

The application should start without any errors, and the text "Hello world!" should be displayed in the browser.

## Actual Behavior

The application fails to start, and an error is thrown indicating that the `pages/index.js` module cannot be found.

## Solution

The solution involves updating the Next.js configuration (see `bugSolution.js`) and potentially other adjustments depending on your project structure and dependencies.  Ensure you consult Next.js documentation for the most up-to-date best practices and configuration options.