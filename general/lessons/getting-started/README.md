## What is Python?
 * High-level programming language
 * Named after Monty Python
 * Used for programming servers and all sorts of things

## Installing Python
On Macs, Python should come preinstalled. Otherwise, click [here](https://www.python.org/). The click `Downloads` and find the latest version of Python 3.

## Git
Git is a *version control system* (VCS) that allows you to save your code to [GitHub](https://github.com/) and collaborate on projects. It's very nice. There will be a [lesson on Git and GitHub]({{ "/general/lessons/git" | absolute_url }}) later, but for now just [install it](https://git-scm.com/downloads). On a Mac, Git will automatically install itself when you try to use it.

## Command prompt/terminal
**Windows:** Run *Git Bash* from the start menu. Consider getting Linux.

**Linux:** Open a terminal window.

**Mac OSX:** Run *Terminal* from Applications. Consider getting Linux.

The terminal is where you type commands, and your computer does them. Be careful not to break your computer. You use the terminal for running programs, editing files in Vim, navigating files (like file explorer, but better), and doing just about anything you want. In terminal, you can press tab to autocomplete and the up (and down) arrow to go to previous commands.

## Running the Python REPL
Type `python` into your terminal and hit enter. You should see something like this:

    Python 3.5.2 (default, Nov 23 2017, 16:37:01)
    [GCC 5.4.0 20160609] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

This is the **Python Read-Evaluate-Print Loop (REPL)**.

If it doesn’t look exactly like this, don’t worry. As long as it says `Python 3.x.x` and has the `>>>` prompt, everything is working properly.

To test that this works, type `print ("Hello, world!")` after the `>>>` prompt. If it says `Hello, world!` back to you, it works.
