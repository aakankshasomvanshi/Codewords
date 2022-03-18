
A) Problem Statement : 
    Count Words Program
     Write a program called Count Words that processes a List of Strings and applies the following business rules:
   - Counts and returns the NUMBER of words (i.e. Strings) that start with "M" or "m"
   - Returns all the words longer than 5 characters

B) Assumption :
    We will process file as input which will contain all the words. File words are separated by space. 
    Current code will work for small sized input file. If in case file very big/multiple files, 
    multi-threading can also be implemented to read input records and process them.
		
C) Installation Instruction:
   - 'InputDataFile' file need to be place under "C:\TEST\"
   -  Download below 3 Impacted java file from github and make sure to copy file under 'com.countwords' directory.

D) Impacted Classes:
   - CountWords.java - Entry point to run the program.
   - FileUtility.java - Main business logic for getting required list of words.
   - ConstantConfig.java - Configuration file for word separator, minLength, character to match (This can be changed as per business needs. 
						If we will proceed with some framework, then these configurations can be added into some config file/env variable/etc. e.g SpringBoot)

E) High Level Solution :
     -File with words will be processed and will be read line by line. 
       Each line will be split as per separator to get the words from line. And then filter the words as per our problem statement.

F) Unit Test cases :
      - I have prepared CHL and executed . Please review testing artifact of project 
          CountWordsTestCaseCalenderWithStatus.xlsx 
     -  Another approach to add all TC in SOAP UI suit and run from SOAP UI.
