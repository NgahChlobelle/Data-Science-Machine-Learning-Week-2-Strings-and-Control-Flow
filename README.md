# Strings Manipulation-and-Control-Flow

# Objectives
## - To master Python string methods for data cleaning, validation, and transformation, ensuring strings are in the correct format for program control flow
## - Apply case transformation methods like .upper() and .lower() to ensure consistency in string datasets.
## - Use boolean-based methods such as .isalpha(), .isdigit(), .startswith(), and .endswith() to verify data integrity before processing
## - Manipulate string structures using .split() to convert sentences into lists and .join() to merge lists back into single, formatted strings

# Tools Used
## Language : Python
## Environment : Jupyter Notebook

# Step-by-Step Process
## 1. Case Transformation 
### - Converted string data to all UPPER and all LOWER case.
## 2. Data Validation 
### - Tested strings for specific content (alphabetical only, digits only, or case specific).
## 3. Structural Changes 
### - Used .split() to break sentences into lists.
### - Used .join() to rebuild strings with custom delimeters
## 4. Content Search
### Verified the beginning and end of strings using .startswith() and .endswith()

# Commands Executed
## Name_.upper()          : Checks casing of letters in a strings 
## Name_.lower()          : Checks casing of letters in a strings
## Name_.isalpha()        : Checks if string contains only alphabetic characters (letters) and returns a Boolean value (T/F)
## Name_.isdigit()        : Checks if a string consists only of numbers and returns a Boolean value (T/F) as output
## Greeting.split(' ')    : Breaks a single string into a list of smaller strings.
## '_'.join(Word)         : Merges list of strings into a single string using a specific character ('_') as a delimeter 
## Flower.startswith('s') : Checks if string begins with a specific character and returns a boolean value
## Flower.endswith('s')   : Checks if string end with a specific character and returns a boolean value

# Screenshots of Results
![image alt](https://github.com/NgahChlobelle/Data-Science-Machine-Learning-Week-2-Strings-and-Control-Flow/blob/c14659a994eba096b5ff05d78d14a9aedb0d7e39/String%20and%20Control%20Flow%201.PNG)
![image alt](https://github.com/NgahChlobelle/Data-Science-Machine-Learning-Week-2-Strings-and-Control-Flow/blob/c14659a994eba096b5ff05d78d14a9aedb0d7e39/String%20and%20Control%20Flow%202.PNG)
![image alt](https://github.com/NgahChlobelle/Data-Science-Machine-Learning-Week-2-Strings-and-Control-Flow/blob/c14659a994eba096b5ff05d78d14a9aedb0d7e39/String%20and%20Control%20Flow%203.PNG)
![image alt](https://github.com/NgahChlobelle/Data-Science-Machine-Learning-Week-2-Strings-and-Control-Flow/blob/c14659a994eba096b5ff05d78d14a9aedb0d7e39/String%20and%20Control%20Flow%204.PNG)

# Key Observations / Lessons Learned
## - Validation Sensitivity: .isalpha() and .isdigit() returns False if there are spaces or mixed characters in the string
## - Delimeter Flexibility: The .join() method allows you to insert any character like (_) between elements of a list.
## - Immutability: String methods like .upper do not change the original string unless the result is reassigned to the variable. 
