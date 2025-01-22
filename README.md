# Unhandled 'error' event in Node.js HTTP server

This repository demonstrates a common error in Node.js HTTP servers: unhandled errors causing server crashes without proper logging. The provided solution showcases best practices for handling such errors gracefully.

## Bug

The `bug.js` file contains a basic HTTP server. However, it lacks error handling, meaning any issues (like network problems) will cause the server to crash silently.

## Solution

The `bugSolution.js` file demonstrates how to handle the 'error' event to prevent crashes and log errors properly, aiding in debugging.

## How to reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `node bug.js` to observe the unhandled error and crash.
4. Run `node bugSolution.js` to see how error handling works correctly.