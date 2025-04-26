

**Casting** -  to specify the data type of a variable
```
x = str(3)    # x will be '3'  
y = int(3)    # y will be 3  
z = float(3)  # z will be 3.0
```

**Type** - get the data type of a variable with the `type()` function.

## Variable Names
- A variable name must start with a letter or the underscore character
-  variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )

## Many Values to Multiple Variables

```
x, y, z = "Orange", "Banana", "Cherry"  
print(x)  
print(y)  
print(z)
```

## One Value to Multiple Variables

```
x = y = z = "Orange"  
print(x)  
print(y)  
print(z)
```
## Unpack a Collection
Python allows you to extract the values into variables.

```
fruits = ["apple", "banana", "cherry"]  
x, y, z = fruits  
print(x)  
print(y)  
print(z)
```

## Output Variables
use the `+` operator to output multiple variables, Also separate them with commas
## Global Variables
Global variables can be used by everyone, both inside of functions and outside.

```
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)
myfunc()

print("Python is " + x)
```

To create a global variable inside a function, you can use the `global` keyword.
