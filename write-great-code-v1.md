My notes from [Write Great Code - Understanding Machine](https://www.amazon.com/Write-Great-Code-Understanding-Machine/dp/1593270038)
===

>In order to write great code, you need to know how to write efficient code,
>and to write efficient code, you must understand how computer systems
>execute programs and how abstractions found in programming languages
>map to the low-level hardware capabilities of the machine.

Table of contents
---
<!-- TOC -->

- [Some attributes of `Great Code`](#some-attributes-of-great-code)
- [Number](#number)
- [Numbering systems](#numbering-systems)
    - [Convert `binary` to `decimal`](#convert-binary-to-decimal)
    - [Convert `decimal` to `binary`](#convert-decimal-to-binary)

<!-- /TOC -->

### Some attributes of `Great Code`
 * Uses the CPU efficiently (is fast)
 * Uses memory efficiently
 * Is easy to read and maintain
 * Has consistent style
 * Is easy to enhance
 * Is well tested
 * Is well documented

### Number
`Number` is an intangible, abstract concept used to denote `quantity` and can be represented in several ways.

### Numbering systems
To represent numeric values we use `positional notation systems` which can use at most 36 symbols (As name suggests, it not only takes into consideration the symbol itself, but it's position in sequence of symbols.)

10 Arabic (Developed by Arabs) numbers: 0-9 </br>
26 Alphabets : a-z/A-Z (Case insensitive) </br>

To create `base-n` system, we need `n` unique symbols

| Numbering system | Base (Radix) | Symbols |
|---|---|---|
|Binary|2|0,1|
|Octal|8|0-7|
|Decimal|10|0-9|
|Hexadecimal|16|0-9,A-Z|

#### Convert `binary` to `decimal`
Add `2^i` for each `i` in binary string

#### Convert `decimal` to `binary`
See my [gist](https://gist.github.com/pradippatil/e9c345d7f8b7a9d10a5bbb09cca18488) in Go: 





