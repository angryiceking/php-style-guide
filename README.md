Proposing a Standards Recommendation – Developer’s Guide to Basic Coding Standards
Based on PSR-0 to PSR-2

As our server uses PHP 5.3, use of shorthand operators are not available. This document only covers the simplest coding standards that should be used by any developers to make their code base readable and help future developers understand what the code is trying to do.

Proposed Coding Standards

Defining Filename
1.	The filename of the php file should always explain briefly what would be its purpose.
2.	If the file contains a class, the name of the Class should be the same as the file.
3.	Always end with a single blank line.
4.	Closing tag must be omitted from files containing only PHP.

Defining Class Names, Method Names, and Constants.
1.	Files must use only <?php tags
2.	Class names must be declared in StudlyCaps
3.	Class constants must be declared in all upper case with underscore operators.
4.	Method names must be declared in camelCase

Defining a Class Structure
1.	Class name should always have three space after the opening tag.
2.	Method names are always camelCase()
3.	Method names should briefly discuss what their function. Ex: multiplyToTen($num)
4.	Method arguments should be in one line, inside the Method. Ex: camelCase($arg1, $arg2=””)
5.	If having multiple method arguments, each arguments should be separated by space.
6.	Method braces should have their respective line.
7.	Keywords and variables should be always in lowercase. Ex: $num, $text, $array
8.	Code must use an indent of 4 spaces and must not use tabs for indenting.
9.	Comments are recommended and is mandatory in every function that requires deep understanding of the algorithm used.

Conditional Statements
1.	If Else statements should look like this in a PHP file,

if ($expr1) {
    
} elseif ($expr2) {
    
} else {
    
}
2.	Foreach statements should look like this in a PHP file,

foreach ($array as $key => $value) {
    
}

3.	For loop statements should look like this in a PHP file,
for ($i = 0; $i < 10; $i++) {
    
}

4.	Try Catch statements should look like this in a PHP file,
try {

} catch (FirstExceptionType $e) {
    
}

