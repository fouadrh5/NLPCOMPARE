# NLPCOMPARE
Python tool to compare 4 NLP tools (Stanford, Google SyntaxNet, spaCy and NLTK) in term of tokenization and POS features.

# Description:  
    The idea of this script is to use the NLP parsers to generate the Part of speech tags and compare the result between the different parsers. This Python script will be used to run any parser out of the following parsers and compare the Part of speach tags between them:  
    - Stanford parser  
    - Google parser  
    - SpaCY parser  
    - NLTK parser  
    Also, the user has the option to run them one by one or to run them all on the same input file. This will save him/her a lot of time instead of waiting each parser to finish. All the options will be provided on easy-followed menu that will not terminate unless specified by the user.
 
# Quick dependency to be able to run it
    - Python 2.7.12 
    - Install all the above mentioned parsers
    - Xcode_11_beta_6
    - Ensure that the location of this file to be under the Stanford directory

# Usage:  
    You need to change the path from /Users/fouadomran/mytmp/ to a dirctory that has all the input file including the excel sheet python NLPCompare.py
    Then follow the questions asked by the script make sure all the provided files are being created in advance to prevent any issues in running the script or any unpleasant exceptions.

# Workflow  
    The workflow of the program will be as follow:
    - The program will read the given input file (full path to the input file)
    - Make sure that the input file is in ASCII Codec schema
    - The program will output two types of files:
        * 1- Excel file (.xlsx) that has all the parsers that you have select like : parser name| POS |parser name | POS ...so on. Also, lso will compare the result of each parser with each others along with generating some statisitics 
        * 2- the output file of each parser as generated by the parser with initial preprocessing i.e. before process it to be in the .xlsx format 

# Info:
    - Written by Fouad Al Omran
    - Version 11.1
    - Date: 11 Oct 2016
