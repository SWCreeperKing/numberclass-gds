# how to use

create a new numberclass

```gdscript
var num: Numberclass = Numberclass.new(1)
```

numberclass has 2 parameters for its constructor:
`mantissa: float = 0` and `exponent: float = 0`

there is also a from string
supports:

- "123"
- "1e2"
- "1e2e3"

has _to_string() for string casts, only outputs in sci notation

has basic math operators like `num.add()`
most operators have float versions too
(but try not to use them because it creates a new numberclass everytime)
