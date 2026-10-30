NumPy Fundamentals

A beginner friendly Jupyter notebook introducing core NumPy array operations through short, runnable examples.

The repository currently contains one notebook, [`NUMPY.ipynb`](NUMPY.ipynb). It is a learning resource for practicing NumPy in Python; it is not a standalone Python package or command line application.

## Topics covered

The notebook walks through:

- Creating arrays with `np.array`, `np.arange`, `np.linspace`, `np.zeros`, `np.ones`, `np.full`, and `np.eye`
- Inspecting array shape, dimensions, size, data type, memory use, and transpose
- Converting data types and reshaping arrays
- Indexing, slicing, flattening, and rearranging dimensions
- Joining and splitting arrays
- Element-wise arithmetic, mathematical functions, and trigonometry
- Reductions and summary statistics such as sum, mean, median, variance, and percentiles
- Sorting, searching, filtering, and finding unique values
- Random number generation and set operations
- Basic statistical functions and correlation/covariance

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- NumPy

## Run the notebook

Clone the repository and install the dependencies:

```bash
git clone https://github.com/shivabenni2-pixel/numpy.git
cd numpy
python -m pip install numpy jupyter
jupyter notebook NUMPY.ipynb
```

You can also open `NUMPY.ipynb` in JupyterLab or upload it to Google Colab. Run the cells from top to bottom so variables defined in earlier examples are available later.

## How to use it

Read each short explanation, run the following cell, and inspect the result. Try changing array values, shapes, axes, and function arguments to see how the output changes. The notebook uses the conventional alias `np` for NumPy.

## Repository contents

```text
numpy/
└── NUMPY.ipynb   # NumPy fundamentals tutorial and examples
```

## Current scope

The notebook focuses on NumPy arrays and their operations. It does not currently demonstrate loading image files, plotting results, or provide a reusable package API. Those topics can be added as separate lessons if the project expands.

## Contributing

Improvements to explanations, examples, and exercises are welcome. Keep examples small and runnable in sequence, and explain any required packages or data files.

## License

No license is currently included in the repository. Add a license file if you want to specify how others may use, modify, or distribute this material.
