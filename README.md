# DAA Experiment 9: Bin Packing Comparison

## File

`bin_packing_tkinter.py`

## Purpose

This Tkinter application compares three bin-packing algorithms:

- First Fit (FF)
- First Fit Decreasing (FFD)
- Best Fit Decreasing (BFD)

Each algorithm places items into bins without exceeding the chosen bin capacity.

## Requirement

- Python 3 with Tkinter

## Run

```powershell
python bin_packing_tkinter.py
```

## Input

1. Enter positive item sizes separated by commas.
2. Enter the bin capacity.
3. Click **Compare Algorithms**.

Example:

```text
Items: 0.5, 0.7, 0.3, 0.9, 0.2, 0.6, 0.8, 0.4, 0.1, 0.5
Capacity: 1.0
```

Every item must be less than or equal to the bin capacity.

## Output

The application displays:

- Lower bound for the number of bins
- Bin contents and used capacity for each algorithm
- Total bins used by FF, FFD, and BFD
authour
sravan kumar
210425148042
