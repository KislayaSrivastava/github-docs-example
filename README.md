# Writing good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste and share** codes.
A good __Cloud Engineer__ uses Codeblocks wherever possible.

Because it allows others to copy and paste their code to replicate or research issues. 

- In order to create codeblocks in markdown you need to use three backticks (```)
- Not to be confused with quotations (''') 
- When you can you should attempt to apply syntax highlighting to your codeblocks (```<NameoftheLanguage after the backticks>```)

  
``` Csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, .NET Core!");
        }
    }
}
```

Make a note of where the backtick button is located. It should appear above the tab key but it may vary based on your keyboard layout.

<img width="200px" src="https://github.com/KislayaSrivastava/github-docs-example/assets/40534292/241eae6b-c262-4bba-aaad-00d3a7770071"/>

Good Cloud Engineers use codeblocks for both code and errors that appear in the console. 
> An example of a code that will produce errors while running.

```bash
#!/bin/bash

# Simulate a command that produces an error
ls /nonexistentdirectory

# Attempt to access a non-existent variable
echo "The value of an_unset_variable is: $an_unset_variable"

# Divide by zero
result=$((10 / 0))

# Attempt to use a command with incorrect syntax
invalid_command

# Access an array element that doesn't exist
my_array=("apple" "banana" "cherry")
echo "The third element of the array is: ${my_array[2]}"

# Attempt to open a non-existent file
cat nonexistentfile.txt

# This line will not be reached
echo "This line will not be reached."

```
## Step 3 - Use Github Flavoured Task Lists

Github extends Markdown to have a list where you can check out items.[<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emojis (Optional)

Github Flavoured Markdown (GFM) supports emoji short codes.
Here are some examples:

|Name |ShortCode|Emoji|
|---|---|---|
|Cloud|`:cloud:`|:cloud:|
|Cloud with Lightning|`:cloud_with_lightning:`|:cloud_with_lightning:|
|Dark Sunglasses|`:dark_sunglasses:`|:dark_sunglasses:|
|Purse|`:purse:`|:purse:|
|Briefcase|`:briefcase:`|:briefcase:|

## Step 5 - How to Create a Table

You can use the following markdown format to create tables:

```md
|Name |ShortCode|Emoji|
|---|---|---|
|Cloud|`:cloud:`|:cloud:|
|Cloud with Lightning|`:cloud_with_lightning:`|:cloud_with_lightning:|
|Dark Sunglasses|`:dark_sunglasses:`|:dark_sunglasses:|
|Purse|`:purse:`|:purse:|
|Briefcase|`:briefcase:`|:briefcase:|
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.<sup>[2]</sup>

## References
- [Github Flavoured Markdown Specs](https://github.github.com/gfm/)
- [Basic Writing and Formatting on Github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Second Link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
- [GFM - Emoji Cheat Sheet]((https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
