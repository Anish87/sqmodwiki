# Description

Move all occurrences of a slot with a speciffic environment to the back so they receive the signal last.

# Specifications

* **Aliases**:
```D
SqSignalBase.TailThis
```
* **Signature**:
```D
(environment);
(environment, one);
(environment, one, append);
```
* **Parameters**:
	* **_environment_** `object` *(optional) The object that represents the environment in the slot.*
	* **_one_** `bool` *(optional) Limit the operation to one slot.*
	* **_append_** `bool` *(optional) Append instead of push when shuffling slots.*
* **Return**:
	* `integer` The number of times there was a match for the specified environment.
* **Throws**:
	* This function may throw errors if any of the given parameters are not valid.

# Remarks

If the environment parameter is not specified. The current root table will be used instead.

# Examples

> No example available.

# See also

* `function` [SqSignalBase.TailFunc](Function.SqSignalBase.Tail)
* `function` [SqSignalBase.TailThis](Function.SqSignalBase.TailThis)

# References

> No references available.
