# MD5
Python implementation of md5, a Message-Digest algorithm

## Function
md5: calculate md5(message)  
md5_lea: calculate md5(message + padding + suffix) when you only know md5(message) and len(message)  

## Usage
```python
from MD5 import md5, md5_lea
s = md5('abc')
print(s)
print(md5_lea('a', s, 3))
# Out: 900150983cd24fb0d6963f7d28e17f72
#      9485808412f89f2b5693bb9f6afd16be
```
