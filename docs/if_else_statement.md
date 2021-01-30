# if/else Statement
The if/else statement executes a block of code if a specified condition is `true`. 
If the condition is `false`, another block of code can be executed.

Use comparison & logical operators to create a condition that's either `true` or `false`

In ScarLang we have the following conditional statements:

* Use `if` to specify a block of code to be executed, if a specified condition is `true`
* Use `else` to specify a block of code to be executed, if the same condition is `false`
* Use `else if` to specify a new condition to test, if the first condition is `false`

## Syntax
The `if` statement specifies a block of code to be executed if a condition is `true`:
```python
if (condition) {
  # block of code to be executed if the condition is true
}
```

The else statement specifies a block of code to be executed if the condition is `false`:
```python
if (condition) {
  # block of code to be executed if the condition is true
} else {
  # block of code to be executed if the condition is false
}
```

The else if statement specifies a new condition if the first condition is `false`:
```python
if (condition1) {
  # block of code to be executed if condition1 is true
} else if (condition2) {
  # block of code to be executed if the condition1 is false and condition2 is true
} else {
  # block of code to be executed if the condition1 is false and condition2 is false
}
```

## Single line if statement
There is also a single line version of the if statement.
It is not possible to use `else` and `else if` with this single line if statement.
```python
if (5 == 5) -> print("5 is 5!")
```
