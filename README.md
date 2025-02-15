# CSS calc() Unexpected Behavior with Percentages and Pixels

This repository demonstrates a problem with the CSS `calc()` function when combining percentages and pixel values.  In some situations, the calculation does not produce the expected result, leading to unexpected layout issues.

## Problem Description

The `calc()` function in CSS is used to perform calculations. However, when used to calculate a width based on a percentage minus a fixed pixel value (e.g., `width: calc(50% - 10px);`),  it may not always yield the correct result across different browsers or contexts.  This can lead to unexpected layout issues and inconsistencies.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the width of the element; it may not be exactly 50% minus 10 pixels as expected. 

## Solution

The provided solution offers potential workarounds to resolve this calculation issue depending on the context and desired behavior.