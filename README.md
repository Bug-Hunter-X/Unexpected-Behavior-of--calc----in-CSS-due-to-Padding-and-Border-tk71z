# Unexpected Behavior of `calc()` in CSS due to Padding and Border

This repository demonstrates a common issue encountered when using the `calc()` function in CSS: unexpected results due to unanticipated padding or border effects. The `calc()` function does not automatically account for the padding or border of the parent element, which can lead to miscalculations and layout problems.

## Bug Description
The `bug.css` file contains CSS that attempts to calculate the width of an element using `calc()`. However, because the parent element has padding, the calculation is incorrect, leading to unexpected layout issues. 

## Solution
The `bugSolution.css` file shows a solution to this problem. The solution includes the padding and border of the parent element in the `calc()` calculation, resulting in the correct width.