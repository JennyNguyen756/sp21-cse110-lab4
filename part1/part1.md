## Part 1a
1. values added: 20
2. final result: 20
3. values added: 20
4. Error because result is not defined. result was defined in a previous block but since let is a block scope, it wasn't able to be accessed. 
5. Error because you can't reassign result. 
6. Error because it doesn't reach this line of code since there was an error on line 9.
   
## Part 1b
1. 3 will be printed because the prices array contains 3 elements which is the length of the array. Therefore, the for loop will run 3 times, adding 1 to the variable i everytime it finishes a loop. Since i is declared as a var, it has a function scope which will allow it to be changed within the function and 3 is its value at the end of this code snippet.
2. 150 will be printed because in the for loop, the 3rd value in the array, 300 will be multiplied by (1-.5) which is 150 and then assigned to var discountedPrice. Therefore, when we console.log(discountedPrice), the value will be 150. 
3. 150 will be printed because the discountedPrice is 150 (we got this from doing the steps in my question 2 answer) which is then multiplied by 100 and divided by 100 and calls Math.round which still returns 150. THerefore, the finalPrice is 150.
4. This function will return the discounted array, which is [50, 100, 150]. These are the final discounted prices based on the inputs. 
5. Error because let is block scope and therefore i is only initialized in the for loop. The i is not initialized outside of this for loop and therefore cannot be printed.
6. Error because let is block scope and therefore discountedPrice is only initialized in the for loop. The i is not initialized outside of this for loop and therefore cannot be printed.
7. 150 will be printed because finalPrice was initialized at the beginning of the function, before the for loop. Then, it was used within the for loop and the final value assigned to finalPrice was 150 from the input of 300. Therefore, 150 will be printed for finalPrice after the computation of the for loop.
8. This function will return the discounted array, which is [50, 100, 150]. These are the final discounted prices based on the inputs. The discounted array was initialized at the beginning of the function, before the for loop, then it was used within the for loop to push finalPrice into the array. Therefore, the function returns the discounted array which is [50, 100, 150].
9. Error because let is block scope and therefore i is only initialized in the for loop. The i is not initialized outside of this for loop and therefore cannot be printed.
10. 3 will be printed because const length is initialized at the beginning of the function and there are 3 prices inputted which gives prices.length a value of 3. Therefore, when you console.log(length), it equals 3.
11. This function will return the discounted array, which is [50, 100, 150]. These are the final discounted prices based on the inputs. The discounted array was initialized at the beginning of the function, before the for loop, then it was used within the for loop to push discountedPrice into the array. Therefore, the function returns the discounted array which is [50, 100, 150].
    

12. Data Types
A. `student.name`  
B. `student["Grad Year"]`  
C. `student.greeting`  
D. `student["Favorite Teacher"].name`  
E. `student.courseLoad[1]`

13. Arithmetic  
A. "32" This is because 3 is a string and 2 is a number so javascript converts the 2 to a string and puts them together. This is also because the plus sign is string concatenation as well as numeric addition.  
B. 1 because the 3 gets converted to a number and then it is numeric computation which is 3-2 = 1.    
C. 3 because the number 3 gets added by nothing which makes it still 3.  
D. "3null" because the null gets string concatenated using the plus sign.  
E. 4 because true has a value of 1 so its 1+3 which is equal to 4.  
F. 0 because false has a value of 0 and adding null which is 0 would be adding 0 so the output would be 0.  
G. 3undefined because the undefined gets string concatenated using the plus sign.  
H. NaN which means Not a Number because the 3 is a string and trying to subtract undefined gives undefined which becomes NaN.
14. Comparison   
A. true because the string '2' becomes a number 2 and 2 is greater than 1.  
B. false because by comparing the first characters, "2" is greater than "1".   
C. true because the string '2' becomes a number and 2 equals 2.   
D. false because there is no type conversion and since these are two different types, it returns false.  
E. false because true equals 1 and 1 does not equal 2.  
F. true because Boolean(2) returns true which is strictly equal to true. 
15. == is a regular equality operator and === is a strict equality operator. The === checks the equality without type conversion while == does type conversion. 
16. Found in part1b-question16.js
17. The result will be [2, 4, 6]. I arrived at this result because first we call modifyArray([1,2,3], doSomething). Therefore, when you go into modifyArray function, you create a new array and go through the for loop 3 times because the length of the inputted array is 3. Then, you push into the new array, the values of the inputted array * 2 because we call callback which is doSomething in this case which multiplies the input by 2. So for the first element in the inputted array, the value is 1, then it gets multiplied by 2, then its pushed into the new array. This continues for 2 and 3 and therefore the newArr is returned which is [2,4,6].
18. Found in part1b-question18.js
19. Output:  
1  
4  
3  
2