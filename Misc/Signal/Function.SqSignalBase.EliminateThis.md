# Description

Eliminate all occurrences of a speciffic environment.

# Specifications

* **Aliases**:
```D
SqSignalBase.EliminateThis
```
* **Signature**:
```D
(environment);
```
* **Parameters**:
	* **_environment_** `object` *(optional) The object that represents the environment in the slot.*
* **Return**:
	* `integer` The number of times there was a match for the specified environment.
* **Throws**:
	* This function may throw errors if any of the given parameters are not valid.

# Remarks

If the environment parameter is not specified. The current root table will be used instead.

# Examples

> No example available.

# See also

* `function` [SqSignalBase.EliminateFunc](Function.SqSignalBase.Eliminate)
* `function` [SqSignalBase.EliminateThis](Function.SqSignalBase.EliminateThis)

# References

> No references available.
