# jsTHING

Doing things with jsTHING instead of Pure JS

## Undefined: undefined

`[][[]]
// get [] index from []`

## String: "undefined"

`undefined+[]
// add [] to undefined, coerce to string

[][[]]+[]`

## Number: n

Let `n` be the number.

`++[` repeated n times concatenated with `[+[]]]` repeated n times
evaluates to n

generation:

`generateNumber=n=>('++['.repeat(n)+'[+[]]]'.repeat(n)); // JavaScript`

`generate_number = lambda n:''.join(['++['*n,'[+[]]]'*n]) # Python`

## Number: NaN

`+undefined
// Undefined cannot be converted to a number properly, so becomes NaN

+[][[]]`

## [].find

`[][
    "undefined"[4]+
    "undefined"[5]+
    "undefined"[6]+
    "undefined"[8]
]

[][([][[]]+[])[++[++[++[++[+[]][+[]]][+[]]][+[]]][+[]]]+([][[]]+[])[++[++[++[++[++[+[]][+[]]][+[]]][+[]]][+[]]][+[]]]+([][[]]+[])[++[++[++[++[++[++[+[]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]+([][[]]+[])[++[++[++[++[++[++[++[++[[+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]][+[]]]]`
