# Unexpected String Concatenation in JavaScript Function

This repository demonstrates a common yet subtle error in JavaScript: unexpected string concatenation due to type coercion.  The `myFunction` is intended to add two numbers, but it concatenates them when one of the inputs is a string.

## Bug
The issue lies in JavaScript's loose typing. When you add a number and a string, JavaScript converts the number to a string and performs string concatenation rather than numerical addition.

## Solution
The solution involves explicit type checking or conversion to ensure both inputs are numbers before performing addition.