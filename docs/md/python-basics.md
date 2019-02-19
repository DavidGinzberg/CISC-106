# Chapter 2

-
# Topics

- Values, Data Types
- Variables
- Operators, Operands, Precedence
- Expressions
- Assignment Statement
- Reassignment
- Updating Variables
- Input/Output
- Lab/Quiz Demonstration

-
-
# Values

- fundamental things a program manipulates
  - Values are objects (EVERYTHING in Python is an object)

Examples:
```Python
"Knowing where your towel is"
42
4.184
```

-
# Data Types

Data Types - Class - classification of values 

-
### Data Types

`int`  - integers, whole numbers, positive or negative

Examples:  `28196`,  	`-67`,  	`0`

-
### Data Types

`float`  - floating point
 numbers with a decimal point, positive or negative  
Examples: 	`5.15296` , 	`1.75`  
Approximate: ~16 digits accuracy  
Stored in binary representation -  some numbers  are approximate - some exact
Try `1.1 – 1.09` in Python Shell


-
# Data Types

str:  string – enclosed in single, double quote characters
Can use three of same quote character
Triple Quotes can span to next line
Examples:   
"double quotes"
'single quotes work too'
'can put a "double" quote inside of single quotes'
"can put a 'single' quote inside of double quotes"

Each Data types allows certain operations 

-
# Type Conversion

Can use type() to determine type or class  of object 
Can convert values from one type to another

Syntax: `int(<float value>)`
	discards decimal part – doesn’t round
Example:   int(8.999) = 8
Syntax: `int(<string value>)`
converts string_value to an int 
Note: must be an integer inside the quote characters
Example:  int("6") = 6
int("6.78")  displays an error

-
# Type Conversion

Syntax: `float(<int value>)`
converts int_value to a float
Example:   float(89) = 89.0

Syntax: `float(<string value>)`
converts string_value to a float
Note: must be a numeric value inside the quote characters
Example:   float("89") = 89.0

Syntax: `str(<any value>)`
converts value to a string
Example:   str(-45.3) = "-45.3"

-
-
# Variables

variable - name that refers to a value
a variable is also an object
rules for naming your variables:
must start with a letter or underscore  followed by any number of alphanumeric characters (letters, underscores or digits)

variable name - no inherent meaning to computer – symbols
create variable names that are meaningful to you / user
pick a convention and stick with it
	my_name – all lowercase and separate words with underscores
	myName – lower camel case

-
# Keywords

- Words with special meaning in Python (also called [Reserved Words](https://docs.python.org/3/reference/lexical_analysis.html#keywords))
- Don't use keywords for variable names. Almost always causes an error.
Some examples: ```
continue, return, yield, True, False, None, import, pass, if, else, elif, and, or, global
```

