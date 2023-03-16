# Dataset Processing



----
## Contents
1. Design Logic
2. Running Instructions
3. Contact



----
## Design Logic
The design logic is illustrated based on the following components. 

0. 0_txt2csv.ipynb
    This program converts .txt files to .csv files which is more commonly used in Python.
    
1. 1_joint_columns.ipynb
    This program gets the joint column names from the dataset of past 11 years.

2. 2_generate_data.ipynb
    This program re-orders columns, adds ICD labels and splits data using 5.31 and 6.1.

3. 3_select_trainset.ipynb
    This program uses disease rules to get training dataset (containing disease rows and other rows).

    


----
## Running Instructions

You just need to run the corresponding code chunk to start each ipynb notebook. The editable hyperparameters are ‘year’ and ‘disease’. By simply editing this two hyperparameters you can apply the code in every situations. 

Remember that the time periods in 2_generate_data should change for the first and last year ( data from 2011 to 2012 starts from 2011.1.1 and data from 2020 to 2021 ends at 2021.12.31) 

 

----
## Contact

Dr. Ye Ye - yey5@pitt.edu
Yiming Sun - yis108@pitt.edu
Wentao Wu - wew92@pitt.edu
