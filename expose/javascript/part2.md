# Part 2
## Question 1
Since i is declared using the var keyword, it has function scope. Line 12 is still located within the function, therefore the variable will retain its value. Since i was incremented throguhout the for loop until it was less than prices.length, its value will be that of prices.length. Therefore on line 12, the console will print the value of i at the current time which will be that of prices.length, which is 3. so The console will print `3`.

## Question 2
On line 13, the console wants to print the value of discountedPrice. The discountedPrice variable is declared with the var keyword, therefore it has function scope which means it retains its value throughout the function, so it will print a value. The variable is changed numerous times throughout the for loop, but will retain the final value that is calculated and that value will be printed. The final value that the for loop calculated discountedPrice is when the prices[i] = 300 and the discount = 0.5, so the final value of discountedPrice will be 150. So line 13 will print ot the console `150`.

## Question 3
Since the finalPrice variable is declared with the var keyword inside of the discountedPrices function, its value will be accessable at line 14. It's value is changed through the for loop, so like the discountedPrice variable, we would have to take the last calculation of it which ould be when discountedPrice = 150, which results in finalPrice being 150. This means that line 14 prints `150` to the console.

## Question 4
Discount is defined as an empty array and it is initiated using the var keyword, so its scope includes the whole function. The array is appended with values of integers through the for loop and is then returned at the end. So the function will return an array of the discounted values of the prices array. This function will return the array `[50, 100, 150]`.

## Question 5
Since i is defined using the let keyword, it will have block scope which restricts it' scope to that of the for loop, therefore line 12 will return an error.

## Question 6
Since discountedPrice is defined using the let keyword, it will have block scope which will restrict its scope to that of the inside of the for loop. So line 13 will return an error.

## Question 7
Since finalPrice is defined using the let keyword, it will have block scope, but it it defined outside of the for loop, therefore it is accessible outside of the loop as well. Therefore it will retain its value form the for loop, whcih will be able to access it, and its value will be the last calculated value which will be 150. So line 14 will print to the console `150`.

## Question 8
This functionb will return the value of the discounted variable which contains an array of the discounted prices. The discounted variable is defined using the let keyword, so it contains block scope, but it is defined in a way that it is accessible throughout the function. Therefore the function will return the array of `[50, 100, 150]`.

## Question 9
Since i is defined using the let keyword, it will have block scope which restricts it' scope to that of the for loop, therefore line 11 will return an error.

## Question 10
Since length is defined using the const keyword, it cannot be changed from its initial value. It is initall desclared as prices.length, which in this example is equal to 3. Since the const keyword has a block scope, we are able to access length throguhout the function due to its declaration location. Therefore, line 12 will print to the console `3`.

## Question 11
The discounted variable is declared using the keyword const, which means that the variable cannot be changed. However, we can push elemtns to append to the array and on line 8, we have an attempt to append a value to out discounted variable. Therefore, this funciton should be able to funciton normally and the funcitonw ill return the array `[50, 100, 150]`.

## Question 12
### A
`student.name`
### B
`student["Grad Year"]`
### C
`student.greeting()`
### D
`student["Favorite Teacher"].name`
### E
`student.courseLoad[0]`

## Question 13
### A
`32`, the plus operator concatenates the string "3" with the number "2".
### B
`1`, the minus operator converts the string "3" into the number "3" then subtracts the number "1" from it.
### C
`3`, "null" is converted to "0" then added to the number "3".
### D
`3null`, the plus operator converts "null" to a string and since "3" is already a string, it concatenates both of them.
### E
`4`, "true" is converted to the number "1", then added to the number "3".
### F
`0`, both "false" and "null" are converted to the number "0" then added together.
### G
`3undefined`, since "3" is a string, it converts "undefined" to a string and concatenates both values.
### H
`NaN`, "undefined" is cannot be converted to a number while "3" can but any opertation with NaN results in NaN.

## Question 14
### A
`true`, the string "2" is converted to a number.
### B
`false`, the comparison is done be comparing "2" to "1" as they are both the first characters.
### C
`true`, "2" is converted to a number then comapred.
### D
`false`, the triple equals is strictly equal and both are not the same type so they cannot be strictly equal.
### E
`false`, "true" is converted to "1" and 1 does not equal 2.
### F
`true`, Boolean(2) is "true" because "2" is a non-zero numebr so it will convert to true.

## Question 15
The "==" operator is known as equality and it will perform coercion if the values being compared are not the same type, whereas the "===" operator is known as strictly equality and it will compare the values without performing coercion.

## Question 17
The doSomething fucniton in this case doubles the input that is provided to the function. The modifyArray function ffirst creates a new array (newArr) that holds the values of the changed values of the original array. In this case, this function is doubling every element in the original array and appending it to the new array so the function should return the array `[2, 4, 6]`.

## Question 19
The output of the function will be printing `1` to the console. Then it will schedule `2` to be printed to the console after a 1000ms delay. Next, it will schedule a `3` to be logged after a 0ms delay. Finally a `4` will be logged to the console. The overall result will be `1`, `2`, `3`, `4` to be printed to the console.