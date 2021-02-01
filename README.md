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


| Language  | File Extension | run script command  | Pkg Mgr | Dep List  |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Javascript  | .js  | node file.js  | npm  | package.json  |
| Python  | .py  | python file.py  | pip  | requirements.txt  |
| Ruby  | .rb  | ruby file.rb  | Gems  | Gemfile  |
| PHP  | .php  | php file.php  | composer  | composer.json  | 



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
```
<?php

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

## Conditionals
What makes a script useful isn't just being able to outline a sequence of actions but having those actions alter based on the state of the data involved. If statements allow us to ask, is this true? Then choose what our script does based on whether it is true or false.

### Javascript (using NodeJS)
```
let number = 6

if (number > 5){
    console.log(true)
} else {
    console.log(false)
}

```
### Ruby
```
number = 6

if number > 5
    puts true
else
    puts false
end
```
### Python
```
number = 6

if (number > 5):
    print(True)
else:
    print(False)
```
### PHP
```
<?php
$number = 6

if ($number > 5){
    echo true;
} else {
    echo false;
}
?>
```


## Loops
What if you need to repeat a task several times, it would be very tedious to type it over and over again. For this situation, we have loops that will repeat a set of instructions as long as an expression is true and stop once it becomes false.

### Javascript (using NodeJS)
```
let counter = 0

while (count < 10){
    console.log(count)
    count = count + 1
}
```
### Ruby
```
counter = 0

while counter < 10
    puts counter
    counter = counter + 1
end
```
### Python
```
counter = 0

while (counter < 10):
    print(counter)
    counter = counter + 1
```
### PHP
```
<?php
$counter = 0;

while($counter < 10){
    echo counter;
    $counter = $counter + 1
}
?>
```

## Collections
A Collection is a data structure in a language that can hold multiple values. They generally fall into one of two categories.

* An ordered list of values accessibly by a numerical index starting at 0
* A list of values access by a "key" which is usually a string/symbol

| Language  | Using Numerical Index | Using Keys  |
| ------------- | ------------- | ------------- |
| Javascript  | Arrays  | Objects  |
| Python  | List  | Dictionaries  |
| Ruby  | Arrays  | Hashes  |
| PHP  | Arrays  | Associative Arrays  | 
