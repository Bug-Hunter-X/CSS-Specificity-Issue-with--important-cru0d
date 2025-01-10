# CSS Specificity and !important Conflict

This repository demonstrates a subtle issue related to CSS specificity and the `!important` declaration.  The `!important` declaration is commonly used to override styles, but its interaction with specificity can be unpredictable.

The `bug.css` file shows an example where a more specific selector fails to override an `!important` declaration in a less-specific selector.

The `bugSolution.css` file provides a solution to address this issue and illustrates best practices for managing CSS specificity and avoiding the unintended effects of `!important`.