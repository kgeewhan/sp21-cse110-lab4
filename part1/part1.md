# Part 1. Intro to Javascript  
## Part1a.
1. Line 9 prints `values added: 20`
2. Line 13 prints `final result: 20`
3. Line 9 prints `values added: 20`
4. Line 13 will return an error because the result called by console.log is not defined within the block. 
5. Line 9 will return an error because const prevents result from being reassigned.
6. Similar to question 4, line 13 will return an error because result is not defined within the block.
  
## Part1b.
1. At Line 12, the console will print 3 since the for loop at line 6 will stop when `i < prices.length` where `prices.length = 3`. 
2. At Line 13, the console will print 150. This is because the value of `discountedPrice` changes at every iteration. So we can look at the final iteration where we check `var discountedPrice = prices[2] * (1 - 0.5)`. This is equivalent to `discountedPrice = 300 * (0.5) = 150`.
3. At Line 14, the console will print 150. This is because the value of `finalPrice` changes at every iteration. So we can look at the final iteration where `finalPrice = Math.round(150 * 100) /100`. This is equivalent to `finalPrice = Math.round(150) = 150`.
4. This function will return an array `discounted` of values of `finalPrice` of each iteration. The array will look like this: `[50, 100, 150]`.
5. Line 12 will return an error because `i` is not defined outside of the for loop since we are using `let` to declare the value. Therefore, there will be a reference error.
6. Similar to question 5, Line 13 will return a reference error since `discountedPrice` is only defined within the for loop.
7. At Line 14, the console will print 150. This uses the same explanation as question 3 since `finalPrice` is defined within the block. 
8. Similar to question 4, this function will return an array `discounted` of values of `finalPrice` of each iteration.
9. Line 11 will return an error because similar to question 5, `i` is not defined outside of the for loop since we are using `let`. 
10. Line 12 will print 3 since the value of `length` is defined within the block and has not been reassigned. 
11. Similar to qeustion 4 and 8, this function will return an array `discounted` of values of `discountedPrice`. This does not cause an error because we are not reassigning the value of discounted. We are instead modifying it. 
12. 
    - a) `student.name`
    - b) `student['Grad Year']`
    - c) `student.greeting()`
    - d) `student['Favorite Teacher].name`
    - e) `student.courseLoad[0]`
13. 
    - a) '32'
    - b) 1
    - c) 3
    - d) '3null'
    - e) 4
    - f) 0
    - g) '3undefined'
    - h) NaN
14. 
    - a) true
    - b) false
    - c) true 
    - d) false
    - e) false
    - f) true
15. The difference between the == and === operator is that when you use ===, no type conversion is done. On the other hand, if you use ==, a type conversion happens before the comparison. 
16. part1b-question16.js
17. The result is [ 2, 4, 6 ]. We get this result by calling modifyArray with parameters [1,2,3] and doSomething. When we call this function, it does a callback on `doSomething`. Then we multiply each iteration in `array` by 2 as seen in `doSomething`. 
18. part1b-question18.js
19. 1 4 3 2
