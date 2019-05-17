\textit{Formatting your code to a particular style is super important
Linting can be a little confusing though!
This chapter can cover good practise for stying your code so that others can read and understand it easily.}

Coding Conventions

Styles:
comment
indent
line length

naming
- CamelCase
- lowerCamelCase
- Underscore_Methods
- Kebab-Case
_ Mixed_Case_With_Underscores
- lowercase

Kebab wont work with some languages, such as R and python since this will be interpreted as a subtraction sign. 

Each language has its own best-practice guidelines, and these will be available from the relevant websites.  The purpose of this chapter is to highlight the different ways that code can be structured.

Code formatting

When making code open, it is important to ensure that it is legible and easy to follow.

Much like writing prose, there are a number of methods available to help make your code clear.  These include use of whitespace, naming, commenting.

Correct naming has a two-fold benefit.  The first is that it allows you to communicate the purpose of a variable or object without additional commenting.  For example participant_data is more informative than df.  It can also let you see the flow of your code or script.  For instance  participant_data_no_outliers <- filter.outliers(participant_data) tells the reader something about the function that the 


The style that you use is down to preference, however it is important to stick to it, and to ensure that your collaborators are using the same style.  Style includes: variable naming; use of whitespace; 

ThisIs Because_Switching 
	betweenDifferent 
	formats is.difficult 
		to read.

Where_as if_you stick_to one_style, your_code will_be easier_to follow!

# Variable Naming
There are a variety of naming styles that you can follow (not all will work with all languages).
The major ones include:
CamelCase

Commenting
Jon Peirce - "Comments are love-letters to your future self".

Linting?

Linting is error checking on the fly - it will check your syntax as you code and will show you where certain errors are, such as mismatched brackets, missing commas etc.

Linting is often indicated using underlining of potential problems (much like a spell checker).  Until all of the underlining has disappeared, the code will not run.  The degree of linting will depend on the Integrated Development Environment that you are using (IDE). 

Whitespace
The functional importance of whitespace depends on the programming language you use, however the importance for accessibility does not.  In langugages like Python, whitespace is used for nesting i.e. loops and if statements are bracketted by white space:

In R

if(x==y){print("Hello world")}

However, adding whitespace to the R version makes the function easier to read:

x = 1
y = 1

if(x == y){

print("Hello world")

}

In Python, there are no brackets, so you need to be aware of how much whitespace is used.

if x == y:
	print "hello world"


Adding whitespace to your

Naming conventions