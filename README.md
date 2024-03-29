## GAUSSIAN THEOREM

**Gaussian Theorem: A Python Package for Gaussian and Binomial Distributions**

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
  - [From PyPI](#from-pypi)
  - [From Source](#from-source)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Examples](#examples)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Introduction

Gaussian Theorem is a Python package that provides classes for working with Gaussian and Binomial distributions. This package is designed to make it easy for developers and data scientists to perform calculations, visualize distributions, and integrate statistical functionality into their projects.

## Features

- **Gaussian Distribution:**
  - Calculate mean and standard deviation.
  - Generate probability density function (PDF) values.
  - Perform distribution addition.

- **Binomial Distribution:**
  - Calculate mean and standard deviation from given probabilities and sample sizes.
  - Visualize distributions with histograms.
  - Plot PDFs for Binomial distributions.

## Installation

### From PyPI

You can install the package directly from PyPI using `pip`. Make sure you have Python 3.x installed on your machine.

```bash
pip install gaussian_theorems
```

### From Source

If you prefer installing from the source, follow these steps:

**1. Clone the repository:**
   ```bash
   git clone https://github.com/Dharren09/Gaussian_Theorem.git
   cd Gaussian_Theorem
   ```

**2. Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

**3. Install the Package:**
   ```bash
   python setup.py install
   ```

## Usage

```python
# Example code demonstrating how to use the Gaussian class
from Gaussian_Theorems.gaussiandistribution import Gaussian

# Create a Gaussian distribution instance
gaussian = Gaussian(25, 4)

# Read data from a file (replace 'data.txt' with your data file)
gaussian.read_data_file('datasets/numbers.txt')

# Calculate mean and standard deviation
mean = gaussian.calculate_mean()
stdev = gaussian.calculate_stdev()

# Print the Gaussian distribution characteristics
print(gaussian)

# Plot histogram and PDF
gaussian.plot_histogram_pdf()
```
## Project Structure

**The project is structured as follows:**

```lua
GAUSSIAN_THEOREM/
|-- Gaussian_Theorems/
|   |-- __init__.py
|   |-- gaussiandistribution.py
|   |-- generaldistribution.py
|-- Binomialdistributions/
|   |-- __init__.py
|   |-- binomialdistributions.py
|-- tests/
|   |-- __init__.py
|   |-- tests.py
|-- setup.py
|-- License
|-- CODE_OF_CONDUCT.md
|-- contribution_guidelines.md
|-- requirements.txt
|-- datasets/
|   |-- numbers.txt
|   |-- numbers_binomial.txt
|-- build
```

## Testing
**To run tests, execute the following command:**

```bash
python -m unittest tests.tests
```

## Contributing
We welcome contributions! If you find a bug or have an enhancement idea, please open an issue or submit a pull request. Please check our [Contribution Guidelines](contribution_guidelines.md) for details.

## License
This project is licensed under the MIT License - see the [LICENSE](License) file for details.

## Acknowledgments
The project is inspired by the need for a simple yet powerful Python package for working with statistical distributions. Special thanks to the Matplotlib, Scikit-learn, Scipy teams for their excellent libraries Plus Udacity Data Science instructors for their immersive contributions towards my knowlegde base.

## Contact
For any questions or feedback, feel free to reach out:

Email: dharrenpius@outlook.com
[Twitter](https://www.twitter.com/iamdevdharrenzug): @iamdevdharrenzug
[GitHub](https://www.github.com/Dharren09): Dharren09