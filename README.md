# TypeScript Project with Jest Unit Tests

This TypeScript project demonstrates unit testing using Jest.

## Setup Dependencies

Install TypeScript and Jest as development dependencies:

```bash
npm install --save-dev typescript jest ts-jest @types/jest
```

## Running the Code and Tests

Execute the tests using Jest:

```bash
npm test
```

## Core Functions
This project includes three core functions:
- **merge**: Combines three arrays into a single sorted (ascending) array.
- **mergeTwoSortedArrays**: Merges two ascending sorted arrays into one sorted array.
- **reverse**: Reverses an array without using the built-in `reverse()` function, primarily to convert descending order arrays into ascending order.

## Test Cases
There are two test files associated with the core functions:

- **merge.test.ts**: Contains unit tests for the `merge` function with four test cases:
  1) **Standard merge test**: Ensures that merging two ascending arrays with a descending array produces the correct sorted output.
  2) **Empty arrays test**: Verifies the function handles cases where one or more input arrays are empty.
  3) **Duplicate numbers test**: Checks that the function correctly merges arrays containing duplicate numbers.
  4) **Negative numbers test**: Ensures the function properly handles arrays that include negative numbers.

- **reverse.test.ts**: Contains a single test case verifying that the `reverse` function correctly reverses an array.

This project demonstrates efficient merging and sorting techniques without relying on built-in sorting functions.
