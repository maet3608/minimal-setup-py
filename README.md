# A minimal setup.py

It is easy to start with Python scripting but soon the number of files and their dependecies start to grow.
An all-to-common solution to fix the then occuring errors regarding functions not found or modules that
cannot be imported is to modify PYTHONPATH. Don't do it!

`setup.py` avoids all the problems that come with tweaking Python's search path and will give you
packages that can easily be installed on other machines. Unfortunately the documentation on how
to create `setup.py` is rather complex and intimidating. A simple, minimal example is lacking.

Well here it is! Put it in the root folder of your project folder, adjust the properties 
such as author's name, install requirements, make sure you have `__init.py__` files for all
packages and you are good to go.

Use one of the following commands for installation:

```
python setup.py install
```

or

```
python setup.py develop
```

