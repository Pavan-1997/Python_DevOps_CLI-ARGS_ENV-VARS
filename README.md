# Python_DevOps_Command-Line-Arguments_Environment-Variables

## Command Line Argunents

We make use of `sys` keyword to retrieve values from the command line input. This module comes as deafult with Python installation but not from PYPI

```
# test.py

import sys

print (num1)
num1 = int(sys.argv[1])
```

Now when we exceute it 

```
python test.py 12
``` 
