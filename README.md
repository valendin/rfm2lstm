# Customer Base Analysis with Recurrent Neural Networks

This self-supervised sequence-to-sequence neural network model is used in "Customer Base Analysis with Recurrent Neural Networks" [Valendin et al., 2022]

## instructions 
- install conda version 4.8 or above. 
- create a python virtual environment like so: ```conda create -y -n tf python==3.9.9```
- activate the environment: ```conda activate tf```
- install required packages in the environment: ```pip install pandas numpy tqdm tensorflow tensorflow-addons tensorflow-probability matplotlib notebook```
- start ```jupyter notebook``` and open *banking_transactions_demo.ipynb*

Here we demonstrate the model using transaction data from a retail bank,taken from https://data.world/lpetrocelli/czech-financial-dataset-real-anonymized-transactions (trans.csv file only). This is a relatively small dataset (fast training), with a prominent monthly pattern.

With comments or suggestions, please contact the author https://www.linkedin.com/in/valendin/
