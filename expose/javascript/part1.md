Question 1: values added:  20

Question 2: final result:  20

Question 3: values added:  20

Question 4: We get 'ReferenceError: result is not defined'. Since 'result' is indeed scoped within the if block and  variables declared with let have block scope, meaning they're only accessible within the block they're defined in, it's not accessible outside of the block.

Question 5: We get 'TypeError: Assignment to constant variable'. That's because 'result' is declared as a 'constant', which means its value cannot be reassigned after it's initialized. 

Question 6: Line 13 will not be executed due to the error on line 9. But if it can run, we'll still get an error because result is declared as a 'constant', so it's not accessible outside of the 'if' block.