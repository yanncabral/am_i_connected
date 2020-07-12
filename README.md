# am_i_connected
This python3 package is the simplest way to check if there is internet connection.

you can install this library using `pip`. 

`pip install am_i_connected`

example of use:
```python
from am_i_connected import CheckThereIsConnection

if CheckThereIsConnection():
    print('You are connected! Amazing!')
else:
    print("Hey, you aren't connected...")
```