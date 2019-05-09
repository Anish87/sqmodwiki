# Description

Collect into a container all the active [SqBlip](Class.SqBlip) instances where the tag matches the specified mask.

# Specifications

* **Aliases**:
```D
SqCollect.Blip.TagMatches
```
* **Signature**:
```D
(negate, sensitive, value);
```
* **Parameters**:
	* **_negate_** `bool` *The value `true` to negate the result of the comparison, `false` otherwise.*
	* **_sensitive_** `bool` *The value `true` to perform a case sensitive comparison, `false` otherwise.*
	* **_value_** `string` *The mask that should be compared with the tag of each active [SqBlip](Class.SqBlip) instance.*
* **Return**:
	* `array` An array with all [SqBlip](Class.SqBlip) instances that matched the specified criteria.
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
