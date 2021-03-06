---
title: Log a value to the Console
category: Tip
date: '2021-02-27 09:50:00 +7'
topics: JavaScript
---

There are a few ways to log a value to the _Console_, but using object destructuring is the convenient and short one.

```js
const fullName = 'John Doe';

console.log('full name' + fullName);
console.log('full name', fullName);

// Better: use template string
console.log(`full name: ${fullName}`);

// Best: use object destructuring
console.log({ fullName }); // { fullName: 'John Doe' }
```

### See also

-   [Conditional logging in the Console](/conditional-logging-in-the-console.html)
-   [Log a variable in an arrow function](/log-a-variable-in-an-arrow-function.html)
-   [Log a variable to the console using conditional breakpoints](/log-a-variable-to-the-console-using-conditional-breakpoints.html)
-   [Log an array to the Console](/log-an-array-to-the-console.html)
