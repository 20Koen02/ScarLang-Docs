# Variables & Types

Variables are the names you give to computer memory locations which are used to store values in a computer program.

## Syntax
Here, `name` is the variable name and `val` is the value you want to assign
```
var name = val
```

## Value Types
Supported types are: `string, integer, float, array & function`  
Booleans are implemented as integers, where `1` is true and `0` is false

## Example
```
# Assign
var stringVariable = "Hello!"
var integerVariable = 1
var floatVariable = 1.0
var arrayVariable = ["Hello", "world"]
var anonymousFuncVariable = func(prefix) -> prefix + "!"
var anonymousMultiFuncVariable = func(prefix) {
    return prefix + "!"
} 
var resolvedExpression = 123 == 123  # 1

# Reassign
var stringVariable = "Hey!"
```
