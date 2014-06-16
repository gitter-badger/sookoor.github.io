---
layout: post
title: "printf escape and format codes"
date: 2014-06-12 23:46:03 -0500
comments: true
categories: [c, printf]
---

The printf command can be called with the following escape and format codes:

| Escape Code | Output 
|:-|:-
| \a | audible alert (bell)
| \\ \\ | backslash
| \b | backspace
| \r | carriage return
| \\" | double quote
| \f | formfeed
| \t | horizontal tab
| \n | newline
| \0 | null character
| \\' | single quote
| \v | vertical tab
| \? | question mark

<br />

| Format Code | Output
|:-|:-
| d/i | Signed decimal integer
| o | Signed octal
| x/(X) | Unsigned hexadecimal integer (capital letters)
| ld | long decimal ['l' can also be applied to any of the above to change the type to 'long']
| u | Unsigned decimal integer
| lu | unsigned long decimal 
| c | Character
| s | String of characters
| f | Decimal floating point
| g/G | Use the shorter of %e/%E or %f
| e/E | Scientific notation (mantissa/exponent) using e/E character
| p | Pointer address
| n | Nothing printed 