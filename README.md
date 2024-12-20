# Express.js Route Parameter Handling Bug

This repository demonstrates a common bug in Express.js route parameter handling, where the application fails to correctly handle non-integer parameters.  The bug occurs when the route `/users/:id` receives an invalid `id` value (e.g., a string or special characters).  This results in incorrect data retrieval or even unexpected errors.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides a corrected version that addresses the issue.