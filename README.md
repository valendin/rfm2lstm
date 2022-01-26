# Customer Base Analysis with Recurrent Neural Networks

A self-supervised sequence-to-sequence neural network model as described in the forthcoming paper by Valendin et al.

## instructions 
- install conda version 4.8 or above. 
- create a python virtual environment like so: ```conda create -y -n tf python==3.9.9```
- activate the environment: ```conda activate tf```
- install required packages in the environment (ubuntu): ```pip install pandas numpy tqdm tensorflow tensorflow-addons tensorflow-probability matplotlib notebook```
- if you're using macos, replace ```tensorflow``` with ```tensorflow_macos``` and add ```ipywidgets```
- start ```jupyter notebook``` and open *banking_transactions_demo.ipynb*

Retail bank transaction data taken from https://data.world/lpetrocelli/czech-financial-dataset-real-anonymized-transactions (trans.csv file only). This is a small dataset (fast training), with a strong aggregate monthly pattern.

If you apply the method on a dataset you're able to share openly, please send the notebook along with the data to valendin at gmail dot com and we can add it here. With any other comments or suggestions, contact https://www.linkedin.com/in/valendin/

See LICENSE and AUTHORS file for details.
