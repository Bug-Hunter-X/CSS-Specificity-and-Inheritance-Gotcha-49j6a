# CSS Specificity and Inheritance Gotcha

This repository demonstrates a subtle yet common issue in CSS related to specificity and inheritance. The problem arises from the interaction between the `!important` flag, inheritance, and the cascading order of CSS rules.

## The Bug

The `bug.css` file contains CSS code that showcases the unexpected behavior.  A grandchild element inherits a style from its parent, which is overridden by another rule with `!important`. This can be very confusing for developers who aren't familiar with the nuances of CSS specificity.

## The Solution

The `solution.css` file provides a corrected version of the CSS. The solution shows how to better manage specificity and inheritance. Overuse of the `!important` flag is avoided in favor of a better selector specificity and a more maintainable style.