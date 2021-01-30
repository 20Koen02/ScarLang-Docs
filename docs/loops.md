# Loops

A loop is a sequence of instructions that is repeated until a certain condition is reached.

## Examples
```python
# Single line for loop
var result = 1
for (i = 1 to 6 step 1) -> var result = result * i
print(result)  # 120

# Multi line for loop
var result = 1
for (i = 1 to 6 step 1) {
    var result = result * i
}
print(result)  # 120

# Single line while loop
var i = 1000
while (i > 0) -> var i = i - 1
print(result)  # 0

# Multi line while loop
var i = 1000
while (i > 0) {
    var i = i - 1
}
print(result)  # 0
```

## For Loops
`for` loops are used to loop through a block of code a number of times
```python
var count = 0
for (i = 1 to 6 step 1) -> var count = count + 1
print(count)  # 5
```
In this example, `i` starts out at `1` and the loop will stop **before** `i` is 6.
Every time the code block is executed `i` gets incremented by 1.
The loop will execute 5 times: when `i` is `1`, `2`, `3`, `4` and `5`.

## While Loops
`while` loops are used to loop through a block of code while a specified condition is true
```python
var i = 0
while (i < 6) -> var i = i + 1
print(i)  # 6
```
In this example, `i` starts out at `0` and the loop will stop when `i` is smaller than 6
Every time the code block is executed `i` gets incremented by 1.
The loop will execute 6 times: when `i` is `0`, `1`, `2`, `3`, `4` and `5`.

## Break & Continue
The `break` statement breaks the loop and continues executing the code after the loop (if any)
The `continue` statement breaks one iteration in the loop, and continues with the next iteration in the loop.
