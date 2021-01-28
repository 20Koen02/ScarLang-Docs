# String
The string data type is used to represent text.
It is composed of a set of characters that can also contain spaces, numbers, emoji's, etc.  
The character set is unicode, a list can be found [here](https://www.ssec.wisc.edu/~tomw/java/unicode.html).


## Examples
More on the built-in functions can be found in the [Built-in Function]() section
```
var str = "hell"

# Operations
var str = str + "o"  # "hello"
var str = str * 2  # "hellohello"

# Check if type is a string
isString(str)  # 1

# Check if empty (falsy or truthy)
isTrue(str)  # 1
```


## "Unusual" String Operations

### Extend String
> A string can be extended by using the `+` operator on two strings.
```
var str = "ext"
var str = str + "end"
```
In the example above the string "ext" is extended with "end", resulting in "extend"

### Repeat String
> A string can be repeated with the `*` operator. You're essentially multiplying the string by a given amount
```
var str = "repeat"
var str = str * 3
```
In the example above the string "repeat" is repeated 3 times, resulting in "repeatrepeatrepeat"
