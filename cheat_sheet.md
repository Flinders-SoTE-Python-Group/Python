Derived from "learn python the hard way"

| Keyword | Description | Example |
| ------- | ----------- | ------- |
| ```as```      | part of "with-as" | ```with X as Y: pass``` |
| ```assert```  | ensure something is true | ```assert False, "Error!"``` |
| ```continue``` | same as cycle in Fortran | ```while True: continue``` |
| ```del```     | delete from dictionary | ```del X[Y]``` |
| ```except```  | if exception, do this | ```except ValueError, e: print e``` |
| ```exec```    | run string as Python   | ```exec 'print "Hello"'``` |
| ```finally ```| do this no matter what | ``` finally: pass  ```|
| ```global ``` | define global variable | ``` global x  ```|
| ```is ```     | like "==" to test equality | ``` 1 is 1 == True  ```|
| ```lambda ``` | create short anonymous function | ``` s=Lambda y:y**y; s(3)  ```|
| ```pass ```   | this block is empty | ``` def empty(): pass  ```|
| ```raise ```  | raise exception | ```raise ValueError("No")   ```|
| ```try ```    | try block and if exception go to except | ```try: pass   ```|
| ```with ```   | with an expression as a variable do | ``` with X as Y: pass  ```|
| ```yield ```  | pause here and return to caller | ``` def(x): yield Y; X().next()  ```|

## Type
```python
True, False, None, str, int, float, list, dict
```

## Escape sequences
| Sequence | Meaning |
| --- | --- |
| \\  | Backslash (\) |
| \'  | Single quote |
| \"  | Double quote |
| \a  | ASCII Bell   |
| \b  | ASCII Backspace |
| \f  | ASCII Formfeed |
| \n  | ASCII Linefeed |
| \t  | ASCII Carriage Return |
| \v  | ASCII Vertical Tab |

## String Formats
```%d, %i ``` (integers) 
