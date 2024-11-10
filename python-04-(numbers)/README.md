### Numbers
There are three numeric types in Python
* int
* float
* complex

Variables of numeric types are created when you assign a value to them.
```
x = 1
y = 2.8
z = 1j
```

To verify the type of any object in Python, use the type() function.
```
print(type(x))
print(type(y))
print(type(z))
```

#### int
int or integer is a whole number positive or negative without decimals of unlimited length.
```
x = 1
y = 3555445554445
z = -3343344

print(type(x))
print(type(y))
print(type(z))
```

#### float
float or floating point number is a number, positive or negative, containing one or more decimals.
```
x = 1.10
y = 1.0
z = -345.3

print(type(x))
print(type(y))
print(type(z))
```

#### complex
complex numbers are written with a 'j' as the imaginary part
```
x = 3+5j
y = 5j
z = -5j

print(type(x))
print(type(y))
print(type(z))
```

#### Type conversion
You can convert from one type to another with the int(), float(), and complex() methods.
```
x = 1
y = 2.4
z = 1j

a = float(x)
b = int(y)
c = complex(x)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
```

#### Random number
Python does not have a `random()` function to make a random number, but python has a build in module called `random` that can be used to make random numbers.
```
import random

print(random.randrange(1, 10))
```