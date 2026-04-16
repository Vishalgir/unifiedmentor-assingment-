# unifiedmentor-assingment-
By combining these concepts, you have moved from writing simple linear scripts to developing dynamic, modular code. These skills form the essential foundation required for data preprocessing and algorithm development in the "next-generation data science eco-system."

<a id='1'></a><center> <h3 style="background-color:orange; color:white" ><br>Python Basics<br></h3>
# What is your name! print your name! 
# Only use one print function


print('My name is Vishal Gir Goswami')
* `()` <= `Parentheses`
* `''` <= `Single Quotes`
* `""` <= `Double Quotes`
* `\n` <= `New_line `
* `#` <= `Used to comment inside code`
# define variables named as with values: mukesh=7, z=6, rohan=5, longitude=4
mukesh = 7
z = 6
rohan =5 
logitude = 4
# print required variable
# output - 5
print(rohan)
Variable Assignment:
**`Variable_Name = Value`**

Variables Naming Rules:
* `Python is case-senstive` => x=5 is different from X=5 (one is lowe and other is upper case)
* `var name can't start with special character except underscore(_)` => _X = 7 is `valid`, @X = 7 is `invalid`
* `var name can't start with number` => 9X = 7 is `invalid`, X9 = 7 is `valid`
* can't use `keywords` as a variable name
    * 
# **`Declaring a Variable`** <br>

# declare 4 variables with values as: ur_age 21,ur_weight 50.6, ur_first_name = 'Mukesh',ur_last_name = "Manral"
ur_age = 21
ur_weight =  50.6
ur_first_name = 'Mukesh'
ur_last_name = "Manral"
print(f"{ur_first_name} {ur_last_name} is {ur_age} year old")
# **`Data Type(Type of variable)`**
| Name | Type | Description |
| ---- | ---- | ----| 
|Integers | int | Integer number, like 34,-56 ...|
|Float | float | Decimal number, like 3.4,-5.6 ...|
|String| str | Ordered sequence of characters, like 'your name' |
|Boolean |bool |Logical values indicating True or False only |
# print type of ur_age,ur_weight,ur_first_name,ur_last_name variables
print(type(ur_age), type(ur_weight), type(ur_first_name), type(ur_last_name))
# print values of ur_age,ur_weight,ur_first_name,ur_last_name variables
print(ur_age, ur_weight, ur_first_name, ur_last_name)
# make 2 variables with values as: ur_first_name 'Mukesh',ur_last_name'Mukesh' 

# make a variable TrueOrFalse which will have comparison of variables ur_last_name == ur_first_name 

ur_first_name = 'Mukesh'
ur_last_name = 'Mukesh'

TrueOrFalse = ur_last_name == ur_first_name
print("First Name:", ur_first_name)
print("Last Name:", ur_last_name)
print( TrueOrFalse)
# define a variable name "x" and assign value 777 and print it

x = 777
print(x)
* To view some data on screen, python have `print` function
    * Using `print` function we can control view on output screen


`Operators`: Symbols that represent mathematical or logical tasks 

Example:<br>
`700` `+` `77`<br>
* `+` <= Operator
* `700` & `77` <= Operands

# Initialize variables [x,y,z,zz] with values 
# x as 7 =>int ,
# y as 77 =>int, 
# z as 77.7 => float, 
# zz as 'Hi' => string

# **`Arithmetic Operators`**
# add x and z
x = 7
z = 77.7
result = x + z
print(result)
# subtract z and y

z= 77.7
y= 77

result  = z - y
print(result)
# Multiply x and z
result = x*y
print(result)
# Exponent (raise the power or times) x times z
result = x**z
print(result)
# division on x and z
result = x / z

print(result)
`//` => divides and returns integer value of quotient
* It will dump digits after decimal
# floor division(ignores decimal) on x and z (gives quotient)
result1 = x // z
result2 = z // x
print(result1)
print(result2)
# Modulo(gives remainder) on x and z
result1 = x % z
result2 = z % z

print(result1)
print(result2)
# **`Comparison Operators`**
# comapre and see if x is less then z 
# can use '<' symbol

result = x < z
print(result)
result_type = type(x < z)
print(result_type)
* `Bool` => takes two values, either `True` or `False`
# compare and see if x is less then or equall to z
# can use '<=' symbol
result = x <= z
print(result)
# comapre and see if x equall to z
# can use '==' symbol
result = x == z
print(result)
# comapre and see if x is greater than z
# can use '>' symbol

result = x > z
print(result)

# comapre and see if x is greater than or equall to z
# can use '>=' symbol

W = x >= z
print(W)
# comapre and see if x is Not equall to z
# can use '!=' symbol

W = x != z
print(W)
# **`Logical Operators`**
# compare if 108 is equall to 108, 21 is equall to 21 using logical and 
# equall to => '=='
# logical and => and

# in and both condition must be True to get a True

result = (108 == 108) and (21 == 21)

print(result)
# how above condition can give False as output show all those conditions
result = (108 == 21) and (21 == 108)

print(result)
# compare if 108 is equall to 108, 21 is equall to 11 using logical or
# equall to => '=='
# logical or => or

# in or Only one condition need to be True to get a True

result = (108 == 108) or (21 == 21)
print(result)
# this is for you to understand it
(108 == 108) or (21 == 11) or (108 <= 11)

# **`if`--- `else`** => to handle single condition <br>
# **`if`--- `elif`--- `else`** => to handle Multiple condition
`Observe in Python code:` 
* `if` => statement in python
* `else` => statement in python
* `:` => colon => denotes start of if block i.e. any line written after colon belong to if condition
* `....` => see then as indentation i.e. 4 spaces => indentation indicates all code belong to only if and then another indentation indicates code for only else block 
# make variable with value as : money 100000

# see output of money > 2000 

money = 100000

result = money > 2000
print(result)

# assign money variable value of 10000
##### say you have this much ammount in your account

# start of if condition
# if money is greater then 1000 which is data science course free
# if money > 1000 is false i.e. you have less money then 1000 in your account then else will work for now only if is working.

money = 10000
if money > 1000:
    print('which is data science course free.')
else: 
    print('your account then else will work for now only if is working.')    
# take a test_score variable with 80 in it.

# if test_score greater then 80 then print A grade
# elif test_score greater then 60 and less then 80 print B grade
# else print Nothing for you

test_score = 80
if test_score > 80:
    print("A grade")
elif test_score > 60:
    print('B grade')    
else:
    print('nothing for you')    

# **`Python Loops`**
"""
for iterating_variable in sequence:
    statement(s)
"""
for iterating_variable in range(10):
    print(iterating_variable)
# print 'I love sports' 10 times using for loop
for i in range(10):
    print('I love sports')
`10` => `stoping criteria` of, for loop
* `in` => keyword
* `sequence` => on which to itterate
* `:` => colon , start of for loop
`!=` = not equall to => `behaves as a stoping criteria`
# Syntax of while loop
"""
while comparison:
    statements(s)
"""
# while loop

# save 0 in variable number

# print till 10 using while loop
# Start with 1
number = 1


while number <= 10:
    print(number)      
    number = number + 1 
* Initialized variable `number = 0` and then increment it's value in each iteration
* Loop will only continue to run only if value is less than 10
# **`Type of Jump Statements`** <br>
`Break Statement`
`Continue Statement`
# **`Break Statement`**

# example that uses break statement in a for loop

# take range(10) and print 'The number is' + value
# break when num equals 5

# **`Continue Statement`**

# Using same `for loop program` as in Break Statement section above
# Use a continue statement rather than a break statement

# take range(10) and print 'The number is' + value
# continue when num equals 5

for num in range(10):
    if num == 5:
       break 
    print('The number is', num)

print("Loop terminated.")

# **`String Manipulation`**
string_ = '' or "" or """ """

# define a string variable with "We are creating next generation data science eco-system at CollegeRanker"

description = "We are creating next generation data science eco-system at CollegeRanker"
print(description)
# Find length of string including spaces

string_langth = len(description)

print(string_langth)


# Access characters in a string with indexing i.e string[0]

print(description[0])
# Access characters with negative indexing i.e string[-1]

print(description[-1])
# String Slicing
# select string from first to 6th element i.e string[:6]

first_six = description[:6]
print(f"Oringnal: {description}")
print(f"Sliced: '{first_six}'")
# select string from 7th to negative 10th element i.e string[7:-10]

middel_section = description[7:-10]

print(middel_section)
Count of a particular `character` in a string

count_c = description.count('e')
print(count_c)
Count of a particular `sub-string` in a string 
word_count = description.count("science")
print(f"Occurrences of 'science': {word_count}")
Find a substring in string using `find` and `index` function
# .find() => if present it will return starting index, not found then it will return -1
# .index() => if present it will return starting index, not found then it will give error

print(description.find("creating"))
### Checking whether string `startswith` or `endswith` a particular substring or not


print(description.index("creating"))
### Converting string to upper case ###

upper_description = description.upper()
print(upper_description)
### Converting only first character of string to upper case

capitalizaed_text = description.capitalize()
print(capitalizaed_text)
### Checking if string is in lower case or upper case

print(f" Lower case:{description.islower()}")
print(f"Upper case:{description.isupper()}")
### Checking if string is digit, alpabetic, alpha-numeric

score = "100.00"
print(score.isdigit())
name = "CollegeRank"
print(name.isalpha())
user_id = "DataScientist007"
print(user_id.isalnum())

# assign "C++ is easy to learn" to a new_str variable

new_str = "C++ is easy to learn"
print(new_str)
### Replace C++ with Python

update_str = new_str.replace("C++", "python")
print(update_str)
### Use Split function on new_str ###
word_list = new_str.split()
print(word_list)

# **`Python Functions`**
"""
def function_name():
    stetement(s)
"""
# define a function with welcome_message(name) and body 'Welcome to Functions !!!'

def welcome_message(name):
    print(f"Hello {name}, Welcome to Functions !!!")
# call a function with your name
welcome_message("vishal")

* `def` Keyword marking start of function
* `function name` to uniquely identify function
    * `function naming` follows same `rules of writing identifiers`
* `parameters`(arguments) to pass values to a function => totally optional
* `()` paranthesis
* `colon (:)` start of function
* `documentation string`(docstring) describe's what function does => totally optional
* `return statement` returns a value from function => totally optional
* inside colon is `function definition` it should always be present before function call or get an error
# Write a function to add two number which are as 3 and 4
# in total variable store adition of 3 + 4
# print total variable 
def add_number(a, b):
    total = a + b
    print(total)

add_number(3, 4)    

# ***`Positional Arguments`*** 
Most arguments are identified by their position in function call
* Say `print(x,y)` will give different results from `print(y,x)`

What ever sequence is given while defining a function values must be taken in that sequence only
* Otherwise use argument name **`(keyword arguments)`** to take values
* We first define `positional argument` and then `keyword arguments`

## Create substraction_function(small_number,large_number) and return difference between large_number and small_number


def substraction_function(small_number, large_number):
    difference = large_number - small_number
    return difference



# pass arguments in right order

result = substraction_function(15, 50)
print (f"The difference is: {result}")
# always pass arguments using there name(keyword arguments) then order does not matter

print(substraction_function(10,50))

# ***`Scope of Variables`*** means that part of program where we can access particular variable
* `Local Variable` => variables defined inside a function and can be only accessed from inside of that particular function
* `Global Variable` => variables defined outside a function and can be accessed throughout program

Let's define a global variable, `"global_variable"` outside function
* We will return its value using a function `"randome_function"` and see that we would be able to access its value using that function also
#### Observe every output from here onwords #####
# defining a global variable
global_variable = 'variable outside of function'

# defining function
def random_function():
    # accessing variable which is outside of this function
    return global_variable
print(random_function())
`See we can acess the data of golbal variable from Inside of the Function`

# **`=> Let's see what will happen if we try to change value of global variable from Inside of the Function`**
#### Observe every output from here onwords #####
# defining a global variable
global_variable = 'variable outside of function'

# defining function
def random_function():
    # changing value of global variable from inside of the function
    global_variable = 'changing variable outside of function from inside of function'
    # accessing variable which is outside of this function
    return global_variable
print(random_function())
print(global_variable)


