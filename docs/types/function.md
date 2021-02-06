# Function
A function is a named section of a program that performs a specific task.
In this sense, a function is a type of procedure or routine.
A function can take parameters to do operations on and return a value to use after the procedure or routine has ended.


## Examples
More on the built-in functions can be found in the [Built-in Function]() section
```python
func function(prefix) -> prefix + "!"

func multilineFunction(prefix) {
    return prefix + "!"
} 

var anonymousFunction = func(prefix) -> prefix + "!"

var anonymousMultilineFunction = func(prefix) {
    return prefix + "!"
} 

# Check if type is a function
isFunction(multilineFunction)  # 1
```

## Anonymous function
An anonymous function is a function that was declared without any named identifier to refer to it.
In the examples section, we assign such anonymous functions to variables.
This is not the identifier, because we can reassign the anonymous function to a different variable

## Single line function
A single line function does not need to return any values using the `return` keyword.
The result of the single line expression is automatically returned.
