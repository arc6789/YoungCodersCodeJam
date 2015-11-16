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
