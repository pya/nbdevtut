# Reproduction of the `nbdev` Tutorial
> Trying to reproduce https://nbdev.fast.ai/tutorial.html


```python
%load_ext autoreload
%autoreload 2
```

This file will become your README and also the index of your documentation.

## Install

`pip install nbdevtut`

## How to use

Currently there is only one function:

```python
from nbdevtut import say_hello
```


    ---------------------------------------------------------------------------

    ImportError                               Traceback (most recent call last)

    <ipython-input-3-fbd9372688f6> in <module>
    ----> 1 from nbdevtut import say_hello
    

    ImportError: cannot import name 'say_hello' from 'nbdevtut' (/Users/mike/Dev/nbdev_tutorial/nbdevtut/nbdevtut/__init__.py)


```python
say_hello('Developer')
```




    'Hello Developer!'


