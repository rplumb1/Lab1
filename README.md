# Lab1

```python
from datetime import datetime


def howold():
  try:
  
    currentyear = datetime.now().year

    birthday = int(input('What year were you born? '))

    age = currentyear - birthday

    return age

  except TypeError:
     
     print('“Please enter an int”')
  
  
  
age = howold()
print('You are ' + str(age) + ' years old.') 
```
