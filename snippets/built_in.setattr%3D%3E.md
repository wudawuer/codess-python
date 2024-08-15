## built_in.setattr=>
#### built_in.setattr=>
An example for using setattr
```
class Person:
  name = 'John'
  age = 36
  country = 'Norway'
setattr(Person, 'age', 40)
# The age property will now have the value: 40
x = getattr(Person, 'age')
print(x)
```