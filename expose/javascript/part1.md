1. values added: 20
2. final result: 20
3. You should not use var because var ignores the block it is defined in. Var can be accessed outside of its block which can lead to leaks if the variable is accessed or changed anywhere else in the function.
4. values added: 20
5. Error because in the if block, result is defined with let so it is confined to that specific block. Outside the block, result was not defined so returns an error.
6. Error because a const variable cannot be changed after declaration.
7. Error because result not defined in the else scope.

