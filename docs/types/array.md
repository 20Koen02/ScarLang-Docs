# Array
The array data type is used to store multiple values.
An array can hold elements of different types.
An array can store any kind of elements — from integers to strings to functions.


## Examples
More on the built-in functions can be found in the [Built-in Function]() section
```
var arr = ["first", "second"]

# Operations
arr + 3  # ["first", "second", 3]
arr - 0  # ["second", 3]
arr * [4, "fifth"]  # ["second", 3, 4, "fifth"]
var selected = arr / 1  # 3

# Append using a function
append(arr, 6)  # ["second", 3, 4, "fifth", 6]

# Remove using a function
pop(arr, 2)  # ["second", 3, "fifth", 6]

# Extend using a function
extend(arr, ["seven", 8])  # ["second", 3, "fifth", 6, "seven", 8]

# Returns size of the array
var size = length(arr)  # 6

# Check if type is an array
isArray(arr)  # 1

# Check if empty (falsy or truthy)
isTrue(arr)  # 0
```


## "Unusual" Array Operations

### Append to Array
> There are two ways to append a value to an array.
> The first one is to use the `+` operator, and the second way is to use the built-in function `append()`
```
var arr = ["first", "second"]
arr + 3  # ["first", "second", 3]
append(arr, "fourth")  # ["first", "second", 3, "fourth"]
```
In the example above we first append `3` to the array using the `+` operator,
then appending `"fourth"` to the array using the built-in function `append()` 

### Remove from Array
> There are two ways to remove a value from an array.
> The first one is to use the `-` operator, and the second way is to use the built-in function `pop()`
```
var arr = ["first", "second"]
arr - 1  # ["first"]
pop(arr, 0)  # []
```
In the example above we first remove the 1st element (we count from 0) from the array using the `-` operator,
then removing the 0th element from the array using the built-in function `append()`.
These actions result in an empty array

### Extend Array
> There are two ways to extend an array with another array.
> The first one is to use the `*` operator, and the second way is to use the built-in function `extend()`
```
var arr = ["first", "second"]
arr * [3, "fourth"]  # ["first", "second", 3, "fourth"]
extend(arr, [5, "sixth"])  # ["first", "second", 3, "fourth", 5, "sixth"]
```
In the example above we first extend the array with `[3, "fourth"]` using the `+` operator,
then the array with `[5, "sixth"]` using the built-in function `append()` 

### Get element from array
> Use the `/` operator to get a specific element from the array
```
var arr = ["first", "second"]
var selected = arr / 1  # "second"
```
In the example above we select the 1st element in the array (we count from 0) and put it in the variable `selected`.
This results in `"second"`

### Get size of the array
> Use the built-in function `length()` to get the size of the array
```
var arr = ["first", "second"]
var size = length(arr)  # 2
```
In the example above the variable `size` is `2` because there are two elements in `arr`
