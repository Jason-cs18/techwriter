# XXX-MNIST
![Branch](https://img.shields.io/badge/Branch-Main-blue) ![Version](https://img.shields.io/badge/Version-0.0-blue) ![License](https://img.shields.io/badge/License-MIT%202.0-blue.svg) 

<details><summary>Table of Contents</summary><p>

* [Why we made XXXX-MNIST](#why-we-made-XXXX-mnist)
* [Get the Data](#get-the-data)
* [Usage](#usage)
* [Benchmark](#benchmark)
* [Visualization](#visualization)
* [Contributing](#contributing)
* [Contact](#contact)
* [Citing Fashion-MNIST](#citing-fashion-mnist)
* [License](#license)
</p></details><p></p>

`XXX-MNIST` is a dataset of xxx

Here's an example of how the data looks (*each class takes three-rows*):

a gif of dataset

## Why we made XXXX-MNIST

Reasons for building XXXX-MNIST

## Get the Data

xxx

Dataset statistics 

| Class | # of examples |
| --- | --- |
| xxx | xxx |

## Usage

### Loading data with Numpy

```Python
import numpy as np

# Load the dataset
mnist_data = np.load('mnist_data.npz')
```

### Loading data with PyTorch
```Python
import torch
from torchvision import datasets, transforms
xxx
```

## Benchmark
We built an automatic benchmarking system based on `scikit-learn` that covers 129 classifiers (but no deep learning) with different parameters.

| Classifier | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| XXX | xxx | xxx | xxx | xxx | xxx |

## Visualization

### Class distribution

![Class distribution](./class_distribution.png)

## Contributing

We welcome contributions from the community. Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for more information.

## Citing XXXX-MNIST

If you use XXXX-MNIST in a scientific publication, we would appreciate references to the following paper:

```latex
@online{Jason20xx/online,
  author       = {xxx},
  title        = {xxx},
  date         = {xxx},
  year         = {xxx},
  eprintclass  = {cs.LG},
  eprinttype   = {arXiv},
  eprint       = {cs.LG/xxx},
}
```

## License

XXXX-MNIST is licensed under the [MIT license](LICENSE).