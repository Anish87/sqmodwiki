# Description

Collect into a container all the active Player entity instances where the tag ends with the specified value.

# Specifications

* **Aliases**:
```D
SqCollect.Player.TagEnds
```
* **Signature**:
```D
(negate, sensitive, value);
```
* **Parameters**:
	* **_negate_** `bool` *The value `true` to negate the result of the comparison, `false` otherwise.*
	* **_sensitive_** `bool` *The value `true` to perform a case sensitive comparison, `false` otherwise.*
	* **_value_** `string` *The string value that should be searched for in the tag of each active entity instance.*
* **Return**:
	* `array` An array with all entity instances that matched the specified criteria.
* **Throws**:
	* This function may throw errors if any element fails to be appended to the array (*most likely due to memory limitations*).

# Remarks

> No remarks available.

# Examples

> No example available.

# See also

* `function` [SqCollect.Player.Active](Function.SqCollect.Player.Active)
* `function` [SqCollect.Player.TagEquals](Function.SqCollect.Player.TagEquals)
* `function` [SqCollect.Player.TagBegins](Function.SqCollect.Player.TagBegins)
* `function` [SqCollect.Player.TagEnds](Function.SqCollect.Player.TagEnds)
* `function` [SqCollect.Player.TagContains](Function.SqCollect.Player.TagContains)
* `function` [SqCollect.Player.TagMatches](Function.SqCollect.Player.TagMatches)

# References

> No references available.
