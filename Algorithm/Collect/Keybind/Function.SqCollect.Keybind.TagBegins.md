# Description

Collect into a container all the active [SqKeybind](Class.SqKeybind) instances where the tag begins with the specified value.

# Specifications

* **Aliases**:
```D
SqCollect.Keybind.TagBegins
```
* **Signature**:
```D
(negate, sensitive, value);
```
* **Parameters**:
	* **_negate_** `bool` *The value `true` to negate the result of the comparison, `false` otherwise.*
	* **_sensitive_** `bool` *The value `true` to perform a case sensitive comparison, `false` otherwise.*
	* **_value_** `string` *The string value that should be searched for in the tag of each active [SqKeybind](Class.SqKeybind) instance.*
* **Return**:
	* `array` An array with all [SqKeybind](Class.SqKeybind) instances that matched the specified criteria.
* **Throws**:
	* This function may throw errors if any element fails to be appended to the array (*most likely due to memory limitations*).

# Remarks

> No remarks available.

# Examples

> No example available.

# See also

* `function` [SqCollect.Keybind.Active](Function.SqCollect.Keybind.Active)
* `function` [SqCollect.Keybind.TagEquals](Function.SqCollect.Keybind.TagEquals)
* `function` [SqCollect.Keybind.TagBegins](Function.SqCollect.Keybind.TagBegins)
* `function` [SqCollect.Keybind.TagEnds](Function.SqCollect.Keybind.TagEnds)
* `function` [SqCollect.Keybind.TagContains](Function.SqCollect.Keybind.TagContains)
* `function` [SqCollect.Keybind.TagMatches](Function.SqCollect.Keybind.TagMatches)

# References

> No references available.
