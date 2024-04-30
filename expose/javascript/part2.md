Question 1: This line will print 3 because 'i' will hold the value of the index at the end of the loop, which is equal to the length of the prices array.

Question 2: This line will print 150 because 'discountedPrice' is declared as a 'var', so its scope is not limited to the loop block. And after the last iteration of the loop, 'discountedPrice' is set to the discounted value of the last element of the prices array, which is 300 with a discount of 0.5.

Question 3: This line will print 150 because finalPrice is declared outside of the loop and its scope extends throughout the function. And in the last iteration of the loop, finalPrice is set to the rounded value of the discounted price, which is 150. 

Question 4: The function discountPrices will return an array [50, 100, 150].Explanation: Variable 'discounted' declared with var has function scope, meaning it is accessible throughout the entire function. The function calculates discounted prices for each item in the given 'prices' array by applying the provided 'discount' rate. After rounding each discounted price to two decimal places, it returns an array containing these rounded discounted prices.

Question 5: This line will result in a 'ReferenceError: i is not defined' error. The reason for this error is that i is declared using 'let' within the for loop. So i is scoped to the for loop and is not accessible outside of it.

Question 6: This line will result in a 'ReferenceError: discountedPrice is not defined' error. The reason for this error is that 'discountedPrice' is declared using 'let' within the for loop. So 'discountedPrice' is scoped to the for loop and is not accessible outside of it.

Question 7: This line will print 150 because 'finalPrice' is declared with 'let' within the function scope, which means it's accessible throughout the entire discountPrices function. Thus, after the last iteration, it is set to 150, which represents the rounded discounted price calculated as the original price multiplied by the discount rate.

Question 8: The function will return an array [50, 100, 150]. Despite finalPrice being declared with 'let', it can still be returned from the function because it's within the function scope (declared at beginning of the function). Then the function calculates discounted prices for each item in the given 'prices' array by applying the provided 'discount' rate. Thus, it returns an array containing the rounded discounted prices.

Question 9: This line will result in a 'ReferenceError: i is not defined' error. The reason for this error is that i is declared using 'let' within the for loop. So i is scoped to the for loop and is not accessible outside of it.

Question 10: The line will print 3 because the variable 'length' is declared using 'const' and initialized with the length of the prices array. And its value remains constant throughout the execution of the function.

Question 11: The function will return the array [50, 100, 150]. The reason is even though 'discounted' is declared as 'const', it remains bound to the same array throughout its execution. Elements are added to this array within the for loop, but the binding of 'discounted' to the array itself remains constant. So the function can successfully return it, which is the array of prices after applying the discount.

Question 12: A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]

Question 13: A. '32'
B. 1
C. 3
D. '3null'
E. 4
F. 0
G. '3undefined'
H. NaN

Question 14: A. true
B. false
C. true
D. false
E. false
F. true

Question 15: A strict equality operator === checks the equality without type conversion while different types are converted to numbers by the equality operator ==.

Question 16: Check 'part2-question16.js' file.

Question 17: The result will be [ 2, 4, 6 ]. Explanation: The modifyArray function takes an array and a callback function as parameters. It creates a new array by applying the callback function to each element of the input array. In the case, the doSomething function doubles each element of the input array [1, 2, 3]. Thus, we will get the result [2, 4, 6].

Question 18: Check 'part2-question18.js' file.

Question 19: The output is:
1
4
3
2
Explanation: The code prints 1, then 4. After that, 3 is scheduled to be printed immediately after the current code finishes. Finally, 2 is printed after 1 second.