                        Technical Blog
```
  My journey to the Marcy Labs School has introduced me to some new things. 
 When I started I knew little about coding. But the past few months have been hard but am getting there. 
 One of the harder ones was the If statement. The if/else statement executes a block of code if a specified condition is true. 
 I use the if statement mostly in a loop. I love the for loop because, in my opinion, it is the easiest to understand compared to the rest. 
 Alright, so you put a condition in an if statement and if the conditions are true it runs the code in the code block. 
```
```javascript
Const statement = true
 If (statement) {
   Console.log(true)
} else {
Console.log(false)
}
=>//true
```
```
This code is always going to log the Boolean value true because we have a variable name statement with a value of true, 
Which means that the condition will always be true. The tricky part of the if statement is when to use the! symbol because 
sometimes you want to check if the conditions are not meant to run the code block.
```
```javascript
 Const statement = true
If (!statement) {
    Console.log(true)
} else {
    Console.log(false)
}
=>//false
```
```
This code will always log false because the not operator is telling the if statement to run the code block when the condition is not true,
And we assigned a boolean true to (statement) so it is always going to log false to the console. Another problem I constantly face with an 
if statement is knowing whether to add an else statement which is when you want a code to run when the condition is false.
```
```javascript
Let age = 17
 if (age > 18) {
    console.log(You are eligible)
} else {
   console.log(You are not eligible)
}
=>//You are not eligible
```
```
 Sometimes an else statement is not needed when you don’t have a code to run when the condition is false.
When you want to log or print true you don’t need an else statement to print false.
```
```javascript
Let age = 17
 if (age > 18) {
    Return true
} 
```
```
 The if statement can accept a wide range of conditions you can have two or more with the handy &&(And operator),
|| (Or operator). The and-operator only returns true when both conditions passed is true.
```
```javascript
If (2<3 && 4<5) {
    Console.log(true)
} else {
     Console.log(false)
}
=>//true
```
```
This code will log true because both conditions are true so the first code block will run. 
Both conditions have to be true for the first block to run. 
The or operator only requires one of the conditions to be true to run the first code block. 
The logical OR operator finds the first truthy value.
```
```javascript
If (2<3 || 5<4) {
    Console.log(true)
} else {
     Console.log(false)
}
=>//true
```
```
This code will log true because the first condition is true so it will log true to the console.
Truthy values are just values that are considered true in a boolean example (true, 1, 3).
Falsy values are considered false as a boolean example (null, 0, false).
```
