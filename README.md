# CSS Specificity Conflict Bug

This repository demonstrates a common yet often tricky CSS bug related to selector specificity.  The bug highlights how unexpected style overrides can occur due to the cascading nature of CSS and the way that specificity is calculated.

## Bug Description

The `bug.css` file contains CSS rules that conflict due to differing levels of selector specificity. This leads to unexpected styling behaviors that can be difficult to debug without a good understanding of CSS specificity.

## Bug Solution

The `bugSolution.css` file offers a possible solution, demonstrating strategies to manage and resolve the specificity conflicts, such as using more specific selectors or employing the `!important` flag (though the latter should be used sparingly).

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected styling and compare it to the expected behavior (as indicated in comments within the code).
4. Examine `bugSolution.css` to see how the issue can be resolved.