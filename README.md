# Tailwind CSS @apply Directive Bug

This repository demonstrates a bug where Tailwind CSS's `@apply` directive fails to apply styles correctly when used with complex class names. This can occur when class names contain spaces, special characters, or are generated dynamically.

## Bug Description
The `@apply` directive does not correctly parse and apply styles from a class name if the name is too complex.

## Reproduction Steps
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the styling is not applied as expected due to a problem with the `@apply` directive.
4. Open `bugSolution.html` to see how to resolve the issue.

## Solution
The solution involves using a simpler and more straightforward class name or avoiding using `@apply` altogether. In this example, the preferred solution is to write out the styles directly rather than trying to use `@apply` with a complex name.