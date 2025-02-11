# Node.js Server Hang

This repository demonstrates a common issue in Node.js where a long-running task in a server can cause it to hang and become unresponsive.  The `server.js` file shows the problem, while `serverSolution.js` offers a solution using asynchronous programming.

## Problem

The server uses a `while` loop to simulate a 5-second delay.  During this time, the server is unresponsive to new requests.

## Solution

The solution utilizes asynchronous operations and promises to prevent blocking the event loop. 