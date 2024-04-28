### Question 1
The bug was that when calculating result, the type of result was a string. This means the two inputs num1 and num2 were being concatenated instead of arithmetically summed up.

### Question 2
I would fix the bug by type-casting num1 and num2 to be numbers using the Number() function.
