# Unexpected Results with CSS calc() Function

This repository demonstrates a common issue encountered when using the `calc()` function in CSS. The problem arises from the order of calculations and element rendering, which can lead to unexpected results if not handled properly.

The `bug.css` file showcases the problematic code that results in an incorrect layout. The `bugSolution.css` file provides a solution to the problem. The solution involves ensuring the parent element's width is correctly calculated before using it in the `calc()` function, and using appropriate units to avoid unexpected behavior. 