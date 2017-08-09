# App v1: Hello World

**Description**

The hello world application is exactly what it says: an application that prompts
the user for their name, and it will echo back their name.

This app will allow us to:

* Verify our python environmental
* Basic syntax, strings, variables, concatenation
* Accepting input from user
* Console output
* Getting familiar with our IDE

Concept: Calling Functions

Function invocations start with a name, then parentheses.

The input function takes a string, and returns another string using 
the 'saying' variable.

```python
main() #Main function takes/returns no arguments

saying = input("Enter your favorite string")

```

Concept: Variables

Variables are first declared upon assigment. Note that Python
is dynamically typed unlike Go.

Variables can be assigned literals or initialized from function return
values.

```python

name = 'Toby'   #string
age = 7         #int
age += 1        #adding to int

hobbies = ['barking', 'eating', 'fetching', 'petting']  #list

def load_address_from_db(n)     #func
    return name + 'lives at 123 main street'

home_address = load_address_from_db(name)
```

In Python, we're all about the underscore in terms of programming/languages.


What have I learned from this App?
* Print function
* Passing in string literals as argument
* Calling input function
* Capturing input into a variable
* Concatenating strings