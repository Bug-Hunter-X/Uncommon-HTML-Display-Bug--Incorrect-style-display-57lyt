# Uncommon HTML Display Bug

This repository demonstrates an uncommon bug related to using the `style.display` property in JavaScript to hide HTML elements.  The bug occurs due to an extra character in the style declaration, causing unexpected behavior in some browsers. This issue highlights the importance of careful attention to detail when working with CSS properties.

## Bug Description
The `bug.html` file contains a div element which is intended to be hidden using JavaScript. However, due to an extra '!' character in the `style.display` assignment,  the element may not hide properly in all browsers, resulting in unexpected visibility.

## Solution
The `solution.html` file demonstrates the corrected approach, using the correct value for hiding the element.