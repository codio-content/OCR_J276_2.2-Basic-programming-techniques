Iteration is the process of repeating  set of instructions for  fixed number of times or until there is a desired outcome.

Have a look at this website:
[http://www.cambridgedigital.com/mooc/html/phase2/63/63_Starter_Activity.html](http://www.cambridgedigital.com/mooc/html/phase2/63/63_Starter_Activity.html)

Iteration is accomplished by loops and in the OCR pseudocode there are two constructs for creating them.

### For loops

These are used for **count controlled** iteration – where a loop is executed for a fixed number of times. 
It is often called **definite iteration**.

```
for index == 0 to 9
`print(“This is number “ + index)
next index   //This closes the loop and redirects processing back
             //to the start while ‘index’ is within the range 0 to 9. 
             //The value of ‘index’ is incremented at each turn of the loop.
```

## Condition controlled iteration**
These loops turn until a certain condition is met.

### While
```
selection = “”
while selection == “”
  selection = input(“Please enter your name.”)
endwhile
```

The while loop will run while a condition remains true – while the variable ‘selection’ is an empty string.
As soon as a user actually enters data the loop will terminate.
Note that the variable to be checked must be declared and a value assigned before the ‘while’ loop is run or an error message will be displayed.

### do…until
This is similar to the while loop but the comparison is not done until the end of the code and so it will execute at least once.
```
do
`selection = input(“Please enter your name.”)
until selection != ””
```

The loop will repeat until an entry has been made.

Have a look at this website.
[http://www.cambridgedigital.com/mooc/html/phase2/63/63_Plenary_Activity.html](http://www.cambridgedigital.com/mooc/html/phase2/63/63_Plenary_Activity.html)
