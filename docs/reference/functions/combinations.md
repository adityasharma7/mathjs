# Function combinations

Compute the number of ways of picking `k` unordered outcomes from `n` possibilities.

Combinations only takes integer arguments. The following condition must be enforced: k <= n.


## Syntax

```js
math.combinations(n, k)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------


### Returns

Type | Description
---- | -----------
Number &#124; BigNumber | Number of possible combinations.


## Examples

```js
var math = mathjs();

math.combinations(7, 5); // returns 21
```


## See also

[permutations](permutations.md),
[factorial](factorial.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->