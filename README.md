# CSS `calc()` Issue in Nested Elements

This repository demonstrates a subtle bug related to the CSS `calc()` function when used with percentages within nested elements.  The issue arises because the calculation of the percentage-based width of the parent element might not be finalized before the nested element's `calc()` function is executed, leading to incorrect width calculations.

## Reproduction Steps

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Observe the unexpected width of the inner element.

## Solution

The provided solution showcases a workaround to resolve the issue. This might involve using alternative approaches, such as Javascript or a different CSS layout strategy.

## Technologies Used

* HTML
* CSS