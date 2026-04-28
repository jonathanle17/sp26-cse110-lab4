1. 3
2. 150
3. 150
4. [50, 100, 150]
5. Error because with let, i is only defined in the scope of the for loop.
6. Error because with let, discountedPrice is only defined in the scope of the for loop.
7. 150
8. [50, 100, 150]
9. Error because with let, i is only defined in the scope of the for loop.
10. 3
11. [50, 100, 150]

12a. student.name; 

12b. student['Grad Year'];

12c. student.greeting();

12d. student['Favorite Teacher'].name;

12e. student.courseload[0];

13a. '32', when '+' is used with at least one string, the operator defaults to string concatenation.

13b. 1, '-' only works with numbers.

13c. 3, null is converted to 0 when dealing with numerical operators.

13d. '3null' because '3' is treated as a string so then null is too.

13e. 4, boolean is converted to numbers for math (true = 1).

13f. 0, both false and null are converted to 0 for addition.

13g. '3undefined', undefined is converted into a string since working with a '3' string.

13h. NaN, '-' requires number and any operation with undefined which is NaN results in Nan.

14a. true, '2' is converted into a number for comparison.

14b. false, comparing strings goes character by character so since 2 is greater than 1 in 12, false.

14c. true, == is loose comparison so type conversion can be checked for equality.

14d. false, === checks same value as well as type.

14e. false, under loose comparison, true converted to 1 which is not equal to 2.

14f. true, boolean of any non-zero is true so booleans match.

15. == is loose comparison so just checks for same value (can be type converted). === is strict comparison so requires same value and type.

17. [2, 4, 6], in the for loop, the callback function is called on the i value of the array and then pushed into the new array. In this scenario, the callback multiples the value by 2 so the double of the original array value is pushed into the new array and then returned after the for loop.
