# Missing Error Handling in Express.js POST Request

This repository demonstrates a common error in Express.js applications: the lack of proper error handling for invalid or missing data in POST requests.

## Bug
The `bug.js` file contains an Express.js application that handles POST requests to the `/user` endpoint.  It lacks error handling for cases where the request body is missing or contains invalid data.  This can lead to unexpected behavior or crashes.

## Solution
The `bugSolution.js` file provides a corrected version of the application.  It includes comprehensive error handling to validate the request body and gracefully handle errors.