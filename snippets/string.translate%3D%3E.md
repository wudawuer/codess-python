## string.translate=>
#### string.translate=>
An example for using translate
```
# translation table - a dictionary
translation = {97: None, 98: None, 99: 105}

string = 'abcdef'
print('Original string:', string)

# translate string
print('Translated string:', string.translate(translation))
```