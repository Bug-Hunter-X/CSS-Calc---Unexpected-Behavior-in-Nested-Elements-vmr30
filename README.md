# CSS Calc() Unexpected Behavior in Nested Elements
This repository demonstrates a common issue encountered when using the CSS `calc()` function within nested elements. The problem arises from inconsistencies in operator precedence or unit mismatches, leading to unexpected layout results. The `bug.css` file shows the problematic code, while `bugSolution.css` provides a corrected version.
## Bug Description
The main issue lies in calculating the width of an inner element based on the parent's width using `calc()`. If the parent's width isn't explicitly defined, the calculation might not work as expected, resulting in incorrect rendering.
## Solution
The solution in `bugSolution.css` addresses the issue by ensuring the parent element has its width explicitly set. This allows the `calc()` function to accurately determine the inner element's width.