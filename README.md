# serial_db

Simple counter submodule. Unlike the auto-increment, the purpose is mainly for event count, not serialization. An additional is the serialized short unique id generation.  

## serialAdd
Adding a serial count with zero value.
```
serialAdd
```

## serialGet
Get a serial number and increment.
```
serialGet
```

## serialShortGet
Get a short unique and increment.
```
serialShortGet
```

## serialShow
Show the current serial status of a number without increment
```
serialShow
```
