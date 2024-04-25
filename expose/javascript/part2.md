12:

    A. 'Sarah'
    B. '2022'
    C. 'Hello!'
    D. 'Thomas Powell'
    E. 'CSE 110'
13. 

    A. 32 because the '3' is a string and '+' operator is treating it as a concatenation
    B. 1 because the '3' is treated as a number and '-' is just the regular subtration operator
    C. 3 because the '3' is a number and null value is just 0
    D. 3null because the '3' is a string so it used the concatenation of '+' operator
    E. 4 because the "true" value becomes 1 so it's an addition operator
    F. 0 because the "false" value becomes 0 and null is also 0
    G. 3undefined because the '3' is a string and it uses the '+' operator as a concatenation
    H. NaN because the '3' is a number, but undefined cannot be changed to a number
14.
    
    A. True because the '2' is changed to a number and it's true that 2 > 1
    B. False because the two variables are strings and for comparison it compares each character so 2 is not less than 1
    C. True because the '2' will be treated as a number, and the two numbers are the same
    D. False because the '===' operator checks for both value and type quality. One is a number and the other is a string so it's false
    E. False because the true will be converted to 1 and it's not equal to 2
    F. True because the Boolean function will return true since is not a zero, and both value and type are the same

15. The difference between "==" and "===" is that "==" is considered an equality operator while "===" is a string equality operator meaning that it doesn't perform type coercion, it compares both values and types, and it will return true if it satisfies both condition false otherwise. The "==" compares two values after converting them to the same type, and it will return true if it satiesfies the condition

17. The function will return a list [2, 4, 6] because at first it calls the the modifyArray function with the correct argument, but the doSomething works as a callback so it is happening asychronoously, and when the program is inside the for loop, it uses the callback value from doSomething so 1 becomes 2 and 2 becomes 4, and 3 becomes 6.

19. 

    1
    4
    3
    2
    