1. The line of code at line 12 will print 3 since var varible can be access anywhere inside the function and the for loop iterate three times.
2. The line of code at line 13 will print 150 since 300 *(1-0.5) and var varible can be access anywhere inside the function.
3. The line of code at line 13 will print 150 since discountedPrice = 150 and Math.round(150*100)/100 = 150.
4. The function will return [ 50, 100, 150 ] since for each prince given in the input, we calculate the price after 50% discount which is half of each input.
5. The line 12 will cause an error since i is a let varible declared inside the for loop, so it cannot be access after the for loop.
6. The line 13 will cause an error since discountPrice is a let varible declared inside the for loop, so it cannot be access after the for loop.
7. The line 14 will print 150. Since finalPrice is declared ar function scope. It saves the last discount price in the input array.
8. The function will return [ 50, 100, 150 ] since the sicounted is declared at functio scope and is edited within the for loop. It saves the 50% discounted price of the input. 
9. The line 11 will cause an error since i is a let varible declared inside the for loop, so it cannot be access after the for loop.
10. The line 12 will print 3 since it is a constant declared in function scope and the length of the input array is 3.
11. The function will return [ 50, 100, 150 ]. The reason is that even discounted is a constant, we do not reasign it to another value. We just keep adding numbers to the value it assigned, so it does not cause any errors.
12. 1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favourite Teacher'].name
    5. student.courseLoad[0]
13. 1. '3' + 2 = '32'  Concatenates '3' and 2 as strings, because one of the operands is a string
    2. '3' - 2 = 1  Subtracts 2 from '3' after converting the string '3' to a number
    3. 3 + null = 3  null is treated as 0 in arithmetic operations
    4. '3' + null = '3null'  Concatenates '3' and null as strings
    5. true + 3 = 4  true is treated as 1 in arithmetic operations
    6. false + null = 0  false and null are both treated as 0 in arithmetic operations
    7. '3' + undefined = '3undefined'  Concatenates '3' and undefined as strings
    8. '3' - undefined = NaN  Cannot perform subtraction with undefined, results in NaN
14. 1. '2' > 1 = true  '2' is converted to a number for comparison, 2 > 1
    2. '2' < '12' = false  String comparison, '2' is greater than '1' in character code
    3. 2 == '2' = true  == allows type coercion, so the string '2' is converted to a number
    4. 2 === '2' = false  === requires both value and type to be equal, 2 is a number and '2' is a string
    5. true == 2 = false  true is treated as 1 in comparison, 1 is not equal to 2
    6. true === Boolean(2) = true  Boolean(2) is true, so both the value and type are equal
15. == checks for equality between two values after performing type coercion, while === checks for strict equality requiring both the value and the type to be equal.
16. In part2-question16.js
17. The modifyArray function takes an array and a callback as arguments. In this case, the array is [1, 2, 3], and the callback is the doSomething function. Inside modifyArray, a new empty array newArr is created. The for loop iterates through each element of the input array. For each element, the callback function is called with the element as an argument, and the result is pushed into the newArr. The doSomething function takes a number as input and returns the number multiplied by 2. After iterating through all elements in the input array, the newArr is returned. In this case, the returned array will be [2, 4, 6], as each element of the input array is doubled.
18. In part2-question18.js
19. 1 4 3 2 are printed.

