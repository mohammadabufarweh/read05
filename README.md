# read05

## comparison operators: evalyation condition :


In these operator we can compares (numbers,string or boolean)

### Is equal to ==
This operator compares tow values to if they the same.

`x == 8`

### Is not equal to !=

This operator compares tow values to if they the not same
`x != 8`

### Strict rqual to ===
This operator compares tow values to check that both the dta type and value are the same
`x === 5`
### Strict not rqual to !==

This operator compares tow values to check that both the dta type and value are not the same
`x !== 5`

### Greater than >
This operator checks if the the number on the left is greater than the number on right side.
`x > 8`

### less than >
This operator checks if the the number on the left is less than the number on right side.
`x < 8`

### Greater than or equal >=
This operator checks if the the number on the left is greater or equal than the number on right side.
`x >= 8`
### Less than or equal <=
This operator checks if the the number on the left is less or equal than the number on right side.
`x <= 8`
## Logical operators
Logical operators allow you to compare the result of more than one comparison operator.

| And      | Or |   Not       |
| ----------- | ----------- | ----------- |
| &&      |    ( or)      |      !    |
| T && T = T  | T && T = T        |   !(true) =F       |
|T && F= F|   T && F = F |  !(false) =T|    
|F && F = F| F && F = F| 


## Loops

Loops check a condition if it returns true a code block will run  
then the condition will be checked again and agin till the condition be false it will out of loop

For
we use for in known iteration
```js
for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```
* initial condition (initialzation)--> i=0
* condition --> i < 5
* update --> i++

While
we use while in unknown iteration so the while loop will be looping till condition be false
```js
while (condition) {
  // code block to be executed
} 
```