# Assignment - Functions

1. What is definition of function?
2. What is the function call?
3. What is code block and how does it relate to a function?
4. Create a function that will take a string as an argument and greet the user. For example, if the function is called with "John", the function should return "Hello, John!".
5. Create a function that takes a string as an argument and returns a string with the argument value in reverse. For example, if the function is called with input "hello", the function should return "olleh". **(Use a loop, not a method that does this in one step.)**
6. What is default argument and how does it work?
7. What is scope and lifetime of a variable?
8. What is a return value?
9. What is return value of a function that does not have a return statement?
10. Given the following function, find mistakes in the code and explain what the function is supposed to do.
    ```python
    def foo(x):
        x * 2
    
    x = 7
    x = foo(x)
    print(x)
    ```
11. Given the following code, find and correct the mistake in the code.
    ```python
    def bar(x):
        x += 1

    def foo(x):
        bar(x)
        x *= 2
    
    x = 7
    foo(x)
    print(x)
    ```
12. Given the following function, what is the return value of the function call `foo(2)`? Explain your answer.
    ```python
    def foo(x):
        if x > 5:
            return x
        else:
            return x + foo(x + 1)
    ```
13. Create a function that takes a list of numbers as an argument and returns the sum of the odd numbers in the list. **(Use a loop, not a method that does this in one step.)**
14. Create a function that takes a string as an argument and returns a dictionary with the count of each character in the string. For example, if the function is called with "hello", the function should return `{'h': 1, 'e': 1, 'l': 2, 'o': 1}`. **(Use a loop, not a method that does this in one step.)**
15. Create a function that takes a string as an argument and returns a dictionary with the count of each word in the string. For example, if the function is called with "hello world", the function should return `{'hello': 1, 'world': 1}`. **(Use a loop, not a method that does this in one step.)**
16. Create a function that takes a string as an argunment and returns `True` if string is a Palindrome else `False`. Palindrome is a word that reads the same backward as forward. For example, if the function is called with `"elle"` the function should return `True`, if function receives `"Hello"` it should return `False` 
