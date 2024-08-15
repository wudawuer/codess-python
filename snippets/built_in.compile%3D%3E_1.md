## built_in.compile=>_1
#### built_in.compile=>_1
An example for using compile
```
mytext = 'print(55)'
x = compile('mytext', 'test', 'eval')
exec(x)
```

## built_in.compile=>_1
#### built_in.compile=>_2
An example for using compile
```
mytext = 'print(55)
print(88)'
x = compile('mytext', 'test', 'exec')
exec(x)
```