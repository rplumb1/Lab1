# Lab1

```python
from datetime import datetime


def howold():

  currentyear = datetime.now().year

  birthday = int(input('What year were you born? '))

  age = currentyear - birthday

  return age
  
  
  
age = howold()
print('You are ' + str(age) + ' years old.') 
```
