---
title: SLICING
description: >-
  Slicing


---
## Slicing 1

```yaml
type: NormalExercise
lang: python
xp: 100
skills: 2
key: 1cd9d19166
```



`@instructions`
Print the 1st value in the array

`@hint`



`@sample_code`
```{python}
import numpy as np
a =  np.arange(20)

b = a[ ... ]

print(b)
```
`@solution`
```{python}
import numpy as np
a =  np.arange(20)

b = a[ 0 ]

print(b)
```
`@sct`
```{python}
Ex().check_object('b').has_equal_value()
Ex().test_output_contains('0')
success_msg('Great job!')
```




