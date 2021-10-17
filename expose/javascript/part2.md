1. 3 since i is defined with var which can be referenced anywhere within its function with defined value after its declaration
2. 150 since discountedPrice is defined with var which can be referenced anywhere within its function with defined value after its declaration
3. 150 since finalPrice is defined with var which can be referenced anywhere within its function with defined value after its declaration
4. [50, 100, 150] since all variables are refenced in appropriate scope (since they are defined var in function they can be called anywhere in function without error) and the function essentially halves the values of input array since discount is 0.5
5. There will be an error since i is in the scope of the for loop iteration when defined with let, but not in the scope of when called to be printed to console
6. There will be an error since discountedPrice is in the scope of the for loop when defined with let, but not in the scope of when called to be printed to console
7. 150, because though finalPrice is defined with let, it is within the scope of the body of the function, just as when it is called to be printed in the console.
8. [50, 100, 150], all variables are called and defined in its appropriate scope, and the function takes the input array, multiplies it by (1-0.5)=0.5, then multiplies and divides by 100, resulting in an array with half the values of the input array.
9. There will be an error since i is in the scope of the for loop iteration when defined with let, but not in the scope of when called to be printed to console
10. 3 will be printed, since length though defined with const is defined and called in the body and scope of the function and there are no reassigments of length happening.
11. [50, 100, 150] since there is no reassignments happening for const defined variables, and all variables are called in the appropriate scope. although there is modification of the discounted const variable, it is still not a reassignment, so the function returns the expected output of essentially halving the values of the input array.
12.\
a. student.name \
b. student['Grad Year'] \
c. student.greeting() \
d. student['Favorite Teacher'].name \
e. student.courseLoad[0] \
13.\
a. '32'  since adding string and int just concanetates the int to string \
b. 1   since when using - operator between int and numeric string it converts string to int and performs subtraction \
c. 3 since when adding int and null, the null is converted to 0 then we add 0 to int \
d. '3null' since when adding string and null, null is converted to string 'null' and concatenated to the string \
e. 4 since when adding a boolean with int, boolean is converted to corresponding int and then normal addition happens \
f. 0 since when performing adding between boolean and null we convert each to int then continue with normal addition \
g. '3undefined' since adding string with undefined will convert undefined to equivalent in string and concatenate to string \
h. NaN since we cannot perform a subtraction between a string and undefined since when undefined in converted to int (has happens when strings and substraction is involved), it becomes NaN, so the result with essentially be Nan \
14.\
a. true since with comparison, string '2' becomes 2 which is greater than 1 \
b. false since '2' becomes 2 and '12' becomes 12 and 2 is not greater than 12 \
c. true since '2' becomes 2 which is the same as 2 \
d. false since === checks equality without type conversion so since 2 and '2' are difference types we immediately are returned false \
e. false since true is converted to 1 which is not equal to 2 \
f. true since Boolean(2) casts 2 to true which is equal to true \
15. == performs an equality tests with type conversion but === persion equality test without type conversion so triple equal sign is more strict and will return false immediately if the types of what are compared are different.
16. code in part2-question16.js
17. we pass the array [1,2,3] along with the function doSomething that returns the double of the input number both to the function modify array. The function modifyarray then creates a new array called newArr then iterates through all the elements in the input array [1,2,3], and appends to newArr the result of passing each element of [1,2,3] through doSomething. This means each element in newArr is going to be the corresponding element in [1,2,3] but doubled (ie 1x2-> 2, 2x2-> 4, 3*2-> 6), so ultimately when modifyArray returns newArr, the returned array is [2,4,6]
18. code in part2-question18.js
19. 1
    4
    3
    2