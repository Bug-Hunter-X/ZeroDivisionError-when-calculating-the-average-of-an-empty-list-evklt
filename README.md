# Python: Handling Empty Lists in Average Calculation

This repository demonstrates a common programming error in Python and its solution.  The `bug.py` file shows code that fails when calculating the average of an empty list, resulting in a `ZeroDivisionError`. The `bugSolution.py` file provides a corrected version that gracefully handles empty lists.

## Problem

When calculating the average of a list of numbers, failing to check for an empty list can lead to a `ZeroDivisionError` because the code attempts to divide by zero. 

## Solution

The solution involves adding a check to see if the list is empty before performing the calculation. If the list is empty, a default value (such as 0) is returned.