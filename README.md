# Incorrect Usage of getElementById in HTML

This repository demonstrates a common yet easily overlooked error when using `getElementById` in HTML.

The `getElementById` method is used to select HTML elements based on their ID.  However, it's crucial to understand that you should not include the '#' symbol when using `getElementById`.

**bug.html** shows the incorrect usage, and **bugSolution.html** provides the correct implementation.

## How to Reproduce the Bug

1. Open `bug.html` in a web browser.
2. Observe that there's a JavaScript error.

## How to Fix the Bug

1. Open `bugSolution.html`
2. Observe how the `getElementById` method is correctly used without the '#'.