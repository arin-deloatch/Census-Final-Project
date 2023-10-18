# An Individual's Likelihood on Making Over/Under $50K Based on Certain Features

### Built With Python 3.11

<!-- ABOUT THE PROJECT -->
### Project Description

Using the Census Income dataset from the <a href="https://archive.ics.uci.edu/dataset/2/adult">UCI Machine Learning Repository</a>, our application displays the development of an end-to-end statistical analysis. During our statistical analyses, we used Python 3.11 and a few popular libraries for data manipulation, visualization and statistics. With the use of these libraries, we were able to remove unwanted features from our dataset that we did not want to include in our analysis. We were also able to split our population into samples and incorporate randomization in the process. With this code, you'll be able to conduct similar analyses with the Census dataset as well as change features, test alternative approaches and plot the results!

<!-- Installation and Running the Project -->
### Installation and Running the Project

1. Clone the repo 
   ```sh
   git clone https://github.com/adeloatch/census-final-project 
   
2. Ensure the necessary packages are installed via your package manager (pip, anaconda,etc.) and import the modules into your python/notebook file. 
    ```sh
   import pandas as pd
   import numpy as np
    import statsmodels.api as sm
    import random
    import seaborn as sns 
3. If you're using the ucimlrepo library for importing the data, be sure to install and import the dependencies.
  ```sh
  pip install ucimlrepo
  from ucimlrepo import fetch_ucirepo
