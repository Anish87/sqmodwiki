# Description

Collect into a container all the active [SqPickup](Class.SqPickup) instances where the tag begins with the specified value.

# Specifications

* **Aliases**:
```D
SqCollect.Pickup.TagBegins
```
* **Signature**:
```D
(negate, sensitive, value);
```
* **Parameters**:
	* **_negate_** `bool` *The value `true` to negate the result of the comparison, `false` otherwise.*
	* **_sensitive_** `bool` *The value `true` to perform a case sensitive comparison, `false` otherwise.*
	* **_value_** `string` *The string value that should be searched for in the tag of each active [SqPickup](Class.SqPickup) instance.*
* **Return**:
	* `array` An array with all [SqPickup](Class.SqPickup) instances that matched the specified criteria.
* **Throws**:
	* This function may throw errors if any element fails to be appended to the array (*most likely due to memory limitations*).

# Remarks

> No remarks available.

# Examples

> No example available.

# See also

* `function` [SqCollect.Pickup.Active](Function.SqCollect.Pickup.Active)
* `function` [SqCollect.Pickup.TagEquals](Function.SqCollect.Pickup.TagEquals)
* `function` [SqCollect.Pickup.TagBegins](Function.SqCollect.Pickup.TagBegins)
* `function` [SqCollect.Pickup.TagEnds](Function.SqCollect.Pickup.TagEnds)
* `function` [SqCollect.Pickup.TagContains](Function.SqCollect.Pickup.TagContains)
* `function` [SqCollect.Pickup.TagMatches](Function.SqCollect.Pickup.TagMatches)

# References

> No references available.
