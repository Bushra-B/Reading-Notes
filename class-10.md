# Error Handilong and Debugging

## Order of Excution
**Order of excution is the order in which code statements are excuted (proccessed) when the script is run.  
sometimes some tasks are not completed until another statement or function is excuted.**

## Excution Contexts
**When a script is run, the JS interpreter excutes the code using the concept of excution contexts.**

### Types of excution contexts:

- **global context**  
there is one global context for each page, it includes the code that is in the script, but not in the function

- **function context**
each function has its own function context, it includes the code that is inside a function

-**eval context**
code inside `eval()` function has its own context, eval function is an internal function that excutes text

## The Stack
**JS interpreter excutes one line at a time.**  
**When a code statement needs data from another function, the JS interpreter stacks the function on top of the current task**