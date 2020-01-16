# Progress 8

This repository contains a sample code of how to calculate progress 8 scores using the Python pandas library. The code is to give you an idea of how pandas can be used to calculate Progress 8 scores.

You are free to modify and use the code for your own use in a not for profit setting.

Note that you are strongly recommended to double check your Progress 8 output files is outputting the correct Progress 8 scores for each pupil and cannot be held responsible if there are any issues with the code.

Note that the original code was done as a quick hack for me to personally calculate Progress 8 at work. Already I know that there are some things I can do to make the code cleaner and hope to make improvements to the code over time. Therefore, any suggestions to the code will be greatly appreciated. Also if you have any queries please let me know.


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

### Running the python file

At the moment the code is stored in a single ipynb file which can be opened and run using jupyter notebook which is part of [Anaconda](https://www.anaconda.com/distribution/). Over time I am hoping move it to a .py file and separate out the code into multiple files.

Instructions on how to download the code and the files in the repository (i.e clone the repository) can be found [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

