1) 3 will be printed at the console because the variable i starts at 0 and is incremented three times since the length of the prices array is three. The variable i can also be accessed outside of the for loop since it was declared with the var keyword.

2) 150 will be printed at the console. discountedPrice starts at 50 because prices[0] * (1 - 0.5) = 100 * 0.5 = 50. Now i gets incremented. prices[1] * (1 - 0.5) = 200 * 0.5 = 100 which is the new reassigned value for discountedPrice. Then i gets incremented one more time to 2. prices[2] * (1 - 0.5) = 300 * 0.5 = 150 and so discountedPrice is reassigned a new value again but is no longer changed since we exit the for loop.

3) 150 will be printed at the console. finalPrice essentially goes through the same process as discountedPrice. Being assigned a value and then reassigned two more times. It has the same value as discountedPrice since the assignment of finalPrice is just (discountedPrice * 100) / 100 (which basically cancels out and gives us the original value of discountedPrice).

4) [ 50, 100, 150 ] is returned since finalPrice is being pushed into the array during each iteration and finalPrice is initially assigned to 50 ((100 * 0.5) * 100) / 100), reassigned to 100 ((200 * 0.5) * 100) / 100), and finally reassigned to 150 ((300 * 0.5 * 100) / 100). 

5) The code returns an error because i was declared with the let keyword and is, thus, only accessibile within the for loop.

6) The code returns an error because discountedPrice was declared with the let keyword and is, thus, only accessible within the for loop.

7) 150 will be printed at the console since finalPrice goes through the same process as question 3. 

8) [ 50, 100, 150 ] will be returned for the same reason as question 4.

9) The code returns an error because i was declared with the let keyword and is, thus, only accessible within the for loop.

10) 3 is printed to the console since it is assigned the length of the prices array and is never reassigned.

11) [ 50, 100, 150 ] is returned since for each iteration, each element multiplied by 0.5 is being pushed into the discounted array. 

12)  a) student.name
     b) student['Grad Year']
     c) student.greeting()
     d) student['Favorite Teacher'].name
     e) student.courseLoad[0]

13) a) Output is 32 since integers map to their exact string representation and you're appending '3' in front of '2' so you get 32.
    b) Output is 1 because '3' is converted to an integer for the subtraction operation.
    c) Output is 3 because null has 0 as one of its falsy values and so 3 + 0 = 3.
    d) Output is 3null since null is converted into a string and concatenated to '3'.
    e) Output is 4 since true maps to 1 and so 1 + 3 = 4.
    f) Output is 0 because false maps to 0 and one of null's falsy values is 0 so 0 + 0 = 0.
    g) Output is 3undefined since undefined is converted into a string and concatenated to '3'.
    h) Output is NaN because you're doing a mathematical operation on a string and undefined which are both not numbers, thus producing Not-A-Number.

14) a) Output is true since '2' becomes the integer 2.
    b) Output is false since alphabetically, 2 is greater than 1.
    c) Output is true since '2' is becomes an integer.
    d) Output is false since === checks for equal value AND equal type.
    e) Output is false since true becomes 1 and (1 == 2) evaluates to false.
    f) Output is true since Boolean(2) evaluates to true and true === true is true. Boolean(2) is true because if anything with a "value" is passed in, then it is true.

15) == checks for value equality and === checks for value equality AND equal type.

17) modifyArray will return [ 2, 4, 6 ] because for each number in array, newArr pushes the original number multiplied by 2 since the callback function multiplies the current number by 2.

19) 1 4 3 2
