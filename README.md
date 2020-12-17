# nbdev Practice Project
> Practice.


This file will become your README and also the index of your documentation.

## Install

`pip install git+https://github.com/arunabha24/nbdev_practice.git@master`

## How to use

```python
from modules_practice.core import FileTextIO
file_1 = FileTextIO("file1.txt")
file_1.write("Writing before reading")
content = file_1.read()
print(content)
```

    ['Writing before reading']

