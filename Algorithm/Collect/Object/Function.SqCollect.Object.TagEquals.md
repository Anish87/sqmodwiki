# Description

Collect into a container all the active Object entity instances that have a tag equal to the specified value.

# Specifications

* **Aliases**:
```D
SqCollect.Object.TagEquals
```
* **Signature**:
```D
(negate, sensitive, value);
```
* **Parameters**:
	* **_negate_** `bool` *The value `true` to negate the result of the comparison, `false` otherwise.*
	* **_sensitive_** `bool` *The value `true` to perform a case sensitive comparison, `false` otherwise.*
	* **_value_** `string` *The string value that should be compared with the tag of each active entity instance.*
* **Return**:
	* `array` An array with all entity instances that matched the specified criteria.
* **Throws**:
	* This function may throw errors if any element fails to be appended to the array (*most likely due to memory limitations*).

# Remarks

> No remarks available.

# Examples

> No example available.

# See also

* `function` [SqCollect.Object.Active](Function.SqCollect.Object.Active)
* `function` [SqCollect.Object.TagEquals](Function.SqCollect.Object.TagEquals)
* `function` [SqCollect.Object.TagBegins](Function.SqCollect.Object.TagBegins)
* `function` [SqCollect.Object.TagEnds](Function.SqCollect.Object.TagEnds)
* `function` [SqCollect.Object.TagContains](Function.SqCollect.Object.TagContains)
* `function` [SqCollect.Object.TagMatches](Function.SqCollect.Object.TagMatches)

# References

> No references available.
