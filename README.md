## What does the yield keyword do?

A yield keyword makes a function a lazy iterable. Producing values one at a time.

The function becomes a generator, so when called the code will not execute.

A generator is a function that uses the yield keyword. This function is an iterable that produces values one at a time, or does a lazy production of values


Uses:

* Reading large amounts of data
* Processing unknown amount of items, like those coming from a database
* Reading data for possibly long periods of time

