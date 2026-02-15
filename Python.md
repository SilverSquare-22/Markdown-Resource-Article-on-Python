# How Python is a different breed

Ever wondered if Python has different reasons to stand out, other than the fact that it doesn't need semicolons? No? Well, now you do. Python didn't appear in the spotlight overnight; there are real reasons why it earned this position. In this resource article, we will brush upon *some* of these quirky reasons, that make Python what it is.


### 1. Dynamic typing

Confused by the terminology? Just see this example:

```
x = 67
print(x) # Prints 67
x = "Crocodile"
print(x) # Prints Crocodile
```

Now, try executing the same in Java/C/C++. These languages go crazy during the second assignment, as the type with which a variable is declared will be fixed once specified. But Python? It's friends with flexibility. It doesn't have type declaration. And the final type of the variable will be the type of the value last assigned (in this case, it'll be of 'str' type).


### 2. Swapping Values

How would you swap the values of two variables without using a temporary variable? The following might be the way you would come up with:

```
x = x + y;
y = x - y; // (x + y) - (y) = x
x = x - y; // (x + y) - (x) = y
```

While this method is completely valid, you will not be required to use this in Python, as it offers a cleaner and more compact way to swap two values:

```
x, y = y, x
```

See how simple Python is?
