## Question 1
The bug was that *num1* and *num2* are of type string. So the "+" operator does string concatination instead of number addition.

## Question 2
I can fix it by casting *num1* and *num2* to numeric type then add 2 numbers.