## built_in.issubclass=>
#### built_in.issubclass=>
An example for using isinstance
```
class myAge:
 age = 36

class myObj(myAge):
 name = 'John'
 age = myAge

 x = issubclass(myObj, myAge)

print(x)
```