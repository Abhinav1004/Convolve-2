# Convolve 2.0-Team EkyamAI 

It includes the solution to Round 2 of Convolve 2.0 AI/ML Hackathon.

# Installation Instructions

1. Unzip the file **EkyamAI.zip** in a directory
2. Please find 
	a. Code.ipynb -  Jupyter notebook to generate the result csv file 
	b. result.csv - An output csv file containing 3 columns - 'primary key' , 'target values', and 'probability'.
	d. requirements.txt - list of libraries required to be installed in the virtual environment
	e. README.md - File having installation instructions for the code
	f. EkyamAI_Approach_Document.pdf - document file having description of approach
	
3. Please create a virtual environment using the command `virtualenv venv` and use `source bin/activate` to activate the same
4. Install the required libraries using the command `pip install -r requirements.txt`
5. Launch the jupyter notebook by executing `jupyter notebook` in the current directory

# Code

1. The required jupyter notebook is present in the folder created and associated dataset is present in the data folder inside folder created.
2. The Jupyter notebook expects following file in current working directory for successful execution 
	a. Dev_data_to_be_shared.xlsx - training data file
	b. validation_data_to_be_shared.xlsx -  validation data file
3. Please execute all the cells of jupyter notebook named `EkyamAI_Code.ipynb` to generate result.csv file which was submitted on kaggle


# Team Members
Team Name: EkyamAI
Abhishek Gantait
Abhinav Kumar Jha (cs23mtech15001@iith.ac.in)
Shriram Pradeep
Rohit Singh Rathore