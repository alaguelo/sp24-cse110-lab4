1. At line 12, the code will print the number 3. This is because i is declared as a var within the for loop, and the loop increments the length of the array updating i. The code can recognize it later since i is declared as a var.
2. At line 13, the code will print the last discounted price that was calculated in the for loop. This is because discountedPrice was declared as a var, so the code can still recognize it later.
3. At line 14, the code will print the last finalPrice that was calculated in the for loop. This is because finalPrice was declared in the beginning as a var, so the code can still recognize it later.
4. The function will return an array displaying the correct discounted prices for each price in the prices array. This is because when the variables are declared as var, when they are calculated in the for loop, they can always be accessed and updated correctly.
5. At line 12, the code will error. This is because when it tries to print i, i is a variable that seems to never be declared. Using let in the for loop, it stays within that for loop's scope.
6. At line 13, the code will error. This is because when it tries to print discountedPrice, that is a variable that seems to never be declared. Using let in the for loop, discountedPrice stays within the for loop's scope.
7. At line 14, the code will print 150/the last final price calculated in the for loop. This is because finalPrice was declared within the function's scope, and when the function tries to print it later, the variable is found within the same scope.
8. This function will return an array displaying the correct discounted prices for each price in the prices array. When the variables are declared using let, the function is still written in a way where the variables are updated correctly during calculations.
9. Line 11 will cause an error. This is because i was declared using let, meaning it is only within the block scope of that for loop. When the code tries to print i later on, it cannot find it because it is not defined.
10. At line 12, the code will print out 3. This is because earlier, the length was declared as a const variable of the length of the prices array, which is 3.
11. This function will correctly return an array of the discounted prices. This is because all of the variables are declared in a way that allows the function to run correctly. Specifically, in line 7, though it is a const, that variable is declared a const for every new block scope created by the for loop, so it is fine.
12. Given object
    1.  To access the value of the name property, I can use student.name or student["name"], and can print it using the console.
    2.  To access the value of the Grad Year property, I can use student["Grad Year"], and can print that using the console.
    3.  To call the function for the greeting property in the student object, I would do student.greeting(). This would print out the greeting to the console.
    4.  To access the name property of the the object in the Favorite Teacher property in student, you can use either dot or bracket notation. I could do student["Favorite Teacher"]["name"] or student["Favorite Teacher"].name, and can print both of those out.
    5. To access index zero in the array of the courseLoad property of the student object, I would use student.courseLoad[0] or student["courseLoad"][0].
 13. Arithmetic
     1.  '3' + 2 = 32. This is because integers map to their exact string representation.
     2.  '3' - 2 = 1. This is because when js does subtraction it tires to convert the string into an integer to complete the operation.
     3.  3 + null = 3. This is because js would treat null here as 0.
     4.  '3' + null = 3null. This is because js would treat null here as a string, doing string concatenation.
     5.  true + 3 = 4. This is because js would treat true here as its numerical value of 1. 
     6.  false + null = 0. This is because js would treat both as numerical values of 0.
     7.  '3' + undefinded = 3undefined. This is because js would treat undefined as a string, doing string concatenation.
     8.  '3' - undefined = NaN. This is because js is doing subtraction and would try to treat 3 as a number and undefined as a number, but undefined is not a numeber.
 14. Comparison
     1.  '2' > 1 = true. This is because js would treat this as a math operation, and consider 2 as its numerical value.
     2.  '2' < '12' = false. This is because js would compare these strings in order, first comparing 2 and 1 and finding that 2 is not lexicographically less than 1.
     3.  2 == '2' = true. This is because js uses == as a numerical comparison, which is true in this case.
     4.  2 === '2' = false. This is because js uses === as a strict comparison, and in this case they are not the same type.
     5.  true == 2 = false. This is because js would compare true as a number/1, and 1 is not equal to 2.
     6.  true === Boolean(2) = true. This is because js compares the type, and they are both true booleans since Boolean(any non-zero num) is true.
 15. Difference between == and ===: The difference between these operators is that the === is a strict equality check. The first == can perform type conversions and then check values, while === strcitly checks equality without doing any type conversions, so they must be the same type to come back as equal.
 16. In js file
 17. If the function is called with parameters modifyArray([1,2,3], doSomething), the result will be a new array with doubled values. I know this because modifyArray takes an array, and uses the doSomething function within its modification. When modifyArray takes in an array, for each value in that array, the value will be passed through the doSomething function, then returned as doubled and then pushed into the newArr.
 18. in js file
 19. The output of the code above is a list of numbers in the order of 1, 4, 3, 2. This is because the function has a timer for logging 2 a second after running, and 3 has a timer with no time, but still can have a delay. So, what happpens is 1 prints first, 4 prints immediately after, 3 should print also but can be slightly delayed, then 2 prints after everything.