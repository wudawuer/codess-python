## built_in.delattr=>_1
#### built_in.delattr=>_1
An example for using delattr
```
class Person:
 name = 'John'
 age = 36
 country = 'Norway'

delattr(Person, 'age')
# The Person object will no longer contain an age property
```