# Exercises for Programming Foundations Lesson 3

## Exercise 1
Make a variable `myNumber` with a number value of 10.

a) Make an `if` statement to see if the value of `myNumber` is equal to 10. 

If so, console log out "Bingo, the number is 10".

b) Add an `else` statement that console logs out "Aww, the number wasn't 10". What is console logged out now?

c) Change `myNumber` to something other than 10. What is console logged out now?

## Exercise 2

Make a (boolean) variable named `apple` valued `true` and another variable named `orange` valued `false`.

a) Make an `if` statement that compares the two and console logs out "You cannot compare apples and oranges" as long as the two variables are not equal.

b) Add an `else` statement that console logs out "Hm, it seems apples and oranges are the same, after all". 

c) Change the `orange` variable's value to `true`. What is console logged out?

d) Then change the `apple` variable's value to false. Now, what is console logged out?

## Exercise 3
Ask the user to input their name.

If the name is set display a message saying "Hello, [name]".

If it wasn't display a message saying "Awww!"

> Tip: Use [prompt()](https://www.w3schools.com/jsref/met_win_prompt.asp) to allow input

## Exercise 4
Make a variable `myAge` and give it a numeric value (eg. your age).

Make an if...else if...else statement that console logs out the following scenarios: 

* If `myAge` is less than 0, it says "That's not possible".
* If `myAge` is less than 18, it says "You are juvenile".
* If `myAge` is less than 30, it says "You are still young".
* If `myAge` is less than 50, it says "You aren't exactly young anymore, are you?"
* If `myAge` is less than 70, it says "You're getting really old?"
* If `myAge` is less than 100, it says "How is retirement treating you?"
* If `myAge` is 100 or more, it says "Centennial? Impressive...";

## Exercise 5
Ask the user input a number.

Check to see if it was really a number that was entered.

Display "Valid number entered" or "Not a valid number entered" back to the user.

> Tip: Check the input using [the Number() function](https://www.w3schools.com/jsref/jsref_number.asp) and [the isNaN() function](https://www.w3schools.com/jsref/jsref_isnan.asp).

## Exercise 6
Ask the user input a number.

Display the number and whether it is odd or even, back to the user.

> Tip: To check if a number is odd or even you may use reminder division where you check the reminder when dividing by 2; if the reminder is 1, then the number is odd; if the reminder is 0, then the number is even.

## Exercise 7
Extend the code from Exercise 3, to check if nothing was entered or the user just pressed cancel. 

> Tip: If the user clicks "OK" on a `prompt()`, the input value is returned as a string. If the user clicks "cancel", `null` is returned. If the user clicks OK without entering any text, an empty string is returned. 

## Exercise 8
Make a variable `fruit` and give it the value "pear", and an undefined variable named `output`.

Make a `switch` statement that uses `fruit` as it's expression and the following cases: 

* apple: give `output` the value "An apple a day..."
* orange: give `output` the value "What to do with all the orange peel?"
* pear: give `output` the value "Delicious, from a tree or a can."
* banana: give `output` the value "What, are you a Minion?"
* mango: give `output` the value "Mangos are weird..."

a) Console log out the `output` variable. What is console logged out?

b) Make a `default` case that gives `output` the value "That's not a fruit, at least not one I've heard of." 

c) Change the original `fruit` variable to the value "kiwi". What is console logged out now?
