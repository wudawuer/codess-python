## string.format_map=>
#### string.format_map=>
An example for using format_map
```
point = {'x':4,'y':-5}
print('{x} {y}'.format_map(point))

point = {'x':4,'y':-5, 'z': 0}
print('{x} {y} {z}'.format_map(point))
```