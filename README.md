# CSS Specificity Gotcha: Unexpected Selector Override

This repository demonstrates a subtle bug related to CSS selector specificity.  The bug arises from an unexpected order of CSS rules overriding each other due to specificity.  The `bug.css` file contains the problematic code, while `bugSolution.css` offers a solution.

## Understanding the Bug
The issue stems from the way CSS resolves conflicting styles.  More specific selectors will always take precedence. The main issue is identifying the unexpected precedence given to certain selectors.

## Solution
The solution involves understanding and adjusting CSS selector specificity to ensure the intended styling is applied.