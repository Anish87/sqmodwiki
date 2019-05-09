# Description

Collect into a container all the active Vehicle entity instances that have a tag equal to the specified value.

# Specifications

* **Aliases**:
```D
SqCollect.Vehicle.TagEquals
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

* `function` [SqCollect.Vehicle.Active](Function.SqCollect.Vehicle.Active)
* `function` [SqCollect.Vehicle.TagEquals](Function.SqCollect.Vehicle.TagEquals)
* `function` [SqCollect.Vehicle.TagBegins](Function.SqCollect.Vehicle.TagBegins)
* `function` [SqCollect.Vehicle.TagEnds](Function.SqCollect.Vehicle.TagEnds)
* `function` [SqCollect.Vehicle.TagContains](Function.SqCollect.Vehicle.TagContains)
* `function` [SqCollect.Vehicle.TagMatches](Function.SqCollect.Vehicle.TagMatches)

# References

> No references available.
