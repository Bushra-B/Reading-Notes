# HTML Lists

## Types of HTML lists:

1. **Ordered lists**
    - numbered list – each item is numbered
    - ` ol ` element 

2. **Unordered lists**
    - bullet point list
    - ` ul` element
    - each item in the list is placed between list tags: `<li> <\li>`

3. **Definition lists**
    - set of terms along with their definitions
    - ` dl ` element

**\- Lists can be nested inside each other to make sublists.**

----------------------------------
# CSS Boxes

**In CSS, HTML elements are treated as if each one of them is contained inseide a *box*.  
The appearence of these boxes can be controlled using CSS properties, such as:**

- `width` and `height`
\- used to set the dimensions of the boxes.
\- size of box can be specified using:
    1. pixels
    1. percentages
    1. ems
- `overflow` 
\- takes two values:
    1. hidden
    2. scroll
- Borders
\- separates the edge of one box from another

- Margin
\- it's the space outside the border of the box, and it's used to creat a gap between  the borders of boxes

- Padding 
\- it's the space between the content and the borders of the box, adding padding increases the readability of the content

- `dispaly` 
\- this property turns an inline element into a block-level element, and vice versa. It can take the following values:  
    - `inline` : to turn a block-level element into an inline element
    -  `inline-block`: to turn an inline element into a block-level element
    - `none`: hides an element from the page

### CSS3 Box properties:

- `border-image`
\- applies an image to the border of the boc
- `box-shadow`
\- adds a drop shadow around a box
- `border-radius`
\- makes the corners of the box rounded

-------------------------------------------------
# JS Switch Statements

**A switch statement has a variable (called a *switch value*) and possible values for that variable (called *cases*), and for each case (value) there is a block of code/code statement that should run if the variable matches that value (case)**

```
switch (switch value) {
        case 'value':
               code statement;
               break;
    }
```
- when a case matches the variable, its code statement is excuted and leaves the switch
- the `break`  tells the JavaScript interpreter that it has finished with this switch statement and to proceed to run any subsequent code that appears after it
- switch can have a `default` case, which runs if none of the cases match
- switch statement can be used instead of if, if...else statements and it takes less time to run

# JS Loops

**The idea of a loop is to have a condition and a code block, such that the code block will keep repeating as long as the condition checks true**
## Types of loops:
1. **For loop**
    - when you need to run the code for a specific number of times
    - the condition is a counter
```
for (initial value; condition; counter) {
      code statement;
   }
```
2. While loop
    - if you don't know how many times you should run the code
    - the code will keep looping as long as the condition is true
```
while (condition) {
          code statement;
     }
```
3. Do While
    - same as while loop
    - runs all the code statements at least once even if the condition is false
```
do {
     code statement;
  }
while (condition);
```
