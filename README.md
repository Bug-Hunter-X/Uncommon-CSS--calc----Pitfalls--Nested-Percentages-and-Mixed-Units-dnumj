# Uncommon CSS `calc()` Pitfalls

This repository demonstrates some less common issues that can arise when using the `calc()` function in CSS, specifically concerning nested percentages and the combination of different units.  The `bug.css` file showcases these problems, while `bugSolution.css` offers alternative approaches to achieve the desired layout.

## Issues:

* **Nested Percentages:** Using `calc()` with percentages in nested elements can lead to unexpected results if the percentage is relative to a parent element with a dynamic or restricted width.
* **Mixed Units:** Combining different units like `vw`, `em`, `px`, etc., within a single `calc()` expression can result in inconsistent behavior across different browsers and screen sizes.

## Solutions:

The `bugSolution.css` file offers alternative approaches to avoid these problems, often involving using absolute units or restructuring the CSS to eliminate nested percentage calculations.

This example highlights the importance of careful consideration when using `calc()`, especially in complex layouts or when mixing units.