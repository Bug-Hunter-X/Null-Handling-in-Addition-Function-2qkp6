# JavaScript Null Handling Bug

This repository demonstrates a common JavaScript bug related to unexpected null handling in an addition function.

## Description
The `foo` function is supposed to add two numbers. However, it returns `null` if either input is `null`. This might lead to unexpected behavior if the function is used with values that might be null.