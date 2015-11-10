This package provide you some methods to easily deal with

# Install
```
npm install query-string
```
# Usage

## .extract
Type: `string`  
Default: ``

This function will extract the second part of the given string which will be cut with "?".
If null, the function will return an empty string.
For example :
```txt
  var result = query-string.extract("kelvinhado.com?apiKey=34567")
  // result value : apiKey=34567
```

## .parse
Type: `table[key, val]`  
Default: `{}`

This function parse a string into a table of object key<->value


## .stringify

to Stringify an object.

> Parse and stringify URL [query strings](http://en.wikipedia.org/wiki/Query_string)
