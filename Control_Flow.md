# Control Flow

## If statements

You've already seen how to compare things using comparators like `>`,`<`, and `==`. But what if you want to change what your code does based on the result of a comparison?

Then don't be iffy, use `if`!

Silly jokes aside, computes think about comparisons a lot like we do. They say "If this is true then do that. Else do this other thing."

In code it looks like this:

```python
if (1 == 1):
    print "1 is equal to 1"
else:
    print "1 is not equal to 1"
```
What do you think this will print?


In Python, the generic way to put together an `if` statement is:
```python
if (condition):
    <some code> # executed if condition is True
else:
    <some other code> # executed if condition is False
```

How is this useful? Let's say you want to know if you need to wear a coat to school today. Let's make a function that would do this:

```python
def coat():
    temperature = float(input('What is the temperature? '))
    if temperature < 60.0:
        print("Wear a coat! It's chilly out.")
    else:
        print("It's not cold at all, you don't need a coat!")
```

what values of `temperature` will cause the function to tell you to wear a coat?  What happens if you type in 60?

### Try It!

Type the `coat` function into your Python interpreter and try it for all kinds of different values.  Write a new function called `shorts` that tells you to wear shorts or pants based on the temperature.  How warm should it be before you wear shorts?
