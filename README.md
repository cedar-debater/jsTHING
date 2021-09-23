# jsTHING

`( ) [ ] + !`

How jsTHING (work)s. Shows you the inner (work)ings. Hopefully it makes sense unless you're at (work).

Oh wait, my jokes don't (work)? My bad, I'm trying to (work).

## Boolean: true/false

Let's start simple.

```
![] // false
!![] // true
```

Now for...

## Undefined: undefined

```
[][[]]
// get [] index from []
```

## String: "undefined"

```undefined+[]
// add [] to undefined, coerce to string

[][[]]+[]
```

## Number: 1

`+!![]`

By extension...

## Number: n

Repeat `+!![]` n times.

## Number: NaN

```+undefined
// Undefined cannot be converted to a number properly, so becomes NaN

+[][[]]
```

## Function: [].find

```
[][
    "undefined"[4]+
    "undefined"[5]+
    "undefined"[1]+
    "undefined"[2]
]

[][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]
```

## Function: Function (Part 1)

How do we get this? My answer: `[]['find']['constructor']`

We just found `[]['find']`. Now we need to index `'constructor'` from it to get `Function`.

We need the letters: `constru`

Let's start with...

## String: "u"/"n"

```
"undefined"[0]

([][[]]+[])[+[]]
```

Nice and easy. Similar for `n`, which is made with `"undefined"[1]`

`([][[]]+[])[+!![]]`

`t` and `r` are both in `true`, so

## String: "t"/"r"

```
(true + [])[0]
"true"[0]

(!![]+[])[+[]]
```

Similar for `r`, it's gotten with `"true"[1]`.

`(!![]+[])[+!![]]`

What about `s`?

## String: "s"

If you think, it's just `"false"[3]` which becomes `(![]+[])[+!![]+!![]+!![]]`

It's harder now. We have 2 more characters left to get...

## Function: Function (Part 2)

We needed the letters `constru`

We've gotten `nstru`

That leaves the 2 letters `co`

Luckily, they are both in...

## <s>Function: find</s> String: "function find() { [native code] }"

... which is made with `[]['find']+[]`.

Here's the jsTHING version:

`[][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[]`

(remember brackets if you're using this yourself)

Now for the letters `co`.

## String: "c", "o", "co"

`c`: `([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]]`

`o`: `([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]+!![]+!![]+!![]]`

`co`: `([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]+!![]+!![]+!![]]`

Putting it all together:

## String: "constructor"

Just find the jsTHING version of each character (one by one) and put `+` in between. "c" + "o" + "n" + ...

`([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+(![]+[])[+!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+([][[]]+[])[+[]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]]+(!![]+[])[+[]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+!![]]`

## TBC ->
