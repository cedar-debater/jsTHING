# jsTHING

Doing things with jsTHING instead of Pure JS

`( ) [ ] + !`

## Boolean: true/f

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

## Number: n

Let `n` be the number.

(`++[` repeated n times) concatenated with (`[+[]]]` repeated n times)
evaluates to n

Generation functions:

`generateNumber=n=>('++['.repeat(n)+'[+[]]]'.repeat(n)); // JavaScript`

`generate_number = lambda n:''.join(['++['*n,'[+[]]]'*n]) # Python`

## Number: NaN

```+undefined
// Undefined cannot be converted to a number properly, so becomes NaN

+[][[]]
```

## Function: [].find

```[][
    "undefined"[4]+
    "undefined"[5]+
    "undefined"[6]+
    "undefined"[8]
]

[][([][[]]+[])[++[++[++[++[+[]][+[]]][+[]]][+[]]][+[]]]+([][[]]+[])[++[++[++[++[++[+[]][+[]]][+[]]][+[]]][+[]]][+[]]]+([][[]]+[])[++[++[++[++[++[++[+[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+([][[]]+[])[++[++[++[++[++[++[++[++[[+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]
```

## Function: Function (Part 1)

Idea: `[].find['constructor']`

We have `[].find` from the previous one. Now we need to index `'constructor'` from it to get `Function`.

We need the letters `constru`.

Let's start with...

## String: "u"/"n"

```
"undefined"[0]

([][[]]+[])[+[]]
```

Nice and easy. Similar for `n`, which is made with `"undefined"[1]`

`([][[]]+[])[++[+[]][+[]]]`

`t` and `r` are both in `true`, so

## String: "t"/"r"

```
(true + [])[0]
"true"[0]

(!![])[+[]]
```

Similar for `r`, it's gotten with `"true"[1]`.

`(!![])[++[+[]][+[]]]`

It's harder now. We have a few characters left to get...

## Function: Function (Part 2)

We need the letters `constru`.

We've gotten `untr`.

That leaves the letters `cos`.

## TBC ->
