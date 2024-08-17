# comapre-two-strings
# String Equality Checker

[![npm version](https://badge.fury.io/js/compare-two-strings.svg)](https://badge.fury.io/js/compare-two-strings)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A lightweight and simple npm package to check if two strings are identical.

## Installation

You can install the package via npm:

```bash
npm install compare-two-strings
```
Usage
Import the package into your project and use it to check if two strings are the same.

Example

```code
const areStringsEqual = require('string-equality-checker');

const string1 = 'Hello, World!';
const string2 = 'Hello, World!';

if (areStringsEqual(string1, string2)) {
  console.log('The strings are identical.');
} else {
  console.log('The strings are not the same.');
}
```
Function Signature
typescript
```
areStringsEqual(str1: string, str2: string): boolean
str1: The first string to compare.
str2: The second string to compare.
```
Returns: true if the strings are identical, false otherwise.
Why Use This Package?
Lightweight: No dependencies, just a straightforward function.
Easy to Use: A simple API that does exactly what it says.
Reliable: Handles edge cases like case sensitivity and empty strings.
Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue if you find a bug or have a feature request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

