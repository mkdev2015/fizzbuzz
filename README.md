FizzBuzz Exercise
=================

An exercise using variables, operators, strings, numbers, and loops.

Description
-----------

Create a file called “fizzbuzz.js”, which [logs][Console.log] the numbers from 
**1 to 100** to the console, but for multiples of three (3), log the word “Fizz”
instead of the number, and for multiples of five (5) log “Buzz”, and for numbers
which are multiples of both three and five, log “FizzBuzz”.

For instance, the first twenty lines of output from the program would look like
this:

```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
```

Run `node fizzbuzz.js` and review its output to ensure it is functioning
correctly.

Testing
-------

If you want to test your code as you are going along, you can run this command:

```sh
node test
```

Extra Credit
------------

[Define a function][Declaring functions] called `fizzbuzz` which accepts a
single argument, `max`, and logs the appropriate output up to that number. For
instance, calling `fizzbuzz(5);` would log the following:

```
1
2
Fizz
4
Buzz
```

Call `fizzbuzz` for the numbers 5, 13, 89, and 233.


Completing and submitting the assignment
----------------------------------------

- To begin, [**fork** this repository](https://guides.github.com/activities/forking/).
- [Create a new Cloud9 workspace](https://docs.c9.io/docs/setting-up-github-workspace) from your new repository.
  - Alternatively, you may [**clone**](http://gitref.org/creating/#clone) your new repository to your computer.
- Modify the files and [**commit**](http://gitref.org/basic/#commit) changes to complete your solution.
- Run `node test` to verify that all tests pass.
- [Push](http://gitref.org/remotes/#push)/sync the changes up to GitHub.
- [Create a pull request](https://help.github.com/articles/creating-a-pull-request) on the original repository to turn in the assignment.

You are also welcome commit, push, and create a pull request **before** you’ve completed your solution. You can ask questions or request feedback there in your pull request. Just mention `@barberboy` in your comments to get my attention.


References
----------
- [Declaring variables]
- [`for` loop][for loop]
- [`=` Assignment operator][Assignment operator]
- [`<` Less-than operator][Less-than operator]
- [`++` Increment operator][Increment operator]
- [`%` Remainder operator][Remainder operator]
- [`==` Equality operator][Equality operator]
- [String literals]
- [Numbers]
- [Console.log]
- [Declaring functions]


[Declaring variables]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types#Declaring_variables
[for loop]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for
[Assignment operator]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Assignment_Operators#Assignment_2
[Less-than operator]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Less_than_operator_(<)
[Increment operator]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Increment_() 
[Remainder operator]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Remainder_()
[Equality operator]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Equality_operators
[String literals]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types#String_literals
[Numbers]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types#Integers
[Console.log]: https://developer.mozilla.org/en-US/docs/Web/API/Console/log#Syntax
[Declaring functions]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function