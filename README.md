# MongoDB $inc operator type error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB's `updateOne` method. The `$inc` operator expects a numerical value, but in this case, it receives a string, which causes an error.  The solution shows the correct way to increment a counter using `$inc`.

**Bug:** The original code attempts to increment the `count` field by the string '1' instead of the number 1.  This results in an error because the `$inc` operator only works with numbers.