# JavaScript Loose Equality in Null Checks

This repository demonstrates a common error in JavaScript: the use of loose equality (==) for null checks, leading to unexpected behavior.

## Bug Description
The `foo` function uses loose equality (`==`) to check if `a` or `b` is null. This can lead to unexpected results because `==` performs type coercion, which might not always give you the desired outcome.

## Bug Solution
The solution is to use strict equality (`===`) to check for null and undefined values. Strict equality (`===`) does not perform type coercion, ensuring a precise comparison.

## How to reproduce

1. Clone the repository.
2. Open the `bug.js` file.
3. Run the test cases in the file.