# Description

Collect into a container all the active Checkpoint entity instances that have a tag equal to the specified value.

# Specifications

* **Aliases**:
```D
SqCollect.Checkpoint.TagEquals
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

* `function` [SqCollect.Checkpoint.Active](Function.SqCollect.Checkpoint.Active)
* `function` [SqCollect.Checkpoint.TagEquals](Function.SqCollect.Checkpoint.TagEquals)
* `function` [SqCollect.Checkpoint.TagBegins](Function.SqCollect.Checkpoint.TagBegins)
* `function` [SqCollect.Checkpoint.TagEnds](Function.SqCollect.Checkpoint.TagEnds)
* `function` [SqCollect.Checkpoint.TagContains](Function.SqCollect.Checkpoint.TagContains)
* `function` [SqCollect.Checkpoint.TagMatches](Function.SqCollect.Checkpoint.TagMatches)

# References

> No references available.
