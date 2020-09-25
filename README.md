# Exercise 1.6 - Message Three Times

Write a program that asks the user to write a string. When the user has given a string (that is, written some text and pressed enter), the program must print the user's string three times (you can use the `print` command multiple times).

The exercise template comes with a program template that includes the function and its call.

```python
def message_three_times():
    message = input('Write a message...')
    # Write your code here

if __name__ == '__main__':
    message_three_times()
```

Example output for when the user writes the string "Hi".

```plaintext
Write a message:
*Hi*
Hi
Hi
Hi
```

Example output when the user writes "Once upon a time...".

```plaintext
Write a message:
*Once upon a time...*
Once upon a time...
Once upon a time...
Once upon a time...
```

**Note:** Don't worry too much about `if __name__ == '__main__':` at the moment. We don't technically need it for this program, but it's good practise to include it and it'll be clearer in later exercises.
