# Loops

## While Loops
Let's say we want to annoy our friends and have the computer say "Hello" 100 times! We could type this out but that would take a long time.

If only there was a way to have the computer do it for us.

There is and it's called a loop. There are several kinds of loops, let's start the the `while` loop.

While loops will repeat the code inside them until the conditional evaluates to `False`. What does this look like?

```python
i = 100
while (i > 0):
    print "Hello!"
    i = i - 1
print "Done."
```

What does this code do?

```
i = 100
```
First, we set a variable, `i`, to have the value 100

```
while (i > 0):
```
As long as `i` is greater then 0, we're going to keep running the code inside this loop.
```
    print "Hello!"
    i = i - 1
```
Print 'Hello!' and then we make `i` smaller by 1. This means eventually `i` will be less than 0.
```
print "Done."
```
When `i` is no longer greater than zero we print `Done.`

The generic form of a `while` loop in Python is:
```python
while(conditional):
    <code to run> # as long as the conditional is True
```

## For loops

For loops are another common kind of loop. They are telling the computer to run some code `for` every thing in the conditional. That's a little confusing, let's look at an example.

```python
fruit_list = ['apple', 'banana', 'pear', 'pineaple']
for fruit in fruit_list:
    print fruit
```

Try running this code in your Python interpreter. What does this output?

a `for` loop in Python has the generic form:
```python
for <variable_name> in <iterable>:
    <Code to run>
```

Notice the word 'iterable' up there. A `for` loops uses iterables. This does not have to be a list. It can be a tuple, a string, a dictionary or any other iterable object.

You can use a for loop to do something 10 times:

```python
for x in range(0, 10):
    print "We're on time " + str(x)
```

### Try it!

What values did `x` go through in that last example?  How could you change the example to loop from 1 to 100? From 10 to 20?  Try putting something else in the body of the `for` loop such as printing your name.
