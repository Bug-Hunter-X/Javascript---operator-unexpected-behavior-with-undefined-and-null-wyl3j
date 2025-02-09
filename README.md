# Javascript + operator unexpected behavior with undefined and null
This repository demonstrates an unusual behavior in Javascript's + operator when dealing with undefined and null values.

The `bug.js` file shows how adding `undefined` to a number results in `NaN`, while adding `null` acts as 0.  This behavior is inconsistent and can lead to unexpected results if not handled properly.

The `bugSolution.js` provides a solution demonstrating how to handle undefined and null values to avoid such issues.