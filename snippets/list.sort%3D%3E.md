## list.sort=>
#### list.sort=>
An example for using sort
```
cars = ['Ford', 'BMW', 'Volvo']
cars.sort()
print(cars)
```

## list.sort=>
#### list.sort=> 1
An example for using sort
```
cars = ['Ford', 'BMW', 'Volvo']
cars.sort(reverse=True)
print(cars)
```

## list.sort=>
#### list.sort=> 2
An example for using sort
```
# A function that returns the length of the value:
def myFunc(e):
  return len(e)
cars = ['Ford', 'Mitsubishi', 'BMW', 'VW']
cars.sort(key=myFunc)
print(cars)
```

## list.sort=>
#### list.sort=> 3
An example for using sort
```
# A function that returns the length of the value:
def myFunc(e):
  return len(e)
cars = ['Ford', 'Mitsubishi', 'BMW', 'VW']
cars.sort(reverse=True, key=myFunc)
print(cars)
```