# Dart Reduce Method Error with Empty List

This repository demonstrates a common error encountered when using the `reduce()` method in Dart with an empty list. The `reduce()` method requires at least one element to operate correctly.  Attempting to use it on an empty list results in a `RangeError`. This example shows the error and a solution using a conditional check.

## How to reproduce

1. Clone this repository.
2. Run `bug.dart`.
3. Observe the error message.

## Solution

The solution involves checking for an empty list before calling `reduce()`, using a default value if the list is empty.

Refer to `bugSolution.dart` for the corrected code.