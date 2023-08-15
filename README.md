# IT-HELP-DESK-ANALYSIS
NATURE OF DATA 

##DATA PREPARATION 
##TASK 
 Column Full Name to be split into 2 columns Name and Last Name, where last 
name is missing to be obtained from the email address column.
• Name and Last name columns must be Capitalize first words and trimmed
Approach 
I splitted the email column by delimeter "@" to obtain the firstname.surname , then splitted the column again by delimrtr "." to get the firstname and surname seperately 
i used TRIM and CAPITALIZE FIRST WORD to normalize both column then concatenate the column using [Surname] & " " & [Fullname] in power query 
