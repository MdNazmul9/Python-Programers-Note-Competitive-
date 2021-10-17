# Python-Programers-Note-Competitive-

#Smallest positive float64 number
```
import numpy as np
np.finfo(np.float64).eps = 2.2204460492503131e-16
np.finfo(np.float64).tiny = 2.2250738585072014e-308

# OR

np.nextafter(0, 1)
np.nextafter(np.float32(0), np.float32(1))

```

