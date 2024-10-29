### Variable
Variables are containers for storing data values.
Variable names are case sensitive.

#### Creating variable
Python has no command for declaring variable. 
A variable crated the moment when first assign a value to it.
```
x = 5
y = "Aravinda"
print(x)
print(y)
```

Variable do not need to be declared with any particular type, and can even change type they have been set.
```
x = 5 # x is of type int
x = "Aravinda" # x is of type string
print(x)
```

#### Casting
If you want to specify  the data type of a variable, this can be done with casting.
```
x = str(3) # x will be "3"
y = int(3) # x will be 3
z = float(3) # x will be 3.0
```

#### Get the type
You can get the data type of variable with the type() function.
```
x = 5
y = "Aravinda"
print(type(x))
print(type(y))
```

#### Variable name
A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)
* A variable name cannot be any of the Python keywords.
