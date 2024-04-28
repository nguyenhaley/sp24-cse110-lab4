# Part 2:

### Question 1
The value of i, which is 3, will be logged to the console at line 12. This is because 'i' is visible after the loop seeing that it is a global variable. Since there are three elements in 'prices', the for loop will terminate when i = 3. 

### Question 2
The value of discountedPrice, which is 150, will be logged to the console at line 13. This is because since it is declared using 'var' it is a global variable that's visible after the loop. Therefore, before the loop terminated, the last saved value to discountedPrice was 300 * 0.5 = 150.

### Question 3
The value of finalPrice, which is 150, will be logged to the console at line 14. This is because since it is a global variable declared by 'var', before the loop's termination, the last saved value of finalPrice was 150.

### Question 4
The function will return [50, 100, 150]. This is because at the end of each loop iteration, the discounted price is being pushed to 'discounted', therefore, by the end, discounted will return an array with three discounted values.

### Question 5
An error will occur at line 12 because 'i' is not a global variable seeing that it is declared with 'let'. After the termination of the loop, 'i' can no longer be accessed since it is out of scope. 

### Question 6
An error will occur at line 13 because 'discountedPrice' is not a global variable seeing that it is declared with 'let'. Since 'discountedPrice' is declared inside of the for-loop, you cannot access it outside of the loop.

### Question 7
The value of 'finalPrice', which is 150, will be logged to the console at line 14. Since we declared 'finalPrice' in the scope of the function, whatever the last iteration of the loop sets 'finalPrice' to be will be logged (in this case the last 'finalPrice' is 300 * 0.5 = 150).

### Question 8
The function will return [50, 100, 150]. This is because 'discounted' is declared in the scope of the function. This means that despite any changes made in the for-loop (the calculation of discounted prices that are pushed to 'discounted'), the variable will still be accessible.

### Question 9
An error will occur at line 11 because 'i' is declared using 'let' making it not a global variable. Since 'i' can only be accessed within the for-loop scope, it cannot be called outside of the for-loop.

### Question 10
The value of 'length', which is 3, will be logged to the console at line 12. This is because the length of 'prices' is 3 and it won't change since constants are an unchanging variable. 

### Question 11
The function will return [50, 100, 150]. Although 'const' variables are unchanging, in this case, it is a constant reference to an array. This means that you can change individual elements and push items into an already initialized array declared with 'const'. Therefore, at the end of every loop iteration, the value of 'discountedPrice' is pushed into 'discounted' and returned at the end.

### Question 12
A. student.name
B. student["Grad Year"]
C. student.greeting()
D. student["Favorite Teacher"].name
E. student.courseLoad[0]

### Question 13
A. Output: 32. This is given because javascript coerces the 2 into becoming a string so it can then be concatenated with "3".
B. Output: 1. This is given because "-" is an arithmetic operator where it will convert the string into an integer to be able to compute the question arithmetically.
C. Output: 3. This is given because null maps to 0 and 3+0 = 3.  
D. Output: 3null. This is given because since the first value is a string, "null" is read as a string and then concatenated to "3" with the "+" operation.
E. Output: 4. This is given because true maps to 1 and then it is summed up with 3 resulting in the answer 4.
F. Output: 0. This is given because false maps to 0 and null maps to 0 so by summing the two up you end up with 0.
G. Output: 3undefined. Since "3" is a string, the "+" operation will treat "undefined" as a string and concatenate the two together.
H. Output: NaN. Since "-" is an arithmetic operation, and undefined is not a number the result will be NaN which stands for not a number. 

### Question 14
A. Output: true. This is true because "2" is computed as a number and 2 is greater than 1.
B. Output: false. This is false because "2" is not lexicographically less than "12".
C. Output: true. This is true because "2" is computed as a number (since an equality check converts values using numeric conversion) and 2 is equal to 2.
D. Output: false. This is false because "===" represents a strict equality check where type conversion isn't used so anything of different types will immediately return false.
E. Output: false. This is false because since true maps to 1, 1 is not equal to 2 numerically.
F. Output: true. This is true because Boolean(2) would return true seeing that 2 is a non-zero number and true ==== true is true under the strict equality check.

### Question 15
The difference between "==" and "===" is that under "==", operands of different types are converted to numbers while the "===" will check for equality without type conversion. 

### Question 17
The result of modifyArray([1,2,3], doSomething) would be [2,4,6]. The two parameters are [1,2,3] and the function doSomething. Calling the modifyArray function will lead to newArr being created and then returned. In this function, there is a for-loop that will iterate as many times as the length of [1,2,3], where each time the doSomething function will be called and the result will be pushed into newArr. the doSomething function returns the product of the given number and 2, so every element in [1,2,3] will be multiplied by 2 and returned when modifyArray() is called. 

### Question 19
The output of the code is 1, 4, 3, 2. This is because 1 will immediately by logged, and then due to the nature of the setTimeout() function 4 will be logged and then 3 and then 2 (after 1 second).
