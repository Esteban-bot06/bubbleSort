# BubbleSort readme
* **Overview**: This program is about organizing a array of numbers that are in random order by looking into the set of numbers and seeing which of those is the biggest and sending that number to the end of the list, this process repeats itself until theres no numbers left.

* **list of functions**:
	*  Theres gonna need to be a *main()* function where we are going to call the other functions to make the program work, but first it creates the array of the unorganized integers, then with the printf it prints a 'before:' and then it calls the function printValues, then on the test swap piece of code it declares two variables which are x gets 3 and y gets 5, then it prints them after that the swap function changes the value of the variables by using their address then it prints out the values of x and y, then we call the sort function with the values array as the parameter then prints 'after:' and calls the printValues to print out the sorted array of values, and because its a void function it has to return something so it returns zero. 
	* *sorting()* function is where the important process of the program takes place, in this function we are going to organize the array of integers in the program, we are gonna need to declare the variable max which is a constant so it doesnt change and we are gonna make it so it equals 9 becasue that is the max lenght in the values array, after that we declare the function sort() which takes "values[]" as a parameter, we create the variables we are gonna use on the for loops they are the legacy varaibles, we can make it so i gets 0 and j gets 1, on the for loop we call i that already has the value of 0, then we make it run as long as its less or equal to the max - 1 and the same goes for j, in the conditioinal where it  checks if array j is greater than array j+1 that means that in that if statement it checks if the number in array j is bigger than the number to the right and if it is then it calls the swap function to change that number that is greater to the right, and then calls printValues.  
	* *swap()*: this function takes two integer pointers, first we need to create a variable lets call it *ogValue* that variable gets the value of a variable we can call *x* then we assign the addres of *x* to the value of another variable we can call *y*, then we assign the value of *y* to *ogValue* which has the value of x already stored. 
	* we are also gonna need a *printValues()* function so we can print the integers inside the values[] array. 

