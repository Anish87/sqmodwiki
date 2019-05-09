# Description

Collect into a container all the active [SqObject](Class.SqObject) instances where the tag begins with the specified value.

# Specifications

* **Aliases**:
```D
SqCollect.Object.TagBegins
```
* **Signature**:
```D
(negate, sensitive, value);
```
* **Parameters**:
	* **_negate_** `bool` *The value `true` to negate the result of the comparison, `false` otherwise.*
	* **_sensitive_** `bool` *The value `true` to perform a case sensitive comparison, `false` otherwise.*
	* **_value_** `string` *The string value that should be searched for in the tag of each active [SqObject](Class.SqObject) instance.*
* **Return**:
	* `array` An array with all [SqObject](Class.SqObject) instances that matched the specified criteria.
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
