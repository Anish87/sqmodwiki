# Description

Move all occurrences of a speciffic slot to the front so they receive the signal first.

# Specifications

* **Aliases**:
```D
SqSignalBase.Lead
```
* **Signature**:
```D
(callback);
(environment, callback);
(environment, callback, one);
(environment, callback, one, append);
```
* **Parameters**:
	* **_environment_** `object` *(optional) The object that represents the environment in the slot.*
	* **_callback_** `function` *The function that represents the callback in the slot.*
	* **_one_** `bool` *(optional) Limit the operation to one slot.*
	* **_append_** `bool` *(optional) Append instead of push when shuffling slots.*
* **Return**:
	* `integer` The number of times there was a match for the specified slot.
* **Throws**:
	* This function may throw errors if any of the given parameters are not valid.

# Remarks

If the environment parameter is not specified. The current root table will be used instead.

# Examples

> No example available.

# See also

* `function` [SqSignalBase.LeadThis](Function.SqSignalBase.LeadThis)
* `function` [SqSignalBase.LeadFunc](Function.SqSignalBase.LeadFunc)

# References

> No references available.
