# ClarityBlog-MatureIGA Repo

Welcome to the Clarity Blog - Mature IGA Repo! 

A few things before we get started. 

1. If you stumbled upon this repo outside of the Blog, Welcome! This repo is directly tied to a 
blog series that can be found here - https://claritysecurity.io/how-to-build-a-mature-iga/ 

2. The purpose of the blog and repo is to assist companies in developing an Identity Governance
program using python. The python scripts are extensible and robust enough to get started. However, 
these scripts are not supported by Clarity Security Corporation. If you are looking for a COTS
enterprise platform with premier support, Clarity Security is an enterprise IGA platform with prices 
starting at $2.00 / user per month. 

3. Sign up for the mailing list to receive notifications when the next chapter is published, scripts are updated, and new content
is made available - https://share.hsforms.com/1XCC7nl4KQcuTbA9uaV2j4Acz53j.  

4. Watch this repo and receive a GitHub notification when commits occur.


# Project 1: Create an Identity Inventory

    Language(s): 
        Python 3.9 
    
    Libraries:  
        CSV - Default 
        JSON - Default
        XLSXWriter - https://pypi.org/project/XlsxWriter/
        Pandas - https://pypi.org/project/pandas/
    
    Notes: 
    
        IdentityInventory.py:
        
            Purpose:
        
            Functions:
                collectFileNames():
                csvEvaluation(file, identities):
                main():
    
        ManagerUserReview.py:
        
            Purpose: 
           
            Functions:
                collectIdentitiesFromJson(fileName, managers):
                writeManagerReviews(managers):
                managersToJson(managers):
                main():
        
    
        UserReviewCombiner.py:
        
            Purpose:
           
            Functions:
                readExcelReturnDict(fileName, responseDict):
                loadManagerJson(fileName):
                createSheetsAddHeaders(headerNames, workbook, sheetInfo):
                populateSheet(workbook, sheetName, manager, row, col, content):
                createExcel(managers):
                main():
