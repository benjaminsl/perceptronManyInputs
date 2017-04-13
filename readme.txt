How the data set should be:
* each line has a new data set

* each line is structed like this:
input1, input2, ..., last_input class 

* the number 999999 on a new line ends the data file

* example:
.5, .6, 1, 1 
.1, .3, 5, 2
999999

* In the example, the inputs on the first line belong to class 1
  and the inputs on the second line belong to class 2.

Make sure to put the number 999 at the end of the data set to end it.
Otherwise, program will get stuck in infinite loop.

WHERE TO SET NUMBER OF INPUTS, THRESHOLD, ETC.
Set number of inputs, threshold, and name of training data file in main.c as macros.
