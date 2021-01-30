## Part 1 

1. Line 11 would print out the length of the input `prices`. The for loop updates the variable `i` till it reaches the value `prices.length`, at which point the loop terminates. Also, we used the keyword `var` while declaring the variable, hence we can access it at line 11. 
2. Line 12 would print out the discounted price which hasn't been rounded to the nearest cent, for the last element of the list `prices`. This is because the variable `discountedPrice` gets updated for every `i` and the last time the loop runs, it refers to the last element of `prices`. Also, we used the keyword `var` while declaring the variable, hence we can access it at line 12. 
3. Line 12 would print out the discounted price which has been rounded to the nearest cent, for the last element of the list `prices`. This is because the variable `finalPrice` gets updated for every `i` and the last time the loop runs, it refers to the last element of `prices`. Also, we used the keyword `var` while declaring the variable, hence we can access it at line 13. 
4. The function would return `[50, 100, 150]`. The for-loop goes over each element of the given list and computes the discounted price and rounds it off for each element of the list. This is added to the list `discounted ` and returned.
5. We would get a ReferenceError mentionting that `i` is not defined. This happens because `i` was declared using the keyword `let` in the loop and is thus not accessible outside the for-loop.
6. We would get a ReferenceError mentionting that `discountePrice` is not defined. This happens because `discountePrice` was declared using the keyword `let` inside the for-loop and is thus not accessible outside the for-loop.
7. Line 12 would print out the discounted price which has been rounded to the nearest cent, for the last element of the list `prices`. This is because the variable `finalPrice` gets updated for every `i` and the last time the loop runs, it refers to the last element of `prices`. Also, the variable is accessible at line 13 because it was declared outside the loop in the same block.
8. Disregarding the errors caused in lines 11 and 12, the function would return `[50, 100, 150]`. The for-loop goes over each element of the given list and computes the discounted price and rounds it off for each element of the list. This is added to the list `discounted ` and returned.
9. We would get a ReferenceError mentionting that `i` is not defined. This happens because `i` was declared using the keyword `let` in the loop and is thus not accessible outside the for-loop.
10. We would recieve a ReferenceError in line 12 when we try to access the value of `discountedPrice` since it was defined using `const` which does not allow acces outside the for-loop code block.
11. We would get a TypeError because we are trying to reassign a `const` variable in line 7. However, if we assume these errors did not occur and the updations took place, we would get a value similar to Q3 or Q7.
12. The function would return `[50, 100, 150]` if we assume the updations for `finalPrice` were successful. This is because although `dicounted` has been declared as a constant, we are never reassigning it and rather modifying the list it referes to itself by calling some list methods.
13. The notations are:
    A. `student.name`
    B. `student["Grad Year"]`
    C. `student.greeting()`
    D. `student["Favorite Teacher"].name`
    E. `student.courseLoad[0]`
14. The solutions are:
    A. `'32'` -> This happens because `+` is a valid operator for strings and therefore `2` gets converted to a string.
    B. `1` -> `-` is an operator for numbers and therefore `'3'` gets converted to a number.
    C. `3` -> `null` gets converted to 0 numerically
    D. `'3null'` -> `3` is a stirng and `+` is a valid operator for strings. String conversion occurs for `null`
    E. `4` -> A number conversion occurs for `true`. This is because the operator `+` was already valid for the number `3`.
    F. `0` -> Numerical conversion takes place for both `false` and `null`
    G. `'3undefined'` -> `+` is a valid operator for strings and therefore `undefined` undergoes string conversion
    H. `NaN` -> `-` is not a valid operator for strings. Therefore `"3"` and `undefined` undergo number conversion. Since, `undefined` become `NaN` after number conversion, the result 3 - NaN = `NaN`.
15. The solutins are:
    A. `true` -> JavaScript converts strings to numbers when comparing with numbers
    B. `false` -> String comparison in lexicographical ordering takes place since both operands are strings
    C. `true` -> String gets converted to number to get the same type
    D. `false` -> Type conversion does not take place and returns false due to the operands being different type.
    E. `false` -> true gets converted to the value of 0 by automatic conversion
    F. `true` -> `Boolean(2)` evaluates to `true` and since the type and values are the same, the strict equality returns `true`
16. `==` is the equality operator but it allows automatic type conversion of its inputs. For example, `'2' == 2` returns `true`. On the other hand `===` is the strict equality operator and does not allow automatic type conversions. In fact if the inputs are different types, it simply returns `false`. For example, `'2' === 2` evaluates to `false`.
17. The code would print `How are you?`. This is because the first conditon evaluates to false since the numerical conversion of `true` is `1` which is not equal to `2`. The second condition evaluates to `true` since the 2 gets type casted to a Boolean to satisfy the type of expression expected for an `if` statement. We know that `Boolean(2)` evaluates to `true`. Hence we print `How are you?`.
18. Check `/part1/part1-question18.js`
19. The result would be `[6, 8, 10]`. Let us consider the first iterationf of the for-loop in the function `modifyArray`. The statement `callback(array[i], function(x) {return x*2;})` translates to `doSomething(array[i], function(x) {return x*2;})`, which in turn returns the value of calling the function: `function(x) {return x*2;}` on x = `array[i] + 2`. Therefore, what the code essentially does is, it adds 2 to each element of the list and then multiplies the resultant value with 2 and appends it to the `newArr`. It then returns the `newArr`. So, the value returned for a given `array` is `newArr` such that `newArr[i] = (array[i]+2)*2`.
20. Check `\part1\part1-quesion20.js`.
21. The output is:
    
    `1`  

    `4`

    `3`

    `2`
    
