# Customer Base Analysis with Recurrent Neural Networks

A self-supervised sequence-to-sequence neural network model as described in the forthcoming paper by Valendin et al.

## Installation instructions 
In order to run the example, a virtual environment has to be created with a package manager such as the Miniconda3 (Windows/MacOSX/Linux download available (version 4.11 with Python 3.9 at time of publication) here: https://conda.io/miniconda

To install Miniconda, follow the instructions that apply: 

Windows: https://conda.io/projects/conda/en/latest/user-guide/install/windows.html

MacOSX:  https://conda.io/projects/conda/en/latest/user-guide/install/macos.html

Linux:   https://conda.io/projects/conda/en/latest/user-guide/install/linux.html 
    
After the Miniconda installation is finished, run the Anaconda Prompt (Windows) or open Terminal (MacOSX or Linux). Create a new virtual environment (a Python sandbox in which the example code will run) by running: 

`conda create -y -n tf python==3.9.7` 

The environment is called `tf` in this example, after Tensorflow, our deep learning toolkit of choice. After it's created, we must activate the environment like so: 

`conda activate tf`
    
This coding example is taking advantage of several third-party libraries:
    
* pandas -- for data manipulation 
* numpy -- numerical functions
* tqdm -- progress bar
* tensorflow -- deep learning toolkit
* tensorflow-probability -- probability functions
* matplotlib -- visualisation
* jupyter notebook -- browser interface
    
Install the libraries in the activated virtual environment like so: 

`pip install pandas numpy tqdm matplotlib jupyter notebook tensorflow tensorflow-probability`
    
Get the source code and data by either way: 
A) Download and unpack the repository archive from https://github.com/valendin/rfm2lstm (Code->Download Zip) 
B) Or use `git` to clone the repository by running `git clone https://github.com/valendin/rfm2lstm`
    
Navigate to the `rfm2lstm` directory and start an instance of Jupyter by running: `jupyter notebook`
This creates a web server to display the example source code notebook. With the Jupyter server running, if a browser window doesn't automatically open, open one manually and navigate to: http://localhost:8888/tree

Jupyter should be showing the `rfm2lstm` folder, and we can open the example jupyter notebook called `banking_transactions_demo.ipynb`
    
Inside the source notebook browser window, you can execute each individual cell one by one using the `SHIFT + Enter` key combination, or you can execute the entire notebook from start to finish using the menu option Cell->Run All.

## Notes

Retail bank transaction data taken from https://data.world/lpetrocelli/czech-financial-dataset-real-anonymized-transactions (trans.csv file only). This is a small dataset (fast training), with a strong aggregate monthly pattern.

If you apply the method on a dataset you're able to share openly, please send the notebook along with the data to valendin at gmail dot com and we can add it here. With any other comments or suggestions, contact https://www.linkedin.com/in/valendin/

See LICENSE and AUTHORS file for details. Please use [Valendin et al., 2022] as reference. 
