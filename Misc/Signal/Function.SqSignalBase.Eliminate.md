# Description

Remove all occurrences of a speciffic slot.

# Specifications

* **Aliases**:
```D
SqSignalBase.Eliminate
```
* **Signature**:
```D
(callback);
(environment, callback);
```
* **Parameters**:
	* **_environment_** `object` *(optional) The object that represents the environment in the slot.*
	* **_callback_** `function` *The function that represents the callback in the slot.*
* **Return**:
	* `integer` The number of times there was a match for the specified slot.
* **Throws**:
	* This function may throw errors if any of the given parameters are not valid.

# Remarks

If the environment parameter is not specified. The current root table will be used instead.

# Examples

> No example available.

# See also

* `function` [SqSignalBase.EliminateThis](Function.SqSignalBase.EliminateThis)
* `function` [SqSignalBase.EliminateFunc](Function.SqSignalBase.EliminateFunc)

# References

> No references available.
