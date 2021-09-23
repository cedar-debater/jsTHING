# jsTHING

`( ) [ ] + !`

How jsTHING (work)s. Shows you the inner (work)ings. Hopefully it makes sense unless you're at (work).

Oh wait, my jokes don't (work)? My bad, I'll try to make them (work) better.

## Boolean: true/false

Let's start simple.

```
![] // false for weird reasons
!![] // true for weird reasons
```

Now for...

## Undefined: undefined

```
[][[]]
// get [] index from []
```

## String: "undefined"

```
undefined+[]
// add [] to undefined, coerce to string

[][[]]+[]
```

## Numbers: 0 and 1

0 is simple `+[]`

What that does is force `[]` into a number. It becomes 0.

1 is this: `+!![]`

As we saw before, `!![]` is `true` (for weird reasons) - when coerced into a number, it becomes 1.

By extension...

## Number: <*number to create*>

Simply repeat the code for 1 (`+!![]`) <*number to create*> times.

## Number: NaN

```
+undefined
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

Finally, we're ready.

## Function: Function (Part 3)

How do we get it? Here's how.

```
Function
<any function>.constructor
<any function>['constructor']
[].find['constructor']
[]['find']['constructor']
[][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]][([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+(![]+[])[+!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+([][[]]+[])[+[]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]]+(!![]+[])[+[]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+!![]]]
```

Okay, we got `Function`. But now...

## What next?

Well, we would want to prove you can run ANY code in jsTHING. We could do that with `Function(<normal code>)()`

Very simple, but there's mainly only one way (I can think of) to reliably make a string in jsTHING: `String.fromCharCode`

We can make numbers reliably in jsTHING (repeat `+!![]` <*number to make*> times). We can then pass them to `String.fromCharCode` and get any character we want. Once we concatenate many of these and put `Function(...)()` around that, TADA! Normal JS in jsTHING.

All we need now is String.fromCharCode; once we have that, we can turn any normal JS string into a jsTHING program (with some help from `Function`)

So let's try that.

## Function: String

Mostly simple.
```
([]+[])['constructor']
```

`[]+[]` becomes an empty string due to something called "type coercion"
Then we can get its constructor (which is String)

`([]+[])[([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+(![]+[])[+!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+([][[]]+[])[+[]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]]+(!![]+[])[+[]]+([][([][[]]+[])[+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+([][[]]+[])[+!![]+!![]]]+[])[+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+!![]]]`

Then we'll need `fromCharCode` - the distinct characters are `fromCharde`...

## String: "fromCharCode" (Part 1)

Right now, some of the strings we can get are:

```
"false" // []+![]
"true" // []+!![]
"undefined" // []+[][[]]
"function anonymous(\n) {\n\n}" // []+( Function() )
```

Let's go through them one by one, and see how they help:

### `"false"`

With `"false"`, we can get these bold letters: **f**romCh**a**rd**e**

### `"true"`

With `"true"`, we can get these bold letters: **r**omCh**r**d

### `"undefined"`

With `"undefined"`, we can get these bold letters: omCh**d**

### `"function anonymous(\n) {\n\n}"`

With that, we can get these bold letters: **om**Ch

## String: "fromCharCode" (Part 2)

We just need the letters `C` and `h`.

# TBC ->

<!-- Function()+[] => "function anonymous(\n) {\n\n}" -->
