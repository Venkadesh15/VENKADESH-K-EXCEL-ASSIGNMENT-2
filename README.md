DATA CLEANING AND TRANSFORMATION:
     1) HANDLING MISSING VALUES
           1.1)	PRICE MISSING HANDLING
                  CONVERT GENERAL TO ACCOUNTING
                  Price ($) - PRICE ($) TO USE (IF&ISBLANK&ROUND)  
           1.2) CATEGORY MISSING HANDLING
                  CONVERT GENERAL TO TEXT
                  Category - CATEGORY TO USE (IF&ISBLANK) By GROUP BY
      2) CORRECTING INCONSISTENT DATA
           2.1) IDENTIFIED INCONSISTENT TEXT FORMATS IN PRODUCT NAME
                  IN THIS COLUMN WE GET laptop ,smartphone ,headphones 
                          AND CONVERT TYPOS
          2.2) IDENTIFY ANY TYPOS PRESENT IN THE (CATEGORY) 
  	                      BY IDENTIFED THE TYPOS OF CATEGORY IS (TEXT)
          2.3) FIND AND REPLACE FUNCTION USING IN (PRODUCT NAME) AND 
                             (CATEGORY) COLUMNS   
                              laptop - Laptop 
                              smartphone - Smartphone 
                              headphones – Headphones
                              Electroni – Electronics
                         BY POWER QUERY USING GROUP-BY
                          MEDIAN VALUE IS “FASHION” 
                  IMPUTE CATEGORY COLUMN AND FINAL VIEW OF CATEGORY
      3) REMOVING  DUPLICATES
                  BY USING REMOVE DUPLICATES FEATURE
      4) SPLITTING AND MERGING DATA
             4.1) SPLITTING (PRODUCT ID) INTO TWO COLUMN
                     4.1.1) Manufacturing Date,Month and Country Code  
             4.2) MERGEING TWO COLUMNS
                      Product Name & Brand = Product Brand
      5) NUMBER FORMATTING
            5.1) CHANGE DATA TYPE OF (PRICE) TO CURRENCY FORMAT
                        ACCOUNTING TO CURRENCY FORMAT
            5.2) MANUFACTURING DATE DATE FORMAT
                        MANIFACTURING DATE FORMATE - DD-MM-YYYY
                        5.2.1) MANUAL         
                        5.2.2) DATE FEATURE
      6) CONDITIONAL FORMATTING
            6.1) APPLYING CONDITIONAL FORMATTING IN PRICE COLUMN
                     APPLIED COLOR SCALE IN PRICE
            6.2) CREATING CUSTOM RULE IN CATEGORY COLUMN TO HIGHLIGHT "Electronics"
                     CREATED CUSTOM RULE 
EXCEL ASSIGNMENT : 
DATA CLEANING AND TRANSFORMATION:                  
ASSIGNMENT EXCEL LINK : 
https://1drv.ms/x/c/0e84664e5b6deee1/IQDG-ePYQKWNTaDYizVRWKAQAZelSu_axa2GQ0t7sLnqfQ4?e=XMstff



