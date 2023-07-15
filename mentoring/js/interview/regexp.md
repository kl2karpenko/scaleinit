### 1

Given the string 'aaa@bbb@ccc@ddd@ggg@www@'.

Find and replace all letters between "@ ... @" characters with spaces.

### 2

Write a regular expression that for each picture will add a closing slash at the end:

```js
const text = '<img src="a">   <img src="b" id="c">';

// text = text.replace(... place here your replacement ... )

// now text = '<img src="a"/>   <img src="b" id="c"/>'
```

### 3

Write a pattern that matches e-mail addresses.

The personal information part contains the following ASCII characters:

Uppercase (A-Z) and lowercase (a-z) English letters.
Digits (0-9).
Characters ! # $ % & ' * + - / = ? ^ _ ` { | } ~
Character . ( period, dot or fullstop) provided that it is not the first or last character and it will not come one after the other.

### 4

Create regexp that will find only positive digits in string

Example:

```js
var re = /* your regexp */

var str = "1.5 0 12. 123.4.";

alert( str.match(re) );   // 1.5, 0, 12, 123.4
```

### 5

Create a reg expression that will find all words that are written like this: WoRd and dump them into an array:

Example:

```js
var re = /* your regexp */

var str = "SoMeTiNg sPeCiAl happens EvErY day.";
```