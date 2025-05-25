```
➜  lifetime_learner git:(master) ✗ ipython
Python 3.13.3 (main, Apr  8 2025, 13:54:08) [Clang 17.0.0 (clang-1700.0.13.3)]
Type 'copyright', 'credits' or 'license' for more information
IPython 9.2.0 -- An enhanced Interactive Python. Type '?' for help.
Tip: Use `--theme`, or the `%colors` magic to change IPython's themes and colors.

In [1]: len?
Signature: len(obj, /)
Docstring: Return the number of items in a container.
Type:      builtin_function_or_method

In [2]: L = [1,2,3]

In [3]: L.insert?
Signature: L.insert(index, object, /)
Docstring: Insert object before index.
Type:      builtin_function_or_method

In [4]: L?
Type:        list
String form: [1, 2, 3]
Length:      3
Docstring:  
Built-in mutable sequence.

If no argument is given, the constructor creates a new empty list.
The argument must be an iterable if specified.

In [5]: def square(a):
   ...:     """Return the square of a.""""
  Cell In[5], line 2
    """Return the square of a.""""
                                 ^
SyntaxError: unterminated string literal (detected at line 2)


In [6]: def square(a):
   ...:     """Return the square of a."""
   ...:     return a ** 2
   ...: 

In [7]: square?
Signature: square(a)
Docstring: Return the square of a.
File:      ~/workspace/lifetime_learner/<ipython-input-6-0cb64132186d>
Type:      function

In [8]: square??
Signature: square(a)
Source:   
def square(a):
    """Return the square of a."""
    return a ** 2
File:      ~/workspace/lifetime_learner/<ipython-input-6-0cb64132186d>
Type:      function

In [9]: 
```