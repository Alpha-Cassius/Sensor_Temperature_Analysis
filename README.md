# Sensor Temperature Analysis

This project demonstrates core **NumPy** operations for data analysis, including array manipulation, statistical computation, boolean indexing, and data normalization.

## 📊 Overview

The script processes a 2D NumPy array representing temperature readings from **4 weather stations**, each recorded **5 times** daily.

### Tasks Completed:

1. **Shape & Statistics:** Identified the array structure $(4, 5)$ and calculated the mean temperature for each station.
2. **Filtering:** Used boolean masking to extract all temperature readings exceeding $28.0^{\circ}C$ into a 1D array.
3. **Normalization:** Scaled the entire dataset to a range of $[0, 1]$ using the Min-Max normalization formula:

$$\text{normalized} = \frac{\text{data} - \text{data.min()}}{\text{data.max()} - \text{data.min()}}$$



## 🛠️ Requirements

* Python 3.x
* NumPy

## 🚀 How to Run

1. Ensure you have NumPy installed:
```bash
pip install numpy

```


2. Run the script:
```bash
python Firstname_Lastname_Assignment.py

```



## 📈 Sample Output

The script prints the array shape, the computed means, the filtered high-temperature list, and the final normalized matrix rounded to two decimal places.

THANK YOU
