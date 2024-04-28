# Part 1
## Question 1
The line will print `values added: 20` to the console becuase the add parameter is true and the two values of num1 and num2 are added to form the answer in the result variable.

## Question 2
This line will print `final result: 20` to the console because result is set to 20 in the previous if statement and because var has a function scope, the value for result stays outside of the for loop.

## Question 3
The line will print `values added: 20` to the console becuase the add parameter is true and the two values of num1 and num2 are added to form the answer in the result variable.

## Question 4
This line will return an error as result is not defined in the scope outside of the if statement as it is defined using let which provides the variable with a block scope, restricting its scope to only the inside of the if statement.

## Question 5
This line will return an error as we have defined result using the const keyword, meaning that it cannot be changed. Line 7, however, tries to change the value of result, therefore we will get an error due to this.

## Question 6
This line will return an error as the const keyword has the same scope as the let keyword which is a block scope. Since the result varaible is defined inside of the if statement, and it has a block scope, it cannot be accessed outside of the if statement, therefore line 13 will return an error.