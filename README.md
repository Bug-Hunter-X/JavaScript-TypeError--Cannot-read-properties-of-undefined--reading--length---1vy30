# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: a TypeError thrown when attempting to access the 'length' property of an undefined value.

The `bug.js` file contains the erroneous code.  The `bugSolution.js` file provides a corrected version.

The error occurs because the function doesn't explicitly handle the case where the input is undefined.  Accessing the 'length' property of undefined results in the TypeError.

The solution adds a check for undefined, returning a default value (0 in this case) to prevent the error.