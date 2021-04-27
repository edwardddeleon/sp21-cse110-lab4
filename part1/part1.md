1a)
1) values added: 20
2) final result: 20
3) values added: 20
4) error, since let means that result is not in scope since it is only accessible in the block it is defined in
5) error, since it is trying to assign to a constant variable so it will not print anything
6) error, since it is trying to assign to a constant variable so it will not print anything

1b)
1) it prints 3, since var i can be used outside of the scope of the for loop. i increases until it is prices.length, and prices.length is 3 since discountPrices has an array of size 3
2) it prints 150, since prices[2] * (1 - 0.5) = 300 * 0.5 = 150 and var means discountedPrice can be used outside of the loop
3) it prints 150, since on the final loop it would round (150*100)/100 which is just 150 and set it to finalPrice, then printing it
4) it returns [50, 100, 150] because it pushes half of the argument's array values into an array. Since the original is [100, 200, 300], it will be halved and be [50, 100, 150]
5) error, since i is defined using let which means it cannot be used outside of the scope of the for loop
6) error, since discountedPrice is defined using let which means it cannot be used outside of the scope of the for loop
7) 150, since finalPrice is defined in the same scope as where it is called to be printed
8) [50, 100, 150], since discounted can still be edited within the for loop. It pushes 50, 100, 150 (half of the argument array), and then is returned
9) error, since i is not defined as i is defined using let and cannot be used outside of the for loop
10) 3, since prices.length is equal to 3 and cannot be changed
11) [50, 100, 150], since discountedPrice is being calculated and reassigned each time in the for loop. It's correctly calculating half of the original price and then pushing it to discounted. Though discounted is a const, the array values inside discounted can be changed
12)
a) student.name
b) student.["Grad Year"]
c) student.greeting()
d) student.["Favorite Teacher"].name
e) student.courseLoad[0]
13) 
a) 32, integers map to their exact string representation
b) 1, 3 becomes an integer and 2 is subtracted from it
c) 3, null becomes 0 and 3 + 0 is 3
d) 3null, null becomes a string and is appended to 3, making 3null
e) 4, true maps to 1 and 1 + 3 is 4
f) 0, false maps to 0 and null becomes 0, 0 + 0 is 0
g) 3undefined, undefined becomes a string and is appended to 3
h) NaN, undefined becomes NaN since you cannot subtract undefined from 3
14)
a) true, 2 becomes a number and 2 > 1 evaluates to true
b) false, 2 and 12 become a number and 2 < 12 evaluates to false
c) true, 2 becomes a number and 2 is equal to 2 is a true statement
d) false, one 2 is a number and the other 2 is a string, strict type checking means they are not equal
e) false, true maps to 1 and 1 equals 2 is a false statement
f) true, Boolean(x) maps to true unless x = 0, null, undefiend, NaN, or "" and x = 2. true === true
15) == is an equality test, checking if the left side and right side are equal. === checks equality, but without type conversion
16) On part1b-question16.js
17) [2,4,6] is the result. The callback is doSomething which multiplies the value of a num by 2. An array is passed in with [1,2,3] and then the contents are multiplied by 2 in the for loop and put in a new array, newArr which is returned
18) On part1b-question18.js
19) The output is "1 4 3 2", with each space representing a newline. 1 prints, then 4, then 3 prints, then there is a second delay and 2 prints
