# Part 2
## 1
The bug was taht the "result" variable was of type string, so the two numbers were just getting concatenated.

## 2
I fixed it by casting the "num1" and "num2" variables to numbers so that when they are added, they are added as numbers, therefore making the result a number as well.