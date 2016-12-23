# Empty

*empty* is the most useless package ever. It does nothing at all!
It is just an empty module.

You can use it, for example,
to store global variables that you can share between modules.
Don't use *global*. This is a bit cleaner because it does not pollute the namespace.

Add variables as empty.var = val,
then import the module somewhere else and use them as empty.var

Don't blame me if it does not work ;)

## Install
<code>python setup.py install</code>