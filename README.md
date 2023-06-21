# Predict Stock Prices
Predict the everchanging of stock prices by fetching historical data straight from Yahoo Finance. Demonstrate data preparation and the use of pandas dataframe for machine learning models.

## Replication
Follow the following steps to set up the virtual environment.
### 1. Install requirements
Clone git repo: `git clone https://github.com/vanmyngo/stock-predictor.git`  

***Either*** to install anaconda, follow the instruction on [here](https://docs.anaconda.com/free/anaconda/install/index.html).  
Anaconda: `conda env create -f ./stock-predictor/requirements.yml`  

***Or*** execute below command only after create a [virtual environment](https://docs.python.org/3/library/venv.html), preferably.    
Python: `pip install -r ./stock-predictor/requirements.txt`  
### 2.1 Anaconda environment
You can use Jupyer Lab or Notebook but I'm more familiar with Jupyter Lab.  
Install Jupyter Lab into base environment, if not already by: `conda install -c conda-forge jupyterlab`  

Add conda environment into Jupyter:   
```
(base)$ conda activate cenv
(cenv)$ conda install ipykernel
(cenv)$ ipython kernel install --user --name=<any_name_for_kernel>
(cenv)$ conda deactivate
```

If ipykernel is already installed, add conda environment to Jupyter in the next step.  
Open Jupyer Lab: `(base)$ jupyter lab`  
Open notebook in Jupyter Lab and select "Run All Cells" in the upper "Run" tab.
### 2.2 Python script
While Jupyter Notebook(.ipynb) can be converted to python script(.py), there are many plots that might not be printed as originally.
### 3. Enjoy!
You can add more models in the "Train Models" section as you please. I decide to use classifiers since my laptop is not able to train complicated models like Long Short-Term Memory(LSTM) without a GPU. This project is not to demonstrate ML skillset but my ability to analyze data.  
***Click on .ipynb in this repo to see the results.***
# Licenses
Licenses for third-party libraries used in this project are stored in "Licenses" folder and are named accordingly.
