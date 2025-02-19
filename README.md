# CSS `calc()` Bug: Incompatible Units

This repository demonstrates an uncommon bug related to the CSS `calc()` function.  The bug arises when subtracting pixel values from percentage values within the `calc()` function. This may lead to unexpected width calculations in older browsers or specific contexts. The solution explores workarounds to ensure compatibility across different browsers and situations.

## Bug Description

The `calc()` function in CSS is powerful for dynamic calculations. However, unexpected results can occur if used incorrectly with incompatible units. The provided example subtracts pixels from a percentage, causing rendering issues in some cases. This problem stems from the browser's inability to directly handle a mix of percentage and pixel units in the subtraction operation.

## Solution

The suggested solution involves using a different approach to achieve the same outcome, ensuring compatibility across various browsers.