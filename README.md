# CSS calc() Unexpected Behavior

This repository demonstrates a common issue encountered when using the `calc()` function in CSS: unexpected results due to operator precedence and unit incompatibility. The `bug.css` file shows code that produces unexpected layout behavior. The `bugSolution.css` file provides corrected code and best practices for avoiding this issue.

## Problem
The `calc()` function, while powerful, can be tricky to use correctly.  Mixing percentages with fixed units or different types of units without proper understanding of precedence can lead to incorrect calculations and unexpected rendering in the browser.

## Solution
Ensure unit consistency when using `calc()`. If mixing units, ensure that proper conversions are applied. Understand operator precedence to control how the expression is evaluated.  Always test your `calc()` expressions thoroughly across different browsers.