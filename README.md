# Java-Assignment-005 - Switch it Up

## Part 1: - Tracing the Code
As a new Java developer, you will be required to familiarize yourself with existing code before beginning to develop. That's what this section is about, developing your code tracing skills and familiarizing yourself with parts you may be able to use.
* Scan through all the existing code and note what you have to work with.
    * Method names
    * Variables
* Using Java terminology, break down every piece of the method **convertF2K**.
    * What is the access modifier?
	fahrenheit
    * Is it a class or object method, how do you know?
	class, because it says it is static`
    * What is its return type?
	double
    * What parameters does it require, and what are the parameter(s) datatype(s)?
	It requires fahrenheit, and the conversion of fahrenheitto celsius and the conversion of celsius to kelvin.  They are all double.
    * Describe for me how the body of the method executes (i.e. its flow of execution).
	fahrenheit gets converted to celsius and the celsius gets converted to kelvin.
* Using Java terminology, break down method **getUnitChoice**.
    * What is the access modifier?
	public
    * Is it a class or object method, how do you know?
	String, 
    * What is its return type?
	static
    * What parameters does it require, and what are the parameter(s) datatype(s)?
	C,F,K,Q string
    * Describe for me how the body of the method executes (i.e. its flow of execution).
		Its going to print the 4 options for the user to input and pass that to Scanner class input.
    * How do the format specifiers differ than what you've seen before and what do they do?
		%-4s : %40s - means left justfied, the 4 means the space will be 40 characters wide and the %40 means the space will be 40 characters wide. 

## Part 2: - Implement Missing Method: convertK2F
This Part is aimed at teaching you to use methods and code you have to add new functionality to existing code. In this case you will add the missing conversion method, but you don't need to know math :-)
* Hint: You can use existing methods!

## Part 3: - Switch it Up
Part 3 is all about learning how to use the **switch** conditional statement, or the **enhanced switch** statement. You've learned about **if/else** now you will learn about **switch**.
* Using the provided method and class variables, write a program in the **while** loop of the **main** method that:
    * Requests a temperature Unit to convert from
    * Requests a temperature Unit to convert to
    * Quits the program if Q is entered for either choice
    * Requests the double temperature value to convert
    * Uses a **switch** or **enhanced switch** conditional to call the proper conversion method.
    * Prints out the result as indicated below:

          Result 40.000000°C is 104.000000°F

## Part 4: Pull Request
Part 4, as usual, is repetition of duties you will be doing in industry.
* Make sure to use the Git tab at the bottom of IntelliJ to create a Sprint2023 feature branch
* Commit and Push your running code back to your GitHub account
* Issue a Pull request back to my Java-Assignment-005 repo
* Cut and Paste the Pull request URL into your Canvas assignment to turn it in.
