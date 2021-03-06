# Function pow

Calculates the power of x to y, `x ^ y`.
Matrix exponentiation is supported for square matrices `x`, and positive
integer exponents `y`.


## Syntax

```js
math.pow(x, y)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; BigNumber &#124; Boolean &#124; Complex &#124; Array &#124; Matrix | The base
`y` | Number &#124; BigNumber &#124; Boolean &#124; Complex | The exponent

### Returns

Type | Description
---- | -----------
Number &#124; BigNumber &#124; Complex &#124; Array &#124; Matrix | The value of `x` to the power `y`


## Examples

```js
math.pow(2, 3);               // returns Number 8

var a = math.complex(2, 3);
math.pow(a, 2)                // returns Complex -5 + 12i

var b = [[1, 2], [4, 3]];
math.pow(b, 2);               // returns Array [[9, 8], [16, 17]]
```


## See also

[multiply](multiply.md),
[sqrt](sqrt.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->
