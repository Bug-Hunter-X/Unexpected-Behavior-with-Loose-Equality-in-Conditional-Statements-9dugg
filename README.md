# JavaScript Loose Equality Bug
This repository demonstrates a common JavaScript bug related to loose equality (==) in conditional statements. Loose equality can lead to unexpected behavior when comparing values of different types. 

## Bug Description
The provided code uses loose equality (==) to check for null values. While seemingly correct, it can lead to unexpected results due to JavaScript's type coercion. 

## How to Reproduce
Clone this repository and run `bug.js`.  Observe the output, which highlights the unintended behavior caused by loose equality.

## Solution
The solution demonstrates using strict equality (===) to avoid type coercion and ensure accurate comparisons. 

## Contributing
Feel free to contribute improvements or report other related issues.