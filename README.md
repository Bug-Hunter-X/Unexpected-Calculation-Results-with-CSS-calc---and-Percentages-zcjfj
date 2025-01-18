# Unexpected Calculation Results with CSS calc() and Percentages

This repository demonstrates a bug where the `calc()` function in CSS produces unexpected results when combining percentages and other units.  The issue is described in detail below. The `bug.css` file shows the problematic code, and `bugSolution.css` demonstrates a workaround or fix.

**Problem:** The `calc()` function in CSS doesn't always correctly handle calculations involving percentages in combination with other units such as pixels.

**Solution:**  The solution involves restructuring the calculation to avoid ambiguity and ensure accurate results.  See `bugSolution.css` for implementation details.  The specific workaround depends on the exact calculation.