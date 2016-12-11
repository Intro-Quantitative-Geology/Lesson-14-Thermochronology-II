# Hints for Exercise 14
## Contents
- [General hints for Exercise 14](#general-hints)
- [Problem 1 hints](#problem-1)
- [Problem 2 hints](#problem-2)

## General hints
### Plotting predicted ages as horizontal lines
I suggest that you add horizontal lines to your plots of the thermochronometer data to show the predicted ages you calculate.
If you have read in the data file with the values for latitude stored in a variable `latitude`, you can plot a predicted age `predictedAge` as a black horizontal line as follows:

```python
plt.plot([min(latitude), max(latitude)], [predictedAge, predictedAge], 'k-')
plt.show()
```
This will create a horizontal line from the minimum `latitude` to the maximum `latitude` with a vertical value of `predictedAge`.
The "trick" here is to put Python lists into the `plt.plot()` command instead of list or array variables.
Lists are values separated by commas within square brackets (`[ ]`), and here we just give 2 values in each list for the *x* and *y* points that define the ends of the line.

## Problem 1

## Problem 2
