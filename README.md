# TDDA_dataset
Preprocessed dataset for deep domain adaptation research. Collected from a Matlab simulation of a triplex pump system.

### Overview

![](/img/TDDA.png)

### How to:

There are two available versions of TDDA: .mat or .npy files. Check the Mat2Py notebook for more information about the .mat to .npy conversion process. To access the .npy files directly, simply use numpy's 

```
import numpy as np
d = np.load('/npy_dataset/750_rpm.npy')
```
