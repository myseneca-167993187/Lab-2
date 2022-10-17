## The following code below is for a python function that uses command line arguements to display the script and variable names.

```

#!/usr/bin/env python3

import sys

def intro():
    name = str(sys.argv[1])
    age = int(sys.argv[2])
    scriptname = str(sys.argv[0])
    arguments = str(sys.argv)

    print('Hi ' + name + ', you are ' + str(age) + ' years old.')
    print('Variable1 = ' + name)
    print('Variable2 = ' + str(age))
    print('The script and variables used are: ' + arguments)
intro()

def helloWorld():
	print(‘Hello World’)


helloWorld()

```
