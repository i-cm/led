## LED random
First, a block!
That is...
Toggle led!

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```
Second, random x and y

```blocks
led.toggle(randint(0, 4), randint(0, 4))

```

Third, play

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
