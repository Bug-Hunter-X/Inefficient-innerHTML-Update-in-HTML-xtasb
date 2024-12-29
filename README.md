# Inefficient innerHTML Update

This repository demonstrates a common but inefficient way to update the `innerHTML` property of an HTML element using JavaScript.  Repeatedly appending to `innerHTML` can lead to performance issues, especially in large or complex applications.

## Bug
The `bug.html` file shows incorrect usage of `innerHTML` where we repeatedly append to the existing `innerHTML` which is an inefficient approach.

## Solution
The `bugSolution.html` file shows an improved version using text manipulation, which is more efficient before updating the DOM only once.