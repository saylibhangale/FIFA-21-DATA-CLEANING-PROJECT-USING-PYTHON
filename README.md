Here's a README file based on the provided code for your FIFA 21 dataset cleaning project:

---

# FIFA 21 Dataset Cleaning Project

This project aims to clean and preprocess the FIFA 21 dataset for further analysis and exploration. The dataset contains various attributes of football players such as club, contract details, height, weight, and hits.

## Table of Contents

- [Importing Libraries](#importing-libraries)
- [Read in the Dataset](#read-in-the-dataset)
- [Data Cleaning](#data-cleaning)
  - [Club](#club)
  - [Contract](#contract)
  - [Height](#height)
  - [Weight](#weight)
  - [Loan Date End](#loan-date-end)
  - [W/F](#wf)
  - [Hits](#hits)

## Importing Libraries

```python
import pandas as pd
import numpy as np
```

## Read in the Dataset

```python
pd.set_option('display.max_columns', None)
data = pd.read_csv('fifa21 raw data v2.csv')
```

## Data Cleaning

### Club

```python
fifa['Club'] = fifa['Club'].str.strip()
```

### Contract

```python
# Extract contract start date, end date, and length
# Categorize contract status
```

### Height

```python
# Convert height to centimeters
```

### Weight

```python
# Convert weight to kilograms
```

### Loan Date End

```python
# Extract loan date end for players on loan
```

### W/F

```python
# Remove special characters from W/F attribute
```

### Hits

```python
# No cleaning needed
```

---

This README provides an overview of the steps taken to clean the FIFA 21 dataset. Each section describes the cleaning process for specific attributes along with the corresponding code snippets.

Feel free to add more sections or details to this README to provide additional context or instructions for users.
