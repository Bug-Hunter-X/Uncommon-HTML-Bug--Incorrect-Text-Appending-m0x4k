# Uncommon HTML Bug: Incorrect Text Appending

This repository demonstrates a subtle bug in appending text to an HTML element using `innerText` and provides a more robust solution.  The `bug.html` file showcases the problem, while `bugSolution.html` offers a corrected implementation.

**Problem:** Incorrectly using `innerText +=` to append text to an existing element can lead to issues in some scenarios. It's generally better to use methods that handle potential issues around existing HTML elements within the target element.

**Solution:** Use `innerHTML` with care or better yet manipulate the DOM using methods such as `appendChild` for better control and predictability.