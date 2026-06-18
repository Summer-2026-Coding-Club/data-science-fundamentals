# Setup: Installing the Data Science Libraries

## 1. Install the libraries

Open a terminal and run:

```
pip install numpy pandas matplotlib jupyter
```

- **NumPy**: fast arrays and math.
- **Pandas**: tables (DataFrames), built on top of NumPy.
- **Matplotlib**: plotting/charts.

## 2. Check it worked

```
python3 -c "import numpy, pandas, matplotlib; print('all good')"
```

You should see `all good` printed, which means you are able to import ("use") these packages!

## 3. Open the first lesson

Easiest way, no install required: upload [`01_numpy_and_pandas_basics.ipynb`](01_numpy_and_pandas_basics.ipynb) to [Google Colab](https://colab.research.google.com/) (these libraries are pre-installed there).

To run it locally instead:
```
jupyter notebook
```
then open `01_numpy_and_pandas_basics.ipynb`.

## Next step

Once `import numpy, pandas, matplotlib` works, head to `01_numpy_and_pandas_basics.ipynb` and start from the top.
