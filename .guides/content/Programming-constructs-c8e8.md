The basic constructs of algorithms and programs are sequence, selection and iteration.

**Sequence** is the order in which tasks are carried out and instructions are executed.

**Selection** is used to choose between two or more options.
In the OCR pseudocode there are `if` `elseif` `else` and `switch/case` statements for selection.

The following example shows how these could be used in a simple program to indicate to a user which number they had entered.

```
selection = input(“Please enter a number between 1 and 3.”)
if selection == 1 then
  print(“You entered the number one”.)
elseif selection == 2 then
  print(“You entered the number two.”)
elseif selection == 3 then
  print(“You entered the number three.”)
else
  print(“Sorry. That is not recognised.”)
endif           //There must be an endif statement at the end of the ‘if’ construct.
```
```
selection = input(“Please enter a number between 1 and 3.”)
switch selection
`case 1:
    print(“You entered the number one”.)
  case 2:
    print(“You entered the number two.”)
  case 3:
    print(“You entered the number three.”)
  default:
    print(“Sorry. That is not recognised.”)
endswitch
```