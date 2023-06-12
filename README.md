# Lab2

```python

import sys


def scriptandvariables():

  script = sys.argv[0]

  variables = sys.argv[1:]

  print('These are the variables - ' + str(variables))
  
  print('The script name is ' + str(script))
  
  print(script, variables)

scriptandvariables()


```
