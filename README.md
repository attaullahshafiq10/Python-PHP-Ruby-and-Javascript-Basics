# Python, PHP, Ruby and Javascript Basics

## Getting Started
Below we will have the patterns for all the main programming concepts in four different languages. To try them out head over the website, repl.it and create a free environment to practice in these languages.

We will follow the process you should always follow when learning a new language:
1. Learn how to print values to the console
2. Learn how to assign variables
3. Conditionals
4. Loops
5. Collections
6. Functions


After these building blocks, you'll be able to begin pushing yourself further and do challenges on websites


## Printing Values to the Console
You will generally interact with a programming language via your command line shell (Bash on mac/linux, cmd/powershell/gitBash on windows). So once you have any of these languages on your computer you'll write files and run them with a command. We can't see what our code is doing visually beyond occasionally printing values to the console to assure us the program is following our instructions.

Table





This is why the first program you always create is, Hello World.

### Javascript (using NodeJS)
```
console.log("Hello World")
```
### Ruby
```
puts "hello world"
```
### Python
```
print("Hello World")
```
### PHP
```<?php

echo "hello world";
?>
```


## Variables
Programming is all about creating dynamic code. There are often values we may not know or may change overtime. Instead of hard coding these values and making our code more rigid we use variables to store and refer to the values in our code.

There are different types of data:
1. Numbers - numerical data that can be used in math expressions
2. Strings - a sequence of letters, text, and symbols usually within quotation marks
3. Booleans - a value that can either represent true or false
4. nothing - the absence of value called null, nil, undefined, etc.

We can store these values in little cubby holes called variables we can then use to refer to the value.

### Javascript (using NodeJS)
```
let myString = "Hello World"
let myNumber = 5
let myBool = true

console.log(myString)
console.log(myNumber)
console.log(myBool)
```
### Ruby
```
my_string = "Hello World"
my_number = 5
my_boolean = true

puts my_string
puts my_number
puts my_boolean
```
### Python
```
my_string = "Hello World"
my_number = 5
my_boolean = True

print(my_string)
print(my_number)
print(my_boolean)
```
### PHP
```
<?php

$my_string = "Hello World";
$my_number = 5;
$my_boolean = true;

echo $my_string;
echo $my_number;
echo $my_boolean;
?>
```
