# matplotkitty

Fork of [matplotlib-backend-kitty](https://github.com/jktr/matplotlib-backend-kitty), released under CC0, by @jktr.

### Installation

```sh
pip install .
export MPLBACKEND=module://matplotkitty; export MPLBACKEND_KITTY_SIZING=manual
```

### Test

```sh
export MPLBACKEND=module://matplotkitty; export MPLBACKEND_KITTY_SIZING=manual
python -c 'import pandas as pd; import matplotlib.pyplot as plt; pd.DataFrame(range(10)).plot.line(); plt.show()'
```

Or use with an interactive python:

```sh
export MPLBACKEND=module://matplotkitty; export MPLBACKEND_KITTY_SIZING=manual
python -i -c 'import pandas as pd; pd.DataFrame(range(10)).plot.line()'
```
