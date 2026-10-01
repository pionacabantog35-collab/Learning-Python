 Learning-Python

Python Language makes a computer usable.

Language - means for expressing and recording thoughts.

Machine Language - Computer own language

Instruction List - Complete set of known commands.

What makes a Language?

**Alphabet** - set of symbols used to build of a certain language.

**Lexis** - set of words the language offers its users

**Syntax** - set of rules used to determine if a certain string of words forms a valid sentence.

**Semantics** - set of rules determining if a certain phrase makes sense

**Source Code** - program wrien in a high level

**Source File** - the file containing the source code

COMPILATION VS INERPRETATION

**Alphabetically** - program needs to be written in a recognizable script

**Lexically** - programming language has its dictionary and you need to master it

**Syntactically** - each language has its rules and they must be obeyed

**Semantically** - the program has to make sense

Two different ways of transforming a program from a high level programming language into machine learning.


**Compilation** - the resource origram is tanslated once(however, this act must be repeated each time you modify the source code) by getting file (example an exe file) containing the machine code now you can distribute the file worldwide; the program that performs this translation is called compiler or translator.

**Interpretation** - you can translate the source program each time it has to be run.The program performing this kind of transformation is called an interpreter, as it interprets the code every time it is intended to be executed

**WHAT IS PYTHON?**

Python is a widely used, interpreted, object oriented and high level programming language with dynamics semantics, used general purpose programming.

The name of the python programming language comes from an old BBC televesion comedy sketch series called monty python's flying circus.

- created by **Guido van Rossum**

**PYTHON GOALS**
- easy and intuitive

- open source

- understandable

- suitable for everyday tasks

**PYTHON RIVALS**

- **perl** scripting language originally authored by larry wall

- **ruby** scripting language originally authored by yukihiro matsumoto.

**PYTHON 2 VS PYTHON 3**

Python 2 is an older version of teh original python.

Python 3 is the newer version of the language.

**PYTHON IMPLEMENTATIONS**

In addition to python 2 and python 3 there is more than one version of each.

**Cpython** - one of a possible number solutions to the most painful of python traits - lack efficiency. Large and complex mathematical calculations may be easily coded in python but resulting code execution may be extremely time consuming.

**Jython** - j is for java. Imagine a python written in Java instead C. This is useful for example, if you develop large anc complex systems written entirely in java and want to add some python flexibility to them.

**PyPy** - logo is a rebus. It represents a python environment written in python.

**Micropython** - an efficient open source software implementation of python 3 that is optimixed run on microcontrollers.

Function may have an effect and result.

Python functions strongly demand the presence of a pair of **parentheses**.

FUNCTION INVOCATION
CAlling a function strongly so  python can execute it.

<img width="182" height="37" alt="image" src="https://github.com/user-attachments/assets/b18ff755-0e13-43d5-b795-cd7eee92b54c" />

- print = function name
- ("Hello, World!") parentheses + argument
- print("Hello, World!)function invocation.

What happens when python sees function_name(argument)?

1. Python finds the function

If checks whether function_name actually exist

print("Hello")

Python knows print, so it can continue.

After the function finishes, Python foes back to the line after the function invocation and continues running the rest of the program.

EASY WAY TO TEMEMBER:

CALL > CHECK > ENTER > EXECUTE > RETURN

**INSTRUCTIONS**

An instruction is basically a command that tells Python to do something.

Example:

print("The itsy bitsy climed up the watersprout.")

print("Down came the rain and washed the spider out.")

There are two instructions there.

IMPORTANT PYTHON RULE

Normally, **one line = one insruction**

\n = new line

Example

code:

print("Hello\nWorld")

Output:

Hello
World

\ is special
Backlash is called an **escape character**

\n= newline

\\= backlash

\"= double quotation mark

\'= single quotation mark

\t= tab

**Python escape and new line**

<img width="483" height="373" alt="image" src="https://github.com/user-attachments/assets/33926331-5168-476a-bc70-1d77d748b4a8" />


**USING MULTIPLE ARGUMENTS**

about how print() works when you give it more than one argument.

Here, there is one print() function, but it has three arguments:

1. "The itsy bitsy spider"

2. "climbed up"

3. "the watersprout"

The arguments are seperated by **commas**.

<img width="617" height="346" alt="image" src="https://github.com/user-attachments/assets/cb5219a1-d03b-4b22-a17c-7d08785e1755" />

**POSITIONAL ARGUMENTS**

Example:

<img width="202" height="33" alt="image" src="https://github.com/user-attachments/assets/1f2f5086-7819-4ca6-97fb-117ff6889724" />

There are two arguments:
"My name is" → first argument
"Python." → second argument

Python prints them in the same order:

<img width="332" height="347" alt="image" src="https://github.com/user-attachments/assets/0d7bcbfb-05f0-40ea-9a8e-4aaa599a7334" />


**KEYWORD**

<img width="537" height="315" alt="image" src="https://github.com/user-attachments/assets/18106a91-f03b-4723-8c09-806c69669525" />

**sep**
<img width="777" height="285" alt="image" src="https://github.com/user-attachments/assets/17e7cef6-5e99-4059-b226-1f240eaf0ee9" />

<img width="815" height="316" alt="image" src="https://github.com/user-attachments/assets/2be6a794-190d-44d3-a1d0-569ad04a16c6" />

**Literals**

data whose values are determined by the literal iself

Example:
python
print(123)> Python knows exactly what 123 means: 123 There is no guessing involved. 123 represents the number 123 that's why 123 is literal.

What about c?

c could be
- a variable

-a name

Python cannot treat c as a specific value just from the letter itself.

c is not a literal in this context

Example:

c=123
print(c)

- 123 > literal

- c > variable/name

-print(c) > python looks at what value c currently refers to.

<img width="477" height="166" alt="image" src="https://github.com/user-attachments/assets/0e8c95de-5a03-4052-a6f1-5812536125cd" />


"2" > string literal, bec it has quotation marks, python treats it as text.

print("2" + "2")

output 22

2 integer literal 

2 no quotation marks > python treats it as number

For example

print(2 + 2)

output

4

**Integer (int)**

whole number with no decimal/fractional part

-10

-0

-100

**Float(float)**

A number that can have decimal/fractional part.

-10.5
-3.14

Type tells python what kind of data something is.

example

10 > integer
10.5 > float


you can check the type using 

code

print(type(10))

print(type(10.5))

output 

<class "int">

<class "float">


**Float **

number that has decimal point or can be represented using scientific rotation.

example:

2.5

0.4

10.75

**String **

examples:

"Hello"

"Python"

"Arellano"

**Strings** need quotation marks

print("Hello")

string = text > put it inside quotes.


**What if the string itself contains qoutes.**

solution 1 use escape 

<img width="818" height="308" alt="image" src="https://github.com/user-attachments/assets/385debb9-c883-4683-ac6b-0fe56f61ff5d" />

solution 2 python allows strings to be surrounded by "'"

<img width="735" height="317" alt="image" src="https://github.com/user-attachments/assets/e6f865e3-6a3a-4724-9f40-ce918714a0d5" />


**Boolean**

True > Yes/Correct

Flase > No/Incorrect

Example:

<img width="455" height="227" alt="image" src="https://github.com/user-attachments/assets/ace0f961-05ce-4bc4-8459-d964ef5edb7b" />

Because 10 is really greater than 5.

True or FAlse are case-sensitive

Wrong:

print(True)

print(False)

Correct:

print(true)

print(false)

**OPERATORS - DATA MANIPULATION**

Basic operators

Symbol of the programming language which is able on the values.

+ 

-

*

/

//

%

**

Exponentiation    Output      Type
  
print(2 ** 3)       8          int

print(2 ** 3.)     8.0         float

print(2. ** 3)     8.0         float

print(2. ** 3.)    8.0         float

Both operators are integers > integer results

Atleast one operand is a float > float results

**MULTIPLICATION**

* is used for multiplication

print(2 * 3) output 2 x 6

**DIVISION**

A slash sign is a division operator (/)

print(6 / 3) is 2.0

/ = always produce a float

Expression     Result    Type
6 / 3           2.0     float
6 / 3.          2.0     float
6./ 3           2.0     float
6./.3           2.0     float


Integer Division //

// = called integer division

It removes the fractional part by rounding down to the lesser integer.

print(6//3)      2
print(6//3.)     2.0
print(6.//3)     2.0
print(6.//6.)    2.0

rule            normal div     Floor Div
print(6//4)     6 / 4 = 1.5    6 // 4 = 1


Why? bec 1 is the largest integer what is less than or equal to 1.5.


Operators and their priorities

When an expression contains more than one operator python needs to know chich operation to perform first.

print(2 + 3 * 5)

Wrong             Correct      
2 + 3 = 5        3 * 5 = 15
5 * 5 = **25 **      2 + 15 = **17**

Operator priority multiplication hsa higher priority than addition

Higher - Priority list

1. ** - exponent

2. *, /, //, % - multiplication and division

3. +, - -addition/subraction

Operators and their binding

Sometimes operators have the same priority

example:

9% 6% 2%

So python needs another rule to decide which one comes first, binding / asscociativity.

Left sided binding(left to right)

print(9% 6% 2%)

python does: 9 % 6 = 3 then: 3 % 2 = 1
therefore: 1

Exponentiation is different

right sided binding

<img width="382" height="170" alt="image" src="https://github.com/user-attachments/assets/b85a076c-b64a-4801-99b1-678d2db3c879" />

2 ** 3 = 8

2 ** 8 = 256

**List of Priorities**

1     **

2     unary, +, -

3     *,/,//%

4     binary +, -


Example

2 * % 5 both * and % have the same priority python evaluates from left to right.


1st 2 * 3 = 6

2nd 6 % 5 = 1


**Python Variable**

Think of a variable as a box where you can sore information

age = 21

-age > variable name
-21 > value
-= > assigns the value to the variable

<img width="412" height="165" alt="image" src="https://github.com/user-attachments/assets/4eaf7f27-5a88-4849-a353-07d39984125f" />

**Variable naming rules**

-letters : A-Z or a-z

-numbers : 0-9

-underscore : _

Examples:

student1 = "Piona"

student_name = "Piona

studentAge = 21

Rule 1: dont start with a number

Wrong: 10t =50

Correct t50 = 20

Rule 2: case sensitive

age = 21
Age = 25

Rule 3: spaces are not allowed

student name = 21

Rule 4: Dont use keyowrds

- if

- else

- for

- while

- class

- reurn

- true

- false


Basic Syntax

variable_name = value

for example

name = "piona"

age = 21

price = 99.50

sample

var = 1

account_balance = 1000

client_name ="John Doe"

print(var, account_balance, client_name)

print(var)

output 

1 1000 John Doe

1

var = "3.8.5"

print=("Python version: " + var)

output

Python version: 3.8.5

ASsigning a new value to a variable if a variable already exist, you can give it a new value using the assignment operator =.

Example                  Output

var = 1                    1

print(var)


var = 5                    5

print(var)

example                   
           
var = 1                    2(This is called **Incrementing**)
 
var = var + 1

print(var)


= means assignment

== comparison

