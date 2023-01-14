# pycounts_ykz

Calculate word counts in a text file!

## Installation

```bash
$ cd dist/
$ pip install pycounts-0.1.0-py3-none-any.whl
```

## Usage

`pycounts_ykz` can be used to count words in a text file and plot
results as follows:

```python
from pycounts_ykz.pycounts_ykz import count_words
from pycounts_ykz.plotting_ykz import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt" # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_ykz` was created by Yukun Zhang. It is licensed under the terms of the MIT license.

## Credits

`pycounts_ykz` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
