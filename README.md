# Time_Series_Decomposition_Python


# Decomposing Trend, Seasonality and Residuals

## Content of the project
The goal of this project is to better understand the three components of time series data and of additive and multiplicative models, as well as the ways in which this can be done more efficiently in Python.

## Instructions
I will be using the dataset `dataset_A.npy` and `dataset_B.npy`. It contains the text of the tweet, as well as information about the days in which those tweets were written.


## Methodology
First, I will separately construct each time series component.
Then, I will bring the three components together to create a simulated time series dataset.
Finally, I will leverage time series model decomposition in Python to deconstruct the series.


## Usage

To run the analysis, open the `NLP_BI_Airline_Industry.ipynb` notebook and execute each cell sequentially. Ensure that the required datasets are in the correct file paths.


## Dependencies

The following libraries are used in different parts of the project. Proceed to their installation with the following code:

```
import sys
import statsmodels as ss
import numpy as np
import matplotlib
import matplotlib.pyplot as plt
import os
import seaborn as sns
from statsmodels.tsa.seasonal import seasonal_decompose
```

## Installation
Ensure that you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/downloads/).


## Usage
You are allowed to view and fork the repository for personal use. If you have any questions or would like to discuss potential collaborations, feel free to reach out.


## Contributing
Although this project is not open-source, I welcome feedback, bug reports, and suggestions. If you encounter any issues or have ideas for improvements, feel free to send me an email to julian.enciso.izquierdo@gmail.com.


## License
This project is not open-source, and it does not come with a specific open-source license. All rights are reserved, and usage, modification, or distribution of the code is not permitted without explicit permission.

If you are interested in using or collaborating on this project, please send me an email to julian.enciso.izquierdo@gmail.com.


