README file for FIFA 21 Dataset Cleaning Project:

---

# FIFA 21 Dataset Cleaning Project

This project focuses on cleaning and preparing the FIFA 21 dataset for analysis. The dataset includes various attributes related to football players such as club affiliation, contract details, physical attributes like height and weight, and search popularity.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Data Cleaning Steps](#data-cleaning-steps)
  - [1. Club](#1-club)
  - [2. Contract](#2-contract)
  - [3. Height](#3-height)
  - [4. Weight](#4-weight)
  - [5. Loan Date End](#5-loan-date-end)
  - [6. W/F](#6-wf)
  - [7. Hits](#7-hits)

## Introduction

The FIFA 21 dataset is loaded and processed using Python and pandas library. Various cleaning techniques are applied to ensure consistency and accuracy in the data before analysis.

## Setup

```python
import pandas as pd
import numpy as np
```

## Data Cleaning Steps

### 1. Club

```python
# Remove leading/trailing whitespaces from club names
```

### 2. Contract

```python
# Extract contract start date, end date, and length
# Categorize contract status (Free, On Loan, Contract)
```

### 3. Height

```python
# Convert height from feet-inches to centimeters
```

### 4. Weight

```python
# Convert weight from pounds to kilograms
```

### 5. Loan Date End

```python
# Extract loan end date for players on loan
```

### 6. W/F

```python
# Remove special characters from W/F attribute
```

### 7. Hits

```python
# No cleaning required for Hits attribute
```

---

This README provides an overview of the FIFA 21 dataset cleaning process, outlining the steps taken to ensure the data is uniform and ready for analysis. Each section includes a brief description of the cleaning step along with the corresponding code snippet.
