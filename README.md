# CSCI160-CH05-EXERCISES
About Programming Exercises From Java Illuminated Book by Anderson and Franceschi
## Q05_42 Instructions  
Write a program that takes two *ints* as inputs from the keyboard, representing the number of hits and the number of at-bats for a batter.  Then calculate the batter's hitting percentage and check if the hitting percenage is above .300.  If it is, output that player is eligible for the All Stars Game; otherwise, output that the player is not eligible.  
### Q05_42 Test 1  
**Input:**  
30  
35  
**Output:**  
The batting average is 86%  
Batter is eligible for All Stars Game  
### Q05_42 Test 2  
**Input:**  
6    
30    
**Output:**  
The batting average is 20%  
Batter is not eligible for All Stars Game  
## Q05_44 Instructions  
Write a program that calculates the area of the following figures:  
*  a square of side 0.666666667  
* a rectangle of sides 1/9 and 4  
Test the two calculated areas for equality.  
### Q05_44 Test  
**Input:**  
*none*  
**Output:**  
The area of a square of size 0.666666667 is 0.4444444448888889  
The area of a rectangle with sides of  
0.1111111111111111 and 4 is 0.4444444444444444  
The areas are considered equal.  
## Q05_45 Instructions  
Write a program that reads a sentence from the keyboard.  Depending on the last character of the sentence, print a message identifying the sentence as declarative (ends with a period), interrogative (ends with a question mark), exclamatory (ends with an exclamation point), or other.  
### Q05_45 Test 1
**Input:**  
This is your Test 1.   
**Output:**  
The sentence is declarative.  
### Q05_45 Test 2
**Input:**  
How do you feel about Test 2?   
**Output:**  
The sentence is interrogative.  
### Q05_45 Test 3
**Input:**  
Test 3 is sure to be your favorite!    
**Output:**  
The sentence is exclamatory.  
### Q05_45 Test 4
**Input:**  
Something is missing from Test 4      
**Output:**  
Sentence type is unknown.  
## Q05_47 Instructions  
Write a program that takes two words as input from the keyboard, representing a password and the same password again.  (Often, websites ask users to type their password twice when they register to make sure there was no typo the first time around.) Your program should do the following:  
* if both passwords match, then output "You are now registered as a new user"  
* otherwise, output "Sorry, there is a typo in your password"  
### Q05_47 Test 1
**Input:**  
PaSsWoRd    
PaSsWoRd  
**Output:**  
You are now registered as a new user.  
### Q05_47 Test 2
**Input:**  
PaSsWoRd    
pAsSwOrD  
**Output:**  
Sorry, there is a typo in your password.  
## Q05_48 Instructions  
Write a program that takes a word as input from the keyboard, representing a user ID.  (Often, websites place constraints on user IDs.)  Your program should do the following:  
* if the user ID contains between 6 and 10 characters inclusive, then output "Welcome barbara" (assuming *barbara* is the user ID entered)  
* otherwise, output "Sorry, user ID invalid"  
### Q05_48 Test 1
**Input:**  
barbara  
**Output:**  
Welcome, barbara  
### Q05_48 Test 2
**Input:**  
barbaragordon  
**Output:**  
Sorry, user ID is invalid.  
## Q05_50 Instructions  
Write a program that reads a temperature as a whole number from the keyboard and outputs a "probable" season (winter, spring, summer or fall) depending on the temperature.
* If the temperature is greater than or equal to 90, it is probably summer.  
* If the temperature is greater than or equal to 70 and less than 90, it is probably spring.  
* If the temperature is greater than or equal to 50 and less than 70, it is probably fall.  
* If the temperature is less than 50, it is probably winter.  
* If the temperature is greater than 100 or less than -5, then you should output that the temperature entered is outside the valid range.  
### Q05_50 Test 1
**Input:**  
100  
**Output:**  
It is probably summer.   
### Q05_50 Test 2
**Input:**  
80  
**Output:**  
It is probably spring.   
### Q05_50 Test 3
**Input:**  
60    
**Output:**  
It is probably fall.  
### Q05_50 Test 4
**Input:**  
32     
**Output:**  
It is probably winter.  
### Q05_50 Test 5
**Input:**  
-10     
**Output:**  
The temperature is out of range.  
### Q05_50 Test 6
**Input:**  
115       
**Output:**  
The temperature is out of range.  
## Q05_51 Instructions  
Write a program that takes a *String* as an input from the keyboard, representing a year.  Your program should do the following:
* If the year entered has two characters, convert it to an *int*, add 2000 to it and output it.  
* If the year entered has four characters, just convert it to an *int* and output it.  
* If the year entered has neither two nor four characters, output that the year is not valid.  
### Q05_51 Test 1
**Input:**  
12       
**Output:**  
The year is 2012  
### Q05_51 Test 2
**Input:**  
2012       
**Output:**  
The year is 2012  
### Q05_51 Test 3
**Input:**  
300       
**Output:**  
The year is not valid  
