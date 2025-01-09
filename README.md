# Swift `map()` Unexpected Modification Bug

This repository demonstrates a common misconception regarding the `map()` function in Swift.  Many developers assume `map()` modifies the original array, when in reality it returns a *new* array containing the transformed elements.  The example below highlights this behavior and demonstrates the correct usage.

## Bug

The provided `bug.swift` file contains code that attempts to use `map()` to double the values in an array. However, the code incorrectly assumes that the original array is modified.

## Solution

The `bugSolution.swift` file corrects this by correctly using the returned array from the `map()` function. 

## How to reproduce

1. Clone this repository.
2. Open the project in Xcode.
3. Run the `bug.swift` file to see the unexpected behavior.
4. Run the `bugSolution.swift` file to see the correct behavior.