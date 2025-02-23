# Express.js Route Handler Error: Missing Input Validation

This repository demonstrates a common error in Express.js route handlers: the lack of input validation.  The provided code attempts to fetch a user based on an ID provided in the route parameters. However, it fails to handle cases where the ID is not a valid integer, resulting in potential errors and unexpected behavior.

The `bug.js` file contains the buggy code, and `bugSolution.js` demonstrates the corrected version with proper input validation and error handling.