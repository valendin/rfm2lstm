# Customer Base Analysis with Recurrent Neural Networks

A self-supervised sequence-to-sequence neural network model as described in the forthcoming paper by Valendin et al.

## instructions 
- install conda version 4.8 or above. 
- create a python virtual environment like so: ```conda create -y -n tf python==3.9.9```
- activate the environment: ```conda activate tf```
- install required packages in the environment: ```pip install pandas numpy tqdm tensorflow tensorflow-addons tensorflow-probability matplotlib notebook```
- start ```jupyter notebook``` and open *banking_transactions_demo.ipynb*

Retail bank transaction data taken from https://data.world/lpetrocelli/czech-financial-dataset-real-anonymized-transactions (trans.csv file only). This is a small dataset (fast training), with a strong aggregate monthly pattern.

With comments or suggestions, contact https://www.linkedin.com/in/valendin/
See LICENSE and AUTHORS file for details.
