1. values added: 20
2. final result: 20
3. values added: 20
4. error result in line 13 is not defined (ie out of scope) since it was defined with let in the scope of if block.
5. there is an error before line 9 since we are reassigning values to result in line 7, but it was declared as a const so that it cannot be reassigned
6. if we ignore the error from line 7, we still would have another error since line 13 references a variable that is defined as const within the scope of an if block, so it is not referenced outside the if block scope.