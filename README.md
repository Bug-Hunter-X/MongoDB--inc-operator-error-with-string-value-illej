# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment a numerical field in a document. However, if a string value is provided instead of a number, the update will fail silently and produce incorrect results.

## Bug

The original code attempts to increment a field named `field` by the string value 'value'.  This is incorrect and leads to unexpected behavior.

## Solution

The solution corrects the update query by providing a numerical value to the `$inc` operator. This ensures the field is incremented correctly.
