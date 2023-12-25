# Multiplication-of-two-numpy-arrays
Multiply two numpy arrays to find Indian company’s revenues in US dollars. Using NumPy can you convert this into Indian rupees? 1 USD = 75 INR
# Multiplication of Two NumPy Arrays for Currency Conversion

## Introduction

This Python script utilizes the power of NumPy to convert the revenues of Indian companies from US dollars to Indian Rupees. The company revenues are stored in a NumPy array, where each row corresponds to a company, and each column represents revenue in different quarters.

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
