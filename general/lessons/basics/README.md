## Python REPL
* So far, all of the code you’ve written has been in the Python REPL
* The REPL is great for testing ideas or simple one-liners
* It does not easily allow you to save your code between runs
* If you want to work on a program where you will be frequently editing, saving and working on your code, the REPL is not ideal

## Vim
* Take a look at the [lesson on Vim](/general/lessons/vim).
* Once you've installed Vim, you can type `vim <filename` into terminal to open that file. If the file doesn't exist, it creates a new file.
* Before typing anything, press `i` to go into insert mode (so you can actually type). You can then press `Esc` to go into normal mode. Then you can type `:w` to write (save) a file and `:q` to quit (close a file).
* Make sure you use the `.py` extension on all your Python files. Otherwise, you won't get nice color coding. That would be sad.

## Running a Python program
* Use `cd` and `ls` to navigate to the directory your file is in.
* Type `python <name of your program>.py`. Press `enter`. Observe the following demo:

    cd ~/robotics/training
    $ ls
    test.py
    $ python test.py
    test: It works!
    It works!

Try printing these arithmetic calculations and see what happens!

    5 + 9
    4 * 2 - 3
    7 * 10 ** .5

Once you are familiar with these, try one that shows 5 arithmetic expressions of your choice that results in the number 42. Feel free to look up how to do any fancy expressions.

## Order of operations
Arithmetic and logical calculations in Python follow the order of operations. Here is the hierarchy (PEMDAS):

* `()` **P**arentheses
* `**` **E**xponent
* `*`,`/` **M**ultiplication, **D**ivision
* `+`,`-` **A**ddition, **S**ubtraction
* `>>`,`<<` Bitshift Operations (not often used)
* `^`,`&`,`|` Bitwise Operations (not often used)
* `>`,`<`,`>=`,`<=`,`==`,`!=` Comparison
* `not`
* `and`
* `or`

For exponents, be sure not to use `^`. It is a bitwise xor operator and will give you very different numbers.

## Try it!
Print arithmetic expressions in both the Python REPL and by running files.
