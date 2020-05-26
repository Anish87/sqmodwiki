# Description

Move all occurrences of a slot with a speciffic function to the front so they receive the signal first.

# Specifications

* **Aliases**:
```D
SqSignalBase.LeadFunc
```
* **Signature**:
```D
(callback);
(callback, one);
(callback, one, append);
```
* **Parameters**:
	* **_callback_** `function` *The function that represents the callback in the slot.*
	* **_one_** `bool` *(optional) Limit the operation to one slot.*
	* **_append_** `bool` *(optional) Append instead of push when shuffling slots.*
* **Return**:
	* `integer` The number of times there was a match for the specified function.
* **Throws**:
	* This function may throw errors if any of the given parameters are not valid.

# Remarks

> No remarks available.

# Examples

> No example available.

# See also

* `function` [SqSignalBase.LeadFunc](Function.SqSignalBase.Lead)
* `function` [SqSignalBase.LeadThis](Function.SqSignalBase.LeadThis)

# References

> No references available.
