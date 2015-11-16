# Functions

## What is a function?

Imagine you want to sing Happy Birthday to Jeremy. You could do this in python by writing the following:
```python
print("Happy Birthday to you!")
print("Happy Birthday to you!")
print("Happy Birthday, dear Jeremy.")
print("Happy Birthday to you!")
```

But what if I want to sing the song to someone else? What if I don't want to type that much? That's a lot of typing just to sing happy birthday! Wouldn't it be nice if I could save all that code into some kind of box and just use that to sing happy birthday?

We can. In python these are called Functions. And they're very easy to make.

Let's make a Birthday Song function.

```python
def birthday_song():
    print("Happy Birthday to you!")
    print("Happy Birthday to you!")
    print("Happy Birthday, dear Jeremy.")
    print("Happy Birthday to you!")
```

Let's break this down. You define a function by using the `def` keyword followed by the function name. Just like this:

```python
def function_name():
    <Code you want to run>
```

When you want to run the code you just run:
```
>>> birthday_song()
```

### Try It!

Type the `birthday_song` function into your Python interpreter.  Try running it.  Change some of the text in the song, does it print out what you think it should?

## Adding Parameters

That birthday function is pretty handy for anyone named Jeremy. But what if I want to sing Happy Birthday to someone else? Is there a way to pass in a different name?

There is. Values you pass into functions are called parameters. They can be anything, even other functions! In this case let's pass in a parameter called 'name' to help us customize the happy birthday song.

```python
def birthday_name_song(name):
    print("Happy Birthday to you!")
    print("Happy Birthday to you!")
    print("Happy Birthday, dear " + name + ".")
    print("Happy Birthday to you!")
```

To use this function you would run:
```
>>> birthday_song("Kacie")
```

Functions can take as many parameters as you'd like. Parameters are separated with commas.

### Try It!

Type the `birthday_name_song` into your Python interpreter.  Try running it!  What happens when you don't give it a value?  What happens when you give it two values?  What other values could you add to the function to make it more useful?
