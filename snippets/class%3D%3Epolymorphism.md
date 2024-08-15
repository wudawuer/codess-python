## class=>polymorphism
#### class=>polymorphism
class polymorphism example
```
class Parrot:

 def fly(self):
   print('Parrot can fly')

 def swim(self):
   print('Parrot can not swim')

class Penguin:

 def fly(self):
   print('Penguin can not fly')

 def swim(self):
   print('Penguin can swim')

# common interface
def flying_test(bird):
  bird.fly()

#instantiate objects
blu = Parrot()
peggy = Penguin()

# passing the object
flying_test(blu)
flying_test(peggy)
```

## class=>polymorphism
#### class=>polymorphism 1
class polymorphism example
```
class Parrot:

 def fly(self):
   print('Parrot can fly')

 def swim(self):
   print('Parrot can not swim')

class Penguin:

 def fly(self):
   print('Penguin can not fly')

 def swim(self):
   print('Penguin can swim')

# common interface
def flying_test(bird):
  bird.fly()

#instantiate objects
blu = Parrot()
peggy = Penguin()

# passing the object
flying_test(blu)
flying_test(peggy)
```