# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it _very easy_ for tech people to **copy, paste, share** code.
A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use backticks (`)
- Not to be confused with qoutation (')

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
```

- When you can you should attempt to apply sintax highlighting to your codeblocks

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the factorial function
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
```

- Make note of where the backtick button is located in a portuguese keyboard. 
- In a US keyboard the backtick button is located above the tab key.

<img width="200px" src="https://github.com/f616/github-docs-example/assets/3826426/7faaf4a3-5153-429b-a077-5176ca460a51" />

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.



```bash
Traceback (most recent call last):
  File "your_file.py", line X, in <module>
    result = numerator / denominator
ZeroDivisionError: division by zero
```

> Here is an example of using a codeblock for an error that apperar in bash.

## Step 3 - Use Github Flavored Markdown Taks Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning| `:cloud_with_lightning:` | :cloud_with_lightning: |

## Step 5 - How to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning| `:cloud_with_lightning:` | :cloud_with_lightning: |
```

Github extends the funcionality of Markdown tables to provide more aligment and table cell formatting options. [<sup>[2]</sup>](#external-references)



## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (GitHub Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CHeatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
