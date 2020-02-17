# HTML - Text

## Types of tags (markups):

1. Structural markup
    - elements that describe headings and paragraphs  
     i.e. ` <h1> ` and ` <p> `
1. Semantic markup
    - elements that provide extra information and meaning
     i.e. ` <strong> ` and ` <nav> `

# Introducing CSS

- CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

- Rules are made up of *selectors* and *declarations*   
selectors are the elements names and declarations are the styles added to the selectors, as:  
```
             selector { 
                           declaration; }
```

- Different types of selectors allow you to target your rules at different elements

- Declarations are made up of two parts: 
    * the properties of the element that you want to change 
    * and the values of those properties
- CSS rules usually appear in a separate document, although they may appear within an HTML page
- Types of CSS style:

1. External CSS 
2. Internal CSS
3. Inline/embeded CSS


 ------------------------------------------------
# Basic JavaScript Instructions

## 1. Statements and Scripts
**A series of instructions that a computer can follow one-by-one is called a *script*,
While an individual instruction/step is called a *statement***

- statements should end with a semicolon


## 2. Comments
 **Comments are used to explain what your code does and to make it easier to understand**
 - for a single-line comment: use `//comment`
 
 - for a multi-line comment:  use `/*comment*/`
 
## 3. Variables
**Information use in a script are stored in *variables***
- the information stored in a variable can change each time the script runs (that's why they're called variables)
- variables must be *declared* befor they are used, which means they must be created and given a name, declaration is done as:
`var variable-name;`, where var is the *keyword* for a variable

## 4. Data Types
**JS has three data types, which are:**
- Numbers: for numeric data
- Strings: for letters and charecters, anything between (" ") is a string

- Booleans: have one value, True or False

## 5. Naming Variables Rules
**In JS, there are six rules for naming a variable, which are:**
- a name *MUST NOT* start with a number, it must start with a letter, ($) or ( _ )
- a name *MUST NOT* contain a ( - ) or  a ( . )
- you can't use a *keyword* or a *reserved word*
- all variables are *case sensetive*
- use a name that describes the information it stores
- use *camel case* if the variable name has more than one word

## 6. Arrays
**An array is a special type of variable that stores a list of values.**

- Arrays are used when dealing with lists and sets of related values

## 7. Expressions
**Expresions are statements that result in single values.**

### Tyoes of expressions:
1. Expressions that assign a value to a variable
2. Expressions that use more than one value to return a single value

## 8. Operators
- Assignment operators
- Arethmetic operators
- String operators
- Comparision operators
- Logical operators

-----------------------
# Decisions and Loops

## Decision components:
1.  An expression
    - returns a value when evaluated
2. A conditional statement
    - determines what to do at certain conditions

## Comparision operators

- `==` 
compares the *values* to see if they are the same

- `!=` 
compares the *values* to see if they are not the same

- `===` 
compares the values to check if the data types are the same

- `!===`
compares the values to check if the data types are not the same

- `>` 
checks if the number on the left is greater than the number on the right

- `<`
checks if the number on the left is less than the number on the right

- `>=`
checks if the number on the left is greater than or equal the number on the right

- `<=`
checks if the number on the left is less than or equal the number on the right

## Logical operators

- `&&`
T && T : T
T && F : F
F && T : F
F && F : F

- `||`
T || T : T
T || F : T
F || T : T 
F || F : F

- ` ! `
!T : F
!F : T

## If Statement

```
if ( condition) {
    code statement;
    }
```

- the code statement is excuted only if the condition evaluates to *true*

## If...Else Statement

```
if ( condition) {
    code statement 1;
    }
else {
    code statement 2;
  }
``` 

- code statement 1 is excuted only if the condition evaluates to *true*
- code statement 2 is excuted only if the condition evaluates to *false*

