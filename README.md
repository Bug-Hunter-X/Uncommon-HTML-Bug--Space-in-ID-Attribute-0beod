# Uncommon HTML Bug: Space in ID Attribute

This repository demonstrates a subtle bug that can occur in HTML when a space is included within an element's `id` attribute.

The `getElementById()` method in JavaScript is case-sensitive and does not work correctly when the ID contains spaces.  This can lead to unexpected behavior and errors in your web application.

**Bug:** The `bug.html` file contains a `div` element with an `id` containing a space.  The JavaScript code attempts to access this element using `getElementById()`, which fails because of the space in the ID.

**Solution:** The `bugSolution.html` file demonstrates the correct way to use IDs—without spaces.  This ensures that `getElementById()` works correctly and that your JavaScript code functions as expected.

This example highlights the importance of following HTML best practices and carefully constructing IDs for elements.