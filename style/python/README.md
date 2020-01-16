# Python
Python is the primary language used for a Django-centric backend. 
We use PyCharm as our primary IDE; to ensure proper code formatting and compatibility with our projects, import [these settings](./settings.jar) into PyCharm.

For the most part, we follow the [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html).

## Typing and Annotations

[As of Python 3.5](https://docs.python.org/3/library/typing.html), typing and annotations have been officially included in the language. 
These annotations don't necessarily turn Python into a typed language, 
however most IDEs support type hinting which will warn the user whenever an unexpected or invalid type is assigned to a variable or returned by a function.
It is ideal to attempt to annotate/type functions and variables wherever it is reasonable to do so.

[This tutorial](https://realpython.com/python-type-checking/) offers a comprehensive guide on how and why typing and annotations are implemented.
