# Description

Collect into a container all the active Blip entity instances that have a tag equal to the specified value.

# Specifications

* **Aliases**:
```D
SqCollect.Blip.TagEquals
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

* `function` [SqCollect.Blip.Active](Function.SqCollect.Blip.Active)
* `function` [SqCollect.Blip.TagEquals](Function.SqCollect.Blip.TagEquals)
* `function` [SqCollect.Blip.TagBegins](Function.SqCollect.Blip.TagBegins)
* `function` [SqCollect.Blip.TagEnds](Function.SqCollect.Blip.TagEnds)
* `function` [SqCollect.Blip.TagContains](Function.SqCollect.Blip.TagContains)
* `function` [SqCollect.Blip.TagMatches](Function.SqCollect.Blip.TagMatches)

# References

> No references available.
