# How Python is a different breed

Ever wondered if Python has different reasons to stand out, other than the fact that it doesn't need semicolons? No? Well, now you do. Python didn't appear in the spotlight overnight; there are real reasons why it earned this position. In this resource article, we will brush upon *some* of these quirky reasons, that make Python what it is.


## 1. Indentation

Thought indentations are just for aesthetics? From if-else blocks to loops to function definitions, Python lives by indentations. Miss one, and the code will collapse!


## 2. Dynamic Typing

Confused by the terminology? Just see this example:

```
x = 67
print(x) # Prints 67
x = "Crocodile"
print(x) # Prints Crocodile
```

Now, try executing the same in Java/C/C++. These languages go crazy during the second assignment, as the type with which a variable is declared will be fixed once specified. But Python? It's friends with flexibility. It doesn't have type declaration. And the final type of the variable will be the type of the value last assigned (in this case, it'll be of 'str' type).


## 3. GIF (Greatest Integer Function)

Python has an exclusive operator to extract the integral part of a float quotient. It is indicated by double slashes, //.

```
9/4 # 2.25
9//4 # 2
```

The reason for the existence of such an operator is attributed to dynamic typing. Despite the operands being integers, the resultant will be of 'float' type, unlike C/C++/Java, wherein type casting takes place implicitly.


## 4. Swapping Values

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


## 5. Memory Location Shifting

What happens when a variable is overwritten? In statically typed languages like C/C++/Java, the old value is discarded and a new value occupies the emptied space. But, the memory location of the variable remains unaltered, before and after overwriting. Python is an exception here too! Changing the value of a variable will bind it to a new memory location. In this way, the previous value in the previous memory location remains unaffected.
