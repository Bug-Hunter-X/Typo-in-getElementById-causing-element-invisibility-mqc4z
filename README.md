# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle bug in HTML/JavaScript where a simple typo prevents an element from being hidden as intended. The problem lies in a misspelling of the `getElementById` method used to select a DOM element.

## Bug Description:
The `bug.html` file contains JavaScript code that attempts to hide a div element. However, due to a typo in `getElementByIdx`, the script fails to select the element, resulting in the element remaining visible.

## Solution:
The `bugSolution.html` file corrects the typo in the script, successfully hiding the div element using the correct `getElementById` method.

## Learning Points:
- Pay close attention to detail when writing JavaScript, especially when dealing with DOM manipulation.  Typos can have significant consequences.
- Thorough testing and debugging are essential for finding these kinds of subtle issues.