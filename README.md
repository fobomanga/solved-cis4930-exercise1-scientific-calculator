Download Link: https://assignmentchef.com/product/solved-cis4930-exercise1-scientific-calculator
<br>
<h1></h1>

In this project students will build a scientific calculator on the command line. The program will display a menu of options which includes several arithmetic operations as well as options to clear the result, display statistics, and exit the program. The project is designed to give students an opportunity to practice looping, type conversion, and data persistence.

Specification

When the program starts it should display a menu, prompt the user to enter a menu option, and read a value:

Current Result: 0.0

Calculator Menu

—————

<ol>

 <li>Exit Program</li>

 <li>Addition</li>

 <li>Subtraction</li>

 <li>Multiplication</li>

 <li>Division</li>

 <li>Exponentiation</li>

 <li>Logarithm</li>

 <li>Display Average</li>

</ol>




Enter Menu Selection: <strong>1</strong>




If an option with operands (1-6) is selected, the program should prompt for and read <strong><u>double</u></strong><u> precision</u> floating point numbers as follows:

Enter first operand: <strong>89.1</strong>

Enter second operand: <strong>42</strong>

Once the two operands have been read, the result should be calculated and displayed, along with the menu:

Current Result: 131.1

Calculator Menu

—————

…Operational Behavior

This calculator includes multiple behaviors that are unique depending on the input and operation specified; they are detailed in this section. Results should be displayed to default precision except where specified.

<u>Exponentiation</u>

For exponentiation, the first operand should be used as the base and the second as the exponent, i.e.:

If the first operand is 2 and the second is 4…           2<sup>4</sup> = 16

<u>Logarithm</u>

For logarithms, the first operand should be used as the base and the second as the yield, i.e.:

If the first operand is 2 and the second is 4…           log<sub>2</sub>4 = 2

<u>Displaying the Average</u>

As the program progresses, it should store the <u>total of all results</u> of calculation and the <u>number of calculations</u>. Note that this does <strong>not</strong> include the starting value of 0! The program should display the average of all calculations as follows:

Sum of calculations: 101.3

Number of calculations: 2

Average of calculations: 50.15

Note that the average calculation should show a maximum of <strong>two</strong> decimal places. The program should immediately prompt the user for the next menu option (<u>without redisplaying the menu</u>).

If no calculations have been performed, this message should be displayed:

Error: no calculations yet to average!

<u>Using Results of Calculation</u>

The program should allow the user to use the previous result in an operation. The user may enter the word “<strong>RESULT</strong>” in place of an operand; if the user does so, the program should replace this operand with the <u>result of</u> <u>the previous calculation</u> (or zero if this is the first calculation):

Enter first operand: <strong>89.1</strong>

Enter second operand: <strong>RESULT</strong>