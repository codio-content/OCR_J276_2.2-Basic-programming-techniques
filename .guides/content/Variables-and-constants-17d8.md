A **variable** is a container which is used to store a value which can change as a program is running e.g.

```
price = 1.3    //The variable price contains the value 1.3. This is called an assignment. 
               // The variable ‘price’ has been assigned the value ‘1.3’.
print(price)   //This would print ‘1.3’
price = price * 2
print(price)   //This would print ’2.6’ as the value stored in ‘price’ has changed
               //-  it has been multiplied by 2.
```

Each variable is given a name or an **identifier**.

Variable identifiers should be as descriptive as possible so that anyone reading the code will be able to see what they represent.

For example a variable to store the age of a person should have the identifier ‘age’ rather than ‘X’ so that its intention is obvious.

One convention when writing longer or compound identifiers is to use **camel case** where each word begins with an upper case character – usually except the first e.g. ageOfPerson, distanceFromSchool, testResult

Identifiers should be as short as possible so that there is less chance of them being misspelt when coding the algorithm.

A **constant** is a container which is used to store a value which must **not** change as a program is running.

A constant is fixed e.g. Pi = 3.142 or inchToCm = 2.54