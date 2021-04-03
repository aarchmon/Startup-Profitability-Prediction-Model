# Startup Profitability Prediction Model

![Neural Networks](./Images/neural_network.jpeg)

---

## Technologies


Before attempting to execute any _Python_ code in `credit_risk_resampling.ipynb`, it is imperative that your development environment holds the following modules:

[numpy](https://numpy.org/) - Scientific computing module.

[pandas](https://pandas.pydata.org/pandas-docs/stable/) - Data analysis module.

[pathlib](https://docs.python.org/3/library/pathlib.html) - Object-oriented filesystem path library.

[sklearn](https://sklearn.org/) - Machine learning module.

[imblearn](https://pypi.org/project/imblearn/) - Imbalanced machine learning module. 

[warnings](https://docs.python.org/3/library/warnings.html) - System alerts. 

---

## Installation Guide

With your _Python 3.7+_ environment, run the following commands via CLI:

```
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from sklearn.metrics import classification_report
from imblearn.metrics import classification_report_imbalanced
import warnings
```

---

## Examples

![Imbalanced](./Images/example_1.png)

![Oversampled](./Images/example_2.png)

---

## Usage

1. Clone repository onto your personal machine. 

2. Open _Jupyter Lab_ or _Jupyter Notebook_ via _Anaconda Navigator_ and navigate to the directory in which the file `credit_risk_resampling.ipynb` is present. _All relevant code for this repository will be executed via Jupyter Notebook and no output will be printed to the command line_. Ensure that all relevant dependencies and _Python_ modules are installed (see __Technologies__ and __Installation Guide__ for more details) before attempting to execute code within _Jupyter Notebook_; otherwise, you will receive multiple interpreter errors! 

3. With the notebook open, start at the very first cell reading "__Credit Risk Classification__" (a cell will be active when a rectangular border is surrounding the area in question). Run each cell in sequential order. _It is vital that all cells are ran in sequential order or your notebook will generate compiler errors_!. 

---

## Contributors

New development created by Aaron C. Montano. **Code from 'Initial commit.' commit originates from UC Berkeley Extension and I do not claim original ownership nor scholarship**.

---

## License

Software tool available for public use. 
