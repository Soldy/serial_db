# serial_db

Simple counter submodule. Unlike the auto-increment, the purpose is mainly for event count, not serialization. An additional is the serialized short unique id generation.  

## Functions

### serialAdd
Adding a serial count with zero value.
```
serialAdd
```

### serialGet
Get a serial number and increment. Please note all the Get functions will automatically increment the value.
```
serialGet
```

### serialShortGet

Get a short unique string, and increment the value. Please note this is not a UUID. The goal is a serialized unique. This function is still WIP.
```
serialShortGet
```

### serialShow

Show the current serial status of a number without incrementing the value.

```
serialShow
```


## Procedures

### serial list
List all the existing values. Not increment any values.
```
serialList
```
