# Part 1: Answers

1. Prints the value of `prices.length` to the console.
   1. This is because `var i` is a function variable, so it will remain after the `for` loop.
2. Prints the last assignment to `discountedPrice` to the console.
   1. This is because `var discountedPrice` is a function variable, and will remain after the `for` loop.
3. Prints the last assignment to `finalPrice` to the console.
   1. This is because `var finalPrice` is a function variable which is reassigned throughout the `for` loop.
4. The function will return the array: `[50, 100, 150]`.
   1. The function will iterate if the prices given.
   2. Each price is multiplide by 0.5, then rounded by `(value * 100)/100;
   3. The new `finalPrice` is pushed into the return array.
5. The line will cause an Error because the value of `i` is out of the scope as it is only visible inside of its `for` loop.
6. The line will cause an Error because the value of `discountedPrice` is out of the scope as it is only visible inside of its `for` loop.
7. The line will print the last assignment for the value of `finalPrice`, this is because the value is assigned inside the scope of the function which also where is it being referenced.
8. Assuming the `console.log` errors don't get in the way, the function will return the array, `[50, 100, 150]`.
   1. The function will iterate over the prices and give them their proper discounts.
   2. Each discounted price will be added to an array that will be returned.
9. The line will cause an Error because the value of `i` is out of the scope as it is only visible inside of its `for` loop. This will also cause issues in terms of scope as the `console.log` command is out of the scope of the `for` loop.
10. This will cause an error as the `const` type does not allow reassignments of its value. This will also cause issues in terms of scope as the `console.log` command is out of the scope of the `for` loop.
11. There will be no scope issues as the value and print command are assigned and called within the function scope, thus the value of `finalPrice` that should be printed is `0`.
12. Due to both scoping errors and `const` value errors, the function will not be able to return anything.
13. Accessing JSON
    1. `student["name"];`
    2. `student["Grad Year"];`
    3. `student.greeting();`
    4. `student["Favorite Teacher"]["name"]`
    5. `student["courseLoad"][0]`
14. Arithmetic
    1. '32'
       1. Appends the value 2 to the string '3'.
    2. 1
       1. Subtraction of 3 - 1, converted strings to numbers.
    3. 3
       1. 3 + 0 (null becomes 0).
    4. 3null
       1. Append null to string, '3'.
    5. 4
       1. Add the value 1 (true) to 3.
    6. 0
       1. Add the value 0 (false) + 0 (null).
    7. '3undefined'
       1. Append undefined to string, "3".
    8. NaN
       1. Not good arithmetic.
15. Comparison
    1. true
       1. Compares integers, numeric conversion.
    2. false
       1. Compares strings.
    3. true
       1. Compares integers, numeric conversion.
    4. false
       1. Equality check without conversion.
    5. false
       1. true (1) != 2, thus false.
    6. true
       1. Boolean(2) returns true, thus true.
16. The `==` logic checks with conversions, the `===` does not check for equality with conversions.
17. Due to Boolean Conversion, the value `Boolean(2)` returns true as it meets the requirements for returning true.
18. See: `part1/part1-question18.js`
19. The returned value will be: `[ 6, 8, 10 ]`. This is because the function iterates over the given array, for each index, the function runs the given callback method: doSomething, which returns the value `(value + 2) * 2`. This is done through the process of the callback doSomething running the callback on the value: `value + 2` which is then doubled. This value is added to the array, `newArr` which then returned onced the for loop ends.
20. See: `part1/part1-question20.js`
21. Below is the ouput due to `setTimeout`.

~~~text
1
4
3
2
~~~
