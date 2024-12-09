# Dart Reduce Method and Empty Lists

This example demonstrates a common error encountered when using the `reduce` method in Dart with an empty list.  The `reduce` method requires at least one element in the list to operate correctly. Attempting to use it on an empty list results in a `RangeError`.

The provided code shows both a working example with a non-empty list and an example that throws the error with an empty list. The solution demonstrates a way to handle this gracefully.

## How to fix it

The solution shows how to use a conditional statement to check if the list is empty before calling the `reduce` method. If the list is empty, it returns a default value (0 in this case) to prevent errors.