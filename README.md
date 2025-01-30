# Express.js Unresponsive Server Bug

This repository demonstrates a common error in Express.js applications where the server appears unresponsive because the request handler lacks a response using `res.send()` or `res.end()`.  The server receives requests but doesn't send any response, resulting in hanging requests.  The solution shows how to correctly send responses to resolve this issue.

**Bug:** `bug.js`

**Solution:** `bugSolution.js`