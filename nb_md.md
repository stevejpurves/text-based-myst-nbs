---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# text based case

this is markdown

```
THIS IS RAW
```

```{code-cell} python
import numpy as np
np.__version__
```

this is more markdown

then an explicit block break 👇

+++

```{code-cell} python
a = np.arange(4).reshape((2,2))
np.min(a, axis=0)
```
