# Multiplication-of-two-numpy-arrays
Multiply two numpy arrays to find Indian company’s revenues in US dollars. Using NumPy can you convert this into Indian rupees? 1 USD = 75 INR

# Multiplication of Two NumPy Arrays for Currency Conversion

## Introduction

This Python script utilizes the power of NumPy to convert the revenues of Indian companies from US dollars to Indian Rupees. The company revenues are stored in a NumPy array, where each row corresponds to a company, and each column represents revenue in different quarters.

## Explanation

# The script defines a NumPy array named `revenue` to represent the company revenues in US dollars.
# It then declares an array named `exchange_rate` to store the conversion rate (1 USD = 75 INR).
# The script performs the currency conversion by multiplying the `revenue` array by the `exchange_rate` array element-wise, resulting in a new array named `rupee`.
# The converted revenues in Indian Rupees are displayed using `print(rupee)`.

## Conclusion

# This script offers a simple and efficient method for currency conversion using NumPy arrays, demonstrating how to multiply two arrays element-wise to convert Indian company revenues from US dollars to Indian Rupees.

## Code Overview

```python
import numpy as np

# Company revenues in US dollars
revenue = np.array([[200, 220, 250], [68, 79, 105], [110, 140, 180], [80, 85, 90]])

# Conversion rate: 1 USD = 75 INR
exchange_rate = np.array([75])

# Convert revenues to Indian Rupees
rupee = revenue * exchange_rate

# Display the converted revenues
print(rupee)


