# Binary Search Package

This npm package provides a simple implementation of the binary search algorithm.

## Installation

To install this package, run the following command:

npm install binary-search-package

## Usage

After installing the package, you can import and use the binary search function as follows:

```javascript
const { binarySearch } = require('binary-search-package');

const sortedArray = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
const target = 5;

const index = binarySearch(sortedArray, target);

console.log(index); // Output: 4
```

## Function

`binarySearch(arr, target)`
- Description: Searches for the `target` value in a sorted array `arr` and returns its index. If the `target` is not found, it returns `-1`.
- Parameters:
 `arr` (Array): The sorted array to search in.
 `target` (Number): The value to search for.
- Returns: `Number`: The index of the `target` in the array or `-1` if not found.
