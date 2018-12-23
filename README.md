# TDDA_dataset
Preprocessed dataset for deep domain adaptation research. Collected from a Matlab simulation of a triplex pump system.

### Overview

![](/img/TDDA.png)

### How to:

There are two available versions of TDDA: .mat or .npy files. Check the Mat2Py notebook to learn more about how to work with the original Matlab files. To access the .npy files directly, simply use numpy's 

```
d = np.load('/npy_dataset/900_rpm.npy')
```
