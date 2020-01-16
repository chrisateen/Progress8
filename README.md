# Progress 8

This repository contains a sample code of how to calculate progress 8 scores using the Python pandas library. The code is to give you an idea of how pandas can be used to calculate Porgress 8 scores. 

You are free to modify and use the code for your own use in a not for profit setting.

### Excel files included in the repository

The following excel files are included in the repository in order to calculate progress 8

* **Discount Codes** - Contains the list of all the discount codes by the DfE from 2014 - 2021. This file is used to check whether a student has qualifications that discount against each other. The original DfE file can be found [here](https://www.gov.uk/government/publications/key-stage-4-qualifications-discount-codes-and-point-scores).
* **EBacc Quals** - Contains the list of all the qualifications that counts for EBacc. This is used to determine which qualifications count in the Maths, English and EBacc slots. Can also be used to calculate the EBacc average points score. The original DfE file can be found [here](https://www.gov.uk/government/publications/english-baccalaureate-eligible-qualifications)
* **Performance Points** - Contains the list of all the qualifications that count in the performance tables, all the possible grades and the equivalent points. This is used to get the equivalent points of all the grades a student has achieved. The original DfE file can be found [here](https://www.gov.uk/government/publications/key-stage-4-qualifications-discount-codes-and-point-scores).

### Requirements for the code to work correctly

In order for the code to fully work as is, you need to make sure that you follow the following rules. 
* The students' grade is in the same folder as the code
* The students' grade is in an excel file that follows the same format as the School1 Results and School2 Results excel file and is an xlsx file
* The students' grade file has the word Results at the end of the file name

_Note that if you want to do things differently that you are free to modify the code_
