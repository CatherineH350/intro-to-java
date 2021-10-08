Java file = All of our code 

.md file = Text, definitions, etc 
## Intro to Java
A Java program can be characterized as an **object**  represented in a **class**. Currently our program has a *main* object. Inside of this object, we have the *main* class. 

## Output
In Java, to output an item to the console we use two different statements:`System.out.print()` and `System.out.println()`

`System.out.println()` prints the statement and moves to the next line, while `System.out.print()` will just print out the statment.

## Comments 

A comment is used as user annotation with the purpose of being human readable. 

**Line comments** follow double backslashes `//` 

**Block Comments** are contained within `/* Comments*/`

## Identifier

In Java use the term **identifier** to describe a variable, parameter, or constant, user-defined method or user-defined class.

- Cannot begin with digit
- Can only contain letters, digits, and underscores
- Case-sensitive `age != Age`

*Note: *
- class names starts with a capital letter 
- reserved words are entirely lowercase and may not be used as identifiers
_(reserved words will show up in blue; final; int; char; they may not be used as identifiers or it will show up as an error)_


## Types
**Primitive** or **built-in** types in Java are
- `int` (an integer)

*Note: *Integers have a fixed amount of memory so there is a limit to  how many digits you can store (2^31 - 1)

- `boolean` (true/false) `boolean shirtColor = true` (true/false must be lowercase)
- `double` (floating-point number like 2.73 - float in python)
- `char` (single character)

## Variables
Variables are a type of identifier that stores a value of a specific type 

In opposed to Python, you do not have to declare the value of a variable in Java. You can just note the type, the identifier, and of course the semicolon

Ex. int age;
- int = type
- age = identifier

More examples:
- `double x,y;`
- `boolean found;`
- `char letter; `
- `double month, day; `

We can also intitialize a variable by giving the variable it's value. You can do this during the declaration, or after. 

- `int count = 1`
- `int count` `count = 1`

## Chars
[ASCII CHART](https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit)

## Type Cast

One type can be cast to another compatibel type if apporpriate

`char letter = 'c';`
---

`int total, n;
double average;
average = (double)total/n  //total cast to double to ensure real division is used`

*note:* casting a floating-point number to an integer simply trunactes the number (rounds down)
