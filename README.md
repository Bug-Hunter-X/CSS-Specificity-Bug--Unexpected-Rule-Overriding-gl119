# CSS Specificity Bug: Unexpected Rule Overriding

This repository demonstrates an uncommon CSS bug related to selector specificity.  A seemingly more specific selector is unexpectedly ignored due to the higher specificity of an ID selector.

The `bug.css` file contains the erroneous code.  The `bugSolution.css` file provides a solution.

## Bug Description

The bug involves incorrect style application due to a misunderstanding of CSS specificity.  A more specific selector is being overridden by a less specific selector because of an ID selector's higher specificity. This is a common source of confusion for CSS developers.

## How to Reproduce

1.  Clone this repository.
2.  Open `bug.html` in your browser.
3.  Observe that the inner element does not have the expected width.